## 如何使用 GitHub Pages 预览 HTML

看到这个标题，有些同学可能会问：

> 为什么我要用 GitHub Pages 来预览 HTML 文件呢？我直接用浏览器打开不就完事了吗？

那作为全球最大的同性交友网站，GitHub 会告诉你，来我这预览 HTML 有什么好处呢：

1. 使用 GitHub Pages 不仅可以预览网页，还可以帮我们托管网页，而且是完全免费的；
2. 支持静态脚本，而且自带主题可供我们选择；
3. 可以绑定自己的域名；如何使用 GitHub Pages 预览 HTML
4. 除了预览之外，我们还可以托管自己的博客站，给自己搭建一个舒适的写博客的环境，不用折腾服务器、域名啥的。
5. 其他额外好处任君探索……

那接下来我们就来看看如何使用 GitHub Pages 实现一个简单的 HTML 网页的预览吧~

### Step1 将本地的 html 代码仓库上传到 Github

#### 1.1 在 GitHub 上新建一个仓库

![newrepo.png](https://upload-images.jianshu.io/upload_images/6063788-a0e0f2e0fb9b4017.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

这里我的仓库名为 demo，然后直接点击创建仓库（什么也不要勾选）

#### 1.2 上传仓库到 GitHub

这里使用命令行将本地仓库 push 到 GitHub 的仓库中
![cmd.png](https://upload-images.jianshu.io/upload_images/6063788-6912b293789407e4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![cmd2.png](https://upload-images.jianshu.io/upload_images/6063788-2b6ef9dca96c7175.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### Step2 设置 settings

#### demo 仓库设置

- 进入 Github 的 demo 仓库中，点击右上方的 settings
  ![settings.png](https://upload-images.jianshu.io/upload_images/6063788-1331290fcfdbbb6e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 下拉至 GitHub Pages，将 Source 改为 master branch
  ![source.png](https://upload-images.jianshu.io/upload_images/6063788-31639e09a43ce883.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### Step3 预览网页

- 等待页面刷新后，会自动生成一个网址
  ![ready.png](https://upload-images.jianshu.io/upload_images/6063788-580891cf0fca832a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 点击这个网址，就会看到我们的网页可以打开啦。快去跟你的小伙伴分享你做的网页吧~
  ![preview.png](https://upload-images.jianshu.io/upload_images/6063788-85755f629b146c8f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 后记

本文是~~简陋~~简化版的用 GitHub Pages 预览网页的操作指北，正规军操作指南请期待博主的后续文章，或者直接食用原汁原味的 GitHub[帮助文档](https://help.github.com/cn/github/working-with-github-pages)。
