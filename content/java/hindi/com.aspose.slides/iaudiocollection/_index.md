---
title: IAudioCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एम्बेडेड ऑडियो फ़ाइलों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/iaudiocollection/
---
**सभी लागू इंटरफेस:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

एक एम्बेडेड ऑडियो फ़ाइलों का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | किसी अन्य प्रस्तुति से एक ऑडियो फ़ाइल की प्रति जोड़ता है। |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | स्ट्रीम से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है। |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | स्ट्रीम से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है। |
| [addAudio(byte[] audioData)](#addAudio-byte---) | बाइट एरे से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [IAudio](../../com.aspose.slides/iaudio).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

किसी अन्य प्रस्तुति से एक ऑडियो फ़ाइल की प्रति जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | स्रोत ऑडियो। |

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio) - जोड़ित ऑडियो।
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

स्ट्रीम से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | ऑडियो जोड़ने के लिए स्ट्रीम। |

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio) - जोड़ित ऑडियो।
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

स्ट्रीम से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | वीडियो ऑडियो जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | int | [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) वह मान है जो स्ट्रीम पर लागू किया जाएगा। |

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio) - जोड़ित ऑडियो।
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

बाइट एरे से एक ऑडियो बनाता है और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| audioData | byte[] | ऑडियो बाइट्स। |

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio) - जोड़ित ऑडियो।