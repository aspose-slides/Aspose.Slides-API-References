---
title: IRowCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию строк таблицы.
type: docs
url: /ru/com.aspose.slides/irowcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Представляет коллекцию строк таблицы.

## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Создаёт копию указанной строки-шаблона и вставляет её в конец таблицы. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Создаёт копию указанной строки-шаблона и вставляет её в указанную позицию в таблице. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Удаляет строку в указанной позиции из таблицы. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

Получает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IRow](../../com.aspose.slides/irow)

### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Создаёт копию указанной строки-шаблона и вставляет её в конец таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Строка, используемая в качестве шаблона. |
| withAttachedRows | boolean | True, чтобы также копировать все строки, прикреплённые к строке-шаблону. |

**Возвращаемое значение:**
com.aspose.slides.IRow[] - Добавленные строки.

### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Создаёт копию указанной строки-шаблона и вставляет её в указанную позицию в таблице.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс новой строки. |
| templ | [IRow](../../com.aspose.slides/irow) | Строка, используемая в качестве шаблона. |
| withAttachedRows | boolean | True, чтобы также копировать все строки, прикреплённые к строке-шаблону. |

**Возвращаемое значение:**
com.aspose.slides.IRow[] - Вставленные строки.

### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Удаляет строку в указанной позиции из таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstRowIndex | int | Индекс строки, которую нужно удалить. |
| withAttachedRows | boolean | True, чтобы также удалить все прикреплённые строки. |