---
title: VideoCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: Video ऑब्जेक्ट्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/videocollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Video ऑब्जेक्ट्स का एक संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वीडियो फ़ाइलों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | दूसरी प्रस्तुति से एक वीडियो फ़ाइल की प्रति जोड़ता है। |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | स्ट्रीम से एक वीडियो बनाता और प्रस्तुति में जोड़ता है। |
| [addVideo(byte[] videoData)](#addVideo-byte---) | बाइट एरे से एक वीडियो बनाता और प्रस्तुति में जोड़ता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | निर्दिष्ट इंडेक्स से शुरू करके वीडियो को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | संग्रह तक पहुँच के समकालिक (थ्रेड-सेफ़) होने को दर्शाने वाला मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | समकालिक मूल लौटाता है। |
| [iterator()](#iterator--) | एक enumerator लौटाता है जो संग्रह के माध्यम से इटरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरा संग्रह के लिए java iterator लौटाता है। |
### size() {#size--}
```
public final int size()
```


संग्रह में वीडियो फ़ाइलों की संख्या लौटाता है। केवल पढ़ने योग्य int.

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [IVideo](../../com.aspose.slides/ivideo).

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```


दूसरी प्रस्तुति से एक वीडियो फ़ाइल की प्रति जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | स्रोत वीडियो। |

**रिटर्न:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया वीडियो।
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


स्ट्रीम से एक वीडियो बनाता और प्रस्तुती में जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | वीडियो फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | int | स्ट्रीम पर लागू किया जाएगा ऐसा व्यवहार। |

**रिटर्न:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया [IVideo](../../com.aspose.slides/ivideo)।
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```


बाइट एरे से एक वीडियो बनाता और प्रस्तुति में जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| videoData | byte[] | वीडियो बाइट्स। |

**रिटर्न:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया वीडियो।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


निर्दिष्ट इंडेक्स से शुरू करके वीडियो को निर्दिष्ट एरे में कॉपी करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | एरे। |
| index | int | इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


संग्रह तक पहुँच के समकालिक (थ्रेड-सेफ़) होने को दर्शाने वाला मान लौटाता है। केवल पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


समकालिक मूल लौटाता है। केवल पढ़ने योग्य Object.

**रिटर्न:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


एक enumerator लौटाता है जो संग्रह के माध्यम से इटरेट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


पूरा संग्रह के लिए java iterator लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - An java.util.Iterator for the entire collection.