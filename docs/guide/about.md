---
title: 关于飞冰
order: 1
---

<img style={{
  height: 200,
  width: "100%",
  objectFit: "cover"
}} src="https://gw.alicdn.com/tfs/TB1vBRYaVOWBuNjy0FiXXXFxVXa-2558-1306.jpg" />

## 特性

- **React 研发框架**：通过 icejs 研发框架集成目录规范、路由、状态管理、样式、权限管理、微前端等最佳实践
- **可视化多端研发套件**：通过 VS Code 插件集合 AppWorks 简化前端工程复杂度，提供可视化、配置化、代码提示等能力
- **丰富的物料**：基于物料拼装提高项目开发效率，官方提供丰富的 antd&fusion 物料，同时支持开发构建私有的物料体系
- **领域解决方案**：提供微前端、Serverless、React Hooks、表单等面向领域的解决方案

## 核心能力

#### ice.js

> 基于 React 的渐进式研发框架

- 提供 React 项目开发的最佳实践，包含工程配置、路由、状态管理、数据请求、调试日志等解决方案
- 开箱即用的工程能力，包含 TypeScript、Less/Sass/CSS Modules 等，无需关心繁琐的 webpack 基础配置
- 结合阿里业务沉淀的大量开发规范，包括目录规范、代码风格、单元测试等方面
- 集成微前端、Serverless、Hooks 等领域解决方案

#### AppWorks

> 基于 VS Code 插件的可视化开发助手

- 在 VS Code 中支持可视化创建项目、启动调试等能力
- 增强代码提示、代码重构等能力
- 官方提供基于 fusion、antd 组件体系的上层物料，同时支持可视化拼装物料能力

## 相关链接

| GitHub                                           | npm                                                                                                        | 文档                                                                               | 描述                         |
| ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------- |
| [icejs](https://github.com/alibaba/ice)          | ![](https://img.shields.io/npm/v/ice.js.svg)                                                               | [docs](/guide/basic/start.md)                                                      | 基于 React 的渐进式研发框架  |
| [icestark](https://github.com/ice-lab/icestark)  | ![](https://img.shields.io/npm/v/@ice/stark.svg)                                                           | [docs](https://micro-frontends.ice.work/)                                          | 面向大型应用的微前端解决方案 |
| [AppWorks](https://github.com/appworks-lab/pack) | ![](https://vsmarketplacebadge.apphb.com/version-short/iceworks-team.iceworks.svg?logo=visual-studio-code) | [docs](https://marketplace.visualstudio.com/items?itemName=iceworks-team.iceworks) | 可视化多端研发套件           |

## 常见问题

#### 使用飞冰是否需要具备一定的前端基础？

毫无疑问是需要的，我们在努力降低前端开发的门槛，但一些基础的前端知识还是需要具备的，比如 JavaScript 的基础语法、前后端如何通信等。为了便于快速入门前端知识，我们整理了一份 [前端基础知识](/resource/front-basic.md)，希望能帮助到开发者。

#### 资深前端同学是否适合使用飞冰？

适合，面向前端场景飞冰团队有大量的最佳实践，无论是工程、规范、状态管理还是微前端都可以开箱即用。

#### 飞冰的浏览器兼容策略是怎样的？

飞冰官方 React 物料默认使用 React 16+，其需要的最低 IE 版本为 11，如果您需要在以下的版本使用，您可能需要引入一些 polyfill 来支持 `Map`, `Set` 等特性。参考[React 官网说明](https://reactjs.org/blog/2017/09/26/react-v16.0.html#javascript-environment-requirements)。

#### 飞冰可以使用哪些 UI 组件？

飞冰的框架和工具都不耦合 UI 组件，因此开发者可以选择自己喜欢的 UI 组件使用，比如：

- [使用 fusion 组件](/plugin/list/fusion.md)
- [使用 antd 组件](/plugin/list/antd.md)

#### 飞冰跟低代码方案有什么关系？

低代码方案一般指以可视化拖拽搭建为主，少量地方使用代码辅助，此类方案往往是面向具体领域而非通用场景的，飞冰是面向通用领域的，以源码研发为主，通过框架、物料、GUI 操作等能力降低研发门槛，因此飞冰并不是通俗意义的低代码方案。

## 联系我们

- 反馈/建议：<https://github.com/alibaba/ice/issues/new>
- 答疑钉钉群，**社区同学请扫以下二维码，内部同学请搜索「飞冰（ICE）万能群」**：

  <img src="http://ice.alicdn.com/assets/images/qrcode.png" width="300" />