---
title: AutoShape
second_title: Aspose.Slides for Java API リファレンス
description: AutoShape を表します。
type: docs
url: /ja/com.aspose.slides/autoshape/
---
**継承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**実装されたすべてのインターフェイス：**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

AutoShape を表します。
## メソッド

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | シェイプのロックを返します。 |
| [getAutoShapeLock()](#getAutoShapeLock--) | AutoShape のロックを返します。 |
| [getTextFrame()](#getTextFrame--) | AutoShape の TextFrame オブジェクトを返します。 |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | この AutoShape を、スタイルや塗りつぶし形式で指定する代わりにスライドの背景塗りつぶしで塗りつぶすかどうかを決定します。 |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | この AutoShape を、スタイルや塗りつぶし形式で指定する代わりにスライドの背景塗りつぶしで塗りつぶすかどうかを決定します。 |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | シェイプに新しい TextFrame を追加します。 |
| [isTextBox()](#isTextBox--) | シェイプがテキストボックスかどうかを指定します。 |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

シェイプのロックを返します。 読み取り専用 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**戻り値：**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

AutoShape のロックを返します。 読み取り専用 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**戻り値：**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

AutoShape の TextFrame オブジェクトを返します。 読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

この AutoShape を、スタイルや塗りつぶし形式で指定する代わりにスライドの背景塗りつぶしで塗りつぶすかどうかを決定します。 読み書き boolean。

**戻り値：**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

この AutoShape を、スタイルや塗りつぶし形式で指定する代わりにスライドの背景塗りつぶしで塗りつぶすかどうかを決定します。 読み書き boolean。

**パラメータ：**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

シェイプに新しい TextFrame を追加します。シェイプにすでに TextFrame がある場合は、テキストを単に変更します。

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

**パラメータ：**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しい TextFrame のデフォルトテキスト。 |

**戻り値：**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

シェイプがテキストボックスかどうかを指定します。

--------------------

シェイプがテキストボックスであるように指定されていないからといって、テキストを添付できないわけではありません。テキストボックスは、特定のプロパティを持つ特殊なシェイプにすぎません。

**戻り値：**
boolean