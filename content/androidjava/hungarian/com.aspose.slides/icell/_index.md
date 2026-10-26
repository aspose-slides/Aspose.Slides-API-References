---
title: ICell
second_title: Aspose.Slides for Android Java API hivatkozás
description: Egy táblázat celláját képviseli.
type: docs
url: /hu/com.aspose.slides/icell/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

A táblázat egy celláját képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Visszaadja a táblázat bal oldalától a cella bal oldaláig tartó távolságot. |
| [getOffsetY()](#getOffsetY--) | Visszaadja a táblázat felső oldalától a cella felső oldaláig tartó távolságot. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Visszaadja a cella által lefedett első sor indexét. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Visszaadja a cella által lefedett első oszlop indexét. |
| [getWidth()](#getWidth--) | Visszaadja a cella szélességét. |
| [getHeight()](#getHeight--) | Visszaadja a cella magasságát. |
| [getMinimalHeight()](#getMinimalHeight--) | Visszaadja a cella minimális magasságát. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja vagy beállítja a bal margót egy TextFrame-ben. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Visszaadja vagy beállítja a bal margót egy TextFrame-ben. |
| [getMarginRight()](#getMarginRight--) | Visszaadja vagy beállítja a jobb margót egy TextFrame-ben. |
| [setMarginRight(double value)](#setMarginRight-double-) | Visszaadja vagy beállítja a jobb margót egy TextFrame-ben. |
| [getMarginTop()](#getMarginTop--) | Visszaadja vagy beállítja a felső margót egy TextFrame-ben. |
| [setMarginTop(double value)](#setMarginTop-double-) | Visszaadja vagy beállítja a felső margót egy TextFrame-ben. |
| [getMarginBottom()](#getMarginBottom--) | Visszaadja vagy beállítja az alsó margót egy TextFrame-ben. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Visszaadja vagy beállítja az alsó margót egy TextFrame-ben. |
| [getTextVerticalType()](#getTextVerticalType--) | Visszaadja vagy beállítja a függőleges szöveg típusát. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Visszaadja vagy beállítja a függőleges szöveg típusát. |
| [getTextAnchorType()](#getTextAnchorType--) | Visszaadja vagy beállítja a szöveg rögzítési típusát. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Visszaadja vagy beállítja a szöveg rögzítési típusát. |
| [getAnchorCenter()](#getAnchorCenter--) | Megállapítja, hogy a szövegdoboz középre van-e igazítva a cellában. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Megállapítja, hogy a szövegdoboz középre van-e igazítva a cellában. |
| [getFirstColumn()](#getFirstColumn--) | Az első oszlopot adja vissza a cellából. |
| [getFirstRow()](#getFirstRow--) | Az első sort adja vissza a cellából. |
| [getColSpan()](#getColSpan--) | Visszaadja a szülő tábla rácsában lévő, az aktuális cella által lefedett rácsoszlopok számát. |
| [getRowSpan()](#getRowSpan--) | Visszaadja a egyesített cella által lefedett sorok számát. |
| [getTextFrame()](#getTextFrame--) | Visszaadja a cella szövegkeretét. |
| [getTable()](#getTable--) | Visszaadja a cellához tartozó szülő Table objektumot. |
| [isMergedCell()](#isMergedCell--) | Igaz értéket ad, ha a cella egy bármely módosított cellával össze van vonva, egyébként hamis. |
| [getCellFormat()](#getCellFormat--) | Visszaadja a CellFormat objektumot, amely a cella formázási tulajdonságait tartalmazza. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Felosztja a cellát két cellára az oszlop indexe alapján. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Felosztja a cellát két cellára a sor indexe alapján. |
| [splitByHeight(double height)](#splitByHeight-double-) | A cellát magasság alapján osztja fel. |
| [splitByWidth(double width)](#splitByWidth-double-) | A cellát szélesség alapján osztja fel. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Visszaadja a táblázat bal oldalától a cella bal oldaláig tartó távolságot. Csak olvasható double.

**Visszatér:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Visszaadja a táblázat felső oldalától a cella felső oldaláig tartó távolságot. Csak olvasható double.

**Visszatér:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Visszaadja a cella által lefedett első sor indexét. Csak olvasható int.

**Visszatér:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Visszaadja a cella által lefedett első oszlop indexét. Csak olvasható int.

**Visszatér:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Visszaadja a cella szélességét. Csak olvasható double.

**Visszatér:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Visszaadja a cella magasságát. Csak olvasható double.

**Visszatér:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Visszaadja a cella minimális magasságát. Ez a cella által lefedett összes sor minimális magasságának összege. Csak olvasható double.

**Visszatér:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Visszaadja vagy beállítja a bal margót egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Visszaadja vagy beállítja a bal margót egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Visszaadja vagy beállítja a jobb margót egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Visszaadja vagy beállítja a jobb margót egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Visszaadja vagy beállítja a felső margót egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Visszaadja vagy beállítja a felső margót egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Visszaadja vagy beállítja az alsó margót egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Visszaadja vagy beállítja az alsó margót egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Visszaadja vagy beállítja a függőleges szöveg típusát. Olvasás/írás [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Visszatér:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Visszaadja vagy beállítja a függőleges szöveg típusát. Olvasás/írás [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Visszaadja vagy beállítja a szöveg rögzítési típusát. Olvasás/írás [TextAnchorType](../../com.aspose.slides/textanchortype).

**Visszatér:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Visszaadja vagy beállítja a szöveg rögzítési típusát. Olvasás/írás [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Megállapítja, hogy a szövegdoboz középre van-e igazítva a cellában. Olvasás/írás boolean.

**Visszatér:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Megállapítja, hogy a szövegdoboz középre van-e igazítva a cellában. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Az első oszlopot adja vissza a cellából. Csak olvasható [IColumn](../../com.aspose.slides/icolumn).

**Visszatér:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Az első sort adja vissza a cellából. Csak olvasható [IRow](../../com.aspose.slides/irow).

**Visszatér:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Visszaadja a szülő tábla rácsában lévő, az aktuális cella által lefedett rácsoszlopok számát. Ez a tulajdonság lehetővé teszi, hogy a cellák úgy jelenjenek meg, mint egyesített cellák, mivel átlépik más cellák függőleges határait a táblázatban. Csak olvasható int.

**Visszatér:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Visszaadja a egyesített cella által lefedett sorok számát. Ezt más cellák vMerge attribútumával együtt használják annak meghatározására, hogy melyik cella a vízszintes egyesítés kezdőcellája. Csak olvasható int.

**Visszatér:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Visszaadja a cella szövegkeretét. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Visszaadja a cellához tartozó szülő Table objektumot. Csak olvasható [ITable](../../com.aspose.slides/itable).

**Visszatér:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Igaz értéket ad, ha a cella egy bármely módosított cellával össze van vonva, egyébként hamis. Csak olvasható boolean.

**Visszatér:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Visszaadja a CellFormat objektumot, amely a cella formázási tulajdonságait tartalmazza. Csak olvasható [ICellFormat](../../com.aspose.slides/icellformat).

**Visszatér:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Felosztja a cellát két cellára az oszlop indexe alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az oszlop indexe. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Felosztja a cellát két cellára a sor indexe alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A sor indexe. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

A cellát magasság alapján osztja fel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| height | double | A sor magassága. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

A cellát szélesség alapján osztja fel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | double | Az oszlop szélessége. |