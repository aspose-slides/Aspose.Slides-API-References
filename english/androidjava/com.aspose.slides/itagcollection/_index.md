---
title: ITagCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the collection of tags user defined pairs of strings
type: docs
weight: 1071
url: /androidjava/com.aspose.slides/itagcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Represents the collection of tags (user defined pairs of strings)
## Methods

| Method | Description |
| --- | --- |
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
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
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
public abstract void remove(String name)
```


Removes the tag with a specified name from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of tag to remove. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
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
public abstract boolean contains(String name)
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
public abstract void removeAt(int index)
```


Removes the tag at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the tag to remove. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all tags from the collection.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
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
public abstract String getNameByIndex(int index)
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
public abstract String[] getNamesOfTags()
```


Returns names of tags.

**Returns:**
java.lang.String[] - Names of tags.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```


Returns or sets a key and a value pair of a tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Key of a tag. |
| value | java.lang.String |  |

