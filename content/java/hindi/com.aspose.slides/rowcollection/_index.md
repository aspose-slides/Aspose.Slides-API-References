---
title: RowCollection
second_title: Aspose.Slides जावा API संदर्भ
description: टेबल पंक्ति संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/rowcollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

टेबल पंक्ति संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तविक रूप से सम्मिलित पंक्तियों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर पंक्ति लौटाता है। |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | निर्दिष्ट टेम्पलेट पंक्ति की प्रति बनाता है और इसे तालिका के नीचे सम्मिलित करता है। |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | निर्दिष्ट टेम्पलेट पंक्ति की प्रति बनाता है और इसे तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | तालिका से निर्दिष्ट स्थान पर पंक्ति को हटाता है। |
| [iterator()](#iterator--) | एक एनोमेरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृत्ति करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समकालिक (थ्रेड-सेफ) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक रूट (सिंक्रोनाइज़ेशन रूट) लौटाता है। |
### size() {#size--}
```
public final int size()
```


संग्रह में वास्तविक रूप से सम्मिलित पंक्तियों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


निर्दिष्ट सूचकांक पर पंक्ति लौटाता है। केवल-पढ़ने योग्य [Row](../../com.aspose.slides/row).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


निर्दिष्ट टेम्पलेट पंक्ति की प्रति बनाता है और इसे तालिका के नीचे सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | टेम्पलेट के रूप में उपयोग की जाने वाली पंक्ति। |
| withAttachedRows | boolean | True to copy also all rows attached to the template row. |

**वापसी:**
com.aspose.slides.IRow[] - Added rows.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


निर्दिष्ट टेम्पलेट पंक्ति की प्रति बनाता है और इसे तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | नई पंक्ति का अनुक्रमणांक। |
| templ | [IRow](../../com.aspose.slides/irow) | टेम्पलेट के रूप में उपयोग की जाने वाली पंक्ति। |
| withAttachedRows | boolean | True to copy also all rows attached to the template row. |

**वापसी:**
com.aspose.slides.IRow[] - Inserted rows.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


तालिका से निर्दिष्ट स्थान पर पंक्ति को हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| firstRowIndex | int | हटाने के लिए पंक्ति का अनुक्रमणांक। |
| withAttachedRows | boolean | True to delete also all attached rows. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


एक एनोमेरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृत्ति करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


संग्रह से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित एरे। |
| index | int | लक्षित एरे में प्रारंभिक अनुक्रमणांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समकालिक (थ्रेड-सेफ) है या नहीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक समकालिक रूट लौटाता है। केवल-पढ़ने योग्य Object.

**वापसी:**
java.lang.Object