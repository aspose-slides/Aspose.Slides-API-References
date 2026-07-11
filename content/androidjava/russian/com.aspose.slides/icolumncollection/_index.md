---
title: IColumnCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию столбцов в таблице.
type: docs
url: /ru/com.aspose.slides/icolumncollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Представляет коллекцию столбцов в таблице.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает столбец по указанному индексу. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Создает копию указанной строки-шаблона и вставляет её в конец таблицы. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Создает копию указанного столбца-шаблона и вставляет её в указанную позицию в таблице. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Удаляет столбец в указанной позиции из таблицы. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


Возвращает столбец по указанному индексу. Только для чтения [IColumn](../../com.aspose.slides/icolumn).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Создает копию указанной строки-шаблона и вставляет её в конец таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Столбец, используемый как шаблон. |
| withAttachedColumns | boolean | True, если также копировать все столбцы, прикреплённые к строке-шаблону. |

**Возвращаемое значение:**
com.aspose.slides.IColumn[] - Добавленные столбцы.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Создает копию указанного столбца-шаблона и вставляет её в указанную позицию в таблице.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового столбца. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Столбец, используемый как шаблон. |
| withAttachedColumns | boolean | True, если также копировать все столбцы, прикреплённые к столбцу-шаблону. |

**Возвращаемое значение:**
com.aspose.slides.IColumn[] - Вставленные столбцы.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Удаляет столбец в указанной позиции из таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstColumnIndex | int | Индекс столбца для удаления. |
| withAttachedRows | boolean | True, если также удалить все прикреплённые столбцы. |