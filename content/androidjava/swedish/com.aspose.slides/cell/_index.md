---
title: Cell
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en cell i en tabell.
type: docs
url: /sv/com.aspose.slides/cell/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Representerar en cell i en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Returnerar ett avstånd från vänstra sidan av en tabell till vänstra sidan av en cell. |
| [getOffsetY()](#getOffsetY--) | Returnerar ett avstånd från övre sidan av en tabell till övre sidan av en cell. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Returnerar index för den första raden som täcks av cellen. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Returnerar index för den första kolumnen som täcks av cellen. |
| [getWidth()](#getWidth--) | Returnerar cellens bredd. |
| [getHeight()](#getHeight--) | Returnerar cellens höjd. |
| [getMinimalHeight()](#getMinimalHeight--) | Returnerar den minsta höjden för en cell. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar eller anger den vänstra marginalen i en TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returnerar eller anger den vänstra marginalen i en TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returnerar eller anger den högra marginalen i en TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returnerar eller anger den högra marginalen i en TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returnerar eller anger den övre marginalen i en TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returnerar eller anger den övre marginalen i en TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returnerar eller anger den nedre marginalen i en TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returnerar eller anger den nedre marginalen i en TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Returnerar eller anger typen av vertikal text. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Returnerar eller anger typen av vertikal text. |
| [getTextAnchorType()](#getTextAnchorType--) | Returnerar eller anger ankartypen för texten. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Returnerar eller anger ankartypen för texten. |
| [getAnchorCenter()](#getAnchorCenter--) | Bestämmer om en textruta är centrerad i en cell eller inte. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Bestämmer om en textruta är centrerad i en cell eller inte. |
| [getFirstRow()](#getFirstRow--) | Hämtar den första raden i cellen. |
| [getFirstColumn()](#getFirstColumn--) | Hämtar den första kolumnen i cellen. |
| [getColSpan()](#getColSpan--) | Returnerar antalet rutnätskolumner i föräldertabellens tabellrutnät som ska sträcka över av den aktuella cellen. |
| [getRowSpan()](#getRowSpan--) | Returnerar antalet rader som en sammanslagen cell sträcker över. |
| [getTextFrame()](#getTextFrame--) | Returnerar textramen för en cell. |
| [getTable()](#getTable--) | Returnerar föräldra-Table-objektet för en cell. |
| [isMergedCell()](#isMergedCell--) | Returnerar sant om cellen är sammanslagen med någon justerad cell, annars falskt. |
| [getCellFormat()](#getCellFormat--) | Returnerar CellFormat-objektet som innehåller formateringsegenskaper för denna cell. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Delar cellen i två celler efter kolumnindex. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Delar cellen i två celler efter radindex. |
| [splitByHeight(double height)](#splitByHeight-double-) | Delar cellen efter höjd. |
| [splitByWidth(double width)](#splitByWidth-double-) | Delar cellen efter bredd. |
| [getSlide()](#getSlide--) | Returnerar föräldra-slide för en cell. |
| [getPresentation()](#getPresentation--) | Returnerar föräldrapresentationen för en cell. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Returnerar ett avstånd från vänstra sidan av en tabell till vänstra sidan av en cell. Skrivskyddad double.

**Returnerar:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Returnerar ett avstånd från övre sidan av en tabell till övre sidan av en cell. Skrivskyddad double.

**Returnerar:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Returnerar index för den första raden som täcks av cellen. Skrivskyddad int.

**Returnerar:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Returnerar index för den första kolumnen som täcks av cellen. Skrivskyddad int.

**Returnerar:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Returnerar cellens bredd. Skrivskyddad double.

**Returnerar:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Returnerar cellens höjd. Skrivskyddad double.

**Returnerar:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Returnerar den minsta höjden för en cell. Detta är en summa av minsta höjderna för alla rader som täcks av cellen. Skrivskyddad double.

**Returnerar:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Returnerar eller anger den vänstra marginalen i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Returnerar eller anger den vänstra marginalen i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Returnerar eller anger den högra marginalen i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Returnerar eller anger den högra marginalen i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Returnerar eller anger den övre marginalen i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Returnerar eller anger den övre marginalen i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Returnerar eller anger den nedre marginalen i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Returnerar eller anger den nedre marginalen i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Returnerar eller anger typen av vertikal text. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returnerar:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Returnerar eller anger typen av vertikal text. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Returnerar eller anger ankartypen för texten. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returnerar:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Returnerar eller anger ankartypen för texten. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Bestämmer om en textruta är centrerad i en cell eller inte. Läs/skriv boolean.

**Returnerar:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Bestämmer om en textruta är centrerad i en cell eller inte. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Hämtar den första raden i cellen. Skrivskyddad [IRow](../../com.aspose.slides/irow).

**Returnerar:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Hämtar den första kolumnen i cellen. Skrivskyddad [IColumn](../../com.aspose.slides/icolumn).

**Returnerar:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Returnerar antalet rutnätskolumner i föräldertabellens tabellrutnät som ska sträcka över av den aktuella cellen. Detta egenskap tillåter celler att se ut som sammanslagna, då de sträcker över vertikala gränser för andra celler i tabellen. Skrivskyddad int.

**Returnerar:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Returnerar antalet rader som en sammanslagen cell sträcker över. Detta används i kombination med vMerge-attributet på andra celler för att specificera startcellen för en horisontell sammanslagning. Skrivskyddad int.

**Returnerar:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Returnerar textramen för en cell. Skrivskyddad [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Returnerar föräldra-Table-objektet för en cell. Skrivskyddad [ITable](../../com.aspose.slides/itable).

**Returnerar:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Returnerar sant om cellen är sammanslagen med någon justerad cell, annars falskt. Skrivskyddad boolean.

**Returnerar:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Returnerar CellFormat-objektet som innehåller formateringsegenskaper för denna cell. Skrivskyddad [ICellFormat](../../com.aspose.slides/icellformat).

**Returnerar:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Delar cellen i två celler efter kolumnindex.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för kolumn. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Delar cellen i två celler efter radindex.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för rad. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Delar cellen efter höjd.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| height | double | Höjd på en rad. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Delar cellen efter bredd.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | double | Bredd på en kolumn. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar föräldra-slide för en cell. Skrivskyddad [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar föräldrapresentationen för en cell. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject