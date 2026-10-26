---
title: RowCollection
second_title: Aspose.Slides для Android через Java API
description: Представляет коллекцию строк таблицы.
type: docs
url: /ru/com.aspose.slides/rowcollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Представляет коллекцию строк таблицы.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Получает фактическое количество строк, содержащихся в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает строку по указанному индексу. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Создает копию указанной шаблонной строки и вставляет её в конец таблицы. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Создает копию указанной шаблонной строки и вставляет её в указанную позицию таблицы. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Удаляет строку в указанной позиции из таблицы. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корень синхронизации. |
### size() {#size--}
```
public final int size()
```

Получает фактическое количество строк, содержащихся в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

Возвращает строку по указанному индексу. Только для чтения [Row](../../com.aspose.slides/row).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Создает копию указанной шаблонной строки и вставляет её в конец таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Строка, используемая в качестве шаблона. |
| withAttachedRows | boolean | True, чтобы также копировать все строки, прикрепленные к шаблонной строке. |

**Возвращаемое значение:**
com.aspose.slides.IRow[] - Добавленные строки.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Создает копию указанной шаблонной строки и вставляет её в указанную позицию таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс новой строки. |
| templ | [IRow](../../com.aspose.slides/irow) | Строка, используемая в качестве шаблона. |
| withAttachedRows | boolean | True, чтобы также копировать все строки, прикрепленные к шаблонной строке. |

**Возвращаемое значение:**
com.aspose.slides.IRow[] - Вставленные строки.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Удаляет строку в указанной позиции из таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstRowIndex | int | Индекс строки для удаления. |
| withAttachedRows | boolean | True, чтобы также удалить все прикрепленные строки. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Перечислитель IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает корень синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object