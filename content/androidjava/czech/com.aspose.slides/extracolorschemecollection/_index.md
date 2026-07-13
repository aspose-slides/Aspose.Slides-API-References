---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides pro Android pomocí Java API
description: Představuje kolekci dalších barevných schémat.
type: docs
url: /cs/com.aspose.slides/extracolorschemecollection/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Představuje kolekci dalších barevných schémat.
## Metody

| Metoda | Popis |
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


Returns a number of elements int the collection. Read-only int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```


Returns an color scheme by index. Read-only [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent_Immediate object. Read-only IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```


Returns an enumerator that iterates through the collection.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```


Returns a java iterator for the entire collection.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements of the collection to the specified array.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the ArrayList is synchronized (thread safe). Read-only boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns an object that can be used to synchronize access to the collection. Read-only Object.

Returns a synchronization root. Read-only Object.

**Vrací:**
java.lang.Object