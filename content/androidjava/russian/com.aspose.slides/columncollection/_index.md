---
title: ColumnCollection
second_title: Справочник API Aspose.Slides для Android через Java
description: Представляет коллекцию столбцов в таблице.
type: docs
url: /ru/com.aspose.slides/columncollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Представляет коллекцию столбцов в таблице.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество столбцов в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает столбец по указанному индексу. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Создаёт копию указанной шаблонной строки и вставляет её в конец таблицы. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Создаёт копию указанного шаблонного столбца и вставляет её в указанную позицию таблицы. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Удаляет столбец в указанной позиции из таблицы. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корень синхронизации. |

### size() {#size--}
```
public final int size()
```

Возвращает количество столбцов в коллекции. Только для чтения int.

**Возвращаемое значение:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Возвращает столбец по указанному индексу. Только для чтения [Column](../../com.aspose.slides/column).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IColumn](../../com.aspose.slides/icolumn)

### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Создаёт копию указанной шаблонной строки и вставляет её в конец таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Столбец, используемый в качестве шаблона. |
| withAttachedColumns | boolean | True, чтобы также скопировать все столбцы, прикреплённые к шаблонной строке. |

**Возвращаемое значение:**
com.aspose.slides.IColumn[] - Добавленные столбцы.

### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Создаёт копию указанного шаблонного столбца и вставляет её в указанную позицию таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового столбца. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Столбец, используемый в качестве шаблона. |
| withAttachedColumns | boolean | True, чтобы также скопировать все столбцы, прикреплённые к шаблонному столбцу. |

**Возвращаемое значение:**
com.aspose.slides.IColumn[] - Вставленные столбцы.

### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Удаляет столбец в указанной позиции из таблицы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstColumnIndex | int | Индекс столбца для удаления. |
| withAttachedRows | boolean | True, чтобы также удалить все прикреплённые столбцы. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - IGenericEnumerator, который можно использовать для перебора коллекции.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - java.util.Iterator для всей коллекции.

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