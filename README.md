# react16 源码学习

## 纲要
- JSX 转 JS
- React API
- React 创建更新方法
- Fiber 调度系统
- 组件更新过程
- VDom、错误捕获
- UI update
- 事件、context实现、ref实现


## 源码目录结构

├── ...
├── packages
|   ├── ...
|   ├── react     react 核心模块
|   ├── react-dom react-dom 核心模块(DOM 渲染、更新) 
|   └── schedule  调度模块
└── scripts       打包工具库