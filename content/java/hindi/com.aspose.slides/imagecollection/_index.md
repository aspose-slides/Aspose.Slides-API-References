---
title: ImageCollection
second_title: Aspose.Slides for Java API संदर्भ
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

PPImage का संग्रह प्रस्तुत करता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में छवियों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | एक अन्य प्रस्तुति से छवि की एक प्रति जोड़ता है। |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | प्रस्तुति में एक छवि जोड़ता है। |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | स्ट्रीम से प्रस्तुति में एक छवि जोड़ता है। |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | स्ट्रीम से एक छवि बनाता है और प्रस्तुति में जोड़ता है। |
| [addImage(byte[] buffer)](#addImage-byte---) | निर्दिष्ट बफ़र से प्रस्तुति में एक छवि जोड़ता है। |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Svg ऑब्जेक्ट से प्रस्तुति में एक छवि जोड़ता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेट करने वाला एनेरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | समक्रमण रूट लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में छवियों की संख्या लौटाता है। केवल-पढ़ने योग्य  int .

**रिटर्न:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [IPPImage](../../com.aspose.slides/ippimage)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**  
[IPPImage](../../com.aspose.slides/ippimage)

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

एक अन्य प्रस्तुति से छवि की एक प्रति जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | स्रोत छवि। |

**रिटर्न:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

प्रस्तुति में एक छवि जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | जोड़ने के लिए छवि। |
--------------------

यह विधि WMF/EMF मेटाफाइल को प्रस्तुति में सम्मिलित करने से पहले रैस्टर PNG छवि में परिवर्तित करती है। |

**रिटर्न:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

स्ट्रीम से प्रस्तुति में एक छवि जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | छवि जोड़ने के लिए स्ट्रीम। |
--------------------

यह विधि WMF/EMF मेटाफाइल को रास्टर PNG छवि में परिवर्तित किए बिना प्रस्तुति में जोड़ सकती है। |

**रिटर्न:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

स्ट्रीम से एक छवि बनाता है और प्रस्तुति में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | छवि फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | int | स्ट्रीम पर लागू किया जाने वाला व्यवहार। |

**रिटर्न:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ा गया [IPPImage](../../com.aspose.slides/ippimage)।

### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

निर्दिष्ट बफ़र से प्रस्तुति में एक छवि जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | byte[] | बफ़र। |

**रिटर्न:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Svg ऑब्जेक्ट से प्रस्तुति में एक छवि जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg छवि ऑब्जेक्ट [ISvgImage](../../com.aspose.slides/isvgimage) |

**रिटर्न:**  
[IPPImage](../../com.aspose.slides/ippimage) - जोड़ी गई छवि।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला एनेरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

पूरे संग्रह के लिए जावा इटरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। केवल-पढ़ने योग्य  boolean .

**रिटर्न:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समक्रमण रूट लौटाता है। केवल-पढ़ने योग्य  Object .

**रिटर्न:**  
java.lang.Object