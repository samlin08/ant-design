# 带ICON图标的步骤条

- order: 2

通过设置 `Steps.Step` 的 `icon` 属性，可以启用自定义图标。

---

````jsx
var Steps = antd.Steps;
var Step = Steps.Step;
var container = document.getElementById('components-steps-demo-icon');

React.render(<Steps>
  <Step status='finish' title='步骤1' icon='cloud'></Step>
  <Step status='process' title='步骤2' icon='apple'></Step>
  <Step status='wait' title='步骤3' icon='github'></Step>
</Steps>, container);
````
