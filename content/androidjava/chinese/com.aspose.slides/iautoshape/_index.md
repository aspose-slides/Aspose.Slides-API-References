---
title: IAutoShape
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示一个 AutoShape。
type: docs
url: /zh/com.aspose.slides/iautoshape/
---
**所有已实现的接口：**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

表示一个 AutoShape。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returns AutoShape's locks. |
| [getTextFrame()](#getTextFrame--) | Returns TextFrame object for the AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adds a new TextFrame to a shape. |
| [isTextBox()](#isTextBox--) | Specifies if the shape is a text box. |
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


确定此自动形状是否应使用幻灯片的背景填充，而不是由样式或填充格式指定。可读写布尔值。

**返回：**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


确定此自动形状是否应使用幻灯片的背景填充，而不是由样式或填充格式指定。可读写布尔值。

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

如果形状未被指定为文本框，并不意味着它不能附加文本。文本框只是具有特定属性的专用形状。

**返回：**
boolean