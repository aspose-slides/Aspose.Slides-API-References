---
title: ColumnCollection
second_title: Aspose.Slides के लिए Android, Java API रेफ़रेंस
description: एक तालिका में कॉलम के संग्रह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/columncollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

एक तालिका में कॉलम का संग्रह दर्शाता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | एक संग्रह में कॉलमों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर कॉलम लौटाता है। |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और तालिका के नीचे सम्मिलित करता है। |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | निर्दिष्ट टेम्पलेट कॉलम की एक प्रति बनाता है और तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | तालिका से निर्दिष्ट स्थिति पर कॉलम हटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेट करने वाला एनेमरेटर वापस करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटररेटर वापस करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समक्रमण मूल लौटाता है। |

### size() {#size--}
```
public final int size()
```

एक संग्रह में कॉलमों की संख्या लौटाता है। केवल-पढ़ने-योग्य int.

**रिटर्न:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

निर्दिष्ट सूचकांक पर कॉलम लौटाता है। केवल-पढ़ने-योग्य [Column](../../com.aspose.slides/column)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IColumn](../../com.aspose.slides/icolumn)

### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और तालिका के नीचे सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | टेम्पलेट के रूप में उपयोग किया जाने वाला कॉलम। |
| withAttachedColumns | boolean | टेम्पलेट पंक्ति से जुड़े सभी कॉलम भी कॉपी करने के लिए true। |

**रिटर्न:**
com.aspose.slides.IColumn[] - जोड़े गए कॉलम।

### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

निर्दिष्ट टेम्पलेट कॉलम की एक प्रति बनाता है और तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नया कॉलम का सूचकांक। |
| templ | [IColumn](../../com.aspose.slides/icolumn) | टेम्पलेट के रूप में उपयोग किया जाने वाला कॉलम। |
| withAttachedColumns | boolean | टेम्पलेट कॉलम से जुड़े सभी कॉलम भी कॉपी करने के लिए true। |

**रिटर्न:**
com.aspose.slides.IColumn[] - डाली गई कॉलम।

### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

तालिका से निर्दिष्ट स्थिति पर कॉलम हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstColumnIndex | int | हटाने के लिए कॉलम का सूचकांक। |
| withAttachedRows | boolean | सभी जुड़े कॉलम भी हटाने के लिए true। |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला एनेमरेटर वापस करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

पूरा संग्रह के लिए जावा इटररेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - पूरे संग्रह के लिए एक java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने-योग्य boolean।

**रिटर्न:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समक्रमण मूल लौटाता है। केवल-पढ़ने-योग्य Object।

**रिटर्न:**
java.lang.Object