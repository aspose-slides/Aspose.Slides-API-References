---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию дополнительных цветовых схем.
type: docs
url: /ru/com.aspose.slides/extracolorschemecollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Представляет коллекцию дополнительных цветовых схем.
## Методы

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns a number of elements int the collection. |
| [get_Item(int index)](#get-Item-int-) | Returns an color scheme by index. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements of the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the ArrayList is synchronized (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns an object that can be used to synchronize access to the collection. |
### size() {#size--}
```
public final int size()
```


Возвращает количество элементов в коллекции. Только для чтения int.

**Возвращает:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```


Возвращает цветовую схему по индексу. Только для чтения [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent\_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```


Возвращает перечислитель, который проходит по коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Копирует все элементы коллекции в указанный массив.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Возвращает значение, указывающее, синхронизирован ли доступ к ArrayList (потокобезопасен). Только для чтения boolean.

**Возвращает:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Возвращает объект, который может быть использован для синхронизации доступа к коллекции. Только для чтения Object.

Возвращает корень синхронизации. Только для чтения Object.

**Возвращает:**
java.lang.Object