---
title: ControlPropertiesCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: AcitveX प्रॉपर्टीज़ का संग्रह।
type: docs
url: /hi/com.aspose.slides/controlpropertiescollection/
---
**विरासत:**
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

AcitveX प्रॉपर्टीज़ का संग्रह।
## विधियां

| विधि | विवरण |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | कलेक्शन में एक प्रॉपर्टी जोड़ता है। |
| [remove(String name)](#remove-java.lang.String-) | निर्दिष्ट नाम वाली प्रॉपर्टी को हटाता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | प्रॉपर्टी को प्राप्त करता है या सेट करता है। |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | प्रॉपर्टी को प्राप्त करता है या सेट करता है। |
| [getNamesOfProperties()](#getNamesOfProperties--) | प्रॉपर्टीज़ के नामों का संग्रह लौटाता है। |
| [clear()](#clear--) | सभी प्रॉपर्टीज़ को हटाता है। |
| [getCount()](#getCount--) | कलेक्शन में प्रॉपर्टीज़ की संख्या लौटाता है। |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटरेट करने वाला एन्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिए एक जावा इटरेटर लौटाता है। |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```


कलेक्शन में एक प्रॉपर्टी जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी का नाम। |
| value | java.lang.String | प्रॉपर्टी का मान। |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


निर्दिष्ट नाम वाली प्रॉपर्टी को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाने के लिए प्रॉपर्टी का नाम। |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


प्रॉपर्टी को प्राप्त करता है या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी का नाम। |

**वापसी:**
java.lang.String - प्रॉपर्टी।

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


प्रॉपर्टी को प्राप्त करता है या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी का नाम। |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


प्रॉपर्टीज़ के नामों का संग्रह लौटाता है। Read-only [IGenericCollection](../../com.aspose.slides/igenericcollection).

**वापसी:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```


सभी प्रॉपर्टीज़ को हटाता है।

### getCount() {#getCount--}
```
public final int getCount()
```


कलेक्शन में प्रॉपर्टीज़ की संख्या लौटाता है। Read-only int.

**वापसी:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


कलेक्शन के माध्यम से इटरेट करने वाला एन्यूमरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


पूरे कलेक्शन के लिए एक जावा इटरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.