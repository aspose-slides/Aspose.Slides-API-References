---
title: LayoutSlideCollection
second_title: Aspose.Slides for Java API संदर्भ
description: लेआउट स्लाइड्स के संग्रह के लिए एक आधार वर्ग का प्रतिनिधित्व करता है।
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

लेआउट स्लाइड्स के संग्रह के लिए एक आधार वर्ग का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | कलेक्शन में लेआउट स्लाइड्स की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा लेआउट स्लाइड लौटाता है। |
| [getByType(byte type)](#getByType-byte-) | निर्दिष्ट प्रकार की पहली लेआउट स्लाइड लौटाता है। |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | संग्रह से एक लेआउट हटाता है। |
| [removeUnused()](#removeUnused--) | अप्रयुक्त लेआउट स्लाइड्स को हटाता है (जिन लेआउट स्लाइड्स की HasDependingSlides झूठी है)। |
| [iterator()](#iterator--) | संग्रह को इटररेट करने वाला एन्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सेफ) है या नहीं। केवल-पढ़ने-योग्य boolean. |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक मूल लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

कलेक्शन में लेआउट स्लाइड्स की संख्या लौटाता है। केवल-पढ़ने-योग्य int.

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

इंडेक्स द्वारा लेआउट स्लाइड लौटाता है। केवल-पढ़ने-योग्य [LayoutSlide](../../com.aspose.slides/layoutslide).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

निर्दिष्ट प्रकार की पहली लेआउट स्लाइड लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | byte | खोजने के लिए लेआउट स्लाइड का प्रकार। |

**रिटर्न:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) निर्दिष्ट प्रकार के साथ या यदि कोई लेआउट नहीं मिला तो null।
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

संग्रह से एक लेआउट हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | संग्रह से हटाने के लिए लेआउट स्लाइड। |

--------------------

1) PptxEditException को फेंकने से बचने के लिए लेआउट की HasDependingSlides प्रॉपर्टी को पहले जांचें। 2) आप कोड को सरल बनाने के लिए [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) विधि का भी उपयोग कर सकते हैं। |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

अप्रयुक्त लेआउट स्लाइड्स को हटाता है (जिन लेआउट स्लाइड्स की HasDependingSlides झूठी है)।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

संग्रह को इटररेट करने वाला एन्यूमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - एक IGenericEnumerator जिसका उपयोग संग्रह को इटररेट करने के लिए किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - एक java.util.Iterator पूरे संग्रह के लिए।
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

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सेफ) है या नहीं। केवल-पढ़ने-योग्य boolean.

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालिक रूट लौटाता है। केवल-पढ़ने-योग्य Object.

**रिटर्न:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य IDOMObject.

**रिटर्न:**
com.aspose.slides.IDOMObject