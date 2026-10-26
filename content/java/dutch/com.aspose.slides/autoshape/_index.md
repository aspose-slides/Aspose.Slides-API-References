---
title: AutoShape
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een AutoShape voor.
type: docs
url: /nl/com.aspose.slides/autoshape/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Stelt een AutoShape voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Retourneert de vergrendelingen van de vorm. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Retourneert de vergrendelingen van de autovorm. |
| [getTextFrame()](#getTextFrame--) | Retourneert TextFrame-object voor de AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bepaalt of deze autovorm moet worden gevuld met de achtergrondvulling van de dia in plaats van gespecificeerd door stijl of vulopmaak. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bepaalt of deze autovorm moet worden gevuld met de achtergrondvulling van de dia in plaats van gespecificeerd door stijl of vulopmaak. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Voegt een nieuw TextFrame toe aan een vorm. |
| [isTextBox()](#isTextBox--) | Specificeert of de vorm een tekstvak is. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Retourneert de vergrendelingen van de vorm. Alleen-lezen [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Retour:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Retourneert de vergrendelingen van de autovorm. Alleen-lezen [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Retour:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Retourneert TextFrame-object voor de AutoShape. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Bepaalt of deze autovorm moet worden gevuld met de achtergrondvulling van de dia in plaats van gespecificeerd door stijl of vulopmaak. Lezen/Schrijven boolean.

**Retour:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Bepaalt of deze autovorm moet worden gevuld met de achtergrondvulling van de dia in plaats van gespecificeerd door stijl of vulopmaak. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Voegt een nieuw TextFrame toe aan een vorm. Als de vorm al een TextFrame heeft, wordt gewoon de tekst ervan gewijzigd.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Standaardtekst voor een nieuw TextFrame. |

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Specificeert of de vorm een tekstvak is.

--------------------

Als een vorm niet is opgegeven als een tekstvak, betekent dat niet dat er geen tekst aan kan worden gekoppeld. Een tekstvak is slechts een gespecialiseerde vorm met specifieke eigenschappen.

**Retour:**
boolean