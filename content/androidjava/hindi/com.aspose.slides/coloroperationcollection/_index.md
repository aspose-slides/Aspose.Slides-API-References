---
title: ColorOperationCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: रंग रूपांतरण संचालन के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/coloroperationcollection/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

रंग रूपांतरण कार्यों के संग्रह का प्रतिनिधित्व करता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | कलेक्शन में संचालन की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट क्रमांक पर संचालन को लौटाता है या सेट करता है। |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | निर्दिष्ट क्रमांक पर संचालन को लौटाता है या सेट करता है। |
| [add(int operation, float parameter)](#add-int-float-) | कलेक्शन के अंत में एक नया संचालन जोड़ता है। |
| [add(int operation)](#add-int-) | कलेक्शन के अंत में एक नया संचालन जोड़ता है। |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | नया संचालन कलेक्शन में सम्मिलित करता है। |
| [insert(int position, int operation)](#insert-int-int-) | नया संचालन कलेक्शन में सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | कलेक्शन से रंग संचालन को हटाता है। |
| [clear()](#clear--) | सभी रंग संचालन को हटाता है। |
| [iterator()](#iterator--) | कलेक्शन के भीतर क्रमशः चलने वाले एक इटेरेटर को लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिये एक Java इटेरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | कलेक्शन के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाने वाला मान लौटाता है कि कलेक्शन तक पहुँच समन्वित (थ्रेड-सेफ) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समन्वयन मूल (synchronization root) लौटाता है। |
| [deepClone()](#deepClone--) | एक ColorOperationCollection का कॉपी बनाता है। |
| [cloneT()](#cloneT--) | वर्तमान वस्तु की क्लोन बनाता है |

### size() {#size--}
```
public final int size()
```

कलेक्शन में संचालन की संख्या लौटाता है। केवल पढ़ने योग्य int.

**रिटर्न:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

निर्दिष्ट क्रमांक पर संचालन को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [ColorOperation](../../com.aspose.slides/coloroperation).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

निर्दिष्ट क्रमांक पर संचालन को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [ColorOperation](../../com.aspose.slides/coloroperation).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

कलेक्शन के अंत में एक नया संचालन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operation | int | संचालन प्रकार। |
| parameter | float | संचालन का पैरामीटर। |

**रिटर्न:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - जोड़ा गया संचालन।

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

कलेक्शन के अंत में एक नया संचालन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operation | int | संचालन प्रकार। |

**रिटर्न:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - जोड़ा गया संचालन।

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

कलेक्शन में नया संचालन सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | int | वह क्रमांक जहाँ संचालन सम्मिलित किया जाएगा। |
| operation | int | संचालन प्रकार। |
| parameter | float | संचालन का पैरामीटर। |

**रिटर्न:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - सम्मिलित किया गया संचालन।

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

कलेक्शन में नया संचालन सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | int | वह क्रमांक जहाँ संचालन सम्मिलित किया जाएगा। |
| operation | int | संचालन प्रकार। |

**रिटर्न:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - सम्मिलित किया गया संचालन।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

कलेक्शन से रंग संचालन को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिये रंग संचालन का क्रमांक। |

### clear() {#clear--}
```
public final void clear()
```

सभी रंग संचालन को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

कलेक्शन के भीतर क्रमशः चलने वाले एक इटेरेटर को लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - एक IGenericEnumerator जो कलेक्शन के माध्यम से इटरेट करने के लिये उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

पूरे कलेक्शन के लिये एक Java इटेरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - पूरे कलेक्शन के लिये एक java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

कलेक्शन के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारम्भिक क्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

कलेक्शन तक पहुँच समन्वित (थ्रेड-सेफ) है या नहीं, यह दर्शाने वाला मान लौटाता है। केवल पढ़ने योग्य boolean।

**रिटर्न:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समन्वयन मूल (synchronization root) लौटाता है। केवल पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

एक ColorOperationCollection का कॉपी बनाता है।

**रिटर्न:**
java.lang.Object - नया [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) कलेक्शन।

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

वर्तमान वस्तु की क्लोन बनाता है।

**रिटर्न:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - क्लोन