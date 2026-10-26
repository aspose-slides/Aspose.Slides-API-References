---
title: ITable
second_title: Aspose.Slides Java API-referencia
description: Egy dián lévő táblát reprezentál.
type: docs
url: /hu/com.aspose.slides/itable/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Egy dián megjelenő táblát reprezentál.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Visszaadja a megadott oszlop- és sorindexeknél lévő cellát. |
| [getRows()](#getRows--) | Visszaadja a sorok gyűjteményét. |
| [getColumns()](#getColumns--) | Visszaadja az oszlopok gyűjteményét. |
| [getTableFormat()](#getTableFormat--) | Visszaadja a TableFormat objektumot, amely tartalmazza ennek a táblázatnak a formázási tulajdonságait. |
| [getStylePreset()](#getStylePreset--) | Lekéri vagy beállítja a beépített táblastílust. |
| [setStylePreset(int value)](#setStylePreset-int-) | Lekéri vagy beállítja a beépített táblastílust. |
| [getRightToLeft()](#getRightToLeft--) | Megállapítja, hogy a tábla jobbról balra olvasási sorrendet használ-e. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Megállapítja, hogy a tábla jobbról balra olvasási sorrendet használ-e. |
| [getFirstRow()](#getFirstRow--) | Megállapítja, hogy egy táblázat első sorát speciális formázásban kell-e megjeleníteni. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Megállapítja, hogy egy táblázat első sorát speciális formázásban kell-e megjeleníteni. |
| [getFirstCol()](#getFirstCol--) | Megállapítja, hogy egy táblázat első oszlopát speciális formázásban kell-e megjeleníteni. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Megállapítja, hogy egy táblázat első oszlopát speciális formázásban kell-e megjeleníteni. |
| [getLastRow()](#getLastRow--) | Megállapítja, hogy egy táblázat utolsó sorát speciális formázásban kell-e megjeleníteni. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Megállapítja, hogy egy táblázat utolsó sorát speciális formázásban kell-e megjeleníteni. |
| [getLastCol()](#getLastCol--) | Megállapítja, hogy egy táblázat utolsó oszlopát speciális formázásban kell-e megjeleníteni. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Megállapítja, hogy egy táblázat utolsó oszlopát speciális formázásban kell-e megjeleníteni. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Megállapítja, hogy a páros sorokat eltérő formázásban kell-e megjeleníteni. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Megállapítja, hogy a páros sorokat eltérő formázásban kell-e megjeleníteni. |
| [getVerticalBanding()](#getVerticalBanding--) | Megállapítja, hogy a páros oszlopokat eltérő formázásban kell-e megjeleníteni. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Megállapítja, hogy a páros oszlopokat eltérő formázásban kell-e megjeleníteni. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Összevonja a szomszédos cellákat. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Visszaadja a megadott oszlop- és sorindexeknél lévő cellát. Csak olvasható [ICell](../../com.aspose.slides/icell).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Visszaad:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Visszaadja a sorok gyűjteményét. Csak olvasható [IRowCollection](../../com.aspose.slides/irowcollection).

**Visszaad:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Visszaadja az oszlopok gyűjteményét. Csak olvasható [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Visszaad:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Visszaadja a TableFormat objektumot, amely tartalmazza ennek a táblázatnak a formázási tulajdonságait. Csak olvasható [ITableFormat](../../com.aspose.slides/itableformat).

**Visszaad:**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Lekéri vagy beállítja a beépített táblastílust. Olvasás/írás [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Visszaad:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Lekéri vagy beállítja a beépített táblastílust. Olvasás/írás [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Megállapítja, hogy a tábla jobbról balra olvasási sorrendet használ-e. Olvasás/írás boolean.

**Visszaad:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Megállapítja, hogy a tábla jobbról balra olvasási sorrendet használ-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Megállapítja, hogy egy táblázat első sorát speciális formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Visszaad:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Megállapítja, hogy egy táblázat első sorát speciális formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Megállapítja, hogy egy táblázat első oszlopát speciális formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Visszaad:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Megállapítja, hogy egy táblázat első oszlopát speciális formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Megállapítja, hogy egy táblázat utolsó sorát speciális formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Visszaad:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Megállapítja, hogy egy táblázat utolsó sorát speciális formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Megállapítja, hogy egy táblázat utolsó oszlopát speciális formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Visszaad:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Megállapítja, hogy egy táblázat utolsó oszlopát speciális formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Megállapítja, hogy a páros sorokat eltérő formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Visszaad:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Megállapítja, hogy a páros sorokat eltérő formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Megállapítja, hogy a páros oszlopokat eltérő formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Visszaad:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Megállapítja, hogy a páros oszlopokat eltérő formázásban kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Összevonja a szomszédos cellákat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Az összevonandó cella. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Az összevonandó cella. |
| allowSplitting | boolean | True, ha engedélyezi a cellák felosztását. |

**Visszaad:**
[ICell](../../com.aspose.slides/icell) - Összevont cella.