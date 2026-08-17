---
title: ExtraColorSchemeCollection
second_title: Справочник API Aspose.Slides для Java
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

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество элементов в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает цветовую схему по индексу. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к ArrayList (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект, который может использоваться для синхронизации доступа к коллекции. |
### size() {#size--}
```
public final int size()
```


Возвращает количество элементов в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```


Возвращает цветовую схему по индексу. Только для чтения [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```


Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Копирует все элементы коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в массиве. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Возвращает значение, указывающее, синхронизирован ли доступ к ArrayList (потокобезопасен). Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Возвращает объект, который может использоваться для синхронизации доступа к коллекции. Только для чтения Object.

Возвращает корень синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object