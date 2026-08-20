---
title: VbaReferenceCollection
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: VBA प्रोजेक्ट रेफ़रेंस का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/vbareferencecollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
```
public class VbaReferenceCollection implements IVbaReferenceCollection
```

VBA प्रोजेक्ट रेफ़रेंसेज़ का संग्रह दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में शामिल तत्वों की संख्या प्राप्त करता है। |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | नया रेफ़रेंस रेफ़रेंसेज़ संग्रह में जोड़ता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरिट करने वाला एन्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रोनाइज़ेशन रूट लौटाता है। |
### size() {#size--}
```
public final int size()
```


संग्रह में वास्तव में शामिल तत्वों की संख्या प्राप्त करता है। पढ़ने-के-लिए-केवल int.

**रिटर्न:**
int
### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```


नया रेफ़रेंस रेफ़रेंसेज़ संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```


निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IVbaReference](../../com.aspose.slides/ivbareference)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```


संग्रह के माध्यम से इटरिट करने वाला एन्यूमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```


पूरे संग्रह के लिए एक जावा इटरटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। पढ़ने-के-लिए-केवल boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक सिंक्रोनाइज़ेशन रूट लौटाता है। पढ़ने-के-लिए-केवल Object।

**रिटर्न:**
java.lang.Object