---
title: AutoShape
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/autoshape/
---
## AutoShape 类

  Represents an AutoShape.
 
### addTextFrame {#addTextFrame}

| 名称 | 描述 |
| --- | --- |
| addTextFrame (String) | 向形状添加一个新的 TextFrame。如果形状已经拥有 TextFrame，则仅更改其文本。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 新 TextFrame 的默认文本。 |

 **返回：**
[TextFrame](../textframe)


---


### getAutoShapeLock {#getAutoShapeLock}

| 名称 | 描述 |
| --- | --- |
| getAutoShapeLock () | 返回自动形状的锁。只读 IAutoShapeLock。 |

 **返回：**
[AutoShapeLock](../autoshapelock)


---


### getShapeLock {#getShapeLock}

| 名称 | 描述 |
| --- | --- |
| getShapeLock () | 返回形状的锁。只读 IAutoShapeLock。 |

 **返回：**
[AutoShapeLock](../autoshapelock)


---


### getTextFrame {#getTextFrame}

| 名称 | 描述 |
| --- | --- |
| getTextFrame () | 返回 AutoShape 的 TextFrame 对象。只读 ITextFrame。 |

 **返回：**
[TextFrame](../textframe)


---


### getUseBackgroundFill {#getUseBackgroundFill}

| 名称 | 描述 |
| --- | --- |
| getUseBackgroundFill () | 确定此自动形状是否应使用幻灯片的背景填充，而不是由样式或填充格式指定。读写 boolean。 |

 **返回：**
boolean


---


### isTextBox {#isTextBox}

| 名称 | 描述 |
| --- | --- |
| isTextBox () | 指定形状是否为文本框。如果形状未指定为文本框，并不意味着它不能附带文本。文本框仅仅是一种具有特定属性的专用形状。 |

 **返回：**
boolean


---


### setUseBackgroundFill {#setUseBackgroundFill}

| 名称 | 描述 |
| --- | --- |
| setUseBackgroundFill (boolean) | 确定此自动形状是否应使用幻灯片的背景填充，而不是由样式或填充格式指定。读写 boolean。 |

 **返回：**
void


---