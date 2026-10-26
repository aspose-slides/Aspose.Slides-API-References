---
title: ICaptionsCollection
second_title: Aspose.Slides के लिए Java API रेफ़रेंस
description: बंद कैप्शन के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icaptionscollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

बंद कैप्शन का एक संग्रह दर्शाता है।
## विधियाँ

| मेथड | विवरण |
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


Returns the closed captions at the specified index. केवल-पढ़ने योग्य [ICaptions](../../com.aspose.slides/icaptions).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


संग्रह के अंत में WebVTT बंद कैप्शन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | java.lang.String | The label of the closed captions. |
| filePath | java.lang.String | The path to the WebVTT file. |

**रिटर्न:**
[ICaptions](../../com.aspose.slides/icaptions) - The added [ICaptions](../../com.aspose.slides/icaptions) instance.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


संग्रह के अंत में WebVTT बंद कैप्शन को एक स्ट्रीम से जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | java.lang.String | The label of the closed captions. |
| stream | java.io.InputStream | The input stream containing data in WebVTT format. |

**रिटर्न:**
[ICaptions](../../com.aspose.slides/icaptions) - The added [ICaptions](../../com.aspose.slides/icaptions) instance.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


संग्रह से निर्दिष्ट बंद कैप्शन हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | The closed captions to remove. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


निर्दिष्ट सूचकांक पर बंद कैप्शन हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | The index of the closed captions to remove. |

### clear() {#clear--}
```
public abstract void clear()
```


संग्रह से सभी बंद कैप्शन हटाता है।

### getCount() {#getCount--}
```
public abstract int getCount()
```


संग्रह में तत्वों की संख्या लौटाता है। केवल-पढ़ने योग्य  int ।

**रिटर्न:**
int