---
title: IVideoCollection
second_title: Aspose.Slides for Java API संदर्भ
description: Video ऑब्जेक्ट्स के एक संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ivideocollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Video ऑब्जेक्ट्स का एक संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | एक अन्य प्रस्तुति से वीडियो फ़ाइल की एक प्रति जोड़ता है। |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | स्ट्रीम से एक वीडियो बनाता है और प्रस्तुति में जोड़ता है। |
| [addVideo(byte[] videoData)](#addVideo-byte---) | बाइट एरे से एक वीडियो बनाता है और प्रस्तुति में जोड़ता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [IVideo](../../com.aspose.slides/ivideo)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IVideo](../../com.aspose.slides/ivideo)

### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

एक अन्य प्रस्तुति से वीडियो फ़ाइल की एक प्रति जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | स्रोत वीडियो। |

**वापसी:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया वीडियो।

### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

स्ट्रीम से एक वीडियो बनाता है और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | वीडियो फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | int | वह व्यवहार जो स्ट्रीम पर लागू किया जाएगा। |

**वापसी:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया [IVideo](../../com.aspose.slides/ivideo)।

### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

बाइट ऐरे से एक वीडियो बनाता है और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| videoData | byte[] | वीडियो बाइट्स। |

**वापसी:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया वीडियो।