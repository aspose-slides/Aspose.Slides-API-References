---
title: AutoShape
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示一个 AutoShape。
type: docs
url: /zh/com.aspose.slides/autoshape/
---
**继承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**所有实现的接口：**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

表示一个 AutoShape。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | 返回形状的锁。 |
| [getAutoShapeLock()](#getAutoShapeLock--) | 返回 AutoShape 的锁。 |
| [getTextFrame()](#getTextFrame--) | 返回 AutoShape 的 TextFrame 对象。 |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | 确定此 AutoShape 是否应使用幻灯片的背景填充，而不是由样式或填充格式指定。 |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | 确定此 AutoShape 是否应使用幻灯片的背景填充，而不是由样式或填充格式指定。 |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | 向形状添加一个新的 TextFrame。 |
| [isTextBox()](#isTextBox--) | 指定形状是否为文本框。 |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

返回形状的锁。只读 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**返回：**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

返回 AutoShape 的锁。只读 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**返回：**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

返回 AutoShape 的 TextFrame 对象。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

确定此 AutoShape 是否应使用幻灯片的背景填充，而不是由样式或填充格式指定。可读写布尔值。

**返回：**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

确定此 AutoShape 是否应使用幻灯片的背景填充，而不是由样式或填充格式指定。可读写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

向形状添加一个新的 TextFrame。如果形状已经有 TextFrame，则仅更改其文本。

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
>  // Instantiates Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Adds an AutoShape with type set as Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Adds TextFrame to the Rectangle
>      ashp.addTextFrame(" ");
>      // Accesses the text frame
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Creates the Paragraph object for text frame
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Creates a Portion object for the paragraph
>      IPortion portion = para.getPortions().get_Item(0);
>      // Sets the text
>      portion.setText("Aspose TextBox");
>      // Saves the presentation to disk
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Add an AutoShape with type set as Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Add TextFrame to the Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Gets the text format of TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Specifies the number of columns in TextFrame
>      format.setColumnCount(3);
>      // Specifies the spacing between columns
>      format.setColumnSpacing(10);
>      // Saves the presentation
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Default text for a new TextFrame. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()

指定形状是否为文本框。

如果形状没有被指定为文本框，并不意味着它不能附带文本。文本框仅仅是具有特定属性的专用形状。

**返回：**
boolean