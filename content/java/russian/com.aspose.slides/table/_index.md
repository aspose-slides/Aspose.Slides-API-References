---
title: Table
second_title: Aspose.Slides для Java справочник API
description: Представляет таблицу на слайде.
type: docs
url: /ru/com.aspose.slides/table/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Представляет таблицу на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Возвращает ячейку по указанным индексам столбца и строки. |
| [getRows()](#getRows--) | Возвращает коллекцию строк. |
| [getColumns()](#getColumns--) | Возвращает коллекцию столбцов. |
| [getTableFormat()](#getTableFormat--) | Возвращает объект TableFormat, содержащий свойства форматирования этой таблицы. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Объединяет соседние ячейки. |
| [getStylePreset()](#getStylePreset--) | Получает или задает встроенный стиль таблицы. |
| [setStylePreset(int value)](#setStylePreset-int-) | Получает или задает встроенный стиль таблицы. |
| [getRightToLeft()](#getRightToLeft--) | Определяет, имеет ли таблица порядок чтения справа налево. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Определяет, имеет ли таблица порядок чтения справа налево. |
| [getFirstRow()](#getFirstRow--) | Определяет, должна ли первая строка таблицы отображаться с особым форматированием. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Определяет, должна ли первая строка таблицы отображаться с особым форматированием. |
| [getFirstCol()](#getFirstCol--) | Определяет, должен ли первый столбец таблицы отображаться с особым форматированием. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Определяет, должен ли первый столбец таблицы отображаться с особым форматированием. |
| [getLastRow()](#getLastRow--) | Определяет, должна ли последняя строка таблицы отображаться с особым форматированием. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Определяет, должна ли последняя строка таблицы отображаться с особым форматированием. |
| [getLastCol()](#getLastCol--) | Определяет, должен ли последний столбец таблицы отображаться с особым форматированием. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Определяет, должен ли последний столбец таблицы отображаться с особым форматированием. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Определяет, должны ли четные строки отображаться с другим форматированием. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Определяет, должны ли четные строки отображаться с другим форматированием. |
| [getVerticalBanding()](#getVerticalBanding--) | Определяет, должны ли четные столбцы отображаться с другим форматированием. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Определяет, должны ли четные столбцы отображаться с другим форматированием. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Устанавливает определённые свойства формата части для всех частей ячеек таблицы. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Устанавливает определённые свойства формата абзаца для всех абзацев ячеек таблицы. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Устанавливает определённые свойства формата текстового кадра для всех текстовых кадров ячеек таблицы. |
| [getFillFormat()](#getFillFormat--) | Возвращает объект TableFormat.FillFormat, содержащий параметры заливки для Таблицы. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Возвращает ячейку по указанным индексам столбца и строки. Только для чтения [Cell](../../com.aspose.slides/cell).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Возвращаемое значение:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Возвращает коллекцию строк. Только для чтения [IRowCollection](../../com.aspose.slides/irowcollection).

**Возвращаемое значение:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Возвращает коллекцию столбцов. Только для чтения [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Возвращаемое значение:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Возвращает объект TableFormat, содержащий свойства форматирования этой таблицы. Только для чтения [ITableFormat](../../com.aspose.slides/itableformat).

**Возвращаемое значение:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Объединяет соседние ячейки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

**Возвращаемое значение:**
[ICell](../../com.aspose.slides/icell) - Объединённая ячейка.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Получает или задает встроенный стиль таблицы. Чтение/запись [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Возвращаемое значение:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Получает или задает встроенный стиль таблицы. Чтение/запись [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Определяет, имеет ли таблица порядок чтения справа налево. Чтение/запись  boolean .

**Возвращаемое значение:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Определяет, имеет ли таблица порядок чтения справа налево. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Определяет, должна ли первая строка таблицы отображаться с особым форматированием. Чтение/запись  boolean .

**Возвращаемое значение:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Определяет, должна ли первая строка таблицы отображаться с особым форматированием. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Определяет, должен ли первый столбец таблицы отображаться с особым форматированием. Чтение/запись  boolean .

**Возвращаемое значение:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Определяет, должен ли первый столбец таблицы отображаться с особым форматированием. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Определяет, должна ли последняя строка таблицы отображаться с особым форматированием. Чтение/запись  boolean .

**Возвращаемое значение:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Определяет, должна ли последняя строка таблицы отображаться с особым форматированием. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Определяет, должен ли последний столбец таблицы отображаться с особым форматированием. Чтение/запись  boolean .

**Возвращаемое значение:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Определяет, должен ли последний столбец таблицы отображаться с особым форматированием. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Определяет, должны ли четные строки отображаться с другим форматированием. Чтение/запись  boolean .

**Возвращаемое значение:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Определяет, должны ли четные строки отображаться с другим форматированием. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Определяет, должны ли четные столбцы отображаться с другим форматированием. Чтение/запись  boolean .

**Возвращаемое значение:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Определяет, должны ли четные столбцы отображаться с другим форматированием. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Устанавливает определённые свойства формата части для всех частей ячеек таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Устанавливает определённые свойства формата абзаца для всех абзацев ячеек таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Устанавливает определённые свойства формата текстового кадра для всех текстовых кадров ячеек таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Возвращает объект TableFormat.FillFormat, содержащий параметры заливки для Таблицы. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**
[IFillFormat](../../com.aspose.slides/ifillformat)