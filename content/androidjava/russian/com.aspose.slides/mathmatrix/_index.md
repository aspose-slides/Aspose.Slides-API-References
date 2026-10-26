---
title: MathMatrix
second_title: Aspose.Slides для Android через справку Java API
description: Указывает объект Matrix, состоящий из дочерних элементов, расположенных в одной или нескольких строках и столбцах.
type: docs
url: /ru/com.aspose.slides/mathmatrix/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object (IMathDelimiter). Null arguments can be used to create gaps in matrices.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Инициализирует новый экземпляр класса MathMatrix. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRowCount()](#getRowCount--) | Количество строк в матрице |
| [getColumnCount()](#getColumnCount--) | Количество столбцов в матрице |
| [getHidePlaceholders()](#getHidePlaceholders--) | Скрывать заполнители для пустых элементов матрицы Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Скрывать заполнители для пустых элементов матрицы Default: false |
| [getBaseJustification()](#getBaseJustification--) | Указывает вертикальное выравнивание относительно окружающего текста. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Указывает вертикальное выравнивание относительно окружающего текста. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Минимальная ширина столбца в твипсах (1/20 части пункта). Расстояние между столбцами (также называемое \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) прибавляется к MinColumnWidth для определения общего интервала столбцов матрицы (расстояние между одинаковыми краями разных столбцов). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Минимальная ширина столбца в твипсах (1/20 части пункта). Расстояние между столбцами (также называемое \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) прибавляется к MinColumnWidth для определения общего интервала столбцов матрицы (расстояние между одинаковыми краями разных столбцов). |
| [getColumnGapRule()](#getColumnGapRule--) | Тип горизонтального интервала между столбцами матрицы; единицы интервала могут быть ems или пункты (хранятся в твипсах). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Тип горизонтального интервала между столбцами матрицы; единицы интервала могут быть ems или пункты (хранятся в твипсах). |
| [getColumnGap()](#getColumnGap--) | Значение горизонтального интервала между столбцами матрицы; если ColumnGapRule имеет значение 3 (\"Exactly\"), единица интерпретируется как твипсы (1/20 пункта). Если ColumnGapRule имеет значение 4 (\"Multiple\"), единица интерпретируется как количество шагов в 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Значение горизонтального интервала между столбцами матрицы; если ColumnGapRule имеет значение 3 (\"Exactly\"), единица интерпретируется как твипсы (1/20 пункта). Если ColumnGapRule имеет значение 4 (\"Multiple\"), единица интерпретируется как количество шагов в 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | Тип вертикального интервала между строками матрицы; единицы интервала могут быть строками или пунктами (хранятся в твипсах). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Тип вертикального интервала между строками матрицы; единицы интервала могут быть строками или пунктами (хранятся в твипсах). |
| [getRowGap()](#getRowGap--) | Значение вертикального интервала между строками матрицы; если RowGapRule равно 3 (\"Exactly\"), единица интерпретируется как твипсы (1/20 пункта). Если RowGapRule равно 4 (\"Multiple\"), единица интерпретируется как полустроки. |
| [setRowGap(long value)](#setRowGap-long-) | Значение вертикального интервала между строками матрицы; если RowGapRule равно 3 (\"Exactly\"), единица интерпретируется как твипсы (1/20 пункта). Если RowGapRule равно 4 (\"Multiple\"), единица интерпретируется как полустроки. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Элемент матрицы |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Элемент матрицы |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Свойства управляющих символов |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Получить горизонтальное выравнивание указанного столбца |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Установить горизонтальное выравнивание указанного столбца |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Установить горизонтальное выравнивание указанных столбцов |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Вставить новую строку перед указанной. Изначально все элементы новой строки равны null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Вставить новую строку после указанной. Изначально все элементы новой строки равны null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Удаляет указанную строку |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Вставить новый столбец перед указанным. Изначально все элементы нового столбца равны null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Вставить новый столбец после указанного. Изначально все элементы нового столбца равны null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Удаляет указанный столбец |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
> ```
public MathMatrix(int rowCount, int columnCount)
```

Инициализирует новый экземпляр класса MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rowCount | int | количество строк |
| columnCount | int | количество столбцов |

### getRowCount() {#getRowCount--}
> ```
public final int getRowCount()
```

Количество строк в матрице

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Возвращаемое значение:**
int
### getColumnCount() {#getColumnCount--}
> ```
public final int getColumnCount()
```

Количество столбцов в матрице

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Возвращаемое значение:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
> ```
public final boolean getHidePlaceholders()
```

Скрывать заполнители для пустых элементов матрицы Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Возвращаемое значение:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
> ```
public final void setHidePlaceholders(boolean value)
```

Скрывать заполнители для пустых элементов матрицы Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
> ```
public final int getBaseJustification()
```

Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Возвращаемое значение:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
> ```
public final void setBaseJustification(int value)
```

Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
> ```
public final long getMinColumnWidth()
```

Минимальная ширина столбца в твипсах (1/20 части пункта). Расстояние между столбцами (также называемое \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) прибавляется к MinColumnWidth для определения общего интервала столбцов матрицы (расстояние между одинаковыми краями разных столбцов). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Возвращаемое значение:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
> ```
public final void setMinColumnWidth(long value)
```

Минимальная ширина столбца в твипсах (1/20 части пункта). Расстояние между столбцами (также называемое \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) прибавляется к MinColumnWidth для определения общего интервала столбцов матрицы (расстояние между одинаковыми краями разных столбцов). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
> ```
public final int getColumnGapRule()
```

Тип горизонтального интервала между столбцами матрицы; единицы интервала могут быть ems или пункты (хранятся в твипсах). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Возвращаемое значение:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
> ```
public final void setColumnGapRule(int value)
```

Тип горизонтального интервала между столбцами матрицы; единицы интервала могут быть ems или пункты (хранятся в твипсах). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
> ```
public final long getColumnGap()
```

Значение горизонтального интервала между столбцами матрицы; если ColumnGapRule равно 3 (\"Exactly\"), единица интерпретируется как твипсы (1/20 пункта). Если ColumnGapRule равно 4 (\"Multiple\"), единица интерпретируется как количество шагов в 0.5 em. В остальных случаях игнорируется. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Возвращаемое значение:**
long
### setColumnGap(long value) {#setColumnGap-long-}
> ```
public final void setColumnGap(long value)
```

Значение горизонтального интервала между столбцами матрицы; если ColumnGapRule равно 3 (\"Exactly\"), единица интерпретируется как твипсы (1/20 пункта). Если ColumnGapRule равно 4 (\"Multiple\"), единица интерпретируется как количество шагов в 0.5 em. В остальных случаях игнорируется. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
> ```
public final int getRowGapRule()
```

Тип вертикального интервала между строками матрицы; единицы интервала могут быть строками или пунктами (хранятся в твипсах). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Возвращаемое значение:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
> ```
public final void setRowGapRule(int value)
```

Тип вертикального интервала между строками матрицы; единицы интервала могут быть строками или пунктами (хранятся в твипсах). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
> ```
public final long getRowGap()
```

Значение вертикального интервала между строками матрицы; если RowGapRule равно 3 (\"Exactly\"), единица интерпретируется как твипсы (1/20 пункта). Если RowGapRule равно 4 (\"Multiple\"), единица интерпретируется как полустроки. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Возвращаемое значение:**
long
### setRowGap(long value) {#setRowGap-long-}
> ```
public final void setRowGap(long value)
```

Значение вертикального интервала между строками матрицы; если RowGapRule равно 3 (\"Exactly\"), единица интерпретируется как твипсы (1/20 пункта). Если RowGapRule равно 4 (\"Multiple\"), единица интерпретируется как полустроки. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
> ```
public final IMathElement get_Item(int row, int column)
```

Элемент матрицы

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
> ```
public final void set_Item(int row, int column, IMathElement value)
```

Элемент матрицы

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
> ```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Свойства управляющих символов

**Возвращаемое значение:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
> ```
public final int getColumnAlignment(int columnIndex)
```

Получить горизонтальное выравнивание указанного столбца

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int | Zero-based column index |

**Возвращаемое значение:**
int - Horizontal Alignment of specified column
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
> ```
public final void setColumnAlignment(int columnIndex, int val)
```

Установить горизонтальное выравнивание указанного столбца

--------------------

> ```
> Example: 
``` (и продолжается ---)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int | Zero-based column index |
| val | int | New value of horizontal alignment of specified column |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
> ```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Установить горизонтальное выравнивание указанных столбцов

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int | Zero-based index of the first column to set alignment |
| columnsCount | long | The number of columns to specify the alignment |
| val | int | New value of horizontal alignment of specified column |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
> ```
public final void insertRowBefore(int rowIndex)
```

Вставить новую строку перед указанной. Изначально все элементы новой строки равны null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | int | Index of the row before which to insert a new one |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
> ```
public final void insertRowAfter(int rowIndex)
```

Вставить новую строку после указанной. Изначально все элементы новой строки равны null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | int | Index of the row after which to insert a new one |

### deleteRow(int rowIndex) {#deleteRow-int-}
> ```
public final void deleteRow(int rowIndex)
```

Удаляет указанную строку

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | int | The zero-based index of the row to delete. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
> ```
public final void insertColumnBefore(int columnIndex)
```

Вставить новый столбец перед указанным. Изначально все элементы нового столбца равны null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int | Index of the column before which to insert a new one |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
> ```
public final void insertColumnAfter(int columnIndex)
```

Вставить новый столбец после указанного. Изначально все элементы нового столбца равны null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int | Index of the column after which to insert a new one |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
> ```
public final void deleteColumn(int columnIndex)
```

Удаляет указанный столбец

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int | The zero-based index of the column to delete. |

### getChildren() {#getChildren--}
> ```
public final IMathElement[] getChildren()
```

Получить дочерние элементы

**Возвращаемое значение:**
com.aspose.slides.IMathElement[]