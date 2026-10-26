---
title: ITable
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en tabell på en bild.
type: docs
url: /sv/com.aspose.slides/itable/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Representerar en tabell på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Returnerar cellen på de angivna kolumn- och radindexen. |
| [getRows()](#getRows--) | Returnerar samlingen av rader. |
| [getColumns()](#getColumns--) | Returnerar samlingen av kolumner. |
| [getTableFormat()](#getTableFormat--) | Returnerar TableFormat-objektet som innehåller formateringsegenskaper för denna tabell. |
| [getStylePreset()](#getStylePreset--) | Hämtar eller anger inbyggd tabelstil. |
| [setStylePreset(int value)](#setStylePreset-int-) | Hämtar eller anger inbyggd tabelstil. |
| [getRightToLeft()](#getRightToLeft--) | Avgör om tabellen har läsordning från höger till vänster. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Avgör om tabellen har läsordning från höger till vänster. |
| [getFirstRow()](#getFirstRow--) | Avgör om den första raden i en tabell ska ritas med särskild formatering. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Avgör om den första raden i en tabell ska ritas med särskild formatering. |
| [getFirstCol()](#getFirstCol--) | Avgör om den första kolumnen i en tabell ska ritas med särskild formatering. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Avgör om den första kolumnen i en tabell ska ritas med särskild formatering. |
| [getLastRow()](#getLastRow--) | Avgör om den sista raden i en tabell ska ritas med särskild formatering. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Avgör om den sista raden i en tabell ska ritas med särskild formatering. |
| [getLastCol()](#getLastCol--) | Avgör om den sista kolumnen i en tabell ska ritas med särskild formatering. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Avgör om den sista kolumnen i en tabell ska ritas med särskild formatering. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Avgör om jämna rader ska ritas med annan formatering. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Avgör om jämna rader ska ritas med annan formatering. |
| [getVerticalBanding()](#getVerticalBanding--) | Avgör om jämna kolumner ska ritas med annan formatering. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Avgör om jämna kolumner ska ritas med annan formatering. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Sammanfogar intilliggande celler. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```


Returnerar cellen på de angivna kolumn- och radindexen. Läs-endast [ICell](../../com.aspose.slides/icell).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Returnerar:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```


Returnerar samlingen av rader. Läs-endast [IRowCollection](../../com.aspose.slides/irowcollection).

**Returnerar:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```


Returnerar samlingen av kolumner. Läs-endast [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Returnerar:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```


Returnerar TableFormat-objektet som innehåller formateringsegenskaper för denna tabell. Läs-endast [ITableFormat](../../com.aspose.slides/itableformat).

**Returnerar:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```


Hämtar eller anger inbyggd tabelstil. Läs/skriv [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Returnerar:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```


Hämtar eller anger inbyggd tabelstil. Läs/skriv [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Avgör om tabellen har läsordning från höger till vänster. Läs-skriv boolesk.

**Returnerar:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```


Avgör om tabellen har läsordning från höger till vänster. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```


Avgör om den första raden i en tabell ska ritas med särskild formatering. Läs-skriv boolesk.

**Returnerar:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```


Avgör om den första raden i en tabell ska ritas med särskild formatering. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```


Avgör om den första kolumnen i en tabell ska ritas med särskild formatering. Läs-skriv boolesk.

**Returnerar:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```


Avgör om den första kolumnen i en tabell ska ritas med särskild formatering. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```


Avgör om den sista raden i en tabell ska ritas med särskild formatering. Läs-skriv boolesk.

**Returnerar:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```


Avgör om den sista raden i en tabell ska ritas med särskild formatering. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```


Avgör om den sista kolumnen i en tabell ska ritas med särskild formatering. Läs-skriv boolesk.

**Returnerar:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```


Avgör om den sista kolumnen i en tabell ska ritas med särskild formatering. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```


Avgör om jämna rader ska ritas med annan formatering. Läs-skriv boolesk.

**Returnerar:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```


Avgör om jämna rader ska ritas med annan formatering. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```


Avgör om jämna kolumner ska ritas med annan formatering. Läs-skriv boolesk.

**Returnerar:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```


Avgör om jämna kolumner ska ritas med annan formatering. Läs-skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


Sammanfogar intilliggande celler.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell att slå ihop. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell att slå ihop. |
| allowSplitting | boolean | Sant för att tillåta cellsplittning. |

**Returnerar:**
[ICell](../../com.aspose.slides/icell) - Sammanfogad cell.