- 这是个 **react** 项目的脚手架工具

- **简介：**

	- **js** 语法用的是 **es6**，然后用 **babel** 来转，不熟悉的可以看我写的 [教程](http://fsociety.cn/post/react%E6%8A%80%E6%9C%AF%E6%A0%88%E7%AC%94%E8%AE%B0%E8%8F%9C%E9%B8%9F%E7%AF%87%E4%B9%8Bes6)

	- 整个目录结构是用 **webpack** 来组织搭建的。

	- 模板用的是 **jade**

	- 这里推荐使用 **yarn** 来取代 **npm**，不了解的可以看我写的这个 [yarn教程](http://fsociety.cn/post/%E6%90%9E%E6%90%9E%E9%AB%98%E5%A4%A7%E4%B8%8A%E7%9A%84yarn)

	- 脚手架里集成了 **redux**， **router**，当然用不用取决于自己

	- 压缩静态文件这些就交给了 **gulp**，配置在 **webpack** 里面了

	- **express** 配合 **browersync** 实现了热更新和控制台

	- 整个项目用 **eslint** 来做代码检查，已经配置在 **webpack** 里面了

[用这个脚手架写的一个计算器demo](https://github.com/zhugeliange/fatManCalculator)

- **常用命令解释：**

```JavaScript
yarn start // 启动项目
yarn lint // 用eslint做检查，当然这里可以加上--fix参数来自动修复
yarn test // 执行测试
yarn clean // 清除旧的不必要的代码包
yarn build // 构建项目
yarn deploy // 发布项目，在tools/deploy.js里面getRemote函数里面填好自己的项目地址和github，就可以实现一键发布到线上了
```

- 更多类似的脚手架可以直接到 [Yeoman](http://yeoman.io/) 上去找，这里就不多说了。