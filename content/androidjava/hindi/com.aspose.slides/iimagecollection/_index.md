---
title: IImageCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: PPImage का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/iimagecollection/
---
**सभी कार्यान्वित इंटरफ़ेस:**  
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

PPImage का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा छवि लौटाता है। |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | एक प्रस्तुति में छवि जोड़ता है। |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | स्ट्रीम से एक प्रस्तुति में छवि जोड़ता है। |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | स्ट्रीम से एक प्रस्तुति में छवि बनाता और जोड़ता है। |
| [addImage(byte[] buffer)](#addImage-byte---) | निर्दिष्ट बफ़र से एक प्रस्तुति में छवि जोड़ता है। |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | किसी अन्य प्रस्तुति से छवि की कॉपी जोड़ता है। |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | SVG ऑब्जेक्ट से एक प्रस्तुति में छवि जोड़ता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

इंडेक्स द्वारा छवि लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | इंडेक्स। |

**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage) - छवि।

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

एक प्रस्तुति में छवि जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | जोड़ने के लिए छवि। |

--------------------

यह मेथड प्रस्तुति में डालने से पहले WMF/EMF मेटा-फ़ाइलों को रास्टर PNG छवि में बदलता है।  

**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

स्ट्रीम से एक प्रस्तुति में छवि जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | छवि जोड़ने के लिए स्ट्रीम। |

--------------------

यह मेथड WMF/EMF मेटा-फ़ाइलों को रास्टर PNG छवि में बदले बिना प्रस्तुति में जोड़ सकता है।  

**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

स्ट्रीम से एक प्रस्तुति में छवि बनाता और जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | छवि फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | int | स्ट्रीम पर लागू किया जाने वाला व्यवहार। |

**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई [IPPImage](../../com.aspose.slides/ippimage)।

### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

निर्दिष्ट बफ़र से एक प्रस्तुति में छवि जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | byte[] | बफ़र। |

**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

किसी अन्य प्रस्तुति से छवि की कॉपी जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | स्रोत छवि। |

**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

SVG ऑब्जेक्ट से एक प्रस्तुति में छवि जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG छवि ऑब्जेक्ट [ISvgImage](../../com.aspose.slides/isvgimage) |

**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।