---
title: ITable
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa una tabla en una diapositiva.
type: docs
url: /es/com.aspose.slides/itable/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Representa una tabla en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Devuelve la celda en los índices de columna y fila especificados. |
| [getRows()](#getRows--) | Devuelve la colección de filas. |
| [getColumns()](#getColumns--) | Devuelve la colección de columnas. |
| [getTableFormat()](#getTableFormat--) | Devuelve el objeto TableFormat que contiene las propiedades de formato para esta tabla. |
| [getStylePreset()](#getStylePreset--) | Obtiene o establece el estilo de tabla incorporado. |
| [setStylePreset(int value)](#setStylePreset-int-) | Obtiene o establece el estilo de tabla incorporado. |
| [getRightToLeft()](#getRightToLeft--) | Determina si la tabla tiene orden de lectura de derecha a izquierda. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Determina si la tabla tiene orden de lectura de derecha a izquierda. |
| [getFirstRow()](#getFirstRow--) | Determina si la primera fila de una tabla debe dibujarse con un formato especial. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Determina si la primera fila de una tabla debe dibujarse con un formato especial. |
| [getFirstCol()](#getFirstCol--) | Determina si la primera columna de una tabla debe dibujarse con un formato especial. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Determina si la primera columna de una tabla debe dibujarse con un formato especial. |
| [getLastRow()](#getLastRow--) | Determina si la última fila de una tabla debe dibujarse con un formato especial. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Determina si la última fila de una tabla debe dibujarse con un formato especial. |
| [getLastCol()](#getLastCol--) | Determina si la última columna de una tabla debe dibujarse con un formato especial. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Determina si la última columna de una tabla debe dibujarse con un formato especial. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Determina si las filas pares deben dibujarse con un formato diferente. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Determina si las filas pares deben dibujarse con un formato diferente. |
| [getVerticalBanding()](#getVerticalBanding--) | Determina si las columnas pares deben dibujarse con un formato diferente. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Determina si las columnas pares deben dibujarse con un formato diferente. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Fusiona celdas vecinas. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```


Devuelve la celda en los índices de columna y fila especificados. Solo lectura [ICell](../../com.aspose.slides/icell).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Devuelve:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```


Devuelve la colección de filas. Solo lectura [IRowCollection](../../com.aspose.slides/irowcollection).

**Devuelve:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```


Devuelve la colección de columnas. Solo lectura [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Devuelve:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```


Devuelve el objeto TableFormat que contiene las propiedades de formato para esta tabla. Solo lectura [ITableFormat](../../com.aspose.slides/itableformat).

**Devuelve:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```


Obtiene o establece el estilo de tabla incorporado. Lectura/escritura [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Devuelve:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```


Obtiene o establece el estilo de tabla incorporado. Lectura/escritura [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Determina si la tabla tiene orden de lectura de derecha a izquierda. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```


Determina si la tabla tiene orden de lectura de derecha a izquierda. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```


Determina si la primera fila de una tabla debe dibujarse con un formato especial. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```


Determina si la primera fila de una tabla debe dibujarse con un formato especial. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```


Determina si la primera columna de una tabla debe dibujarse con un formato especial. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```


Determina si la primera columna de una tabla debe dibujarse con un formato especial. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```


Determina si la última fila de una tabla debe dibujarse con un formato especial. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```


Determina si la última fila de una tabla debe dibujarse con un formato especial. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```


Determina si la última columna de una tabla debe dibujarse con un formato especial. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```


Determina si la última columna de una tabla debe dibujarse con un formato especial. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```


Determina si las filas pares deben dibujarse con un formato diferente. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```


Determina si las filas pares deben dibujarse con un formato diferente. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```


Determina si las columnas pares deben dibujarse con un formato diferente. Booleano de lectura/escritura.

**Devuelve:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```


Determina si las columnas pares deben dibujarse con un formato diferente. Booleano de lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


Fusiona celdas vecinas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Celda a fusionar. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Celda a fusionar. |
| allowSplitting | boolean | True para permitir la división de celdas. |

**Devuelve:**
[ICell](../../com.aspose.slides/icell) - Celda fusionada.