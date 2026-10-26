---
title: ITable
second_title: Aspose.Slides Androidra a Java API Referencián keresztül
description: Egy dián lévő táblázatot képvisel.
type: docs
url: /hu/com.aspose.slides/itable/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Egy dián egy táblázatot képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Visszaadja a cellát a megadott oszlop- és sorindexeknél. |
| [getRows()](#getRows--) | Visszaadja a sorok gyűjteményét. |
| [getColumns()](#getColumns--) | Visszaadja az oszlopok gyűjteményét. |
| [getTableFormat()](#getTableFormat--) | Visszaadja a TableFormat objektumot, amely a táblázat formázási tulajdonságait tartalmazza. |
| [getStylePreset()](#getStylePreset--) | Beállítja vagy lekéri a beépített táblázatstílust. |
| [setStylePreset(int value)](#setStylePreset-int-) | Beállítja vagy lekéri a beépített táblázatstílust. |
| [getRightToLeft()](#getRightToLeft--) | Megállapítja, hogy a táblázat jobbról balra olvasási irányt használ-e. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Megállapítja, hogy a táblázat jobbról balra olvasási irányt használ-e. |
| [getFirstRow()](#getFirstRow--) | Megállapítja, hogy a táblázat első sorát speciális formázással kell-e megjeleníteni. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Megállapítja, hogy a táblázat első sorát speciális formázással kell-e megjeleníteni. |
| [getFirstCol()](#getFirstCol--) | Megállapítja, hogy a táblázat első oszlopát speciális formázással kell-e megjeleníteni. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Megállapítja, hogy a táblázat első oszlopát speciális formázással kell-e megjeleníteni. |
| [getLastRow()](#getLastRow--) | Megállapítja, hogy a táblázat utolsó sorát speciális formázással kell-e megjeleníteni. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Megállapítja, hogy a táblázat utolsó sorát speciális formázással kell-e megjeleníteni. |
| [getLastCol()](#getLastCol--) | Megállapítja, hogy a táblázat utolsó oszlopát speciális formázással kell-e megjeleníteni. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Megállapítja, hogy a táblázat utolsó oszlopát speciális formázással kell-e megjeleníteni. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Megállapítja, hogy a páros sorokat eltérő formázással kell-e megjeleníteni. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Megállapítja, hogy a páros sorokat eltérő formázással kell-e megjeleníteni. |
| [getVerticalBanding()](#getVerticalBanding--) | Megállapítja, hogy a páros oszlopokat eltérő formázással kell-e megjeleníteni. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Megállapítja, hogy a páros oszlopokat eltérő formázással kell-e megjeleníteni. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Összevonja a szomszédos cellákat. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Visszaadja a cellát a megadott oszlop- és sorindexeknél. Csak olvasható [ICell](../../com.aspose.slides/icell).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Visszatérési érték:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Visszaadja a sorok gyűjteményét. Csak olvasható [IRowCollection](../../com.aspose.slides/irowcollection).

**Visszatérési érték:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Visszaadja az oszlopok gyűjteményét. Csak olvasható [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Visszatérési érték:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Visszaadja a TableFormat objektumot, amely a táblázat formázási tulajdonságait tartalmazza. Csak olvasható [ITableFormat](../../com.aspose.slides/itableformat).

**Visszatérési érték:**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Beállítja vagy lekéri a beépített táblázatstílust. Olvasás/írás [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Visszatérési érték:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Beállítja vagy lekéri a beépített táblázatstílust. Olvasás/írás [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Megállapítja, hogy a táblázat jobbról balra olvasási irányt használ-e. Olvasás-írás boolean.

**Visszatérési érték:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Megállapítja, hogy a táblázat jobbról balra olvasási irányt használ-e. Olvasás-írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Megállapítja, hogy a táblázat első sorát speciális formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Megállapítja, hogy a táblázat első sorát speciális formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Megállapítja, hogy a táblázat első oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Megállapítja, hogy a táblázat első oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Megállapítja, hogy a táblázat utolsó sorát speciális formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Megállapítja, hogy a táblázat utolsó sorát speciális formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Megállapítja, hogy a táblázat utolsó oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Megállapítja, hogy a táblázat utolsó oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Megállapítja, hogy a páros sorokat eltérő formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Megállapítja, hogy a páros sorokat eltérő formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Megállapítja, hogy a páros oszlopokat eltérő formázással kell-e megjeleníteni. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Megállapítja, hogy a páros oszlopokat eltérő formázással kell-e megjeleníteni. Olvasás/írás boolean.

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
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

**Visszatérési érték:**
[ICell](../../com.aspose.slides/icell) - Merged cell.