---
title: AutoShape
second_title: Aspose.Slides dla Androida – odwołanie API Java
description: Reprezentuje AutoShape.
type: docs
url: /pl/com.aspose.slides/autoshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

Represents an AutoShape.
## Metody

| Metoda | Opis |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Zwraca blokady kształtu. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Zwraca blokady autoshape. |
| [getTextFrame()](#getTextFrame--) | Zwraca obiekt TextFrame dla AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Określa, czy ten autoshape powinien być wypełniony wypełnieniem tła slajdu zamiast określonego przez styl lub format wypełnienia. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Określa, czy ten autoshape powinien być wypełniony wypełnieniem tła slajdu zamiast określonego przez styl lub format wypełnienia. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Dodaje nowy TextFrame do kształtu. |
| [isTextBox()](#isTextBox--) | Określa, czy kształt jest polem tekstowym. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Zwraca blokady kształtu. Tylko do odczytu [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Zwraca:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Zwraca blokady autoshape. Tylko do odczytu [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Zwraca:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Zwraca obiekt TextFrame dla AutoShape. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Określa, czy ten autoshape powinien być wypełniony wypełnieniem tła slajdu zamiast określonego przez styl lub format wypełnienia. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Określa, czy ten autoshape powinien być wypełniony wypełnieniem tła slajdu zamiast określonego przez styl lub format wypełnienia. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Dodaje nowy TextFrame do kształtu. Jeśli kształt już posiada TextFrame, po prostu zmienia jego tekst.

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
>  // Tworzy obiekt Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Pobiera pierwszy slajd w prezentacji
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Dodaje AutoShape o typie Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Dodaje TextFrame do Rectangle
>      ashp.addTextFrame(" ");
>      // Uzyskuje dostęp do ramki tekstowej
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Tworzy obiekt Paragraph dla ramki tekstowej
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Tworzy obiekt Portion dla akapitu
>      IPortion portion = para.getPortions().get_Item(0);
>      // Ustawia tekst
>      portion.setText("Aspose TextBox");
>      // Zapisuje prezentację na dysk
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Pobiera pierwszy slajd w prezentacji
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Dodaje AutoShape o typie Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Dodaje TextFrame do Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Pobiera format tekstu TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Określa liczbę kolumn w TextFrame
>      format.setColumnCount(3);
>      // Określa odstęp między kolumnami
>      format.setColumnSpacing(10);
>      // Zapisuje prezentację
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Domyślny tekst dla nowego TextFrame. |

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

Określa, czy kształt jest polem tekstowym.

--------------------

Jeśli kształt nie jest określony jako pole tekstowe, nie oznacza to, że nie może mieć do niego dołączonego tekstu. Pole tekstowe jest jedynie specjalnym kształtem o określonych właściwościach.

**Zwraca:**
boolean