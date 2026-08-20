---
title: LineFormatCollection
second_title: Aspose.Slides for Java API संदर्भ
description: लाइन शैलियों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/lineformatcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)
```
public final class LineFormatCollection extends DomObject<FormatScheme> implements ILineFormatCollection
```

लाइन शैलियों का संग्रह दर्शाता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर मौजूद तत्व प्राप्त करता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेट करने वाला एनेुमारेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटररेटर लौटाता है। |
| [size()](#size--) | संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सेफ) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | सिंक्रीकरण रूट लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public final ILineFormat get_Item(int index)
```

निर्दिष्ट इंडेक्स पर मौजूद तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला एनेुमारेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iteratorJava()
```

पूरे संग्रह के लिए जावा इटररेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - पूरे संग्रह के लिए java.util.Iterator।
### size() {#size--}
```
public final int size()
```

संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्व निर्दिष्ट ऐरे में कॉपी करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सेफ) है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

सिंक्रीकरण रूट लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object