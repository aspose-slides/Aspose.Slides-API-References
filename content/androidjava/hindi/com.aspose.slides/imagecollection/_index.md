---
title: ImageCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: PPImage का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/imagecollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)  
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

PPImage का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में छवियों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | एक अन्य प्रस्तुति से छवि की प्रति जोड़ता है। |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | एक प्रस्तुति में छवि जोड़ें। |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | स्ट्रीम से एक प्रस्तुति में छवि जोड़ें। |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | स्ट्रीम से एक प्रस्तुति में छवि बनाता और जोड़ता है। |
| [addImage(byte[] buffer)](#addImage-byte---) | निर्दिष्ट बफ़र से एक प्रस्तुति में छवि जोड़ता है। |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Svg ऑब्जेक्ट से एक प्रस्तुति में छवि जोड़ें। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेट करने वाला enumerator लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए java iterator लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट array में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | समक्रमण रूट लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में छवियों की संख्या लौटाता है। केवल पढ़ने योग्य  int .

**वापसी:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [IPPImage](../../com.aspose.slides/ippimage)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**  
[IPPImage](../../com.aspose.slides/ippimage)

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

एक अन्य प्रस्तुति से छवि की प्रति जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | स्रोत छवि। |

**वापसी:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

एक प्रस्तुति में छवि जोड़ें।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | जोड़ने के लिए छवि। |

--------------------

यह विधि WMF/EMF मेटाफाइलों को प्रस्तुति में सम्मिलित करने से पहले रास्टर PNG छवि में बदलती है।  

**वापसी:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

स्ट्रीम से एक प्रस्तुति में छवि जोड़ें।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | छवि जोड़ने के लिए स्ट्रीम। |

--------------------

यह विधि WMF/EMF मेटाफाइलों को प्रस्तुति में बिना रास्टर PNG छवि में बदले जोड़ सकती है।  

**वापसी:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
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
public final IPPImage addImage(byte[] buffer)
```

निर्दिष्ट बफ़र से एक प्रस्तुति में छवि जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | byte[] | बफ़र। |

**वापसी:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Svg ऑब्जेक्ट से एक प्रस्तुति में छवि जोड़ें।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg छवि ऑब्जेक्ट [ISvgImage](../../com.aspose.slides/isvgimage) |

**वापसी:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला enumerator लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

पूरे संग्रह के लिए java iterator लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट array में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य array। |
| index | int | लक्ष्य array में प्रारंभिक अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। केवल पढ़ने योग्य  boolean .

**वापसी:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समक्रमण रूट लौटाता है। केवल पढ़ने योग्य  Object .

**वापसी:**  
java.lang.Object