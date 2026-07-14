---
title: IColorOperationCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: रंग रूपांतरण ऑपरेशनों का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icoloroperationcollection/
---
**सभी लागू इंटरफ़ेस:**  
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

रंग रूपांतरण कार्यों के संग्रह का प्रतिनिधित्व करता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर ऑपरेशन को लौटाता या सेट करता है। |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | निर्दिष्ट इंडेक्स पर ऑपरेशन को लौटाता या सेट करता है। |
| [add(int operation, float parameter)](#add-int-float-) | संग्रह के अंत में नया ऑपरेशन जोड़ता है। |
| [add(int operation)](#add-int-) | संग्रह के अंत में नया ऑपरेशन जोड़ता है। |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | संग्रह में नया ऑपरेशन सम्मिलित करता है। |
| [insert(int position, int operation)](#insert-int-int-) | संग्रह में नया ऑपरेशन सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह से रंग ऑपरेशन हटाता है। |
| [clear()](#clear--) | सभी रंग ऑपरेशनों को हटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

निर्दिष्ट इंडेक्स पर ऑपरेशन को लौटाता या सेट करता है। पढ़ें/लिखें [IColorOperation](../../com.aspose.slides/icoloroperation)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

निर्दिष्ट इंडेक्स पर ऑपरेशन को लौटाता या सेट करता है। पढ़ें/लिखें [IColorOperation](../../com.aspose.slides/icoloroperation)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

संग्रह के अंत में नया ऑपरेशन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operation | int | ऑपरेशन प्रकार। |
| parameter | float | ऑपरेशन का पैरामीटर। |

**वापसी:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - जोड़ा गया ऑपरेशन।

### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

संग्रह के अंत में नया ऑपरेशन जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operation | int | ऑपरेशन प्रकार। |

**वापसी:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - जोड़ा गया ऑपरेशन।

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

संग्रह में नया ऑपरेशन सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | int | वह इंडेक्स जहाँ ऑपरेशन सम्मिलित किया जाएगा। |
| operation | int | ऑपरेशन प्रकार। |
| parameter | float | ऑपरेशन का पैरामीटर। |

**वापसी:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - सम्मिलित किया गया ऑपरेशन।

### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

संग्रह में नया ऑपरेशन सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | int | वह इंडेक्स जहाँ ऑपरेशन सम्मिलित किया जाएगा। |
| operation | int | ऑपरेशन प्रकार। |

**वापसी:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - सम्मिलित किया गया ऑपरेशन।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह से रंग ऑपरेशन हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले रंग ऑपरेशन का इंडेक्स। |

### clear() {#clear--}
```
public abstract void clear()
```

सभी रंग ऑपरेशनों को हटाता है।