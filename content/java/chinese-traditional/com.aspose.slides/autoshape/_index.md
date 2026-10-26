---
title: AutoShape
second_title: Aspose.Slides for Java API 參考
description: 代表一個 AutoShape。
type: docs
url: /zh-hant/com.aspose.slides/autoshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Represents an AutoShape.

## 方法

| 方法 | 說明 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Returns shape's locks. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returns autoshape's locks. |
| [getTextFrame()](#getTextFrame--) | Returns TextFrame object for the AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Adds a new TextFrame to a shape. |
| [isTextBox()](#isTextBox--) | Specifies if the shape is a text box. |

### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

返回形狀的鎖定。唯讀 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**返回：**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)

### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

返回 AutoShape 的鎖定。唯讀 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**返回：**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

返回 AutoShape 的 TextFrame 物件。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)

### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

確定此 AutoShape 是否應使用投影片的背景填充而非樣式或填充格式指定。可讀寫布林。

**返回：**
boolean

### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

確定此 AutoShape 是否應使用投影片的背景填充而非樣式或填充格式指定。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

向形狀新增 TextFrame。若形狀已經有 TextFrame，則僅修改其文字。

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
>      // 獲取簡報的第一張投影片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 新增 AutoShape，類型設定為 Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // 為 Rectangle 新增 TextFrame
>      ashp.addTextFrame(" ");
>      // 取得文字框架
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // 為文字框架建立 Paragraph 物件
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
>      // 獲取簡報的第一張投影片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 新增 AutoShape，類型設定為 Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // 為 Rectangle 新增 TextFrame
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // 取得 TextFrame 的文字格式
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // 指定 TextFrame 的欄數
>      format.setColumnCount(3);
>      // 指定欄之間的間距
>      format.setColumnSpacing(10);
>      // 儲存簡報
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrame 的預設文字。 |

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)

### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

指定形狀是否為文字方塊。

--------------------

如果形狀未被指定為文字方塊，並不代表它不能附帶文字。文字方塊僅是具有特定屬性的專用形狀。

**返回：**
boolean