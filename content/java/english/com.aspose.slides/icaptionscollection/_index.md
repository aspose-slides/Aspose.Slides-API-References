---
title: ICaptionsCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of the closed captions.
type: docs
url: /com.aspose.slides/icaptionscollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Represents a collection of the closed captions.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the closed captions at the specified index. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Adds WebVTT closed captions to the end of the collection. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Adds WebVTT closed captions to the end of the collection from a stream. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Removes the specified closed captions from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the closed captions at the specified index. |
| [clear()](#clear--) | Removes all closed captions from the collection. |
| [getCount()](#getCount--) | Returns the number of elements in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


Returns the closed captions at the specified index. Read-only [ICaptions](../../com.aspose.slides/icaptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


Adds WebVTT closed captions to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | java.lang.String | The label of the closed captions. |
| filePath | java.lang.String | The path to the WebVTT file. |

**Returns:**
[ICaptions](../../com.aspose.slides/icaptions) - The added [ICaptions](../../com.aspose.slides/icaptions) instance.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


Adds WebVTT closed captions to the end of the collection from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | java.lang.String | The label of the closed captions. |
| stream | java.io.InputStream | The input stream containing data in WebVTT format. |

**Returns:**
[ICaptions](../../com.aspose.slides/icaptions) - The added [ICaptions](../../com.aspose.slides/icaptions) instance.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


Removes the specified closed captions from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | The closed captions to remove. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the closed captions at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the closed captions to remove. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all closed captions from the collection.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Returns the number of elements in the collection. Read-only  int .

**Returns:**
int
