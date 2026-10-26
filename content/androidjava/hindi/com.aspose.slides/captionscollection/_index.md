---
title: CaptionsCollection
second_title: Aspose.Slides for Android हेतु Java API संदर्भ
description: बंद कैप्शन का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/captionscollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

बंद कैप्शन का एक संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the closed captions at the specified index. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Adds WebVTT closed captions to the end of the collection. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Adds WebVTT closed captions to the end of the collection from a stream. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Removes the specified closed captions from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the closed captions at the specified index. |
| [clear()](#clear--) | Removes all closed captions from the collection. |
| [getCount()](#getCount--) | Returns the number of elements in the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


Returns the closed captions at the specified index. केवल-पढ़ने योग्य [ICaptions](../../com.aspose.slides/icaptions).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```


Adds WebVTT closed captions to the end of the collection.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | java.lang.String | The label of the closed captions. |
| filePath | java.lang.String | The path to the WebVTT file. |

**रिटर्न:**
[ICaptions](../../com.aspose.slides/icaptions) - The added [ICaptions](../../com.aspose.slides/icaptions) instance.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```


Adds WebVTT closed captions to the end of the collection from a stream.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | java.lang.String | The label of the closed captions. |
| stream | java.io.InputStream | The input stream containing data in WebVTT format. |

**रिटर्न:**
[ICaptions](../../com.aspose.slides/icaptions) - The added [ICaptions](../../com.aspose.slides/icaptions) instance.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


Removes the specified closed captions from the collection.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | The closed captions to remove. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the closed captions at the specified index.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | The index of the closed captions to remove. |

### clear() {#clear--}
```
public final void clear()
```


Removes all closed captions from the collection.

### getCount() {#getCount--}
```
public final int getCount()
```


Returns the number of elements in the collection. केवल-पढ़ने योग्य int .

**रिटर्न:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


Returns an enumerator that iterates through the collection.

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - A  System.Collections.Generic.IEnumerator1  that can be used to iterate through the collection.