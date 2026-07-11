---
title: IMathMatrix
second_title: Aspose.Slides для Android через справочник Java API
description: Задает объект Matrix, состоящий из дочерних элементов, размещённых в одной или нескольких строках и столбцах.
type: docs
url: /ru/com.aspose.slides/imathmatrix/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Задает объект Matrix, состоящий из дочерних элементов, размещённых в одной или нескольких строках и столбцах. Важно отметить, что у матриц нет встроенных разделителей. Чтобы поместить матрицу в скобки, следует использовать объект-разделитель (IMathDelimiter). Нулевые аргументы можно использовать для создания пробелов в матрицах.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Элементы матрицы |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Элементы матрицы |
| [getRowCount()](#getRowCount--) | Количество строк в матрице |
| [getColumnCount()](#getColumnCount--) | Количество столбцов в матрице |
| [getHidePlaceholders()](#getHidePlaceholders--) | Скрыть заглушки для пустых элементов матрицы. Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Скрыть заглушки для пустых элементов матрицы. Default: false |
| [getBaseJustification()](#getBaseJustification--) | Определяет вертикальное выравнивание относительно окружающего текста. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Определяет вертикальное выравнивание относительно окружающего текста. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Минимальная ширина столбца в твипсах (1/20 пункта). Расстояние между колонками (также называемое \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) добавляется к MinColumnWidth для определения общего расстояния между столбцами матрицы (расстояние между одинаковыми краями разных столбцов). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Минимальная ширина столбца в твипсах (1/20 пункта). Расстояние между колонками (также называемое \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) добавляется к MinColumnWidth для определения общего расстояния между столбцами матрицы (расстояние между одинаковыми краями разных столбцов). |
| [getColumnGapRule()](#getColumnGapRule--) | Тип горизонтального расстояния между столбцами матрицы; единицы измерения могут быть ems или points (хранятся как твипсы). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Тип горизонтального расстояния между столбцами матрицы; единицы измерения могут быть ems или points (хранятся как твипсы). |
| [getColumnGap()](#getColumnGap--) | Значение горизонтального расстояния между столбцами матрицы; если ColumnGapRule установлен в 3 ("Exactly"), единица измерения интерпретируется как твипсы (1/20 пункта). Если ColumnGapRule установлен в 4 ("Multiple"), единица измеряется как количество увеличений на 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Значение горизонтального расстояния между столбцами матрицы; если ColumnGapRule установлен в 3 ("Exactly"), единица измерения интерпретируется как твипсы (1/20 пункта). Если ColumnGapRule установлен в 4 ("Multiple"), единица измеряется как количество увеличений на 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | Тип вертикального расстояния между строками матрицы; единицы измерения могут быть строки или пункты (хранятся как твипсы). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Тип вертикального расстояния между строками матрицы; единицы измерения могут быть строки или пункты (хранятся как твипсы). |
| [getRowGap()](#getRowGap--) | Значение вертикального расстояния между строками матрицы; если RowGapRule установлен в 3 ("Exactly"), единица измерения интерпретируется как твипсы (1/20 пункта). Если RowGapRule установлен в 4 ("Multiple"), единица измеряется как половинные строки. |
| [setRowGap(long value)](#setRowGap-long-) | Значение вертикального расстояния между строками матрицы; если RowGapRule установлен в 3 ("Exactly"), единица измерения интерпретируется как твипсы (1/20 пункта). Если RowGapRule установлен в 4 ("Multiple"), единица измеряется как половинные строки. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Получить горизонтальное выравнивание указанного столбца |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Установить горизонтальное выравнивание указанного столбца |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Установить горизонтальное выравнивание указанных столбцов |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Вставить новую строку перед указанной. Изначально все элементы в новой строке равны null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Вставить новую строку после указанной. Изначально все элементы в новой строке равны null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Удалить указанную строку |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Вставить новый столбец перед указанным. Изначально все элементы в новом столбце равны null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Вставить новый столбец после указанного. Изначально все элементы в новом столбце равны null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Удалить указанный столбец |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Элементы матрицы

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
| row | int | Индекс строки, начиная с нуля, для получения элемента |
| column | int | Индекс столбца, начиная с нуля, для получения элемента |

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Элементы матрицы

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
| row | int | Индекс строки, начиная с нуля, для получения элемента |
| column | int | Индекс столбца, начиная с нуля, для получения элемента |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
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
```
public abstract int getColumnCount()
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
```
public abstract boolean getHidePlaceholders()
```

Скрыть заглушки для пустых элементов матрицы. Default: false

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
```
public abstract void setHidePlaceholders(boolean value)
```

Скрыть заглушки для пустых элементов матрицы. Default: false

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
```
public abstract int getBaseJustification()
```

Определяет вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. Default: Center

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
```
public abstract void setBaseJustification(int value)
```

Определяет вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. Default: Center

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
```
public abstract long getMinColumnWidth()
```

Минимальная ширина столбца в твипсах (1/20 пункта). Расстояние между колонками (также называемое \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) добавляется к MinColumnWidth для определения общего расстояния между столбцами матрицы (расстояние между одинаковыми краями разных столбцов). Default: 0.

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
```
public abstract void setMinColumnWidth(long value)
```

Минимальная ширина столбца в твипсах (1/20 пункта). Расстояние между колонками (также называемое \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) добавляется к MinColumnWidth для определения общего расстояния между столбцами матрицы (расстояние между одинаковыми краями разных столбцов). Default: 0.

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
```
public abstract int getColumnGapRule()
```

Тип горизонтального расстояния между столбцами матрицы; единицы измерения могут быть ems или points (хранятся как твипсы). Default: SingleSpacingGap (0)

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
```
public abstract void setColumnGapRule(int value)
```

Тип горизонтального расстояния между столбцами матрицы; единицы измерения могут быть ems или points (хранятся как твипсы). Default: SingleSpacingGap (0)

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
```
public abstract long getColumnGap()
```

Значение горизонтального расстояния между столбцами матрицы; если ColumnGapRule установлен в 3 ("Exactly"), единица измерения интерпретируется как твипсы (1/20 пункта). Если ColumnGapRule установлен в 4 ("Multiple"), единица измеряется как количество увеличений на 0.5 em. В остальных случаях игнорируется. Default: 0

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
```
public abstract void setColumnGap(long value)
```

Значение горизонтального расстояния между столбцами матрицы; если ColumnGapRule установлен в 3 ("Exactly"), единица измерения интерпретируется как твипсы (1/20 пункта). Если ColumnGapRule установлен в 4 ("Multiple"), единица измеряется как количество увеличений на 0.5 em. В остальных случаях игнорируется. Default: 0

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
```
public abstract int getRowGapRule()
```

Тип вертикального расстояния между строками матрицы; единицы измерения могут быть строки или пункты (хранятся как твипсы). Default: SingleSpacingGap (0)

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
```
public abstract void setRowGapRule(int value)
```

Тип вертикального расстояния между строками матрицы; единицы измерения могут быть строки или пункты (хранятся как твипсы). Default: SingleSpacingGap (0)

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
```
public abstract long getRowGap()
```

Значение вертикального расстояния между строками матрицы; если RowGapRule установлен в 3 ("Exactly"), единица измерения интерпретируется как твипсы (1/20 пункта). Если RowGapRule установлен в 4 ("Multiple"), единица измеряется как половинные строки. Default: 0

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
```
public abstract void setRowGap(long value)
```

Значение вертикального расстояния между строками матрицы; если RowGapRule установлен в 3 ("Exactly"), единица измерения интерпретируется как твипсы (1/20 пункта). Если RowGapRule установлен в 4 ("Multiple"), единица измеряется как половинные строки. Default: 0

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

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
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
| columnIndex | int | Индекс столбца, начиная с нуля |

**Возвращаемое значение:**
int - Horizontal Alignment of specified column

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Установить горизонтальное выравнивание указанного столбца

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int | Индекс столбца, начиная с нуля |
| val | int | Новое значение горизонтального выравнивания указанного столбца |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Установить горизонтальное выравнивание указанных столбцов

--------------------

> ```
> Пример:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int | Индекс первого столбца, для которого задаётся выравнивание |
| columnsCount | long | Количество столбцов, для которых задаётся выравнивание |
| val | int | Новое значение горизонтального выравнивания указанных столбцов |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Вставить новую строку перед указанной. Изначально все элементы в новой строке равны null.

--------------------

> ```
> Пример:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | int | Индекс строки, перед которой будет вставлена новая |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Вставить новую строку после указанной. Изначально все элементы в новой строке равны null.

--------------------

> ```
> Пример:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | int | Индекс строки, после которой будет вставлена новая |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Удалить указанную строку

--------------------

> ```
> Пример:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | int | Индекс строки, которую необходимо удалить (нумерация с нуля). |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Вставить новый столбец перед указанным. Изначально все элементы в новом столбце равны null.

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
| columnIndex | int | Индекс столбца, перед которым будет вставлен новый |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Вставить новый столбец после указанного. Изначально все элементы в новом столбце равны null.

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
| columnIndex | int | Индекс столбца, после которого будет вставлен новый |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Удалить указанный столбец

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
| columnIndex | int | Индекс столбца, который необходимо удалить (нумерация с нуля). |