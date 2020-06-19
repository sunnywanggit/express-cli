## 项目说明

该项目是一个基于 TypeSript 搭建的 Express 脚手架，你可以使用 TypeScript/JavaScript 开发你的 Express 项目。

## 使用方法

```
git clone 
yarn install
node-dev app2.js 或者 ts-node-dev app1.ts
```


## 构建方法

- yarn init -y 初始化 package.json 文件
- yarn add express 安装 Express
- yarn add node-dev 自动重启 Node 进程
- yarn add typescript ts-node ts-node-dev 
- yarn add @types/express 安装 Express 的声明文件
- tsc --init 创建 tsconfig.json 文件
- 配置 tsconfig.json 



## 注意

我们建议仅仅在开发坏境中使用 TypeScript 进行开发，如果你要在生产环境中使用，最好还是把 TS 变成 JS，然后去运行 JS。


