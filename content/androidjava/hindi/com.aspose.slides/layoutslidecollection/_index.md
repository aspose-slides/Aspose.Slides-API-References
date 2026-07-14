---
title: LayoutSlideCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: लेआउट स्लाइड्स के संग्रह के लिए एक बेस क्लास का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/layoutslidecollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

लेआउट स्लाइड्स के संग्रह के लिए एक बेस क्लास का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | किसी संग्रह में लेआउट स्लाइड्स की संख्या लौटाती है। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा लेआउट स्लाइड लौटाती है। |
| [getByType(byte type)](#getByType-byte-) | निर्दिष्ट प्रकार की पहली लेआउट स्लाइड लौटाती है। |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | कलेक्शन से एक लेआउट हटाता है। |
| [removeUnused()](#removeUnused--) | उपयोग नहीं किए गए लेआउट स्लाइड्स हटाता है (जिन लेआउट स्लाइड्स का HasDependingSlides false है)। |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटरेट करने वाला एन्उमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच सिंक्रोनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रोनाइज़ेशन रूट लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


किसी संग्रह में लेआउट स्लाइड्स की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```


इंडेक्स द्वारा लेआउट स्लाइड लौटाता है। केवल-पढ़ने योग्य [LayoutSlide](../../com.aspose.slides/layoutslide)।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```


निर्दिष्ट प्रकार की पहली लेआउट स्लाइड लौटाता है।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| type | byte | खोजने के लिए लेआउट स्लाइड का प्रकार। |

**वापसी:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) निर्दिष्ट प्रकार के साथ या यदि कोई लेआउट नहीं मिला तो null।
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```


कलेक्शन से एक लेआउट हटाता है।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | कलेक्शन से हटाने के लिए लेआउट स्लाइड।  

--------------------

1) PptxEditException के उत्पन्न होने से बचने के लिए लेआउट की HasDependingSlides प्रॉपर्टी को पहले जांचें। 2) आप कोड को सरल बनाने के लिए [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) मेथड का भी उपयोग कर सकते हैं। |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```


उपयोग नहीं किए गए लेआउट स्लाइड्स हटाता है (जिन लेआउट स्लाइड्स का HasDependingSlides false है)।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```


कलेक्शन के माध्यम से इटरेट करने वाला एन्उमरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - कलेक्शन के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```


पूरे संग्रह के लिए एक जावा इटरटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - पूरे संग्रह के लिए एक java.util.Iterator।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


संग्रह के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित एरे। |
| index | int | लक्षित एरे में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच सिंक्रोनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक सिंक्रोनाइज़ेशन रूट लौटाता है। केवल-पढ़ने योग्य Object।

**वापसी:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject