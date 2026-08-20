---
title: FillFormatCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: भरण शैलियों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/fillformatcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)
```
public final class FillFormatCollection extends DomObject<FormatScheme> implements IFillFormatCollection
```

भरण शैलियों का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटररेट करने वाला एनेमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है। |
| [size()](#size--) | संग्रह में वास्तव में सम्मिलित तत्वों की संख्या प्राप्त करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट सरणी में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक जड़ (सिंक रूट) लौटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final IFillFormat get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iterator()
```

संग्रह के माध्यम से इटररेट करने वाला एनेमरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - एक IGenericEnumerator जिसका उपयोग संग्रह के माध्यम से इटररेट करने के लिए किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - एक java.util.Iterator जो पूरे संग्रह के लिए है।

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में सम्मिलित तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**वापसी:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्व निर्दिष्ट सरणी में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य सरणी। |
| index | int | लक्ष्य सरणी में प्रारंभिक अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सुरक्षित) है या नहीं। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालिक जड़ (सिंक रूट) लौटाता है। केवल-पढ़ने योग्य Object।

**वापसी:**
java.lang.Object