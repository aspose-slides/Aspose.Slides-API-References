---
title: ITable
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta una tabella su una diapositiva.
type: docs
url: /it/com.aspose.slides/itable/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Rappresenta una tabella su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Restituisce la cella agli indici di colonna e riga specificati. |
| [getRows()](#getRows--) | Restituisce la raccolta di righe. |
| [getColumns()](#getColumns--) | Restituisce la raccolta di colonne. |
| [getTableFormat()](#getTableFormat--) | Restituisce l'oggetto TableFormat che contiene le proprietà di formattazione per questa tabella. |
| [getStylePreset()](#getStylePreset--) | Ottiene o imposta lo stile di tabella incorporato. |
| [setStylePreset(int value)](#setStylePreset-int-) | Ottiene o imposta lo stile di tabella incorporato. |
| [getRightToLeft()](#getRightToLeft--) | Determina se la tabella ha l'ordine di lettura da destra a sinistra. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Determina se la tabella ha l'ordine di lettura da destra a sinistra. |
| [getFirstRow()](#getFirstRow--) | Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale. |
| [getFirstCol()](#getFirstCol--) | Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale. |
| [getLastRow()](#getLastRow--) | Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale. |
| [getLastCol()](#getLastCol--) | Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Determina se le righe pari devono essere disegnate con una formattazione diversa. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Determina se le righe pari devono essere disegnate con una formattazione diversa. |
| [getVerticalBanding()](#getVerticalBanding--) | Determina se le colonne pari devono essere disegnate con una formattazione diversa. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Determina se le colonne pari devono essere disegnate con una formattazione diversa. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Unisce le celle vicine. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Restituisce la cella agli indici di colonna e riga specificati. Solo lettura [ICell](../../com.aspose.slides/icell).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Restituisce:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Restituisce la raccolta di righe. Solo lettura [IRowCollection](../../com.aspose.slides/irowcollection).

**Restituisce:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Restituisce la raccolta di colonne. Solo lettura [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Restituisce:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Restituisce l'oggetto TableFormat che contiene le proprietà di formattazione per questa tabella. Solo lettura [ITableFormat](../../com.aspose.slides/itableformat).

**Restituisce:**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Ottiene o imposta lo stile di tabella incorporato. Lettura/scrittura [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Restituisce:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Ottiene o imposta lo stile di tabella incorporato. Lettura/scrittura [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Determina se la tabella ha l'ordine di lettura da destra a sinistra. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Determina se la tabella ha l'ordine di lettura da destra a sinistra. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Determina se le righe pari devono essere disegnate con una formattazione diversa. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Determina se le righe pari devono essere disegnate con una formattazione diversa. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Determina se le colonne pari devono essere disegnate con una formattazione diversa. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Determina se le colonne pari devono essere disegnate con una formattazione diversa. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Unisce le celle vicine.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cella da unire. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cella da unire. |
| allowSplitting | boolean | True per consentire la divisione delle celle. |

**Restituisce:**
[ICell](../../com.aspose.slides/icell) - Cella unita.