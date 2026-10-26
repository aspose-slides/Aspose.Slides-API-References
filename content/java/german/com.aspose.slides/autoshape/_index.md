---
title: AutoShape
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein AutoShape dar.
type: docs
url: /de/com.aspose.slides/autoshape/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Stellt ein AutoShape dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Gibt die Sperren des Shapes zurück. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Gibt die Sperren des AutoShape zurück. |
| [getTextFrame()](#getTextFrame--) | Gibt das TextFrame-Objekt für das AutoShape zurück. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bestimmt, ob dieses AutoShape mit dem Hintergrundfüllung der Folie gefüllt werden soll, anstatt durch Stil oder Füllformat festgelegt zu werden. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bestimmt, ob dieses AutoShape mit dem Hintergrundfüllung der Folie gefüllt werden soll, anstatt durch Stil oder Füllformat festgelegt zu werden. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Fügt einem Shape ein neues TextFrame hinzu. |
| [isTextBox()](#isTextBox--) | Gibt an, ob das Shape ein Textfeld ist. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Gibt die Sperren des Shapes zurück. Nur-Lesen [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Rückgabe:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Gibt die Sperren des AutoShape zurück. Nur-Lesen [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Rückgabe:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Gibt das TextFrame-Objekt für das AutoShape zurück. Nur-Lesen [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Bestimmt, ob dieses AutoShape mit dem Hintergrundfüllung der Folie gefüllt werden soll, anstatt durch Stil oder Füllformat festgelegt zu werden. Lese/Schreib Boolean.

**Rückgabe:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Bestimmt, ob dieses AutoShape mit dem Hintergrundfüllung der Folie gefüllt werden soll, anstatt durch Stil oder Füllformat festgelegt zu werden. Lese/Schreib Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Fügt einem Shape ein neues TextFrame hinzu. Wenn das Shape bereits ein TextFrame hat, wird dessen Text einfach geändert.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Standardtext für ein neues TextFrame. |

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Gibt an, ob das Shape ein Textfeld ist.

--------------------

Wenn das Shape nicht als Textfeld angegeben ist, bedeutet das nicht, dass es keinen Text enthalten kann. Ein Textfeld ist lediglich ein spezialisiertes Shape mit spezifischen Eigenschaften.

**Rückgabe:**
boolean