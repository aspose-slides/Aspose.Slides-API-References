---
title: CellFormat
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getFillFormat()](#getFillFormat--) | Gibt ein Zellfüllformatobjekt zurück. |
| [getBorderLeft()](#getBorderLeft--) | Gibt ein Objekt für die linke Rahmenlinie zurück. |
| [getBorderTop()](#getBorderTop--) | Gibt ein Objekt für die obere Rahmenlinie zurück. |
| [getBorderRight()](#getBorderRight--) | Gibt ein Objekt für die rechte Rahmenlinie zurück. |
| [getBorderBottom()](#getBorderBottom--) | Gibt ein Objekt für die untere Rahmenlinie zurück. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Gibt ein Objekt für die diagonal von oben links nach unten rechts zurück. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Gibt ein Objekt für die diagonal von unten links nach oben rechts zurück. |
| [getEffective()](#getEffective--) | Gibt die effektiven Formatierungseigenschaften einer Tabellenzelle zurück, wobei Vererbung und Tabellenstile angewendet werden. |
| [getTransparency()](#getTransparency--) | Gibt die Transparenz der Füllfarbe zurück oder setzt sie. |
| [setTransparency(float value)](#setTransparency-float-) | Gibt die Transparenz der Füllfarbe zurück oder setzt sie. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Nur lesend long.

**Rückgabe:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Gibt ein Zellfüllformatobjekt zurück. Nur lesend [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Gibt ein Objekt für die linke Rahmenlinie zurück. Nur lesend [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Gibt ein Objekt für die obere Rahmenlinie zurück. Nur lesend [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Gibt ein Objekt für die rechte Rahmenlinie zurück. Nur lesend [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Gibt ein Objekt für die untere Rahmenlinie zurück. Nur lesend [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Gibt ein Objekt für die diagonal von oben links nach unten rechts zurück. Nur lesend [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Gibt ein Objekt für die diagonal von unten links nach oben rechts zurück. Nur lesend [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Gibt die effektiven Formatierungseigenschaften einer Tabellenzelle zurück, wobei Vererbung und Tabellenstile angewendet werden.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
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


Gibt die Transparenz der Füllfarbe zurück oder setzt sie. Lesen/Schreiben  float .

**Rückgabe:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Gibt die Transparenz der Füllfarbe zurück oder setzt sie. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |