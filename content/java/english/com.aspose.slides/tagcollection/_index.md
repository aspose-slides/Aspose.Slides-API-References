---
title: TagCollection
second_title: Aspose.Slides for Java API Reference
description: Represents the collection of tags user defined pairs of strings
type: docs
url: /com.aspose.slides/tagcollection/
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
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns a number of tags in the collectoin. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adds a new tag to collection. |
| [remove(String name)](#remove-java.lang.String-) | Removes the tag with a specified name from the collection. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Returns the zero-based index of the specified key in the collection. |
| [contains(String name)](#contains-java.lang.String-) | Determines whether the collection contains a specific name. |
| [removeAt(int index)](#removeAt-int-) | Removes the tag at the specified index. |
| [clear()](#clear--) | Removes all tags from the collection. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Returns value of a tag at the specified index. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Returns key of a tag at the specified index. |
| [getNamesOfTags()](#getNamesOfTags--) | Returns names of tags. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns or sets a key and a value pair of a tag. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returns or sets a key and a value pair of a tag. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection into the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```


Returns a number of tags in the collectoin. Read-only int.

**Returns:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```


Adds a new tag to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the tag. |
| value | java.lang.String | The value of the tag. |

**Returns:**
int - The index of the added tag.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Removes the tag with a specified name from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of tag to remove. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```


Returns the zero-based index of the specified key in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name to locate in the collection. |

**Returns:**
int - The zero-based index of key, if key is found in the collection; otherwise, -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Determines whether the collection contains a specific name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The key to locate. |

**Returns:**
boolean - True if the collection contains an tag with the specified key; otherwise, false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the tag at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the tag to remove. |

### clear() {#clear--}
```
public final void clear()
```


Removes all tags from the collection.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```


Returns value of a tag at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a tag to return. |

**Returns:**
java.lang.String - Value of a tag.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```


Returns key of a tag at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a tag to return. |

**Returns:**
java.lang.String - Key of a tag.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```


Returns names of tags.

**Returns:**
java.lang.String[] - Names of tags.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Returns or sets a key and a value pair of a tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Key of a tag. |

**Returns:**
java.lang.String - Value of a tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Returns or sets a key and a value pair of a tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Key of a tag. |
| value | java.lang.String |  |

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements from the collection into the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array to fill. |
| index | int | Starting position in target array. |

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
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.
