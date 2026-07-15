---
title: AutoShape
second_title: Aspose.Slides for Android via Java API 參考
description: 代表一個 AutoShape。
type: docs
url: /zh-hant/com.aspose.slides/autoshape/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**所有已實作介面：**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

代表 AutoShape。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | 傳回形狀的鎖定。 |
| [getAutoShapeLock()](#getAutoShapeLock--) | 傳回自動圖形的鎖定。 |
| [getTextFrame()](#getTextFrame--) | 傳回 AutoShape 的 TextFrame 物件。 |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | 判斷此自動圖形是否應使用投影片的背景填充，而非樣式或填充格式所指定。 |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | 判斷此自動圖形是否應使用投影片的背景填充，而非樣式或填充格式所指定。 |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | 為形狀新增 TextFrame。 |
| [isTextBox()](#isTextBox--) | 指定形狀是否為文字方塊。 |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```


傳回形狀的鎖定。唯讀 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**傳回：**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```


傳回自動圖形的鎖定。唯讀 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**傳回：**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


傳回 AutoShape 的 TextFrame 物件。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**傳回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```


判斷此自動圖形是否應使用投影片的背景填充，而非樣式或填充格式所指定。可讀寫布林。

**傳回：**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```


判斷此自動圖形是否應使用投影片的背景填充，而非樣式或填充格式所指定。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```


為形狀新增 TextFrame。若形狀已經有 TextFrame，則僅變更其文字。

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  // 實例化 Presentation
>  Presentation pres = new Presentation();
>  try {
>      // 取得簡報中的第一張投影片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 新增一個類型為矩形的 AutoShape
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // 將 TextFrame 新增至矩形
>      ashp.addTextFrame(" ");
>      // 存取文字框
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // 建立文字框的 Paragraph 物件
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // 為段落建立 Portion 物件
>      IPortion portion = para.getPortions().get_Item(0);
>      // 設定文字
>      portion.setText("Aspose TextBox");
>      // 將簡報儲存至磁碟
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // 取得簡報中的第一張投影片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 新增一個類型為矩形的 AutoShape
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // 將 TextFrame 新增至矩形
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // 取得 TextFrame 的文字格式
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // 指定 TextFrame 中的欄位數量
>      format.setColumnCount(3);
>      // 指定欄位之間的間距
>      format.setColumnSpacing(10);
>      // 儲存簡報
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 新的 TextFrame 的預設文字。 |

**傳回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```


指定形狀是否為文字方塊。

--------------------

若形狀未被指定為文字方塊，並不代表它不能附加文字。文字方塊僅是一種具有特定屬性的專用形狀。

**傳回：**
boolean