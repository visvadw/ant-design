---
order: 1
title:
  zh-CN: 自定义样式
  en-US: Custom style
---

## zh-CN

可以自定义回到顶部按钮的样式，限制宽高：`40px * 40px`。

## en-US

You can customize the style of the button, just note the size limit: no more than `40px * 40px`.


````__react
import { BackTop } from 'antd';

ReactDOM.render(
  <div>
    <BackTop>
      <div className="ant-back-top-inner">UP</div>
    </BackTop>
    Scroll down to see the bottom right blue button.
  </div>
, mountNode);
````
