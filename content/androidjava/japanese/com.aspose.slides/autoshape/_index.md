---
title: AutoShape
second_title: Java APIリファレンスによるAndroid向けAspose.Slides
description: AutoShape を表します。
type: docs
url: /ja/com.aspose.slides/autoshape/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

AutoShape を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | シェイプのロックを返します。 |
| [getAutoShapeLock()](#getAutoShapeLock--) | AutoShape のロックを返します。 |
| [getTextFrame()](#getTextFrame--) | AutoShape の TextFrame オブジェクトを返します。 |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | この AutoShape がスタイルや塗りつぶし形式で指定されたものではなく、スライドの背景塗りつぶしで塗りつぶされるかどうかを判断します。 |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | この AutoShape がスタイルや塗りつぶし形式で指定されたものではなく、スライドの背景塗りつぶしで塗りつぶされるかどうかを判断します。 |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | シェイプに新しい TextFrame を追加します。 |
| [isTextBox()](#isTextBox--) | シェイプがテキスト ボックスかどうかを指定します。 |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

シェイプのロックを返します。 読み取り専用 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**返り値:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

AutoShape のロックを返します。 読み取り専用 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)。

**返り値:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

AutoShape の TextFrame オブジェクトを返します。 読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**返り値:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

この AutoShape がスタイルや塗りつぶし形式で指定されたものではなく、スライドの背景塗りつぶしで塗りつぶされるかどうかを判断します。 読み書き可能な boolean。

**返り値:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

この AutoShape がスタイルや塗りつぶし形式で指定されたものではなく、スライドの背景塗りつぶしで塗りつぶされるかどうかを設定します。 読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

シェイプに新しい TextFrame を追加します。シェイプに既に TextFrame がある場合は、そのテキストを単に変更します。

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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しい TextFrame のデフォルト テキスト。 |

**返り値:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

シェイプがテキスト ボックスかどうかを指定します。

--------------------

シェイプがテキスト ボックスとして指定されていないからといって、テキストを保持できないわけではありません。テキスト ボックスは、特定のプロパティを持つ特殊なシェイプにすぎません。

**返り値:**
boolean