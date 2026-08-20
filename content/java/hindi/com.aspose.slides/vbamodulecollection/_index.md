---
title: VbaModuleCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: VBA प्रोजेक्ट मॉड्यूल्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/vbamodulecollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

VBA प्रोजेक्ट मॉड्यूल्स का एक संग्रह दर्शाता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | संग्रह से किसी विशिष्ट ऑब्जेक्ट की पहली उपस्थिति को हटाता है। |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA प्रोजेक्ट में एक नया खाली मॉड्यूल जोड़ता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [iterator()](#iterator--) | संग्रह पर इटरिट करने वाला एनेमरिटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्वों को निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समन्वित (थ्रेड-सेफ) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रोनाइज़ेशन रूट लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**वापसी:**
int

### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

संग्रह से किसी विशिष्ट ऑब्जेक्ट की पहली उपस्थिति को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | संग्रह से हटाए जाने वाला मॉड्यूल। |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

VBA प्रोजेक्ट में एक नया खाली मॉड्यूल जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | मॉड्यूल का नाम |

**वापसी:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - जोड़ा गया मॉड्यूल।

### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IVbaModule](../../com.aspose.slides/ivbamodule)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

संग्रह पर इटरिट करने वाला एनेमरिटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - एक IGenericEnumerator जो संग्रह में इटरिट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - पूरा संग्रह के लिए एक java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्वों को निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | लक्ष्य ऐरे में प्रारम्भिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समन्वित (थ्रेड-सेफ) है या नहीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रोनाइज़ेशन रूट लौटाता है। केवल-पढ़ने योग्य Object.

**वापसी:**
java.lang.Object