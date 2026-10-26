---
title: IRowCollection
second_title: Справочник API Aspose.Slides для Java
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
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Создаёт копию указанной шаблонной строки и вставляет её в конец таблицы. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Создаёт копию указанной шаблонной строки и вставляет её в указанную позицию таблицы. |
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

Создаёт копию указанной шаблонной строки и вставляет её в конец таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Строка, используемая как шаблон. |
| withAttachedRows | boolean | True, если также копировать все строки, прикрепленные к шаблонной строке. |

**Возвращаемое значение:**
com.aspose.slides.IRow[] - Добавленные строки.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Создаёт копию указанной шаблонной строки и вставляет её в указанную позицию таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс новой строки. |
| templ | [IRow](../../com.aspose.slides/irow) | Строка, используемая как шаблон. |
| withAttachedRows | boolean | True, если также копировать все строки, прикрепленные к шаблонной строке. |

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
| firstRowIndex | int | Индекс строки для удаления. |
| withAttachedRows | boolean | True, если также удалить все прикрепленные строки. |