---
title: IVideoCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: Video वस्तुओं के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ivideocollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Video वस्तुओं का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | एक अन्य प्रस्तुतीकरण से video फ़ाइल की प्रति जोड़ता है। |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | स्ट्रीम से प्रस्तुतीकरण में video बनाता है और जोड़ता है। |
| [addVideo(byte[] videoData)](#addVideo-byte---) | बाइट एरे से प्रस्तुतीकरण में video बनाता है और जोड़ता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [IVideo](../../com.aspose.slides/ivideo)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी मान:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

एक अन्य प्रस्तुतीकरण से video फ़ाइल की प्रति जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | स्रोत video। |

**वापसी मान:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया video।
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

स्ट्रीम से प्रस्तुतीकरण में video बनाता है और जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | video फ़ाइल जोड़ने के लिये स्ट्रीम। |
| loadingStreamBehavior | int | स्ट्रीम पर लागू किया जाने वाला व्यवहार। |

**वापसी मान:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया [IVideo](../../com.aspose.slides/ivideo)।
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

बाइट एरे से प्रस्तुतीकरण में video बनाता है और जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| videoData | byte[] | video बाइट्स। |

**वापसी मान:**
[IVideo](../../com.aspose.slides/ivideo) - जोड़ा गया video।