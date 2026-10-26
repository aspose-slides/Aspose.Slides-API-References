---
title: TabCollection
second_title: Aspose.Slides Java API referencia
description: A tabok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/tabcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

A tabok gyűjteményét képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(double position, int align)](#add-double-int-) | Adds a Tab to the collection. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Adds a Tab to the collection. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether two TabsEx instances are equal. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```


Gets the number of elements actually contained in the collection. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```


Gets the element at the specified index. Csak olvasható [Tab](../../com.aspose.slides/tab).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```


Tabot ad a gyűjteményhez.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Visszatér:**
[ITab](../../com.aspose.slides/itab) - Added tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```


Tabot ad a gyűjteményhez.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | The Tab object to be added at the end of the collection. |

**Visszatér:**
int - The index at which the tab was added.
### clear() {#clear--}
```
public final void clear()
```


Eltávolítja a gyűjtemény összes elemét.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolítja a gyűjteményben a megadott indexű elemet.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent_Immediate object. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy két TabsEx példány egyenlő-e.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The TabsEx to compare with the current TabsEx. |

**Visszatér:**
boolean - **true** if the specified TabsEx is equal to the current TabsEx; otherwise, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```


Returns an enumerator that iterates through the collection.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```


Visszatér egy java iterátorral a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Másolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Csak olvasható boolean. Returns a value indicating whether access to the collection is synchronized (thread-safe).

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Csak olvasható Object. Returns a synchronization root.

**Visszatér:**
java.lang.Object