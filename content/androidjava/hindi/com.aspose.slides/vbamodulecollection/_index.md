---
title: VbaModuleCollection
second_title: Aspose.Slides Android के लिये Java API संदर्भ
description: VBA प्रोजेक्ट मॉड्यूल्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/vbamodulecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Represents a collection of a VBA Project modules.
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | कलेक्शन में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | कलेक्शन से विशिष्ट ऑब्जेक्ट की पहली उपस्थिति को हटाता है। |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA प्रोजेक्ट में एक नया खाली मॉड्यूल जोड़ता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से पुनरावृत्ति करने वाला एनेमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | संपूर्ण कलेक्शन के लिए एक java इटरेटोर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | कलेक्शन के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाने वाला मान लौटाता है कि कलेक्शन तक पहुँच समकालीन (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक मूल लौटाता है। |
### size() {#size--}
```
public final int size()
```

कलेक्शन में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। Read-only int.

**रिटर्न:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

कलेक्शन से विशिष्ट ऑब्जेक्ट की पहली उपस्थिति को हटाता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | कलेक्शन से हटाने के लिये मॉड्यूल। |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

VBA प्रोजेक्ट में एक नया खाली मॉड्यूल जोड़ता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | मॉड्यूल का नाम |

**रिटर्न:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - जोड़ा गया मॉड्यूल।
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

कलेक्शन के माध्यम से पुनरावृत्ति करने वाला एनेमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - कलेक्शन के माध्यम से पुनरावृत्ति करने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

संपूर्ण कलेक्शन के लिये एक java इटरेटोर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - पूरे कलेक्शन के लिये java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

कलेक्शन के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो यह दर्शाता है कि कलेक्शन तक पहुँच समकालीन (थ्रेड-सुरक्षित) है या नहीं। Read-only boolean.

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालिक मूल लौटाता है। Read-only Object.

**रिटर्न:**
java.lang.Object