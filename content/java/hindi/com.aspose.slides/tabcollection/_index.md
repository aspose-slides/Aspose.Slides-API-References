---
title: TabCollection
second_title: Aspose.Slides for Java API संदर्भ
description: टैब्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/tabcollection/
---
**विरासत:**
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

टैब्स का एक संग्रह प्रस्तुत करता है।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [add(double position, int align)](#add-double-int-) | संग्रह में एक टैब जोड़ता है। |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | संग्रह में एक टैब जोड़ता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो TabsEx उदाहरण समान हैं या नहीं। |
| [iterator()](#iterator--) | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समक्रमण रूट लौटाता है। |
### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [Tab](../../com.aspose.slides/tab).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

एक टैब जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**रिटर्न:**
[ITab](../../com.aspose.slides/itab) - जोड़ा गया टैब।
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

एक टैब जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | संग्रह के अंत में जोड़े जाने वाला Tab ऑब्जेक्ट। |

**रिटर्न:**
int - टैब जिस सूचकांक पर जोड़ा गया था।
### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी तत्वों को हटाता है।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित सूचकांक। |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि दो TabsEx उदाहरण समान हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | वर्तमान TabsEx के साथ तुलना करने के लिए TabsEx। |

**रिटर्न:**
boolean - **true** यदि निर्दिष्ट TabsEx वर्तमान TabsEx के बराबर है; अन्यथा, **false**।
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - एक IGenericEnumerator जिसका उपयोग संग्रह के माध्यम से इटररेट करने के लिए किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - पूरे संग्रह के लिए एक java.util.Iterator।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | लक्ष्य ऐरे में प्रारम्भिक सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समक्रमण रूट लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object