---
title: CellFormat
second_title: Aspose.Slides für Java API Referenz
description: Stellt das Format einer Tabellenzelle dar.
type: docs
url: /de/com.aspose.slides/cellformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Stellt das Format einer Tabellenzelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Gibt ein Objekt für Zellfüllungs-Properties zurück. |
| [getBorderLeft()](#getBorderLeft--) | Gibt ein Objekt für linke Randlinien-Properties zurück. |
| [getBorderTop()](#getBorderTop--) | Gibt ein Objekt für obere Randlinien-Properties zurück. |
| [getBorderRight()](#getBorderRight--) | Gibt ein Objekt für rechte Randlinien-Properties zurück. |
| [getBorderBottom()](#getBorderBottom--) | Gibt ein Objekt für untere Randlinien-Properties zurück. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Gibt ein Objekt für diagonale Linie von oben-links nach unten-rechts zurück. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Gibt ein Objekt für diagonale Linie von unten-links nach oben-rechts zurück. |
| [getEffective()](#getEffective--) | Ermittelt effektive Tabellenzellenformatierungs-Properties mit Vererbung und angewendeten Tabellenvorlagen. |
| [getTransparency()](#getTransparency--) | Ermittelt oder setzt die Transparenz der Füllfarbe. |
| [setTransparency(float value)](#setTransparency-float-) | Ermittelt oder setzt die Transparenz der Füllfarbe. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbar long.

**Rückgabe:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Gibt ein Objekt für Zellfüllungs-Properties zurück. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

Gibt ein Objekt für linke Randlinien-Properties zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Gibt ein Objekt für obere Randlinien-Properties zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Gibt ein Objekt für rechte Randlinien-Properties zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Gibt ein Objekt für untere Randlinien-Properties zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Gibt ein Objekt für diagonale Linie von oben-links nach unten-rechts zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Gibt ein Objekt für diagonale Linie von unten-links nach oben-rechts zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Ermittelt effektive Tabellenzellenformatierungs-Properties mit Vererbung und angewendeten Tabellenvorlagen.

--------------------

> ```
> Dieses Beispiel demonstriert das Abrufen des effektiven Füllformats für verschiedene logische Tabellenteile.
>  Bitte beachten Sie, dass die Zellformatierung immer höhere Priorität hat als die Zeilenformatierung, Zeilen höher als Spalten, und Spalten höher als die gesamte Tabelle.
>  Daher werden die CellFormatEffectiveData-Eigenschaften letztlich immer zum Zeichnen der Tabelle verwendet. Der folgende Code ist nur ein API-Beispiel.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Ermittelt oder setzt die Transparenz der Füllfarbe. Lesen/Schreiben  float .

**Rückgabe:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Ermittelt oder setzt die Transparenz der Füllfarbe. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |