---
title: AutoShape
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een AutoShape voor.
type: docs
url: /nl/com.aspose.slides/autoshape/
---
**Erfenis:**
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
| [getShapeLock()](#getShapeLock--) | Retourneert de vergrendelingen van shape. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Retourneert de vergrendelingen van autoshape. |
| [getTextFrame()](#getTextFrame--) | Retourneert TextFrame-object voor de AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bepaalt of dit autoshape moet worden gevuld met de achtergrondvulling van de slide in plaats van gespecificeerd door stijl of vullingsopmaak. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bepaalt of dit autoshape moet worden gevuld met de achtergrondvulling van de slide in plaats van gespecificeerd door stijl of vullingsopmaak. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Voegt een nieuw TextFrame toe aan een shape. |
| [isTextBox()](#isTextBox--) | Specificeert of de shape een tekstvak is. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```


Retourneert de vergrendelingen van shape. Alleen-lezen [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Retour:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```


Retourneert de vergrendelingen van autoshape. Alleen-lezen [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

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


Bepaalt of dit autoshape moet worden gevuld met de achtergrondvulling van de slide in plaats van gespecificeerd door stijl of vullingsopmaak. Lezen/schrijven boolean.

**Retour:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```


Bepaalt of dit autoshape moet worden gevuld met de achtergrondvulling van de slide in plaats van gespecificeerd door stijl of vullingsopmaak. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```


Voegt een nieuw TextFrame toe aan een shape. Als de shape al een TextFrame heeft, wordt de tekst eenvoudig gewijzigd.

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
>  // Initialiseert Presentatie
>  Presentation pres = new Presentation();
>  try {
>      // Haalt de eerste slide op in de presentatie
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Voegt een AutoShape toe met type ingesteld op Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Voegt TextFrame toe aan de rechthoek
>      ashp.addTextFrame(" ");
>      // Toegang tot het tekstframe
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Creëert het Paragraph-object voor het tekstframe
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Creëert een Portion-object voor de alinea
>      IPortion portion = para.getPortions().get_Item(0);
>      // Stelt de tekst in
>      portion.setText("Aspose TextBox");
>      // Slaat de presentatie op naar schijf
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Haalt de eerste slide op in de presentatie
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Voeg een AutoShape toe met type ingesteld op Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Voeg TextFrame toe aan de rechthoek
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Haalt het tekstopmaak van TextFrame op
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Specificeert het aantal kolommen in TextFrame
>      format.setColumnCount(3);
>      // Specificeert de afstand tussen kolommen
>      format.setColumnSpacing(10);
>      // Slaat de presentatie op
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


Specificeert of de shape een tekstvak is.

--------------------

Als een shape niet is opgegeven als tekstvak, betekent dat niet dat er geen tekst aan gekoppeld kan worden. Een tekstvak is slechts een gespecialiseerde shape met specifieke eigenschappen.

**Retour:**
boolean