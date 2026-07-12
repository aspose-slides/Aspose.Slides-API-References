---
title: AutoShape
second_title: Aspose.Slides für Android über Java API-Referenz
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
| [getShapeLock()](#getShapeLock--) | Gibt die Sperren der Form zurück. |
| [getAutoShapeLock()](#getAutoShapeLock--) | Gibt die Sperren des AutoShape zurück. |
| [getTextFrame()](#getTextFrame--) | Gibt das TextFrame-Objekt für das AutoShape zurück. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bestimmt, ob dieses AutoShape mit dem Hintergrundfüllungen der Folie gefüllt werden soll, anstatt durch Stil oder Füllformat angegeben zu werden. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bestimmt, ob dieses AutoShape mit dem Hintergrundfüllungen der Folie gefüllt werden soll, anstatt durch Stil oder Füllformat angegeben zu werden. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Fügt einer Form ein neues TextFrame hinzu. |
| [isTextBox()](#isTextBox--) | Gibt an, ob die Form ein Textfeld ist. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

Gibt die Sperren der Form zurück. Nur lesbar [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Rückgabe:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

Gibt die Sperren des AutoShape zurück. Nur lesbar [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Rückgabe:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Gibt das TextFrame-Objekt für das AutoShape zurück. Nur lesbar [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

Bestimmt, ob dieses AutoShape mit dem Hintergrundfüllungen der Folie gefüllt werden soll, anstatt durch Stil oder Füllformat angegeben zu werden. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

Bestimmt, ob dieses AutoShape mit dem Hintergrundfüllungen der Folie gefüllt werden soll, anstatt durch Stil oder Füllformat angegeben zu werden. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

Fügt einer Form ein neues TextFrame hinzu. Wenn die Form bereits ein TextFrame hat, wird einfach ihr Text geändert.

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
>  // Instanziiert die Präsentation
>  Presentation pres = new Presentation();
>  try {
>      // Ermittelt die erste Folie der Präsentation
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Fügt ein AutoShape vom Typ Rechteck hinzu
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Fügt dem Rechteck ein TextFrame hinzu
>      ashp.addTextFrame(" ");
>      // Greift auf das TextFrame zu
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Erstellt das Paragraph-Objekt für das TextFrame
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Erstellt ein Portion-Objekt für das Paragraph
>      IPortion portion = para.getPortions().get_Item(0);
>      // Setzt den Text
>      portion.setText("Aspose TextBox");
>      // Speichert die Präsentation auf dem Datenträger
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Ermittelt die erste Folie der Präsentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Fügt ein AutoShape vom Typ Rechteck hinzu
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Fügt dem Rechteck ein TextFrame hinzu
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Ermittelt das Textformat des TextFrames
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Legt die Anzahl der Spalten im TextFrame fest
>      format.setColumnCount(3);
>      // Legt den Abstand zwischen den Spalten fest
>      format.setColumnSpacing(10);
>      // Speichert die Präsentation
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

Gibt an, ob die Form ein Textfeld ist.

--------------------

Wenn eine Form nicht als Textfeld angegeben ist, bedeutet das nicht, dass sie keinen Text enthalten kann. Ein Textfeld ist lediglich eine spezialisierte Form mit bestimmten Eigenschaften.

**Rückgabe:**
boolean