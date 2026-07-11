---
title: TagCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию тегов, заданных пользователем как пары строк
type: docs
url: /ru/com.aspose.slides/tagcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Represents the collection of tags (user defined pairs of strings)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество тегов в коллекции. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Добавляет новый тег в коллекцию. |
| [remove(String name)](#remove-java.lang.String-) | Удаляет тег с указанным именем из коллекции. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Возвращает нулевой индекс указанного ключа в коллекции. |
| [contains(String name)](#contains-java.lang.String-) | Определяет, содержит ли коллекция конкретное имя. |
| [removeAt(int index)](#removeAt-int-) | Удаляет тег по указанному индексу. |
| [clear()](#clear--) | Удаляет все теги из коллекции. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Возвращает значение тега по указанному индексу. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Возвращает ключ тега по указанному индексу. |
| [getNamesOfTags()](#getNamesOfTags--) | Возвращает имена тегов. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Возвращает или задает пару ключ-значение тега. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Возвращает или задает пару ключ-значение тега. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### size() {#size--}
```
public final int size()
```

Возвращает количество тегов в коллекции. Только для чтения int.

**Returns:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Добавляет новый тег в коллекцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя тега. |
| value | java.lang.String | Значение тега. |

**Returns:**
int - Индекс добавленного тега.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Удаляет тег с указанным именем из коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя удаляемого тега. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Возвращает нулевой индекс указанного ключа в коллекции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя для поиска в коллекции. |

**Returns:**
int - Нулевой индекс ключа, если ключ найден в коллекции; иначе -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Определяет, содержит ли коллекция конкретное имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ для поиска. |

**Returns:**
boolean - true, если коллекция содержит тег с указанным ключом; иначе false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет тег по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс тега для удаления. |
### clear() {#clear--}
```
public final void clear()
```

Удаляет все теги из коллекции.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Возвращает значение тега по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс тега для получения. |

**Returns:**
java.lang.String - Значение тега.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Возвращает ключ тега по указанному индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс тега для получения. |

**Returns:**
java.lang.String - Ключ тега.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Возвращает имена тегов.

**Returns:**
java.lang.String[] - Имена тегов.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Возвращает или задает пару ключ-значение тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ тега. |

**Returns:**
java.lang.String - Значение тега.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Возвращает или задает пару ключ-значение тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ тега. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы из коллекции в указанный массив.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Массив для заполнения. |
| index | int | Начальная позиция в целевом массиве. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - java.util.Iterator для всей коллекции.