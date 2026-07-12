---
title: IParagraph
second_title: Aspose.Slides für Android über Java API-Referenz
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
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Läufe mit gleicher Formatierung. |
| [getText()](#getText--) | Liest oder setzt den reinen Text eines Absatzes. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den reinen Text eines Absatzes. |
| [getRect()](#getRect--) | Liefert die Koordinaten des Rechtecks, das den Absatz begrenzt. |
| [getLinesCount()](#getLinesCount--) | Liefert die Zeilenanzahl in einem Absatz. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Gibt die Abschnitteigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Gibt die Abschnitteigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird. |
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


Verbindet Läufe mit gleicher Formatierung.

### getText() {#getText--}
```
public abstract String getText()
```


Liest oder setzt den reinen Text eines Absatzes. Lese/Schreib-String.

Wert: Der Text.

**Rückgabe:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Liest oder setzt den reinen Text eines Absatzes. Lese/Schreib-String.

Wert: Der Text.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract RectF getRect()
```


Liefert die Koordinaten des Rechtecks, das den Absatz begrenzt. Das Rechteck umfasst alle Textzeilen im Absatz, einschließlich leerer Zeilen.

**Rückgabe:**
android.graphics.RectF - Rechteck, das den Absatz begrenzt android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```


Liefert die Anzahl der Zeilen in einem Absatz.

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
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Gibt die Abschnitteigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird.

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Gibt die Abschnitteigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |