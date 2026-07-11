---
title: IColumn
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет столбец в таблице.
type: docs
url: /ru/com.aspose.slides/icolumn/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Представляет столбец в таблице.
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Возвращает или задает ширину столбца. |
| [setWidth(double value)](#setWidth-double-) | Возвращает или задает ширину столбца. |
| [getColumnFormat()](#getColumnFormat--) | Возвращает объект ColumnFormat, содержащий свойства форматирования для этого столбца. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Возвращает или задает ширину столбца. Чтение/запись double.

**Возвращаемое значение:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Возвращает или задает ширину столбца. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Возвращает объект ColumnFormat, содержащий свойства форматирования для этого столбца. Только чтение [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Возвращаемое значение:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)