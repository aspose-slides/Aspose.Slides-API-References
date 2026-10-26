---
title: Paragraph
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Absatz aus Text dar.
type: docs
url: /de/com.aspose.slides/paragraph/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Stellt einen Absatz aus Text dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Paragraph()](#Paragraph--) | Initialisiert eine neue Instanz der Paragraph Klasse mit Standardwerten. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Kopierkonstruktor, der eine neue Instanz einer Paragraph Klasse initialisiert. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPortions()](#getPortions--) | Gibt die Sammlung von Textportionen zurück. |
| [getParagraphFormat()](#getParagraphFormat--) | Gibt das Formatierungsobjekt für diesen Absatz zurück. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Führt Runs mit gleicher Formatierung zusammen. |
| [getText()](#getText--) | Liest oder schreibt den Klartext eines Absatzes. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder schreibt den Klartext eines Absatzes. |
| [getRect()](#getRect--) | Ermittelt die Koordinaten des Rechtecks, das den Absatz begrenzt. |
| [getLinesCount()](#getLinesCount--) | Ermittelt die Anzahl der Zeilen in einem Absatz. |
| [getImage()](#getImage--) | Gibt ein Bild des Absatzes zurück. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Gibt ein Bild des Absatzes mit dem angegebenen Maßstab zurück. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Gibt die Eigenschaften der Portion an, die verwendet werden sollen, wenn eine weitere Portion nach der letzten eingefügt wird. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Gibt die Eigenschaften der Portion an, die verwendet werden sollen, wenn eine weitere Portion nach der letzten eingefügt wird. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines Absatzes zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines Absatzes zurück. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Initialisiert eine neue Instanz der Paragraph Klasse mit Standardwerten.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Kopierkonstruktor, der eine neue Instanz einer Paragraph Klasse initialisiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Gibt die Sammlung von Textportionen zurück. Nur lesbar [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Rückgabewert:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Gibt das Formatierungsobjekt für diesen Absatz zurück. Nur lesbar [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Das Formatierungsobjekt enthält nur die für den aktuellen Absatz definierten Formatierungsparameter; geerbte Daten werden nicht angewendet.

Um die effektiven Werte einschließlich der geerbten zu erhalten, verwenden Sie die [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) Methode.

**Rückgabewert:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Führt Runs mit gleicher Formatierung zusammen.

### getText() {#getText--}
```
public final String getText()
```

Liest oder schreibt den Klartext eines Absatzes. Lesen/Schreiben String.

Wert: Der Text.

**Rückgabewert:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Liest oder schreibt den Klartext eines Absatzes. Lesen/Schreiben String.

Wert: Der Text.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Ermittelt die Koordinaten des Rechtecks, das den Absatz begrenzt. Das Rechteck umfasst alle Textzeilen im Absatz, einschließlich leerer Zeilen.

**Rückgabewert:**
java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

Ermittelt die Anzahl der Zeilen in einem Absatz.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
int - Zeilenzahl in einem Absatz
### getImage() {#getImage--}
```
public final IImage getImage()
```

Gibt ein Bild des Absatzes zurück.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Ein Bild, das den gerenderten Absatz enthält, oder null, wenn der Absatz in seiner übergeordneten Sammlung nicht gefunden werden kann, keine gültigen Rendergrenzen hat oder beim Rendern des Bildes ein Fehler auftritt.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Gibt ein Bild des Absatzes mit dem angegebenen Maßstab zurück.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | float | Der horizontale Skalierungsfaktor, der auf das Absatzbild angewendet wird. |
| scaleY | float | Der vertikale Skalierungsfaktor, der auf das Absatzbild angewendet wird. |

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Ein Bild, das den gerenderten Absatz enthält, oder null, wenn der Absatz in seiner übergeordneten Sammlung nicht gefunden werden kann, keine gültigen Rendergrenzen hat oder beim Rendern des Bildes ein Fehler auftritt.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Gibt die Eigenschaften der Portion an, die verwendet werden sollen, wenn eine weitere Portion nach der letzten eingefügt wird.

**Rückgabewert:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Gibt die Eigenschaften der Portion an, die verwendet werden sollen, wenn eine weitere Portion nach der letzten eingefügt wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate Objekt zurück. Nur lesbar IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines Absatzes zurück. Nur lesbar [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabewert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines Absatzes zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**
[IPresentation](../../com.aspose.slides/ipresentation)