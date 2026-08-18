---
title: AutoShape
second_title: Aspose.Slides Java API referencia
description: AutoShape-et reprezentál.
type: docs
url: /hu/com.aspose.slides/autoshape/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Minden megvalósított interfész:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Automatikus alakzatot reprezentál.
## Metódusok

| Metódus | Leírás |
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


Visszaadja az alakzat zárolásait. Csak olvasható [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Visszatérési érték:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```


Visszaadja az autoshape zárolásait. Csak olvasható [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Visszatérési érték:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Visszaadja a TextFrame objektumot az AutoShape-hez. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```


Meghatározza, hogy ez az autoshape a dia háttér kitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```


Meghatározza, hogy ez az autoshape a dia háttér kitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```


Új TextFrame-et ad hozzá egy alakzathoz. Ha az alakzat már rendelkezik TextFrame-el, akkor egyszerűen megváltoztatja a szöveget.

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
>  // Példányosítja a Presentation-t
>  Presentation pres = new Presentation();
>  try {
>      // Lekéri a prezentáció első diát
>      ISlide sld = pres.getSlides().get_Item(0);
>      // AutoShape-et ad hozzá, típusként Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // TextFrame-et ad a Rectangle-hez
>      ashp.addTextFrame(" ");
>      // Eléri a szövegkeretet
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Létrehozza a Paragraph objektumot a szövegkerethez
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Létrehozza a Portion objektumot a bekezdéshez
>      IPortion portion = para.getPortions().get_Item(0);
>      // Beállítja a szöveget
>      portion.setText("Aspose TextBox");
>      // Mentse a prezentációt a lemezre
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Lekéri a prezentáció első diát
>      ISlide slide = pres.getSlides().get_Item(0);
>      // AutoShape-et ad hozzá, típusként Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // TextFrame-et ad a Rectangle-hez
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Lekéri a TextFrame szövegformátumát
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Megadja a oszlopok számát a TextFrame-ben
>      format.setColumnCount(3);
>      // Megadja az oszlopok közti távolságot
>      format.setColumnSpacing(10);
>      // Mentse a prezentációt
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Default text for a new TextFrame. |

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```


Megadja, hogy az alakzat szövegdoboz-e.

--------------------

Ha egy alakzat nincs megadva szövegdobozként, az nem jelenti, hogy ne tudna szöveget tartalmazni. A szövegdoboz csupán egy speciális alakzat, amely meghatározott tulajdonságokkal rendelkezik.

**Visszatérési érték:**
boolean