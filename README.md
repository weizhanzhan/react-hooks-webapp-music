>学习掘金小册[《React Hooks 与 Immutable 数据流实战》](https://juejin.im/book/5da96626e51d4524ba0fd237/section/5da974fc518825527a4cec30)
>项目是以 React 全家桶 (包含 hooks) 以及 immutable 数据流为基础打造的一款高质量的移动端音乐类 WebApp 。
## 笔记知识点整理

#### 技术栈

##### 前端
- `react v16.8 全家桶 (react，react-router)` : 用于构建用户界面的 MVVM 框架
- `redux` :  JavaScript 状态管理容器
- `redux-thunk` : 处理异步逻辑的 redux 中间件
- `immutable` :  Facebook 历时三年开发出的进行持久性数据结构处理的库
- `react-lazyload` : react 懒加载库
- `better-scroll` : 提升移动端滑动体验的知名库
- `styled-components` : 处理样式，体现 css in js 的前端工程化神器
- `axios` : 用来请求后端 api 的数据

##### 后端
- 采用 github 上开源的 NodeJS 版 api 接口 [NeteaseCloudMusicApi](https://juejin.im/book/5da96626e51d4524ba0fd237/section/5da974fc518825527a4cec30)提供音乐数据
##### 其他
- create-react-app: React 脚手架，快速搭建项目
- eslint: 知名代码风格检查工具
- iconfont: 阿里巴巴图标库
- fastclick: 解决移动端点击延迟 300ms 的问题
