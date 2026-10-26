---
title: ITable
second_title: Справочник API Aspose.Slides для Java
description: Представляет таблицу на слайде.
type: docs
url: /ru/com.aspose.slides/itable/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Представляет таблицу на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Возвращает ячейку по указанным индексам столбца и строки. |
| [getRows()](#getRows--) | Возвращает коллекцию строк. |
| [getColumns()](#getColumns--) | Возвращает коллекцию столбцов. |
| [getTableFormat()](#getTableFormat--) | Возвращает объект TableFormat, содержащий свойства форматирования для этой таблицы. |
| [getStylePreset()](#getStylePreset--) | Получает или задает встроенный стиль таблицы. |
| [setStylePreset(int value)](#setStylePreset-int-) | Получает или задает встроенный стиль таблицы. |
| [getRightToLeft()](#getRightToLeft--) | Определяет, имеет ли таблица порядок чтения справа налево. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Определяет, имеет ли таблица порядок чтения справа налево. |
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
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Объединяет соседние ячейки. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Возвращает ячейку по указанным индексам столбца и строки. Только для чтения [ICell](../../com.aspose.slides/icell).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Возвращает:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Возвращает коллекцию строк. Только для чтения [IRowCollection](../../com.aspose.slides/irowcollection).

**Возвращает:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Возвращает коллекцию столбцов. Только для чтения [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Возвращает:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Возвращает объект TableFormat, содержащий свойства форматирования для этой таблицы. Только для чтения [ITableFormat](../../com.aspose.slides/itableformat).

**Возвращает:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Получает или задает встроенный стиль таблицы. Чтение/запись [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Возвращает:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Получает или задает встроенный стиль таблицы. Чтение/запись [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Определяет, имеет ли таблица порядок чтения справа налево. Чтение-запись boolean.

**Возвращает:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Определяет, имеет ли таблица порядок чтения справа налево. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Определяет, должна ли первая строка таблицы отображаться со специальным форматированием. Чтение-запись boolean.

**Возвращает:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Определяет, должна ли первая строка таблицы отображаться со специальным форматированием. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Определяет, должен ли первый столбец таблицы отображаться со специальным форматированием. Чтение-запись boolean.

**Возвращает:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Определяет, должен ли первый столбец таблицы отображаться со специальным форматированием. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Определяет, должна ли последняя строка таблицы отображаться со специальным форматированием. Чтение-запись boolean.

**Возвращает:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Определяет, должна ли последняя строка таблицы отображаться со специальным форматированием. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Определяет, должен ли последний столбец таблицы отображаться со специальным форматированием. Чтение-запись boolean.

**Возвращает:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Определяет, должен ли последний столбец таблицы отображаться со специальным форматированием. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Определяет, должны ли четные строки отображаться с другим форматированием. Чтение-запись boolean.

**Возвращает:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Определяет, должны ли четные строки отображаться с другим форматированием. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Определяет, должны ли четные столбцы отображаться с другим форматированием. Чтение-запись boolean.

**Возвращает:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Определяет, должны ли четные столбцы отображаться с другим форматированием. Чтение-запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Объединяет соседние ячейки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Ячейка для объединения. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Ячейка для объединения. |
| allowSplitting | boolean | True to allow cells splitting. |

**Возвращает:**
[ICell](../../com.aspose.slides/icell) - Объединённая ячейка.