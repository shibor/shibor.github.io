---
title: Hello World
date: 2020-03-18
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)



## 草稿功能

### 建立文章草稿

```shell
$ hexo new draft <title>
```

Hexo 提供 `draft` 机制，它的原理是新文章将建立在 `source/_drafts` 目录下， `hexo generate` 并不会将其编译到 `public` 目录下， `hexo deploy` 也不会部署。



### 本地预览草稿

```shell
$ hexo S --draft
```

## 将草稿发布为正式文章

```shell
$ hexo P <filename>
```

其中 `<filename>` 为不包含 `md` 后缀的文章名称，将文章从 `source/_drafts` 移动到 `source/_posts` 

若想将正式文章转为为草稿，手动将文章从 `source/_posts` 目录移动到 `source/_drafts` 目录即可。