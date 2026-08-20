---
title: CaptionsCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: बंद कैप्शन का संग्रह दर्शाता है।
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

बंद कैप्शन का संग्रह दर्शाता है।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर बंद कैप्शन लौटाता है। |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | WebVTT बंद कैप्शन को संग्रह के अंत में जोड़ता है। |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | स्ट्रीम से संग्रह के अंत में WebVTT बंद कैप्शन जोड़ता है। |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | संग्रह से निर्दिष्ट बंद कैप्शन हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट अनुक्रमणिका पर बंद कैप्शन हटाता है। |
| [clear()](#clear--) | संग्रह से सभी बंद कैप्शन हटाता है। |
| [getCount()](#getCount--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरट करने वाला इटररेटर लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

निर्दिष्ट अनुक्रमणिका पर बंद कैप्शन लौटाता है। केवल-पढ़ने योग्य [ICaptions](../../com.aspose.slides/icaptions)।

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

संग्रह के अंत में WebVTT बंद कैप्शन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | java.lang.String | बंद कैप्शन का लेबल। |
| filePath | java.lang.String | WebVTT फ़ाइल का पथ। |

**रिटर्न:**
[ICaptions](../../com.aspose.slides/icaptions) - जोड़ा गया [ICaptions](../../com.aspose.slides/icaptions) उदाहरण।
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

स्ट्रीम से संग्रह के अंत में WebVTT बंद कैप्शन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | java.lang.String | बंद कैप्शन का लेबल। |
| stream | java.io.InputStream | WebVTT फ़ॉर्मेट में डेटा वाली इनपुट स्ट्रीम। |

**रिटर्न:**
[ICaptions](../../com.aspose.slides/icaptions) - जोड़ा गया [ICaptions](../../com.aspose.slides/icaptions) उदाहरण।
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

संग्रह से निर्दिष्ट बंद कैप्शन हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | हटाने के लिए बंद कैप्शन। |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट अनुक्रमणिका पर बंद कैप्शन हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले बंद कैप्शन का अनुक्रमणिका। |
### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी बंद कैप्शन हटाता है।
### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में तत्वों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

एक इटररेटर लौटाता है जो संग्रह में इटरट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - एक System.Collections.Generic.IEnumerator1 जो संग्रह में इटरट करने के लिए उपयोग किया जा सकता है।