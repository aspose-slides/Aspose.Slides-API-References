---
title: IAutoShape
second_title: Aspose.Slides for Android via Java API 參考
description: 代表 AutoShape。
type: docs
url: /zh-hant/com.aspose.slides/iautoshape/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

代表 AutoShape。
## Methods

| Method | Description |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | 傳回 AutoShape 的鎖定。 |
| [getTextFrame()](#getTextFrame--) | 傳回 AutoShape 的 TextFrame 物件。 |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | 判斷此 autoshape 是否應使用投影片的背景填充，而非樣式或填充格式指定。 |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | 判斷此 autoshape 是否應使用投影片的背景填充，而非樣式或填充格式指定。 |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | 在形狀中新增 TextFrame。 |
| [isTextBox()](#isTextBox--) | 指定形狀是否為文字方塊。 |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


傳回 AutoShape 的鎖定。唯讀 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**Returns:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


傳回 AutoShape 的 TextFrame 物件。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


判斷此 autoshape 是否應使用投影片的背景填充，而非樣式或填充格式指定。讀寫布林值。

**Returns:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


判斷此 autoshape 是否應使用投影片的背景填充，而非樣式或填充格式指定。讀寫布林值。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


在形狀中新增 TextFrame。如果形狀已經有 TextFrame，則僅變更其文字。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrame 的預設文字。 |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe) - 新的 [ITextFrame](../../com.aspose.slides/itextframe) 物件。
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


指定形狀是否為文字方塊。

--------------------

若形狀未被指定為文字方塊，並不代表它不能附加文字。文字方塊僅是一種具有特定屬性的專用形狀。

**Returns:**
boolean