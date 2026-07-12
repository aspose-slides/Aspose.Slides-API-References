---
title: IMathMatrix
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Especifica el objeto Matrix que consta de elementos secundarios dispuestos en una o más filas y columnas.
type: docs
url: /es/com.aspose.slides/imathmatrix/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Especifica el objeto Matrix, que consiste en elementos secundarios dispuestos en una o más filas y columnas. Es importante observar que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre corchetes debe usar el objeto delimitador (IMathDelimiter). Los argumentos nulos pueden usarse para crear espacios en blanco en las matrices.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elementos de la matriz |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elementos de la matriz |
| [getRowCount()](#getRowCount--) | Número de filas en la matriz |
| [getColumnCount()](#getColumnCount--) | Número de columnas en la matriz |
| [getHidePlaceholders()](#getHidePlaceholders--) | Ocultar los marcadores de posición para los elementos de la matriz vacíos Predeterminado: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Ocultar los marcadores de posición para los elementos de la matriz vacíos Predeterminado: false |
| [getBaseJustification()](#getBaseJustification--) | Especifica la justificación vertical respecto al texto circundante. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Especifica la justificación vertical respecto al texto circundante. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Ancho mínimo de columna en twips (1/20 de punto) El espaciado de la brecha (también denominado \\u201cColumn Gap\\u201d o \\u201cGap Width\\u201d) se añade al MinColumnWidth para determinar el espaciado total de columnas de la matriz (distancia entre los mismos bordes de diferentes columnas). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Ancho mínimo de columna en twips (1/20 de punto) El espaciado de la brecha (también denominado \\u201cColumn Gap\\u201d o \\u201cGap Width\\u201d) se añade al MinColumnWidth para determinar el espaciado total de columnas de la matriz (distancia entre los mismos bordes de diferentes columnas). |
| [getColumnGapRule()](#getColumnGapRule--) | El tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | El tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). |
| [getColumnGap()](#getColumnGap--) | El valor del espaciado horizontal entre columnas de una matriz; si ColumnGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto) Si ColumnGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como número de incrementos de 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | El valor del espaciado horizontal entre columnas de una matriz; si ColumnGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto) Si ColumnGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como número de incrementos de 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | El tipo de espaciado vertical entre filas de una matriz; las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | El tipo de espaciado vertical entre filas de una matriz; las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). |
| [getRowGap()](#getRowGap--) | El valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto) Si RowGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como medias líneas. |
| [setRowGap(long value)](#setRowGap-long-) | El valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto) Si RowGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como medias líneas. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Obtener la alineación horizontal de la columna especificada |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Establecer la alineación horizontal de la columna especificada |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Establecer la alineación horizontal de las columnas especificadas |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Insertar una nueva fila antes de la especificada. Inicialmente todos los elementos de la nueva fila son nulos. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Insertar una nueva fila después de la especificada. Inicialmente todos los elementos de la nueva fila son nulos. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Elimina la fila especificada |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Insertar una nueva columna antes de la especificada. Inicialmente todos los elementos de la nueva columna son nulos. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Insertar una nueva columna después de la especificada. Inicialmente todos los elementos de la nueva columna son nulos. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Elimina la columna especificada |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Elementos de la matriz

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| row | int | El índice basado en cero de la fila para obtener el elemento |
| column | int | El índice basado en cero de la columna para obtener el elemento |

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Elementos de la matriz

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| row | int | El índice basado en cero de la fila para obtener el elemento |
| column | int | El índice basado en cero de la columna para obtener el elemento |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

Número de filas en la matriz

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Devuelve:**
int

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Número de columnas en la matriz

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```


**Devuelve:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

Ocultar los marcadores de posición para los elementos de la matriz vacíos Predeterminado: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Devuelve:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Ocultar los marcadores de posición para los elementos de la matriz vacíos Predeterminado: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Especifica la justificación vertical respecto al texto circundante. Los valores posibles son top, bottom y center. Predeterminado: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Devuelve:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Especifica la justificación vertical respecto al texto circundante. Los valores posibles son top, bottom y center. Predeterminado: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

Ancho mínimo de columna en twips (1/20 de punto) El espaciado de la brecha (también denominado \\u201cColumn Gap\\u201d o \\u201cGap Width\\u201d) se añade al MinColumnWidth para determinar el espaciado total de columnas de la matriz (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Devuelve:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Ancho mínimo de columna en twips (1/20 de punto) El espaciado de la brecha (también denominado \\u201cColumn Gap\\u201d o \\u201cGap Width\\u201d) se añade al MinColumnWidth para determinar el espaciado total de columnas de la matriz (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

El tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Devuelve:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

El tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

El valor del espaciado horizontal entre columnas de una matriz; si ColumnGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto) Si ColumnGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Devuelve:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

El valor del espaciado horizontal entre columnas de una matriz; si ColumnGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto) Si ColumnGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

El tipo de espaciado vertical entre filas de una matriz; las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Devuelve:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

El tipo de espaciado vertical entre filas de una matriz; las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

El valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto) Si RowGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como medias líneas. Predeterminado: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```


**Devuelve:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

El valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto) Si RowGapRule está configurado en 4 (\"Multiple\"), la unidad se interpreta como medias líneas. Predeterminado: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Obtener la alineación horizontal de la columna especificada

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | int | Índice de columna basado en cero |

**Devuelve:**
int - Alineación horizontal de la columna especificada

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Establecer la alineación horizontal de la columna especificada

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | int | Índice de columna basado en cero |
| val | int | Nuevo valor de la alineación horizontal de la columna especificada |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Establecer la alineación horizontal de las columnas especificadas

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | int | Índice basado en cero de la primera columna para establecer la alineación |
| columnsCount | long | El número de columnas para especificar la alineación |
| val | int | Nuevo valor de la alineación horizontal de la columna especificada |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Insertar una nueva fila antes de la especificada. Inicialmente todos los elementos de la nueva fila son nulos.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rowIndex | int | Índice de la fila antes de la cual insertar una nueva |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Insertar una nueva fila después de la especificada. Inicialmente todos los elementos de la nueva fila son nulos.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rowIndex | int | Índice de la fila después de la cual insertar una nueva |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Elimina la fila especificada

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rowIndex | int | El índice basado en cero de la fila a eliminar. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Insertar una nueva columna antes de la especificada. Inicialmente todos los elementos de la nueva columna son nulos.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | int | Índice de la columna antes de la cual insertar una nueva |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Insertar una nueva columna después de la especificada. Inicialmente todos los elementos de la nueva columna son nulos.

--------------------

> ```
> Example:
>  
  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | int | Índice de la columna después de la cual insertar una nueva |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Elimina la columna especificada

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | int | El índice basado en cero de la columna a eliminar. |