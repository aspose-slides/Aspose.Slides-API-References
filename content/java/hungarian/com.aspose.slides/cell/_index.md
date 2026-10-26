---
title: Cell
second_title: Aspose.Slides Java API hivatkozás
description: Egy táblázat celláját reprezentálja.
type: docs
url: /hu/com.aspose.slides/cell/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Egy táblázat celláját reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Visszaadja a táblázat bal oldalától a cella bal oldaláig mért távolságot. |
| [getOffsetY()](#getOffsetY--) | Visszaadja a táblázat felső oldalától a cella felső oldaláig mért távolságot. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Visszaadja a cella által lefedett első sor indexét. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Visszaadja a cella által lefedett első oszlop indexét. |
| [getWidth()](#getWidth--) | Visszaadja a cella szélességét. |
| [getHeight()](#getHeight--) | Visszaadja a cella magasságát. |
| [getMinimalHeight()](#getMinimalHeight--) | Visszaadja egy cella minimális magasságát. |
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
| [getAnchorCenter()](#getAnchorCenter--) | Megállapítja, hogy a szövegmező középre van-e igazítva a cellában. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Megállapítja, hogy a szövegmező középre van-e igazítva a cellában. |
| [getFirstRow()](#getFirstRow--) | Lekéri a cella első sorát. |
| [getFirstColumn()](#getFirstColumn--) | Lekéri a cella első oszlopát. |
| [getColSpan()](#getColSpan--) | Visszaadja a szülő táblázat táblarácsában lévő oszlopok számát, amelyet az aktuális cella lefed. |
| [getRowSpan()](#getRowSpan--) | Visszaadja a egyesített cella által lefedett sorok számát. |
| [getTextFrame()](#getTextFrame--) | Visszaadja a cella szövegkeretét. |
| [getTable()](#getTable--) | Visszaadja a cellához tartozó szülő Table objektumot. |
| [isMergedCell()](#isMergedCell--) | Igaz értéket ad vissza, ha a cella egy másik cellával össze van vonva, ellenkező esetben hamis. |
| [getCellFormat()](#getCellFormat--) | Visszaadja a CellFormat objektumot, amely a cella formázási tulajdonságait tartalmazza. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Felosztja a cellát két cellára az oszlop indexe alapján. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Felosztja a cellát két cellára a sor indexe alapján. |
| [splitByHeight(double height)](#splitByHeight-double-) | Felosztja a cellát magasság szerint. |
| [splitByWidth(double width)](#splitByWidth-double-) | Felosztja a cellát szélesség szerint. |
| [getSlide()](#getSlide--) | Visszaadja a cella szülő diát. |
| [getPresentation()](#getPresentation--) | Visszaadja a cella szülő prezentációját. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Visszaadja a táblázat bal oldalától a cella bal oldaláig mért távolságot. **Csak olvasható** double.

**Visszatér:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Visszaadja a táblázat felső oldalától a cella felső oldaláig mért távolságot. **Csak olvasható** double.

**Visszatér:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Visszaadja a cella által lefedett első sor indexét. **Csak olvasható** int.

**Visszatér:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Visszaadja a cella által lefedett első oszlop indexét. **Csak olvasható** int.

**Visszatér:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Visszaadja a cella szélességét. **Csak olvasható** double.

**Visszatér:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Visszaadja a cella magasságát. **Csak olvasható** double.

**Visszatér:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Visszaadja egy cella minimális magasságát. Ez a cella által lefedett összes sor minimális magasságának összege. **Csak olvasható** double.

**Visszatér:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Visszaadja vagy beállítja a bal margót egy TextFrame-ben. **Olvasás/írás** double.

**Visszatér:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Visszaadja vagy beállítja a bal margót egy TextFrame-ben. **Olvasás/írás** double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Visszaadja vagy beállítja a jobb margót egy TextFrame-ben. **Olvasás/írás** double.

**Visszatér:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Visszaadja vagy beállítja a jobb margót egy TextFrame-ben. **Olvasás/írás** double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Visszaadja vagy beállítja a felső margót egy TextFrame-ben. **Olvasás/írás** double.

**Visszatér:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Visszaadja vagy beállítja a felső margót egy TextFrame-ben. **Olvasás/írás** double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Visszaadja vagy beállítja az alsó margót egy TextFrame-ben. **Olvasás/írás** double.

**Visszatér:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Visszaadja vagy beállítja az alsó margót egy TextFrame-ben. **Olvasás/írás** double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Visszaadja vagy beállítja a függőleges szöveg típusát. **Olvasás/írás** [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Visszatér:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Visszaadja vagy beállítja a függőleges szöveg típusát. **Olvasás/írás** [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Visszaadja vagy beállítja a szöveg rögzítési típusát. **Olvasás/írás** [TextAnchorType](../../com.aspose.slides/textanchortype).

**Visszatér:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Visszaadja vagy beállítja a szöveg rögzítési típusát. **Olvasás/írás** [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Megállapítja, hogy a szövegmező középre van-e igazítva a cellában. **Olvasás/írás** boolean.

**Visszatér:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Megállapítja, hogy a szövegmező középre van-e igazítva a cellában. **Olvasás/írás** boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Lekéri a cella első sorát. **Csak olvasható** [IRow](../../com.aspose.slides/irow).

**Visszatér:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Lekéri a cella első oszlopát. **Csak olvasható** [IColumn](../../com.aspose.slides/icolumn).

**Visszatér:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Visszaadja a szülő táblázat táblarácsában lévő oszlopok számát, amelyet az aktuális cella lefed. Ez a tulajdonság lehetővé teszi, hogy a cellák egyesítettnek tűnjenek, mivel a táblában más cellák függőleges határait átfogják. **Csak olvasható** int.

**Visszatér:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Visszaadja a egyesített cella által lefedett sorok számát. Ezt a vMerge attribútummal kombinálva használják más cellákon, hogy megadják egy vízszintes egyesítés kiinduló celláját. **Csak olvasható** int.

**Visszatér:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Visszaadja a cella szövegkeretét. **Csak olvasható** [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Visszaadja a cellához tartozó szülő Table objektumot. **Csak olvasható** [ITable](../../com.aspose.slides/itable).

**Visszatér:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Igaz értéket ad vissza, ha a cella egy másik cellával össze van vonva, ellenkező esetben hamis. **Csak olvasható** boolean.

**Visszatér:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Visszaadja a CellFormat objektumot, amely a cella formázási tulajdonságait tartalmazza. **Csak olvasható** [ICellFormat](../../com.aspose.slides/icellformat).

**Visszatér:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Felosztja a cellát két cellára az oszlop indexe alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az oszlop indexe. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Felosztja a cellát két cellára a sor indexe alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A sor indexe. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Felosztja a cellát magasság szerint.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| height | double | A sor magassága. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Felosztja a cellát szélesség szerint.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | double | Az oszlop szélessége. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a cella szülő diát. **Csak olvasható** [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a cella szülő prezentációját. **Csak olvasható** [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent\_Immediate objektumot. **Csak olvasható** IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject