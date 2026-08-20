---
title: AudioCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एम्बेडेड ऑडियो फ़ाइलों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/audiocollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

एम्बेडेड ऑडियो फ़ाइलों का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में ऑडियो फ़ाइलों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | किसी अन्य प्रस्तुति से एक ऑडियो फ़ाइल की कॉपी जोड़ता है। |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | स्ट्रीम से एक ऑडियो बनाता और प्रस्तुति में जोड़ता है। |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | स्ट्रीम से एक ऑडियो बनाता और प्रस्तुति में जोड़ता है। |
| [addAudio(byte[] audioData)](#addAudio-byte---) | बाइट एरे से एक ऑडियो बनाता और प्रस्तुति में जोड़ता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | निर्दिष्ट अनुक्रमांक से शुरू करते हुए निर्दिष्ट एरे में ऑडियो कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समन्वित (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | समन्वयन मूल लौटाता है। |
| [iterator()](#iterator--) | एक एन्यूमरेटर लौटाता है जो संग्रह को इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है। |
### size() {#size--}
```
public final int size()
```

संग्रह में ऑडियो फ़ाइलों की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [IAudio](../../com.aspose.slides/iaudio)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

किसी अन्य प्रस्तुति से एक ऑडियो फ़ाइल की कॉपी जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | स्रोत ऑडियो। |

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio) - जोड़ा गया ऑडियो।
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

स्ट्रीम से एक ऑडियो बनाता और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | ऑडियो जोड़ने के लिए स्ट्रीम। |

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio) - जोड़ा गया ऑडियो।
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

स्ट्रीम से एक ऑडियो बनाता और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | ऑडियो जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | int | स्ट्रीम पर लागू किया जाएगा ऐसा व्यवहार। |

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio) - जोड़ा गया ऑडियो।
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

बाइट एरे से एक ऑडियो बनाता और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| audioData | byte[] | ऑडियो बाइट्स। |

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio) - जोड़ा गया ऑडियो।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

निर्दिष्ट अनुक्रमांक से शुरू करते हुए निर्दिष्ट एरे में ऑडियो कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | एरे। |
| index | int | अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समन्वित (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समन्वयन मूल लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

एक एन्यूमरेटर लौटाता है जो संग्रह को इटररेट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - एक IGenericEnumerator जो संग्रह को इटररेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

एक जावा इटररेटर लौटाता है जो पूरे संग्रह के लिये उपयोग किया जा सकता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - एक java.util.Iterator जो पूरे संग्रह के लिये उपयोग किया जा सकता है।