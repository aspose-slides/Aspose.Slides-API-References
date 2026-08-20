---
title: CellCollection
second_title: Java API संदर्भ के लिए Aspose.Slides
description: सेलों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/cellcollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

सेलों का संग्रह दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | क्लेक्शन में कोशिकाओं की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | स्थिति द्वारा एक सेल लौटाता है। |
| [iterator()](#iterator--) | क्लेक्शन के माध्यम से इटरेट करने वाला एन्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे क्लेक्शन के लिए जावा इटरटर लौटाता है। |
| [getSlide()](#getSlide--) | CellCollection का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | CellCollection का पैरेंट प्रेजेंटेशन लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | क्लेक्शन से सभी तत्व निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि क्लेक्शन तक पहुंच समकालिक (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | सिंक्रोनाइज़ेशन रूट लौटाता है। |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate वस्तु लौटाता है। केवल पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

क्लेक्शन में कोशिकाओं की संख्या लौटाता है। केवल पढ़ने योग्य int।

**वापसी:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

स्थिति द्वारा एक सेल लौटाता है। केवल पढ़ने योग्य [Cell](../../com.aspose.slides/cell)।

--------------------

एक Cell वस्तु कई इंडेक्स के लिए लौटाई जा सकती है यदि सेल मर्ज किया गया हो।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

क्लेक्शन के माध्यम से इटरेट करने वाला एन्यूमरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

पूरे क्लेक्शन के लिए जावा इटरटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - An java.util.Iterator for the entire collection.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

CellCollection का पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

CellCollection का पैरेंट प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

क्लेक्शन से सभी तत्व निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

क्लेक्शन तक पहुंच समकालिक (थ्रेड-सुरक्षित) है या नहीं यह दर्शाने वाला मान लौटाता है। केवल पढ़ने योग्य boolean।

**वापसी:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

सिंक्रोनाइज़ेशन रूट लौटाता है। केवल पढ़ने योग्य Object।

**वापसी:**
java.lang.Object