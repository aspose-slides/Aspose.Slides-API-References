---
title: MathMatrix
second_title: Aspose.Slides для справочника API Java
description: Определяет объект Matrix, состоящий из дочерних элементов, расположенных в одну или несколько строк и столбцов.
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

Определяет объект Matrix, состоящий из дочерних элементов, расположенных в одну или несколько строк и столбцов. Важно отметить, что у матриц нет встроенных разделителей. Чтобы поместить матрицу в скобки, следует использовать объект-разделитель (IMathDelimiter). Нулевые аргументы можно использовать для создания пробелов в матрицах.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Инициализирует новый экземпляр класса MathMatrix. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRowCount()](#getRowCount--) | Количество строк в матрице |
| [getColumnCount()](#getColumnCount--) | Количество столбцов в матрице |
| [getHidePlaceholders()](#getHidePlaceholders--) | Скрыть заполнители для пустых элементов матрицы. По умолчанию: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Скрыть заполнители для пустых элементов матрицы. По умолчанию: false |
| [getBaseJustification()](#getBaseJustification--) | Указывает вертикальное выравнивание относительно окружающего текста. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Указывает вертикальное выравнивание относительно окружающего текста. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Минимальная ширина столбца в twips (1/20 пункта). Промежуток между столбцами (также называется \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) добавляется к MinColumnWidth для определения общего интервала столбцов матрицы (расстояние между одинаковыми краями разных столбцов). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Минимальная ширина столбца в twips (1/20 пункта). Промежуток между столбцами (также называется \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) добавляется к MinColumnWidth для определения общего интервала столбцов матрицы (расстояние между одинаковыми краями разных столбцов). |
| [getColumnGapRule()](#getColumnGapRule--) | Тип горизонтального интервала между столбцами матрицы; единицы горизонтального интервала могут быть ems или points (хранятся как twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Тип горизонтального интервала между столбцами матрицы; единицы горизонтального интервала могут быть ems или points (хранятся как twips). |
| [getColumnGap()](#getColumnGap--) | Значение горизонтального интервала между столбцами матрицы; если ColumnGapRule установлен в 3 (\"Exactly\"), то единица интерпретируется как twips (1/20 пункта). Если ColumnGapRule установлен в 4 (\"Multiple\"), то единица интерпретируется как количество шагов по 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Значение горизонтального интервала между столбцами матрицы; если ColumnGapRule установлен в 3 (\"Exactly\"), то единица интерпретируется как twips (1/20 пункта). Если ColumnGapRule установлен в 4 (\"Multiple\"), то единица интерпретируется как количество шагов по 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | Тип вертикального интервала между строками матрицы; единицы вертикального интервала могут быть lines или points (хранятся как twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Тип вертикального интервала между строками матрицы; единицы вертикального интервала могут быть lines или points (хранятся как twips). |
| [getRowGap()](#getRowGap--) | Значение вертикального интервала между строками матрицы; если RowGapRule установлен в 3 (\"Exactly\"), то единица интерпретируется как twips (1/20 пункта). Если RowGapRule установлен в 4 (\"Multiple\"), то единица интерпретируется как половинные строки. |
| [setRowGap(long value)](#setRowGap-long-) | Значение вертикального интервала между строками матрицы; если RowGapRule установлен в 3 (\"Exactly\"), то единица интерпретируется как twips (1/20 пункта). Если RowGapRule установлен в 4 (\"Multiple\"), то единица интерпретируется как половинные строки. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Элемент матрицы |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Элемент матрицы |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Свойства управляющих символов |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Получить горизонтальное выравнивание указанного столбца |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Установить горизонтальное выравнивание указанного столбца |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Установить горизонтальное выравнивание указанных столбцов |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Вставить новую строку перед указанной. Изначально все элементы в новой строке равны null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Вставить новую строку после указанной. Изначально все элементы в новой строке равны null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Удаляет указанную строку |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Вставить новый столбец перед указанным. Изначально все элементы в новом столбце равны null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Вставить новый столбец после указанного. Изначально все элементы в новом столбце равны null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Удаляет указанный столбец |
| [getChildren()](#getChildren--) | Получить дочерние элементы |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
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
```
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

**Возвращает:**
int
### getColumnCount() {#getColumnCount--}
```
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

**Возвращает:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

Скрыть заполнители для пустых элементов матрицы. По умолчанию: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Возвращает:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

Скрыть заполнители для пустых элементов матрицы. По умолчанию: false

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
public final int getBaseJustification()
```

Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom, center. По умолчанию: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Возвращает:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom, center. По умолчанию: Center

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
public final long getMinColumnWidth()
```

Минимальная ширина столбца в twips (1/20 пункта). Промежуток между столбцами (также называется \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) добавляется к MinColumnWidth для определения общего интервала столбцов матрицы (расстояние между одинаковыми краями разных столбцов). По умолчанию: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Возвращает:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Минимальная ширина столбца в twips (1/20 пункта). Промежуток между столбцами (также называется \\u201cColumn Gap\\u201d или \\u201cGap Width\\u201d) добавляется к MinColumnWidth для определения общего интервала столбцов матрицы (расстояние между одинаковыми краями разных столбцов). По умолчанию: 0.

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
public final int getColumnGapRule()
```

Тип горизонтального интервала между столбцами матрицы; единицы горизонтального интервала могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Возвращает:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

Тип горизонтального интервала между столбцами матрицы; единицы горизонтального интервала могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)

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
public final long getColumnGap()
```

Значение горизонтального интервала между столбцами матрицы; если ColumnGapRule установлен в 3 (\"Exactly\"), то единица интерпретируется как twips (1/20 пункта). Если ColumnGapRule установлен в 4 (\"Multiple\"), то единица интерпретируется как количество шагов по 0.5 em. В остальных случаях игнорируется. По умолчанию: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Возвращает:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

Значение горизонтального интервала между столбцами матрицы; если ColumnGapRule установлен в 3 (\"Exactly\"), то единица интерпретируется как twips (1/20 пункта). Если ColumnGapRule установлен в 4 (\"Multiple\"), то единица интерпретируется как количество шагов по 0.5 em. В остальных случаях игнорируется. По умолчанию: 0

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
public final int getRowGapRule()
```

Тип вертикального интервала между строками матрицы; единицы вертикального интервала могут быть lines или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)

--------------------

> ```
> Пример:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Возвращает:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

Тип вертикального интервала между строками матрицы; единицы вертикального интервала могут быть lines или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)

--------------------

> ```
> Пример:
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
public final long getRowGap()
```

Значение вертикального интервала между строками матрицы; если RowGapRule установлен в 3 (\"Exactly\"), то единица интерпретируется как twips (1/20 пункта). Если RowGapRule установлен в 4 (\"Multiple\"), то единица интерпретируется как половинные строки. По умолчанию: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Возвращает:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

Значение вертикального интервала между строками матрицы; если RowGapRule установлен в 3 (\"Exactly\"), то единица интерпретируется как twips (1/20 пункта). Если RowGapRule установлен в 4 (\"Multiple\"), то единица интерпретируется как половинные строки. По умолчанию: 0

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
```
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
| row | int | Нулевой-базовый индекс строки для получения элемента |
| column | int | Нулевой-базовый индекс столбца для получения элемента |

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
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
| row | int | Нулевой-базовый индекс строки для получения элемента |
| column | int | Нулевой-базовый индекс столбца для получения элемента |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Свойства управляющих символов

**Возвращает:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
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
| columnIndex | int | Нулевой-базовый индекс столбца |

**Возвращает:**
int - Горизонтальное выравнивание указанного столбца
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Установить горизонтальное выравнивание указанного столбца

--------------------

> ```
> Пример:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int | Нулевой-базовый индекс столбца |
| val | int | Новое значение горизонтального выравнивания указанного столбца |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
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
| columnIndex | int | Нулевой-базовый индекс первого столбца для установки выравнивания |
| columnsCount | long | Количество столбцов, для которых задаётся выравнивание |
| val | int | Новое значение горизонтального выравнивания указанного столбца |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
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
public final void insertRowAfter(int rowIndex)
```

Вставить новую строку после указанной. Изначально все элементы в новой строке равны null.

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
| rowIndex | int | Индекс строки, после которой будет вставлена новая |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
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
| rowIndex | int | Нулевой-базовый индекс строки для удаления. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
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
public final void insertColumnAfter(int columnIndex)
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
| columnIndex | int | Нулевой-базовый индекс столбца для удаления. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Получить дочерние элементы

**Возвращает:**
com.aspose.slides.IMathElement[]