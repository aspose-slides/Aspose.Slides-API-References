---
title: VbaReferenceCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию ссылок проекта VBA.
type: docs
url: /ru/com.aspose.slides/vbareferencecollection/
---
**Наследование:**  
java.lang.Object

**Все реализованные интерфейсы:**  
[com.aspose.slides.IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)  
```
public class VbaReferenceCollection implements IVbaReferenceCollection
```

Представляет коллекцию ссылок проекта VBA.

## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество элементов, фактически содержащихся в коллекции. |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | Добавляет новую ссылку в коллекцию ссылок |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |

### size() {#size--}
```
public final int size()
```

Возвращает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возвращаемое значение:**  
int

### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```

Добавляет новую ссылку в коллекцию ссылок

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```

Возвращает элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**  
[IVbaReference](../../com.aspose.slides/ivbareference)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - IGenericEnumerator, который можно использовать для перебора элементов коллекции.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - java.util.Iterator, который можно использовать для всей коллекции.

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

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Возвращаемое значение:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возвращаемое значение:**  
java.lang.Object