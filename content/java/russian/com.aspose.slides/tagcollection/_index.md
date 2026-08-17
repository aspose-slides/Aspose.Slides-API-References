---
title: TagCollection
second_title: Aspose.Slides для Java справочник API
description: Представляет коллекцию тегов, определяемых пользователем как пары строк
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

Представляет коллекцию тегов (пары строк, определяемые пользователем)

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
| [contains(String name)](#contains-java.lang.String-) | Определяет, содержит ли коллекция заданное имя. |
| [removeAt(int index)](#removeAt-int-) | Удаляет тег по указанному индексу. |
| [clear()](#clear--) | Удаляет все теги из коллекции. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Возвращает значение тега по указанному индексу. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Возвращает ключ тега по указанному индексу. |
| [getNamesOfTags()](#getNamesOfTags--) | Возвращает имена тегов. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Возвращает или задает пару «ключ-значение» тега. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Возвращает или задает пару «ключ-значение» тега. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по элементам коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### size() {#size--}
```
public final int size()
```

Возвращает количество тегов в коллекции. Только для чтения int.

**Возврат:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Добавляет новый тег в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя тега. |
| value | java.lang.String | Значение тега. |

**Возврат:**
int - Индекс добавленного тега.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Удаляет тег с указанным именем из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя удаляемого тега. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Возвращает нулевой индекс указанного ключа в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя, которое требуется найти в коллекции. |

**Возврат:**
int - Нулевой индекс ключа, если ключ найден; иначе -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Определяет, содержит ли коллекция заданное имя.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ для поиска. |

**Возврат:**
boolean - true, если коллекция содержит тег с указанным ключом; иначе false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет тег по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс удаляемого тега. |
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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс тега для возврата. |

**Возврат:**
java.lang.String - Значение тега.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Возвращает ключ тега по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс тега для возврата. |

**Возврат:**
java.lang.String - Ключ тега.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Возвращает имена тегов.

**Возврат:**
java.lang.String[] - Имена тегов.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Возвращает или задает пару «ключ-значение» тега.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ тега. |

**Возврат:**
java.lang.String - Значение тега.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Возвращает или задает пару «ключ-значение» тега.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Ключ тега. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Массив для заполнения. |
| index | int | Начальная позиция в целевом массиве. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). Только для чтения boolean.

**Возврат:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возврат:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Возвращает перечислитель, который проходит по элементам коллекции.

**Возврат:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возврат:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - java.util.Iterator для всей коллекции.