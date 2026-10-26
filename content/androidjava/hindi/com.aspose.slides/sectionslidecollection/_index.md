---
title: SectionSlideCollection
second_title: Aspose.Slides for Android हेतु Java API संदर्भ
description: सेक्शन में स्लाइड्स के संग्रह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/sectionslidecollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)  
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

खंड में स्लाइड्स का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | पूरे संग्रह को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो संकेत देता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समक्रमण मूल लौटाता है। |
| [iterator()](#iterator--) | एक इटरेटर लौटाता है जो संग्रह के माध्यम से इटरट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java इटरटर लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। केवल-पठन [ISlide](../../com.aspose.slides/islide)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**  
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पठन int।

**रिटर्न:**  
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

पूरे संग्रह को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे |
| index | int | लक्ष्य एरे में अनुक्रमणिका। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो संकेत देता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। केवल-पठन boolean।

**रिटर्न:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समक्रमण मूल लौटाता है। केवल-पठन Object।

**रिटर्न:**  
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

एक इटरेटर लौटाता है जो संग्रह के माध्यम से इटरट करता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

पूरे संग्रह के लिए एक java इटरटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - An java.util.Iterator for the entire collection.