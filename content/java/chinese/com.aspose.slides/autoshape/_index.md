---
title: AutoShape
second_title: Aspose.Slides for Java API 参考
description: 表示一个 AutoShape。
type: docs
url: /zh/com.aspose.slides/autoshape/
---
**继承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**已实现的接口：**
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
| [getUseBackgroundFill()](#getUseBackgroundFill--) | 确定是否应使用幻灯片的背景填充来填充此 autoshape，而不是由样式或填充格式指定。 |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | 确定是否应使用幻灯片的背景填充来填充此 autoshape，而不是由样式或填充格式指定。 |
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

确定是否应使用幻灯片的背景填充来填充此 autoshape，而不是由样式或填充格式指定。可读写 boolean。

**返回：**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

确定是否应使用幻灯片的背景填充来填充此 autoshape，而不是由样式或填充格式指定。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

向形状添加一个新的 TextFrame。如果形状已经拥有 TextFrame，则直接更改其文本。

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
>  // 实例化 Presentation
>  Presentation pres = new Presentation();
>  try {
>      // 获取演示文稿中的第一张幻灯片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 添加类型为矩形的 AutoShape
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // 向矩形添加 TextFrame
>      ashp.addTextFrame(" ");
>      // 访问文本框
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // 为文本框创建 Paragraph 对象
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // 为段落创建 Portion 对象
>      IPortion portion = para.getPortions().get_Item(0);
>      // 设置文本
>      portion.setText("Aspose TextBox");
>      // 将演示文稿保存到磁盘
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // 获取演示文稿中的第一张幻灯片
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 添加类型为矩形的 AutoShape
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // 向矩形添加 TextFrame
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // 获取 TextFrame 的文本格式
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // 指定 TextFrame 中的列数
>      format.setColumnCount(3);
>      // 指定列之间的间距
>      format.setColumnSpacing(10);
>      // 保存演示文稿
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrame 的默认文本。 |

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

指定形状是否为文本框。

--------------------

如果形状未指定为文本框，并不意味着它不能附加文本。文本框仅是一种具有特定属性的专用形状。

**返回：**
boolean