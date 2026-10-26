---
title: MathMatrix
second_title: Aspose.Slides para Android vía referencia de API Java
description: Especifica el objeto Matrix que consta de elementos secundarios dispuestos en una o más filas y columnas.
type: docs
url: /es/com.aspose.slides/mathmatrix/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Especifica el objeto Matrix, que consiste en elementos secundarios dispuestos en una o más filas y columnas. Es importante notar que las matrices no tienen delimitadores incorporados. Para colocar la matriz entre corchetes debe usar el objeto delimitador (IMathDelimiter). Los argumentos nulos pueden usarse para crear huecos en las matrices.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Inicializa una nueva instancia de la clase MathMatrix. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRowCount()](#getRowCount--) | Número de filas en la matriz |
| [getColumnCount()](#getColumnCount--) | Número de columnas en la matriz |
| [getHidePlaceholders()](#getHidePlaceholders--) | Ocultar los marcadores de posición para elementos de matriz vacíos Predeterminado: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Ocultar los marcadores de posición para elementos de matriz vacíos Predeterminado: false |
| [getBaseJustification()](#getBaseJustification--) | Especifica la justificación vertical con respecto al texto circundante. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Especifica la justificación vertical con respecto al texto circundante. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Ancho mínimo de columna en twips (1/20 de punto). El espaciado de la brecha (también llamado \u201cColumn Gap\u201d o \u201cGap Width\u201d) se suma a MinColumnWidth para determinar el espaciado total de columnas de la matriz (distancia entre los mismos bordes de diferentes columnas). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Ancho mínimo de columna en twips (1/20 de punto). El espaciado de la brecha (también llamado \u201cColumn Gap\u201d o \u201cGap Width\u201d) se suma a MinColumnWidth para determinar el espaciado total de columnas de la matriz (distancia entre los mismos bordes de diferentes columnas). |
| [getColumnGapRule()](#getColumnGapRule--) | Tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). |
| [getColumnGap()](#getColumnGap--) | Valor del espaciado horizontal entre columnas de una matriz; si ColumnGapRule está configurado a 3 (“Exactly”), la unidad se interpreta como twips (1/20 de punto). Si ColumnGapRule está configurado a 4 (“Multiple”), la unidad se interpreta como número de incrementos de 0,5 em. En otros casos se ignora. Predeterminado: 0 |
| [setColumnGap(long value)](#setColumnGap-long-) | Valor del espaciado horizontal entre columnas de una matriz; si ColumnGapRule está configurado a 3 (“Exactly”), la unidad se interpreta como twips (1/20 de punto). Si ColumnGapRule está configurado a 4 (“Multiple”), la unidad se interpreta como número de incrementos de 0,5 em. En otros casos se ignora. Predeterminado: 0 |
| [getRowGapRule()](#getRowGapRule--) | Tipo de espaciado vertical entre filas de una matriz; las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Tipo de espaciado vertical entre filas de una matriz; las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). |
| [getRowGap()](#getRowGap--) | Valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado a 3 (“Exactly”), la unidad se interpreta como twips (1/20 de punto). Si RowGapRule está configurado a 4 (“Multiple”), la unidad se interpreta como media línea. Predeterminado: 0 |
| [setRowGap(long value)](#setRowGap-long-) | Valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado a 3 (“Exactly”), la unidad se interpreta como twips (1/20 de punto). Si RowGapRule está configurado a 4 (“Multiple”), la unidad se interpreta como media línea. Predeterminado: 0 |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elemento de la matriz |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elemento de la matriz |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades de carácter de control |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Obtiene la alineación horizontal de la columna especificada |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Establece la alineación horizontal de la columna especificada |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Establece la alineación horizontal de las columnas especificadas |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Inserta una nueva fila antes de la especificada. Inicialmente todos los elementos en la nueva fila son nulos. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Inserta una nueva fila después de la especificada. Inicialmente todos los elementos en la nueva fila son nulos. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Elimina la fila especificada |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Inserta una nueva columna antes de la especificada. Inicialmente todos los elementos en la nueva columna son nulos. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Inserta una nueva columna después de la especificada. Inicialmente todos los elementos en la nueva columna son nulos. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Elimina la columna especificada |
| [getChildren()](#getChildren--) | Obtiene los elementos hijos |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Inicializa una nueva instancia de la clase MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rowCount | int | recuento de filas |
| columnCount | int | recuento de columnas |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
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
public final int getColumnCount()
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
public final boolean getHidePlaceholders()
```

Ocultar los marcadores de posición para elementos de matriz vacíos Predeterminado: false

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
public final void setHidePlaceholders(boolean value)
```

Ocultar los marcadores de posición para elementos de matriz vacíos Predeterminado: false

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
public final int getBaseJustification()
```

Especifica la justificación vertical con respecto al texto circundante. Los valores posibles son top, bottom y center. Predeterminado: Center

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
public final void setBaseJustification(int value)
```

Especifica la justificación vertical con respecto al texto circundante. Los valores posibles son top, bottom y center. Predeterminado: Center

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
public final long getMinColumnWidth()
```

Ancho mínimo de columna en twips (1/20 de punto). El espaciado de la brecha (también llamado \u201cColumn Gap\u201d o \u201cGap Width\u201d) se suma a MinColumnWidth para determinar el espaciado total de columnas de la matriz (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0.

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
public final void setMinColumnWidth(long value)
```

Ancho mínimo de columna en twips (1/20 de punto). El espaciado de la brecha (también llamado \u201cColumn Gap\u201d o \u201cGap Width\u201d) se suma a MinColumnWidth para determinar el espaciado total de columnas de la matriz (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0.

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
public final int getColumnGapRule()
```

Tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0)

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
public final void setColumnGapRule(int value)
```

Tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0)

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
public final long getColumnGap()
```

Valor del espaciado horizontal entre columnas de una matriz; si ColumnGapRule está configurado a 3 (“Exactly”), la unidad se interpreta como twips (1/20 de punto). Si ColumnGapRule está configurado a 4 (“Multiple”), la unidad se interpreta como número de incrementos de 0,5 em. En otros casos se ignora. Predeterminado: 0

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
public final void setColumnGap(long value)
```

Valor del espaciado horizontal entre columnas de una matriz; si ColumnGapRule está configurado a 3 (“Exactly”), la unidad se interpreta como twips (1/20 de punto). Si ColumnGapRule está configurado a 4 (“Multiple”), la unidad se interpreta como número de incrementos de 0,5 em. En otros casos se ignora. Predeterminado: 0

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
public final int getRowGapRule()
```

Tipo de espaciado vertical entre filas de una matriz; las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0)

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
public final void setRowGapRule(int value)
```

Tipo de espaciado vertical entre filas de una matriz; las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0)

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
public final long getRowGap()
```

Valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado a 3 (“Exactly”), la unidad se interpreta como twips (1/20 de punto). Si RowGapRule está configurado a 4 (“Multiple”), la unidad se interpreta como media línea. Predeterminado: 0

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
public final void setRowGap(long value)
```

Valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado a 3 (“Exactly”), la unidad se interpreta como twips (1/20 de punto). Si RowGapRule está configurado a 4 (“Multiple”), la unidad se interpreta como media línea. Predeterminado: 0

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

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Elemento de la matriz

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
| row | int | Índice basado en cero de la fila para obtener el elemento |
| column | int | Índice basado en cero de la columna para obtener el elemento |

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Elemento de la matriz

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
| row | int | Índice basado en cero de la fila para obtener el elemento |
| column | int | Índice basado en cero de la columna para obtener el elemento |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propiedades de carácter de control

**Devuelve:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Obtiene la alineación horizontal de la columna especificada

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
public final void setColumnAlignment(int columnIndex, int val)
```

Establece la alineación horizontal de la columna especificada

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
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Establece la alineación horizontal de las columnas especificadas

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
| columnsCount | long | Número de columnas para las que se especifica la alineación |
| val | int | Nuevo valor de la alineación horizontal de la columna especificada |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Inserta una nueva fila antes de la especificada. Inicialmente todos los elementos en la nueva fila son nulos.

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
| rowIndex | int | Índice de la fila antes de la cual se insertará una nueva |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Inserta una nueva fila después de la especificada. Inicialmente todos los elementos en la nueva fila son nulos.

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
| rowIndex | int | Índice de la fila después de la cual se insertará una nueva |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
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
| rowIndex | int | Índice basado en cero de la fila a eliminar. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Inserta una nueva columna antes de la especificada. Inicialmente todos los elementos en la nueva columna son nulos.

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
| columnIndex | int | Índice de la columna antes de la cual se insertará una nueva |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Inserta una nueva columna después de la especificada. Inicialmente todos los elementos en la nueva columna son nulos.

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
| columnIndex | int | Índice de la columna después de la cual se insertará una nueva |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
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
| columnIndex | int | Índice basado en cero de la columna a eliminar. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtiene los elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]