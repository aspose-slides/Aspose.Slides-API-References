---
title: Table
second_title: Справочник API Aspose.Slides для Android через Java
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
| [getRightToLeft()](#getRightToLeft--) | Определяет, использует ли таблица порядок чтения справа налево. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Определяет, использует ли таблица порядок чтения справа налево. |
| [getFirstRow()](#getFirstRow--) | Определяет, должна ли первая строка таблицы отображаться со специальным форматированием. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Определяет, должна ли первая строка таблицы отображаться со специальным форматированием. |
| [getFirstCol()](#getFirstCol--) | Определяет, должен ли первый столбец таблицы отображаться со специальным форматированием. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Определяет, должен ли первый столбец таблицы отображаться со специальным форматированием. |
| [getLastRow()](#getLastRow--) | Определяет, должна ли последняя строка таблицы отображаться со специальным форматированием. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Определяет, должна ли последняя строка таблицы отображаться со специальным форматированием. |
| [getLastCol()](#getLastCol--) | Определяет, должен ли последний столбец таблицы отображаться со специальным форматированием. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Определяет, должен ли последний столбец таблицы отображаться со специальным форматированием. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Определяет, должны ли четные строки отображаться с другим форматированием. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Определяет, должны ли четные строки отображаться с другим форматированием. |
| [getVerticalBanding()](#getVerticalBanding--) | Определяет, должны ли четные столбцы отображаться с другим форматированием. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Определяет, должны ли четные столбцы отображаться с другим форматированием. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Устанавливает определенные свойства формата долей для всех долей ячеек таблицы. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Устанавливает определенные свойства формата абзацев для всех абзацев ячеек таблицы. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Устанавливает определенные свойства формата текстовых рамок для всех текстовых рамок ячеек таблицы. |
| [getFillFormat()](#getFillFormat--) | Возвращает объект TableFormat.FillFormat, содержащий параметры заливки для таблицы. |

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
| cell1 | [ICell](../../com.aspose.slides/icell) | Ячейка для объединения. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Ячейка для объединения. |
| allowSplitting | boolean | True, если разрешить разделение ячеек. |

**Возвращаемое значение:**
[ICell](../../com.aspose.slides/icell) - Объединенная ячейка.

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

Определяет, использует ли таблица порядок чтения справа налево. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Определяет, использует ли таблица порядок чтения справа налево. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Определяет, должна ли первая строка таблицы отображаться со специальным форматированием. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Определяет, должна ли первая строка таблицы отображаться со специальным форматированием. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Определяет, должен ли первый столбец таблицы отображаться со специальным форматированием. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Определяет, должен ли первый столбец таблицы отображаться со специальным форматированием. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Определяет, должна ли последняя строка таблицы отображаться со специальным форматированием. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Определяет, должна ли последняя строка таблицы отображаться со специальным форматированием. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Определяет, должен ли последний столбец таблицы отображаться со специальным форматированием. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Определяет, должен ли последний столбец таблицы отображаться со специальным форматированием. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Определяет, должны ли четные строки отображаться с другим форматированием. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Определяет, должны ли четные строки отображаться с другим форматированием. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Определяет, должны ли четные столбцы отображаться с другим форматированием. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Определяет, должны ли четные столбцы отображаться с другим форматированием. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Устанавливает определенные свойства формата долей для всех долей ячеек таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Объект IPortionFormat с установленными необходимыми свойствами. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Устанавливает определенные свойства формата абзацев для всех абзацев ячеек таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Объект IParagraphFormat с установленными необходимыми свойствами. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Устанавливает определенные свойства формата текстовых рамок для всех текстовых рамок ячеек таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Объект ITextFrameFormat с установленными необходимыми свойствами. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Возвращает объект TableFormat.FillFormat, содержащий параметры заливки для таблицы. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**
[IFillFormat](../../com.aspose.slides/ifillformat)