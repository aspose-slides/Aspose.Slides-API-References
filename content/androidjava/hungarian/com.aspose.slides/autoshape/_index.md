---
title: AutoShape
second_title: Aspose.Slides Androidra Java API hivatkozás segítségével
description: Egy AutoShape-et reprezentál.
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

AutoShape-et reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Visszaadja a forma zárolásait. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Visszaadja az autoshape zárolásait. |
| [getTextFrame()](#getTextFrame--) | Visszaadja a TextFrame objektumot az AutoShape-hez. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Megállapítja, hogy ez az autoshape a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Megállapítja, hogy ez az autoshape a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Új TextFrame-et ad a formához. |
| [isTextBox()](#isTextBox--) | Meghatározza, hogy a forma szövegdoboz-e. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Visszaadja a forma zárolásait. Csak olvasható [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

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

Megállapítja, hogy ez az autoshape a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Megállapítja, hogy ez az autoshape a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Új TextFrame-et ad a formához. Ha a forma már rendelkezik TextFrame-el, akkor egyszerűen megváltoztatja annak szövegét.

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
>  // Létrehozza a prezentációt
>  Presentation pres = new Presentation();
>  try {
>      // Lekéri az első diát a prezentációban
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Hozzáad egy AutoShape-et, amelynek típusa Téglalap
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Hozzáad egy TextFrame-et a Téglalaphoz
>      ashp.addTextFrame(" ");
>      // Eléri a szövegkeretet
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Létrehozza a bekezdés objektumot a szövegkerethez
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Létrehozza a Portion objektumot a bekezdéshez
>      IPortion portion = para.getPortions().get_Item(0);
>      // Beállítja a szöveget
>      portion.setText("Aspose TextBox");
>      // Mentése a prezentációt a lemezre
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Lekéri az első diát a prezentációban
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Hozzáad egy AutoShape-et, amelynek típusa Téglalap
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Hozzáad egy TextFrame-et a Téglalaphoz
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
>      // Mentés a prezentáció
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Alapértelmezett szöveg egy új TextFrame-hez. |

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Meghatározza, hogy a forma szövegdoboz-e.

--------------------

Ha a forma nincs megadva szövegdobozként, ez nem jelenti, hogy ne tartalmazhatna szöveget. A szövegdoboz csupán egy speciális tulajdonságokkal rendelkező forma.

**Visszatérési érték:**
boolean