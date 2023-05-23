---
title: CustomXmlPartCollection
second_title: Aspose.Slides for Java API Reference
description: Represents collection of custom xml parts.
type: docs
weight: 147
url: /java/com.aspose.slides/customxmlpartcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Represents collection of custom xml parts.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the element at the specified index. |
| [size()](#size--) | Returns count of custom xml parts in the collection. |
| [add(String xmlString)](#add-java.lang.String-) | Adds new custom xml part. |
| [add(byte[] xmlData)](#add-byte---) | Adds new custom xml part. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Adds new custom xml part. |
| [removeAt(int index)](#removeAt-int-) | Removes custom xml part at the specified index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Removes the first occurrence of a specific object from the collection. |
| [clear()](#clear--) | Removes all items from the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copy to specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```


Returns the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to get. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - The element at the specified index.
### size() {#size--}
```
public final int size()
```


Returns count of custom xml parts in the collection. Read-only int.

**Returns:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```


Adds new custom xml part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlString | java.lang.String | The xml string of new part to be added. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Created custom xml part.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```


Adds new custom xml part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlData | byte[] | The xml data of new part to be added. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Created custom xml part.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```


Adds new custom xml part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The inputStream with xml data of new part to be added. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Created custom xml part.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes custom xml part at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```


Removes the first occurrence of a specific object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | The custom xml part to remove. |

**Returns:**
boolean - true if item is successfully removed; otherwise, false.
### clear() {#clear--}
```
public final void clear()
```


Removes all items from the collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copy to specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array to copy to. |
| index | int | Index to begin copying. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Read-only Object.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - An java.util.Iterator for the entire collection.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
