---
title: AudioCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: एम्बेडेड ऑडियो फ़ाइलों के संग्रह का प्रतिनिधित्व करता है।
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

एम्बेडेड ऑडियो फ़ाइलों के संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में ऑडियो फ़ाइलों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | एक अन्य प्रस्तुति से ऑडियो फ़ाइल की एक प्रति जोड़ता है। |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | स्ट्रीम से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है। |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | स्ट्रीम से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है। |
| [addAudio(byte[] audioData)](#addAudio-byte---) | बाइट एरे से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | निर्दिष्ट अनुक्रमांक से शुरू होकर ऑडियो को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समानक्रमित (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | सिंक्रनाइज़ेशन रूट लौटाता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है। |
### size() {#size--}
```
public final int size()
```


संग्रह में ऑडियो फ़ाइलों की संख्या लौटाता है। केवल पढ़ने योग्य int।

**रिटर्न:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```


निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [IAudio](../../com.aspose.slides/iaudio)।

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


एक अन्य प्रस्तुति से ऑडियो फ़ाइल की एक प्रति जोड़ता है।

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


स्ट्रीम से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है।

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


स्ट्रीम से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | वीडियो ऑडियो जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | int | स्ट्रीम पर लागू किया जाने वाला व्यवहार। |

**रिटर्न:**  
[IAudio](../../com.aspose.slides/iaudio) - जोड़ा गया ऑडियो।
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```


बाइट एरे से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है।

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


निर्दिष्ट अनुक्रमांक से शुरू होकर ऑडियो को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | एरे। |
| index | int | इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समानक्रमित (थ्रेड-सुरक्षित) है या नहीं। केवल पढ़ने योग्य boolean।

**रिटर्न:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


सिंक्रनाइज़ेशन रूट लौटाता है। केवल पढ़ने योग्य Object।

**रिटर्न:**  
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```


एक एनेमरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```


पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - पूरे संग्रह के लिए एक java.util.Iterator।