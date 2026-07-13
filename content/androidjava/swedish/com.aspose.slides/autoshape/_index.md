---
title: AutoShape
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en AutoShape.
type: docs
url: /sv/com.aspose.slides/autoshape/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Representerar en AutoShape.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Returnerar formens lås. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Returnerar autoshapens lås. |
| [getTextFrame()](#getTextFrame--) | Returnerar TextFrame-objekt för AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bestämmer om denna autoshape ska fyllas med bildens bakgrundsfyllning istället för det som anges av stil eller fyllningsformat. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bestämmer om denna autoshape ska fyllas med bildens bakgrundsfyllning istället för det som anges av stil eller fyllningsformat. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Lägger till en ny TextFrame till en form. |
| [isTextBox()](#isTextBox--) | Anger om formen är en textruta. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```


Returnerar formens lås. Skrivskyddad [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Returnerar:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```


Returnerar autoshapens lås. Skrivskyddad [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Returnerar:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Returnerar TextFrame-objekt för AutoShape. Skrivskyddad [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```


Bestämmer om denna autoshape ska fyllas med bildens bakgrundsfyllning istället för det som anges av stil eller fyllningsformat. Läs/skriv boolean.

**Returnerar:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```


Bestämmer om denna autoshape ska fyllas med bildens bakgrundsfyllning istället för det som anges av stil eller fyllningsformat. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```


Lägger till en ny TextFrame till en form. Om formen redan har en TextFrame ändras bara dess text.

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
>  // Instansierar Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Hämtar den första bilden i presentationen
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Lägger till en AutoShape med typen Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Lägger till TextFrame till rektangeln
>      ashp.addTextFrame(" ");
>      // Kommer åt textramen
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Skapar Paragraph-objektet för textramen
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Skapar ett Portion-objekt för paragrafen
>      IPortion portion = para.getPortions().get_Item(0);
>      // Ställer in texten
>      portion.setText("Aspose TextBox");
>      // Sparar presentationen på disk
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Hämtar den första bilden i presentationen
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Lägg till en AutoShape med typen Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Lägg till TextFrame till rektangeln
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Hämtar textformatet för TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Anger antalet kolumner i TextFrame
>      format.setColumnCount(3);
>      // Anger avståndet mellan kolumnerna
>      format.setColumnSpacing(10);
>      // Sparar presentationen
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Standardtext för en ny TextFrame. |

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```


Anger om formen är en textruta.

--------------------

Om formen inte är angiven som en textruta betyder det inte att den inte kan ha text kopplad till sig. En textruta är bara en specialiserad form med specifika egenskaper.

**Returnerar:**
boolean