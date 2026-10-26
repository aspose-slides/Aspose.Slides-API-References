---
title: IAutoShape
second_title: Aspose.Slides Java API 參考
description: 代表一個 AutoShape。
type: docs
url: /zh-hant/com.aspose.slides/iautoshape/
---
**已實作的介面:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

代表一個 AutoShape。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | 返回 AutoShape 的鎖。 |
| [getTextFrame()](#getTextFrame--) | 返回 AutoShape 的 TextFrame 物件。 |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | 判斷此自動圖形是否應使用投影片的背景填充，而非依樣式或填充格式指定。 |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | 判斷此自動圖形是否應使用投影片的背景填充，而非依樣式或填充格式指定。 |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | 在形狀中新增一個 TextFrame。 |
| [isTextBox()](#isTextBox--) | 指定形狀是否為文字方塊。 |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


返回 AutoShape 的鎖。唯讀 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**返回值:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


返回 AutoShape 的 TextFrame 物件。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回值:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


判斷此自動圖形是否應使用投影片的背景填充，而非依樣式或填充格式指定。可讀寫布林值。

**返回值:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


判斷此自動圖形是否應使用投影片的背景填充，而非依樣式或填充格式指定。可讀寫布林值。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


在形狀中新增一個 TextFrame。若形狀已經有 TextFrame，則僅變更其文字。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrame 的預設文字。 |

**返回值:**
[ITextFrame](../../com.aspose.slides/itextframe) - 新的 [ITextFrame](../../com.aspose.slides/itextframe) 物件。
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


指定形狀是否為文字方塊。

--------------------

如果形狀未被指定為文字方塊，並不代表它不能附加文字。文字方塊僅是具有特定屬性的專屬形狀。

**返回值:**
boolean