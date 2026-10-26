---
title: VbaReferenceCollection
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: VBA प्रोजेक्ट संदर्भों का एक संग्रह दर्शाता है।
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

VBA प्रोजेक्ट संदर्भों का एक संग्रह दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | नए संदर्भ को रेफरेंसेज़ संग्रह में जोड़ता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो संग्रह में इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो संकेत देता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रोनाइज़ेशन रूट लौटाता है। |

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। Read-only int.

**रिटर्न मान:**  
int

### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```

नए संदर्भ को रेफरेंसेज़ संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न मान:**  
[IVbaReference](../../com.aspose.slides/ivbareference)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```

एक एनेमरेटर लौटाता है जो संग्रह में इटररेट करता है।

**रिटर्न मान:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - एक IGenericEnumerator जिसे संग्रह के माध्यम से इटररेट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```

पूरे संग्रह के लिए एक java इटरेटर लौटाता है।

**रिटर्न मान:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - एक java.util.Iterator पूरी संग्रह के लिए।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित एरे। |
| index | int | लक्षित एरे में प्रारंभिक अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो संकेत देता है कि संग्रह तक पहुंच समकालिक (थ्रेड-सुरक्षित) है या नहीं। Read-only boolean.

**रिटर्न मान:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रोनाइज़ेशन रूट लौटाता है। Read-only Object.

**रिटर्न मान:**  
java.lang.Object