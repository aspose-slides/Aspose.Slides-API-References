---
title: TagCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: टैग्स के संग्रह का प्रतिनिधित्व करता है जो उपयोगकर्ता द्वारा परिभाषित स्ट्रिंग की जोड़ी हैं
type: docs
url: /hi/com.aspose.slides/tagcollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

टैग्स (उपयोगकर्ता द्वारा परिभाषित स्ट्रिंग की जोड़ी) का संग्रह दर्शाता है

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में टैग्स की संख्या लौटाता है। |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | संग्रह में नया टैग जोड़ता है। |
| [remove(String name)](#remove-java.lang.String-) | संग्रह से निर्दिष्ट नाम वाले टैग को हटाता है। |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | संग्रह में निर्दिष्ट कुंजी का शून्य-आधारित सूचकांक लौटाता है। |
| [contains(String name)](#contains-java.lang.String-) | निर्धारित करता है कि संग्रह में कोई विशिष्ट नाम है या नहीं। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर टैग को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी टैग हटाता है। |
| [getValueByIndex(int index)](#getValueByIndex-int-) | निर्दिष्ट सूचकांक पर टैग का मान लौटाता है। |
| [getNameByIndex(int index)](#getNameByIndex-int-) | निर्दिष्ट सूचकांक पर टैग की कुंजी लौटाता है। |
| [getNamesOfTags()](#getNamesOfTags--) | टैग्स के नाम लौटाता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | टैग की कुंजी और मान जोड़ी को लौटाता या सेट करता है। |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | टैग की कुंजी और मान जोड़ी को लौटाता या सेट करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | संग्रह तक पहुँच के समन्वित (थ्रेड-सेफ) होने का संकेत देने वाला मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | समन्वयन मूल (सिंक्रोनाइज़ेशन रूट) लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटररेट करने वाला एनेमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |
### size() {#size--}
```
public final int size()
```

संग्रह में टैग्स की संख्या लौटाता है। केवल-पढ़ने-योग्य int।

**रिटर्न:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

संग्रह में नया टैग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | टैग का नाम। |
| value | java.lang.String | टैग का मान। |

**रिटर्न:**
int - जोड़े गए टैग का सूचकांक।
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

निर्दिष्ट नाम वाले टैग को संग्रह से हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाए जाने वाले टैग का नाम। |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

संग्रह में निर्दिष्ट कुंजी का शून्य-आधारित सूचकांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | संग्रह में खोजने के लिए नाम। |

**रिटर्न:**
int - कुंजी का शून्य-आधारित सूचकांक, यदि कुंजी मिलती है; अन्यथा -1।
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

निर्धारित करता है कि संग्रह में कोई विशिष्ट नाम है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | खोजने की कुंजी। |

**रिटर्न:**
boolean - यदि संग्रह में निर्दिष्ट कुंजी वाला टैग है तो True; अन्यथा false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट सूचकांक पर टैग को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले टैग का शून्य-आधारित सूचकांक। |
### clear() {#clear--}
```
public final void clear()
```

सभी टैग्स को संग्रह से हटाता है।
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

निर्दिष्ट सूचकांक पर टैग का मान लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लौटाने के लिए टैग का सूचकांक। |

**रिटर्न:**
java.lang.String - टैग का मान।
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

निर्दिष्ट सूचकांक पर टैग की कुंजी लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लौटाने के लिए टैग का सूचकांक। |

**रिटर्न:**
java.lang.String - टैग की कुंजी।
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

टैग्स के नाम लौटाता है।

**रिटर्न:**
java.lang.String[] - टैग्स के नाम।
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

टैग की कुंजी और मान जोड़ी को लौटाता या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | टैग की कुंजी। |

**रिटर्न:**
java.lang.String - टैग का मान।
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

टैग की कुंजी और मान जोड़ी को लौटाता या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | टैग की कुंजी। |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | भरण के लिए एरे। |
| index | int | लक्ष्य एरे में प्रारम्भिक स्थिति। |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

संग्रह तक पहुँच के समन्वित (थ्रेड-सेफ) होने का संकेत देने वाला मान लौटाता है। केवल-पढ़ने-योग्य boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समन्वयन मूल (सिंक्रोनाइज़ेशन रूट) लौटाता है। केवल-पढ़ने-योग्य Object।

**रिटर्न:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

संग्रह के माध्यम से इटररेट करने वाला एनेमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.