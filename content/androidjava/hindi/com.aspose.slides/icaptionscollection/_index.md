---
title: ICaptionsCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: क्लोज़्ड कैप्शन का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icaptionscollection/
---
**सभी कार्यान्वित इंटरफेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

क्लोज़्ड कैप्शन का संग्रह दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर क्लोज़्ड कैप्शन लौटाता है। |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | कलेक्शन के अंत में WebVTT क्लोज़्ड कैप्शन जोड़ता है। |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | स्ट्रीम से कलेक्शन के अंत में WebVTT क्लोज़्ड कैप्शन जोड़ता है। |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | कलेक्शन से निर्दिष्ट क्लोज़्ड कैप्शन हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर क्लोज़्ड कैप्शन हटाता है। |
| [clear()](#clear--) | कलेक्शन से सभी क्लोज़्ड कैप्शन हटाता है। |
| [getCount()](#getCount--) | कलेक्शन में तत्वों की संख्या लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


निर्दिष्ट सूचकांक पर क्लोज़्ड कैप्शन लौटाता है। केवल-पढ़ने योग्य [ICaptions](../../com.aspose.slides/icaptions)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


कलेक्शन के अंत में WebVTT क्लोज़्ड कैप्शन जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | java.lang.String | क्लोज़्ड कैप्शन का लेबल। |
| filePath | java.lang.String | WebVTT फ़ाइल का पथ। |

**वापसी:**
[ICaptions](../../com.aspose.slides/icaptions) - जोड़ा गया [ICaptions](../../com.aspose.slides/icaptions) इंस्टेंस।
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


स्ट्रीम से कलेक्शन के अंत में WebVTT क्लोज़्ड कैप्शन जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | java.lang.String | क्लोज़्ड कैप्शन का लेबल। |
| stream | java.io.InputStream | WebVTT फॉर्मेट में डेटा वाली इनपुट स्ट्रीम। |

**वापसी:**
[ICaptions](../../com.aspose.slides/icaptions) - जोड़ा गया [ICaptions](../../com.aspose.slides/icaptions) इंस्टेंस।
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


कलेक्शन से निर्दिष्ट क्लोज़्ड कैप्शन हटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | हटाने के लिए क्लोज़्ड कैप्शन। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


निर्दिष्ट सूचकांक पर क्लोज़्ड कैप्शन हटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए क्लोज़्ड कैप्शन का सूचकांक। |

### clear() {#clear--}
```
public abstract void clear()
```


कलेक्शन से सभी क्लोज़्ड कैप्शन हटाता है।

### getCount() {#getCount--}
```
public abstract int getCount()
```


कलेक्शन में तत्वों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int