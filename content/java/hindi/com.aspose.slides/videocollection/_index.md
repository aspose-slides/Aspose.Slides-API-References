---
title: VideoCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: Video ऑब्जेक्ट्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/videocollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफेस:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Video ऑब्जेक्ट्स का एक संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वीडियो फ़ाइलों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | एक अन्य प्रस्तुति से वीडियो फ़ाइल की एक प्रति जोड़ता है। |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | स्ट्रीम से वीडियो बनाता है और प्रस्तुति में जोड़ता है। |
| [addVideo(byte[] videoData)](#addVideo-byte---) | बाइट एरे से वीडियो बनाता है और प्रस्तुति में जोड़ता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | निर्दिष्ट सूचकांक से शुरू करके वीडियो को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | संग्रह तक पहुँच समक्रमित (थ्रेड-सेफ़) है या नहीं, दर्शाता मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | समक्रमण मूल लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेट करने वाला इनीमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटररेटर लौटाता है। |
### size() {#size--}
```
public final int size()
```

संग्रह में वीडियो फ़ाइलों की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [IVideo](../../com.aspose.slides/ivideo)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

एक अन्य प्रस्तुति से वीडियो फ़ाइल की एक प्रति जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | स्रोत वीडियो। |

**रिटर्न:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया वीडियो।
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

स्ट्रीम से वीडियो बनाता है और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | वीडियो फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | int | स्ट्रीम पर लागू किया जाने वाला व्यवहार। |

**रिटर्न:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया [IVideo](../../com.aspose.slides/ivideo)।
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

बाइट एरे से वीडियो बनाता है और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| videoData | byte[] | वीडियो बाइट्स। |

**रिटर्न:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया वीडियो।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

निर्दिष्ट सूचकांक से शुरू करके वीडियो को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | एरे। |
| index | int | सूचकांक। |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

संग्रह तक पहुँच समक्रमित (थ्रेड-सेफ़) है या नहीं, दर्शाता मान लौटाता है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समक्रमण मूल लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला इनीमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - एक IGenericEnumerator जो संग्रह के भीतर इटरेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

पूरे संग्रह के लिए जावा इटररेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - एक java.util.Iterator जो पूरे संग्रह के लिए है।