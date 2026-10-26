---
title: IParagraph
second_title: Aspose.Slides für die Java-API-Referenz
description: Stellt einen Absatz eines Textes dar.
type: docs
url: /de/com.aspose.slides/iparagraph/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Stellt einen Absatz eines Textes dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPortions()](#getPortions--) | Gibt die Sammlung von Textabschnitten zurück. |
| [getParagraphFormat()](#getParagraphFormat--) | Gibt das Formatierungsobjekt für diesen Absatz zurück. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Runs mit gleicher Formatierung. |
| [getText()](#getText--) | Liest oder setzt den Klartext eines Absatzes. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den Klartext eines Absatzes. |
| [getRect()](#getRect--) | Ermittelt die Koordinaten des Rechtecks, das den Absatz begrenzt. |
| [getLinesCount()](#getLinesCount--) | Ermittelt die Anzahl der Zeilen in einem Absatz. |
| [getImage()](#getImage--) | Gibt ein Bild des Absatzes zurück. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Gibt ein Bild des Absatzes mit dem angegebenen Maßstab zurück. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Gibt die Abschnittseigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Gibt die Abschnittseigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Gibt die Sammlung von Textabschnitten zurück. Nur lesbar [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Rückgabe:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Gibt das Formatierungsobjekt für diesen Absatz zurück. Nur lesbar [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Rückgabe:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Verbindet Runs mit gleicher Formatierung.
### getText() {#getText--}
```
public abstract String getText()
```

Liest oder setzt den Klartext eines Absatzes. Lesen/Schreiben String.

**Wert:** Der Text.

**Rückgabe:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Liest oder setzt den Klartext eines Absatzes. Lesen/Schreiben String.

**Wert:** Der Text.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Ermittelt die Koordinaten des Rechtecks, das den Absatz begrenzt. Das Rechteck umfasst alle Textzeilen im Absatz, einschließlich leerer Zeilen.

**Rückgabe:**
java.awt.geom.Rectangle2D.Float - Rechteck, das den Absatz begrenzt java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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

**Rückgabe:**
int - Zeilenanzahl in einem Absatz
### getImage() {#getImage--}
```
public abstract IImage getImage()
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

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Ein Bild, das den gerenderten Absatz enthält, oder null, wenn der Absatz in seiner übergeordneten Sammlung nicht gefunden werden kann, keine gültigen Rendergrenzen hat oder beim Rendern des Bildes ein Fehler auftritt.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
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

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Ein Bild, das den gerenderten Absatz enthält, oder null, wenn der Absatz in seiner übergeordneten Sammlung nicht gefunden werden kann, keine gültigen Rendergrenzen hat oder beim Rendern des Bildes ein Fehler auftritt.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Gibt die Abschnittseigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird.

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Gibt die Abschnittseigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |