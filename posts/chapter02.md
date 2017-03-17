# 第二章 玩具应用

本章我们会开发一个较为完整的示例应用，展示 Vue.js 作为视图渲染库的强大功能，这里我们会使用 `.vue` 单文件组件的形式并按组件式的开发方式开发我们的应用。

因为这里会使用 `.vue` 单文件组件的开发方式，所以我们也会正式开始使用 webpack 来构建我们的应用。webpack 是一个功能强大的模块打包工具，基于其强大的特性，现已经为打包工具的首选，本书也会使用 webpack 作为示例讲解，如果你没有接触过也不用担心，这里会对需要用到的功能做一个讲解介绍，不过建议你还是要花时间去深入了解一下 webpack 的相关知识，对于本书的学习也会很有帮助。

## 2.1 webpack

这一节，我们将基于最开始的 hello world 程序的基础上进行改进，因为需要引入 webpack，所以我们需要调整一下项目的目录结构。

```
- src
-- components
- index.html
- README.md
```

在开始使用 webpack 之前，请先安装好如下工具:

* NodeJS
* npm/yarn

安装教程可参见: [https://fengmk2.com/blog/2014/03/node-env-and-faster-npm.html](https://fengmk2.com/blog/2014/03/node-env-and-faster-npm.html)

> NodeJS 将 Javascript 这么语言带到了服务端，不仅仅在服务端开发中大放异彩，在构建工具上也如火如荼，webpack 就是基于 NodeJS 开发的。npm 和 yarn 是包管理工具，通过他们我们可以非常便利的使用第三方模块，也正因为 npm 使得共享模块如此的便利，NodeJS 才能在如此短的时间就得到了广大的普及，可谓功不可没。


