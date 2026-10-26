---
title: RowCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: टेबल पंक्ति संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/rowcollection/
---
**Inheritance:**  
विरासत:

java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
सभी लागू इंटरफेस:

[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

टेबल पंक्ति संग्रह का प्रतिनिधित्व करता है।
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | संकलन में वास्तव में शामिल पंक्तियों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर पंक्ति लौटाता है। |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका के नीचे सम्मिलित करता है। |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | तालिका से निर्दिष्ट स्थान पर पंक्ति हटाता है। |
| [iterator()](#iterator--) | संकलन के माध्यम से आवृत्ति करने वाला एक एन्यूमीटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संकलन के लिए एक जावा इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संकलन से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संकलन तक पहुँच समकालिक (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक मूल लौटाता है। |
### size() {#size--}
```
public final int size()
```


संकलन में वास्तव में शामिल पंक्तियों की संख्या प्राप्त करता है। केवल-पढ़ने-योग्य int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


निर्दिष्ट अनुक्रमांक पर पंक्ति लौटाता है। केवल-पढ़ने-योग्य [Row](../../com.aspose.slides/row).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका के नीचे सम्मिलित करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | टेम्पलेट के रूप में उपयोग की जाने वाली पंक्ति। |
| withAttachedRows | boolean | टेम्पलेट पंक्ति से जुड़े सभी पंक्तियों को भी कॉपी करने के लिए true। |

**Returns:**
com.aspose.slides.IRow[] - जोड़ी गई पंक्तियाँ।
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | नई पंक्ति का अनुक्रमांक। |
| templ | [IRow](../../com.aspose.slides/irow) | टेम्पलेट के रूप में उपयोग की जाने वाली पंक्ति। |
| withAttachedRows | boolean | टेम्पलेट पंक्ति से जुड़े सभी पंक्तियों को भी कॉपी करने के लिए true। |

**Returns:**
com.aspose.slides.IRow[] - सम्मिलित पंक्तियाँ।
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


तालिका से निर्दिष्ट स्थान पर पंक्ति हटाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | हटाने वाली पंक्ति का अनुक्रमांक। |
| withAttachedRows | boolean | जुड़े सभी पंक्तियों को भी हटाने के लिए true। |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


संकलन के माध्यम से आवृत्ति करने वाला एक एन्यूमीटर लौटाता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - एक IGenericEnumerator जो संकलन के माध्यम से आवृत्ति करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


पूरे संकलन के लिए एक जावा इटरेटर लौटाता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - एक java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


संकलन से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि संकलन तक पहुँच समकालिक (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने-योग्य boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक समकालिक मूल लौटाता है। केवल-पढ़ने-योग्य Object.

**Returns:**
java.lang.Object