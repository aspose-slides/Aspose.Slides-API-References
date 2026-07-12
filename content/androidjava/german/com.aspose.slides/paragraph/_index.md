---
title: Paragraph
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Absatz von Text dar.
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

Stellt einen Textabsatz dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Paragraph()](#Paragraph--) | Initialisiert eine neue Instanz der Paragraph-Klasse mit Standardwerten. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Kopierkonstruktor, der eine neue Instanz einer Paragraph-Klasse initialisiert. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPortions()](#getPortions--) | Gibt die Sammlung von Textabschnitten zurück. |
| [getParagraphFormat()](#getParagraphFormat--) | Gibt das Formatierungsobjekt für diesen Absatz zurück. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Führt Läufe mit gleicher Formatierung zusammen. |
| [getText()](#getText--) | Liest oder legt den reinen Text eines Absatzes fest. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder legt den reinen Text eines Absatzes fest. |
| [getRect()](#getRect--) | Ermittelt die Koordinaten des Rechtecks, das den Absatz begrenzt. |
| [getLinesCount()](#getLinesCount--) | Ermittelt die Anzahl der Zeilen in einem Absatz. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Gibt die Abschnittseigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Gibt die Abschnittseigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines Absatzes zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines Absatzes zurück. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Initialisiert eine neue Instanz der Paragraph-Klasse mit Standardwerten.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Kopierkonstruktor, der eine neue Instanz einer Paragraph-Klasse initialisiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```


Gibt die Sammlung von Textabschnitten zurück. Nur lesbar [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Rückgabe:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```


Gibt das Formatierungsobjekt für diesen Absatz zurück. Nur lesbar [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Das Formatierungsobjekt enthält nur die für den aktuellen Absatz definierten Formatierungsparameter; geerbte Daten werden nicht angewendet.

Um die effektiven Werte einschließlich der geerbten zu erhalten, verwenden Sie die [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective)-Methode.

**Rückgabe:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Führt Läufe mit gleicher Formatierung zusammen.

### getText() {#getText--}
```
public final String getText()
```


Liest oder legt den reinen Text eines Absatzes fest. Lesen/Schreiben String.

Wert: Der Text.

**Rückgabe:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Liest oder legt den reinen Text eines Absatzes fest. Lesen/Schreiben String.

Wert: Der Text.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```


Ermittelt die Koordinaten des Rechtecks, das den Absatz begrenzt. Das Rechteck umfasst alle Textzeilen im Absatz, einschließlich leerer Zeilen.

**Rückgabe:**
android.graphics.RectF
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

**Rückgabe:**
int - Zeilenanzahl in einem Absatz
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Gibt die Abschnittseigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird.

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Gibt die Abschnittseigenschaften an, die verwendet werden sollen, wenn ein weiterer Abschnitt nach dem letzten eingefügt wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Gibt die übergeordnete Folie eines Absatzes zurück. Nur lesbar [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Gibt die übergeordnete Präsentation eines Absatzes zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)