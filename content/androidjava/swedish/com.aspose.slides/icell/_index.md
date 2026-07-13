---
title: ICell
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en cell i en tabell.
type: docs
url: /sv/com.aspose.slides/icell/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Representerar en cell i en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Returnerar ett avstånd från tabellens vänstra sida till cellens vänstra sida. |
| [getOffsetY()](#getOffsetY--) | Returnerar ett avstånd från tabellens övre sida till cellens övre sida. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Returnerar indexet för den första rad som täcks av cellen. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Returnerar indexet för den första kolumnen som täcks av cellen. |
| [getWidth()](#getWidth--) | Returnerar cellens bredd. |
| [getHeight()](#getHeight--) | Returnerar cellens höjd. |
| [getMinimalHeight()](#getMinimalHeight--) | Returnerar cellens minsta höjd. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar eller anger vänstermarginalen i en TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returnerar eller anger vänstermarginalen i en TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returnerar eller anger högermarginalen i en TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returnerar eller anger högermarginalen i en TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returnerar eller anger toppmarginalen i en TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returnerar eller anger toppmarginalen i en TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returnerar eller anger bottenmarginalen i en TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returnerar eller anger bottenmarginalen i en TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Returnerar eller anger typen av vertikal text. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Returnerar eller anger typen av vertikal text. |
| [getTextAnchorType()](#getTextAnchorType--) | Returnerar eller anger textankringstypen. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Returnerar eller anger textankringstypen. |
| [getAnchorCenter()](#getAnchorCenter--) | Avgör om textrutan är centrerad i cellen eller inte. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Avgör om textrutan är centrerad i cellen eller inte. |
| [getFirstColumn()](#getFirstColumn--) | Hämtar den första kolumnen i cellen. |
| [getFirstRow()](#getFirstRow--) | Hämtar den första raden i cellen. |
| [getColSpan()](#getColSpan--) | Returnerar antalet kolumngridskolumner i föräldertabellens tabellgrid som den aktuella cellen ska spänna. |
| [getRowSpan()](#getRowSpan--) | Returnerar antalet rader som en sammanslagen cell spänner över. |
| [getTextFrame()](#getTextFrame--) | Returnerar textramen för en cell. |
| [getTable()](#getTable--) | Returnerar föräldertabellobjektet för en cell. |
| [isMergedCell()](#isMergedCell--) | Returnerar sant om cellen är sammanslagen med någon justerad cell, annars falskt. |
| [getCellFormat()](#getCellFormat--) | Returnerar CellFormat-objektet som innehåller formateringsegenskaper för denna cell. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Delar cellen i två celler enligt kolumnindex. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Delar cellen i två celler enligt radindex. |
| [splitByHeight(double height)](#splitByHeight-double-) | Delar cellen efter höjd. |
| [splitByWidth(double width)](#splitByWidth-double-) | Delar cellen efter bredd. |

### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Returnerar ett avstånd från tabellens vänstra sida till cellens vänstra sida. Skrivskyddad double.

**Returnerar:**
double

### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Returnerar ett avstånd från tabellens övre sida till cellens övre sida. Skrivskyddad double.

**Returnerar:**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Returnerar indexet för den första rad som täcks av cellen. Skrivskyddad int.

**Returnerar:**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Returnerar indexet för den första kolumnen som täcks av cellen. Skrivskyddad int.

**Returnerar:**
int

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Returnerar cellens bredd. Skrivskyddad double.

**Returnerar:**
double

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Returnerar cellens höjd. Skrivskyddad double.

**Returnerar:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Returnerar cellens minsta höjd. Detta är en summa av de minsta höjderna för alla rader som cellen täcker. Skrivskyddad double.

**Returnerar:**
double

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Returnerar eller anger vänstermarginalen i en TextFrame. Läs/skriv double.

**Returnerar:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Returnerar eller anger vänstermarginalen i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Returnerar eller anger högermarginalen i en TextFrame. Läs/skriv double.

**Returnerar:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Returnerar eller anger högermarginalen i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Returnerar eller anger toppmarginalen i en TextFrame. Läs/skriv double.

**Returnerar:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Returnerar eller anger toppmarginalen i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Returnerar eller anger bottenmarginalen i en TextFrame. Läs/skriv double.

**Returnerar:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Returnerar eller anger bottenmarginalen i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Returnerar eller anger typen av vertikal text. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returnerar:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Returnerar eller anger typen av vertikal text. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Returnerar eller anger textankringstypen. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returnerar:**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Returnerar eller anger textankringstypen. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Avgör om textrutan är centrerad i cellen eller inte. Läs/skriv boolean.

**Returnerar:**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Avgör om textrutan är centrerad i cellen eller inte. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Hämtar den första kolumnen i cellen. Skrivskyddad [IColumn](../../com.aspose.slides/icolumn).

**Returnerar:**
[IColumn](../../com.aspose.slides/icolumn)

### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Hämtar den första raden i cellen. Skrivskyddad [IRow](../../com.aspose.slides/irow).

**Returnerar:**
[IRow](../../com.aspose.slides/irow)

### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Returnerar antalet kolumngridskolumner i föräldertabellens tabellgrid som den aktuella cellen ska spänna. Detta egenskap möjliggör att celler får ett sammanslaget utseende, då de spänner över vertikala gränser för andra celler i tabellen. Skrivskyddad int.

**Returnerar:**
int

### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Returnerar antalet rader som en sammanslagen cell spänner över. Detta används i kombination med vMerge-attributet på andra celler för att ange den första cellen i en horisontell sammanslagning. Skrivskyddad int.

**Returnerar:**
int

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Returnerar textramen för en cell. Skrivskyddad [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Returnerar föräldertabellobjektet för en cell. Skrivskyddad [ITable](../../com.aspose.slides/itable).

**Returnerar:**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Returnerar sant om cellen är sammanslagen med någon justerad cell, annars falskt. Skrivskyddad boolean.

**Returnerar:**
boolean

### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Returnerar CellFormat-objektet som innehåller formateringsegenskaper för denna cell. Skrivskyddad [ICellFormat](../../com.aspose.slides/icellformat).

**Returnerar:**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Delar cellen i två celler enligt kolumnindex.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för kolumn. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Delar cellen i två celler enligt radindex.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för rad. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Delar cellen efter höjd.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| height | double | Höjd på en rad. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Delar cellen efter bredd.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | double | Bredd på en kolumn. |