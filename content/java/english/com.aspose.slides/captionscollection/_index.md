---
title: CaptionsCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of the closed captions.
type: docs
url: /com.aspose.slides/captionscollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Represents a collection of the closed captions.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the closed captions by index. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Adds WebVTT closed captions at the end of the collection. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Adds WebVTT closed captions at the end of the collection. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Removes the closed captions from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the closed captions at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [getCount()](#getCount--) | Returns the number of elements in the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


Returns the closed captions by index. Read-only [ICaptions](../../com.aspose.slides/icaptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```


Adds WebVTT closed captions at the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | java.lang.String | Label of the closed captions. |
| filePath | java.lang.String | Path to the file in WebVTT format. |

**Returns:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```


Adds WebVTT closed captions at the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | java.lang.String | Label of the closed captions. |
| stream | java.io.InputStream | Input stream with data in WebVTT format. |

**Returns:**
[ICaptions](../../com.aspose.slides/icaptions)
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


Removes the closed captions from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Captions object that should be deleted. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the closed captions at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the closed captions that should be deleted. |

### clear() {#clear--}
```
public final void clear()
```


Removes all elements from the collection.

### getCount() {#getCount--}
```
public final int getCount()
```


Returns the number of elements in the collection. Read-only  int .

**Returns:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - A  System.Collections.Generic.IEnumerator1  that can be used to iterate through the collection.
