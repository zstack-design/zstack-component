## Changelog

`2022-06-21`
- 去掉所有DIN样式
- 修复`Carousel`的默认左侧按钮点击失效问题
- `TablePanel`的ColumnSetting功能回调传递更多参数
- 修复`DateSegmentPicker`在`TablePanel`中的异常更新行为
- 修复`TablePanel`表头水平左右滚动问题
- 优化`Carousel`的无用z-index样式问题
- `TablePanel`的`columnSetting`功能默认新增disabled功能
- `StepsForm`修复`rc-util`引用问题
- 统一`表单类`组件内部引用方式

---

### 2.4.15
`2022-04-21`
- `TablePanel`修复在使用`Page`分页类型时,`index`的计算问题
- `Form`修复warning
- 重构`SecurityEmpty`组件，导出内置Empty样式的上层组件以支持按需加载

---
### 2.4.14
`2022-04-15`
- `TablePanel`新增`autoPagination`参数用于受控数据源是否使用内置的分页模型
- 主题色更新

---
### 2.4.13
`2022-04-07`
- 修复`ActionPanel`和`TablePanel`更新query无法正常渲染的问题
- 修复`Carousel`无法透传根节点样式问题

--- 
### 2.4.12

`2022-03-29`
- 修复`peerDependencies`包名
- 修复`Form`dependencies功能在只有初始值时无法触发问题

---
### 2.4.11  

`2022-03-22`

- 发布外网包版本