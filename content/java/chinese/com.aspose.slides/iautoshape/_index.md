---
title: IAutoShape
second_title: Aspose.Slides Java API 参考
description: 表示一个 AutoShape。
type: docs
url: /zh/com.aspose.slides/iautoshape/
---
**所有实现的接口：**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

表示一个 AutoShape。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | 返回 AutoShape 的锁定。 |
| [getTextFrame()](#getTextFrame--) | 返回 AutoShape 的 TextFrame 对象。 |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | 确定是否应使用幻灯片的背景填充而不是样式或填充格式来填充此自动形状。 |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | 确定是否应使用幻灯片的背景填充而不是样式或填充格式来填充此自动形状。 |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | 向形状添加一个新的 TextFrame。 |
| [isTextBox()](#isTextBox--) | 指定形状是否为文本框。 |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


返回 AutoShape 的锁定。只读 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**返回：**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


返回 AutoShape 的 TextFrame 对象。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


确定是否应使用幻灯片的背景填充而不是样式或填充格式来填充此自动形状。可读写 boolean。

**返回：**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


确定是否应使用幻灯片的背景填充而不是样式或填充格式来填充此自动形状。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


向形状添加一个新的 TextFrame。如果形状已经具有 TextFrame，则仅更改其文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrame 的默认文本。 |

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe) - 新 [ITextFrame](../../com.aspose.slides/itextframe) 对象。
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


指定形状是否为文本框。

--------------------

如果形状未指定为文本框，并不意味着它不能附加文本。文本框仅是具有特定属性的专用形状。

**返回：**
boolean