---
title: Table
second_title: Aspose.Slides for Java API hivatkozás
description: Egy táblát reprezentál egy dián.
type: docs
url: /hu/com.aspose.slides/table/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Egy táblát reprezentál egy dián.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Visszaadja a megadott oszlop- és sorindexeknél lévő cellát. |
| [getRows()](#getRows--) | Visszaadja a sorok gyűjteményét. |
| [getColumns()](#getColumns--) | Visszaadja az oszlopok gyűjteményét. |
| [getTableFormat()](#getTableFormat--) | Visszaadja a TableFormat objektumot, amely a táblához tartozó formázási tulajdonságokat tartalmazza. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Egyesíti a szomszédos cellákat. |
| [getStylePreset()](#getStylePreset--) | Lekéri vagy beállítja a beépített táblastílust. |
| [setStylePreset(int value)](#setStylePreset-int-) | Lekéri vagy beállítja a beépített táblastílust. |
| [getRightToLeft()](#getRightToLeft--) | Megállapítja, hogy a táblának jobb-balra olvasási sorrendje van-e. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Megállapítja, hogy a táblának jobb-balra olvasási sorrendje van-e. |
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
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Beállítja a megadott részformázási tulajdonságokat az összes táblacellához tartozó részre. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Beállítja a megadott bekezdésformázási tulajdonságokat az összes táblacellához tartozó bekezdésre. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Beállítja a megadott szövegdoboz-formázási tulajdonságokat az összes táblacellához tartozó szövegdobozra. |
| [getFillFormat()](#getFillFormat--) | Visszaad egy TableFormat.FillFormat objektumot, amely a tábla kitöltési formázását tartalmazza. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Visszaadja a megadott oszlop- és sorindexeknél lévő cellát. Csak olvasható [Cell](../../com.aspose.slides/cell).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Visszatérési érték:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Visszaadja a sorok gyűjteményét. Csak olvasható [IRowCollection](../../com.aspose.slides/irowcollection).

**Visszatérési érték:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Visszaadja az oszlopok gyűjteményét. Csak olvasható [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Visszatérési érték:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Visszaadja a TableFormat objektumot, amely a táblához tartozó formázási tulajdonságokat tartalmazza. Csak olvasható [ITableFormat](../../com.aspose.slides/itableformat).

**Visszatérési érték:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Egyesíti a szomszédos cellákat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Egyesítendő cella. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Egyesítendő cella. |
| allowSplitting | boolean | Igaz, ha a cellák felosztása megengedett. |

**Visszatérési érték:**
[ICell](../../com.aspose.slides/icell) - Egyesített cella.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Lekéri vagy beállítja a beépített táblastílust. Olvasás/írás [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Visszatérési érték:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Lekéri vagy beállítja a beépített táblastílust. Olvasás/írás [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Megállapítja, hogy a táblának jobb-balra olvasási sorrendje van-e. Olvasás-írás  boolean .

**Visszatérési érték:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Megállapítja, hogy a táblának jobb-balra olvasási sorrendje van-e. Olvasás-írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Megállapítja, hogy a táblázat első sorát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Visszatérési érték:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Megállapítja, hogy a táblázat első sorát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Megállapítja, hogy a táblázat első oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Visszatérési érték:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Megállapítja, hogy a táblázat első oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Megállapítja, hogy a táblázat utolsó sorát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Visszatérési érték:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Megállapítja, hogy a táblázat utolsó sorát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Megállapítja, hogy a táblázat utolsó oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Visszatérési érték:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Megállapítja, hogy a táblázat utolsó oszlopát speciális formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Megállapítja, hogy a páros sorokat eltérő formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Visszatérési érték:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Megállapítja, hogy a páros sorokat eltérő formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Megállapítja, hogy a páros oszlopokat eltérő formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Visszatérési érték:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Megállapítja, hogy a páros oszlopokat eltérő formázással kell-e megjeleníteni. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Beállítja a megadott részformázási tulajdonságokat az összes táblacellához tartozó részre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat objektum a szükséges tulajdonságokkal beállítva. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Beállítja a megadott bekezdésformázási tulajdonságokat az összes táblacellához tartozó bekezdésre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat objektum a szükséges tulajdonságokkal beállítva. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Beállítja a megadott szövegdoboz-formázási tulajdonságokat az összes táblacellához tartozó szövegdobozra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat objektum a szükséges tulajdonságokkal beállítva. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Visszaad egy TableFormat.FillFormat objektumot, amely a tábla kitöltési formázását tartalmazza. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatérési érték:**
[IFillFormat](../../com.aspose.slides/ifillformat)