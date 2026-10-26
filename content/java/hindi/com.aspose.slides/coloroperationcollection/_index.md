---
title: ColorOperationCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: रंग परिवर्तन ऑपरेशनों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/coloroperationcollection/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)  
```
public final class ColorOperationCollection implements IColorOperationCollection
```

रंग परिवर्तन ऑपरेशनों का एक संग्रह दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | क्लेक्शन में ऑपरेशनों की संख्या को लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर ऑपरेशन को लौटाता है या सेट करता है। |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | निर्दिष्ट सूचकांक पर ऑपरेशन को लौटाता है या सेट करता है। |
| [add(int operation, float parameter)](#add-int-float-) | क्लेक्शन के अंत में एक नया ऑपरेशन जोड़ता है। |
| [add(int operation)](#add-int-) | क्लेक्शन के अंत में एक नया ऑपरेशन जोड़ता है। |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | क्लेक्शन में नया ऑपरेशन सम्मिलित करता है। |
| [insert(int position, int operation)](#insert-int-int-) | क्लेक्शन में नया ऑपरेशन सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | क्लेक्शन से रंग ऑपरेशन को हटाता है। |
| [clear()](#clear--) | सभी रंग ऑपरेशनों को हटाता है। |
| [iterator()](#iterator--) | क्लेक्शन के माध्यम से इटरेट करने वाला एनेमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे क्लेक्शन के लिए जावा इटेरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | क्लेक्शन से सभी तत्व निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | क्लेक्शन तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं, यह संकेत देने वाला मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | सिंक्रनाइज़ेशन रूट लौटाता है। |
| [deepClone()](#deepClone--) | एक ColorOperationCollection क्लेक्शन की कॉपी बनाता है। |
| [cloneT()](#cloneT--) | वर्तमान ऑब्जेक्ट को क्लोन करता है। |

### size() {#size--}
```
public final int size()
```

क्लेक्शन में ऑपरेशनों की संख्या को लौटाता है। Read-only int.

**वापसी:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

निर्दिष्ट सूचकांक पर ऑपरेशन को लौटाता है या सेट करता है। Read/write [ColorOperation](../../com.aspose.slides/coloroperation).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**  
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

निर्दिष्ट सूचकांक पर ऑपरेशन को लौटाता है या सेट करता है। Read/write [ColorOperation](../../com.aspose.slides/coloroperation).

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

क्लेक्शन के अंत में एक नया ऑपरेशन जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operation | int | ऑपरेशन प्रकार। |
| parameter | float | ऑपरेशन का पैरामीटर। |

**वापसी:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - जोड़ी गई ऑपरेशन।

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

क्लेक्शन के अंत में एक नया ऑपरेशन जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operation | int | ऑपरेशन प्रकार। |

**वापसी:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - जोड़ी गई ऑपरेशन।

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

क्लेक्शन में नया ऑपरेशन सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | int | वह सूचकांक जहाँ ऑपरेशन सम्मिलित किया जाएगा। |
| operation | int | ऑपरेशन प्रकार। |
| parameter | float | ऑपरेशन का पैरामीटर। |

**वापसी:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - सम्मिलित ऑपरेशन।

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

क्लेक्शन में νέο ऑपरेशन सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | int | वह सूचकांक जहाँ ऑपरेशन सम्मिलित किया जाएगा। |
| operation | int | ऑपरेशन प्रकार। |

**वापसी:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - सम्मिलित ऑपरेशन।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

क्लेक्शन से रंग ऑपरेशन को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए रंग ऑपरेशन का सूचकांक। |

### clear() {#clear--}
```
public final void clear()
```

सभी रंग ऑपरेशनों को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

क्लेक्शन के माध्यम से इटरेट करने वाला एनेमरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - ए नेमरेटर जिसे संग्रह को इटरिट करने के लिये प्रयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

पूरे क्लेक्शन के लिए जावा इटेरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - पूरे क्लेक्शन के लिये java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

क्लेक्शन से सभी तत्व निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

क्लेक्शन तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं, यह संकेत देने वाला मान लौटाता है। Read-only boolean.

**वापसी:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

सिंक्‍क्रोनाइज़ेशन रूट लौटाता है। Read-only Object.

**वापसी:**  
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

एक ColorOperationCollection क्लेक्शन की कॉपी बनाता है।

**वापसी:**  
java.lang.Object - नई [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) संग्रह।

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

वर्तमान ऑब्जेक्ट को क्लोन करता है।

**वापसी:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - क्लोन