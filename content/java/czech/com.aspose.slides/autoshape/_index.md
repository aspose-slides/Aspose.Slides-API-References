---
title: AutoShape
second_title: Aspose.Slides pro Java – referenční příručka API
description: Zastupuje AutoShape.
type: docs
url: /cs/com.aspose.slides/autoshape/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Všechny implementované rozhraní:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Zastupuje AutoShape.
## Metody

| Metoda | Popis |
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

Vrací zámky tvaru. Pouze pro čtení [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Vrací:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Vrací zámky autoshape. Pouze pro čtení [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Vrací:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Vrací objekt TextFrame pro AutoShape. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Určuje, zda má být tento autoshape vyplněn výplní pozadí snímku místo výplně určené stylem nebo formátem výplně. Čtení/Zápis boolean.

**Vrací:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Určuje, zda má být tento autoshape vyplněn výplní pozadí snímku místo výplně určené stylem nebo formátem výplně. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Přidá nový TextFrame do tvaru. Pokud tvar již má TextFrame, pak jednoduše změní jeho text.

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
>  // Vytvoří instanci Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Získá první snímek v prezentaci
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Přidá AutoShape s typem nastaveným na Obdélník
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Přidá TextFrame do Obdélníku
>      ashp.addTextFrame(" ");
>      // Přistoupí k textovému rámci
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Vytvoří objekt Paragraph pro textový rámec
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Vytvoří objekt Portion pro odstavec
>      IPortion portion = para.getPortions().get_Item(0);
>      // Nastaví text
>      portion.setText("Aspose TextBox");
>      // Uloží prezentaci na disk
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Získá první snímek v prezentaci
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Přidá AutoShape s typem nastaveným na Obdélník
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Přidá TextFrame do Obdélníku
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Získá formát textu TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Určuje počet sloupců v TextFrame
>      format.setColumnCount(3);
>      // Určuje rozestup mezi sloupci
>      format.setColumnSpacing(10);
>      // Uloží prezentaci
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Výchozí text pro nový TextFrame. |

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Určuje, zda je tvar textovým polem.

--------------------

Pokud tvar není specifikován jako textové pole, neznamená to, že nemůže mít připojený text. Textové pole je jen specializovaný tvar se specifickými vlastnostmi.

**Vrací:**
boolean