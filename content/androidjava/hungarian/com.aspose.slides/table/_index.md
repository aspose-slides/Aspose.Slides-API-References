---
title: Table
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Egy dián megjelenő táblát reprezentál.
type: docs
url: /hu/com.aspose.slides/table/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Az összes megvalósított interfész:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Egy dián megjelenő táblát reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Visszaadja a megadott oszlop- és sorindexeknél lévő cellát. |
| [getRows()](#getRows--) | Visszaadja a sorok gyűjteményét. |
| [getColumns()](#getColumns--) | Visszaadja az oszlopok gyűjteményét. |
| [getTableFormat()](#getTableFormat--) | Visszaadja a TableFormat objektumot, amely a táblához tartozó formázási tulajdonságokat tartalmazza. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Összevonja a szomszédos cellákat. |
| [getStylePreset()](#getStylePreset--) | Lekérdezi vagy beállítja a beépített táblastílust. |
| [setStylePreset(int value)](#setStylePreset-int-) | Lekérdezi vagy beállítja a beépített táblastílust. |
| [getRightToLeft()](#getRightToLeft--) | Megállapítja, hogy a tábla jobb-balra olvasási sorrendet használ-e. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Megállapítja, hogy a tábla jobb-balra olvasási sorrendet használ-e. |
| [getFirstRow()](#getFirstRow--) | Megállapítja, hogy a tábla első sorát speciális formázással kell-e megjeleníteni. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Megállapítja, hogy a tábla első sorát speciális formázással kell-e megjeleníteni. |
| [getFirstCol()](#getFirstCol--) | Megállapítja, hogy a tábla első oszlopát speciális formázással kell-e megjeleníteni. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Megállapítja, hogy a tábla első oszlopát speciális formázással kell-e megjeleníteni. |
| [getLastRow()](#getLastRow--) | Megállapítja, hogy a tábla utolsó sorát speciális formázással kell-e megjeleníteni. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Megállapítja, hogy a tábla utolsó sorát speciális formázással kell-e megjeleníteni. |
| [getLastCol()](#getLastCol--) | Megállapítja, hogy a tábla utolsó oszlopát speciális formázással kell-e megjeleníteni. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Megállapítja, hogy a tábla utolsó oszlopát speciális formázással kell-e megjeleníteni. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Megállapítja, hogy a páros sorokat eltérő formázással kell-e megjeleníteni. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Megállapítja, hogy a páros sorokat eltérő formázással kell-e megjeleníteni. |
| [getVerticalBanding()](#getVerticalBanding--) | Megállapítja, hogy a páros oszlopokat eltérő formázással kell-e megjeleníteni. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Megállapítja, hogy a páros oszlopokat eltérő formázással kell-e megjeleníteni. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Beállítja a meghatározott részformátum tulajdonságait az összes táblacellához tartozó részre. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Beállítja a meghatározott bekezdésformátum tulajdonságait az összes táblacellához tartozó bekezdésre. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Beállítja a meghatározott szövegkeret-formátum tulajdonságait az összes táblacellához tartozó szövegkeretre. |
| [getFillFormat()](#getFillFormat--) | Visszaad egy TableFormat.FillFormat objektumot, amely a tábla kitöltési formázását tartalmazza. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```


Visszaadja a megadott oszlop- és sorindexeknél lévő cellát. Csak olvasható [Cell](../../com.aspose.slides/cell).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Returns:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public final IRowCollection getRows()
```


Visszaadja a sorok gyűjteményét. Csak olvasható [IRowCollection](../../com.aspose.slides/irowcollection).

**Returns:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```


Visszaadja az oszlopok gyűjteményét. Csak olvasható [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Returns:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```


Visszaadja a TableFormat objektumot, amely a táblához tartozó formázási tulajdonságokat tartalmazza. Csak olvasható [ITableFormat](../../com.aspose.slides/itableformat).

**Returns:**
[ITableFormat](../../com.aspose.slides/itableformat)
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


Összevonja a szomszédos cellákat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | A cella, amelyet össze kell vonni. |
| cell2 | [ICell](../../com.aspose.slides/icell) | A cella, amelyet össze kell vonni. |
| allowSplitting | boolean | True to allow cells splitting. |

**Returns:**
[ICell](../../com.aspose.slides/icell) - Összevont cella.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```


Lekérdezi vagy beállítja a beépített táblastílust. Olvasás/írás [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Returns:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```


Lekérdezi vagy beállítja a beépített táblastílust. Olvasás/írás [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```


Megállapítja, hogy a tábla jobb-balra olvasási sorrendet használ-e. Olvasás/írás  boolean .

**Returns:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```


Megállapítja, hogy a tábla jobb-balra olvasási sorrendet használ-e. Olvasás/írás  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```


Megállapítja, hogy a tábla első sorát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Returns:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```


Megállapítja, hogy a tábla első sorát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```


Megállapítja, hogy a tábla első oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Returns:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```


Megállapítja, hogy a tábla első oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```


Megállapítja, hogy a tábla utolsó sorát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Returns:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```


Megállapítja, hogy a tábla utolsó sorát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```


Megállapítja, hogy a tábla utolsó oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Returns:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```


Megállapítja, hogy a tábla utolsó oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```


Megállapítja, hogy a páros sorokat eltérő formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Returns:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```


Megállapítja, hogy a páros sorokat eltérő formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```


Megállapítja, hogy a páros oszlopokat eltérő formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Returns:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```


Megállapítja, hogy a páros oszlopokat eltérő formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Beállítja a meghatározott részformátum tulajdonságait az összes táblacellához tartozó részre.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Beállítja a meghatározott bekezdésformátum tulajdonságait az összes táblacellához tartozó bekezdésre.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Beállítja a meghatározott szövegkeret-formátum tulajdonságait az összes táblacellához tartozó szövegkeretre.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```


Visszaad egy TableFormat.FillFormat objektumot, amely a tábla kitöltési formázását tartalmazza. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)