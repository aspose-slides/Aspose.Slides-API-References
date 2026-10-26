---
title: Table
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una tabla en una diapositiva.
type: docs
url: /es/com.aspose.slides/table/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Representa una tabla en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Devuelve la celda en los índices de columna y fila especificados. |
| [getRows()](#getRows--) | Devuelve la colección de filas. |
| [getColumns()](#getColumns--) | Devuelve la colección de columnas. |
| [getTableFormat()](#getTableFormat--) | Devuelve el objeto TableFormat que contiene las propiedades de formato para esta tabla. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Fusiona celdas vecinas. |
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
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Establece las propiedades de formato de porción definidas a todas las porciones de las celdas de la tabla. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Establece las propiedades de formato de párrafo definidas a todos los párrafos de las celdas de la tabla. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Establece las propiedades de formato de marco de texto definidas a todos los marcos de texto de las celdas de la tabla. |
| [getFillFormat()](#getFillFormat--) | Devuelve un objeto TableFormat.FillFormat que contiene el formato de relleno para la tabla. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Devuelve la celda en los índices de columna y fila especificados. Solo lectura [Cell](../../com.aspose.slides/cell).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Devuelve:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Devuelve la colección de filas. Solo lectura [IRowCollection](../../com.aspose.slides/irowcollection).

**Devuelve:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Devuelve la colección de columnas. Solo lectura [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Devuelve:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Devuelve el objeto TableFormat que contiene las propiedades de formato para esta tabla. Solo lectura [ITableFormat](../../com.aspose.slides/itableformat).

**Devuelve:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
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

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Obtiene o establece el estilo de tabla incorporado. Lectura/escritura [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Devuelve:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Obtiene o establece el estilo de tabla incorporado. Lectura/escritura [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Determina si la tabla tiene orden de lectura de derecha a izquierda. Lectura/escritura boolean.

**Devuelve:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Determina si la tabla tiene orden de lectura de derecha a izquierda. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Determina si la primera fila de una tabla debe dibujarse con un formato especial. Lectura/escritura boolean.

**Devuelve:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Determina si la primera fila de una tabla debe dibujarse con un formato especial. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Determina si la primera columna de una tabla debe dibujarse con un formato especial. Lectura/escritura boolean.

**Devuelve:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Determina si la primera columna de una tabla debe dibujarse con un formato especial. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Determina si la última fila de una tabla debe dibujarse con un formato especial. Lectura/escritura boolean.

**Devuelve:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Determina si la última fila de una tabla debe dibujarse con un formato especial. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Determina si la última columna de una tabla debe dibujarse con un formato especial. Lectura/escritura boolean.

**Devuelve:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Determina si la última columna de una tabla debe dibujarse con un formato especial. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Determina si las filas pares deben dibujarse con un formato diferente. Lectura/escritura boolean.

**Devuelve:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Determina si las filas pares deben dibujarse con un formato diferente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Determina si las columnas pares deben dibujarse con un formato diferente. Lectura/escritura boolean.

**Devuelve:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Determina si las columnas pares deben dibujarse con un formato diferente. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Establece las propiedades de formato de porción definidas a todas las porciones de las celdas de la tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Objeto IPortionFormat con las propiedades necesarias establecidas. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Establece las propiedades de formato de párrafo definidas a todos los párrafos de las celdas de la tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Objeto IParagraphFormat con las propiedades necesarias establecidas. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Establece las propiedades de formato de marco de texto definidas a todos los marcos de texto de las celdas de la tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Objeto ITextFrameFormat con las propiedades necesarias establecidas. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Devuelve un objeto TableFormat.FillFormat que contiene el formato de relleno para la tabla. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)