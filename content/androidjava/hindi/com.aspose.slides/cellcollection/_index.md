---
title: CellCollection
second_title: Aspose.Slides Android के लिए, Java API संदर्भ के माध्यम से
description: सेलों के एक संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/cellcollection/
---
**विरासत:**
java.lang.Object

**सब सभी लागू इंटरफ़ेसेस:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

सेलों के संग्रह का प्रतिनिधित्व करता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | कलेक्शन में कोशिकाओं की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | स्थिति के आधार पर एक कोशिका लौटाता है। |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से पुनरावृत्ति करने वाला एनेमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिए जावा इटररेटर लौटाता है। |
| [getSlide()](#getSlide--) | CellCollection की माता स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | CellCollection की माता प्रस्तुति लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | कलेक्शन से सभी तत्वों को निर्दिष्ट array में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि कलेक्शन तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रोनाइज़ेशन रूट लौटाता है। |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```


कलेक्शन में कोशिकाओं की संख्या लौटाता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```


स्थिति के आधार पर एक कोशिका लौटाता है। केवल पढ़ने योग्य [Cell](../../com.aspose.slides/cell)।

--------------------

यदि कोशिका मर्ज की गई हो तो एक Cell ऑब्जेक्ट कई इंडेक्स के लिए लौटाया जा सकता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```


कलेक्शन के माध्यम से पुनरावृत्ति करने वाला एनेमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - एक IGenericEnumerator जो कलेक्शन के माध्यम से पुनरावृत्ति करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```


पूरे कलेक्शन के लिए जावा इटररेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - पूरे कलेक्शन के लिए एक java.util.Iterator।
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


CellCollection की माता स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**रिटर्न:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


CellCollection की माता प्रस्तुति लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


कलेक्शन से सभी तत्वों को निर्दिष्ट array में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य array। |
| index | int | लक्ष्य array में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि कलेक्शन तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं। केवल पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक सिंक्रोनाइज़ेशन रूट लौटाता है। केवल पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object