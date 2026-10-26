---
title: ControlPropertiesCollection
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: AcitveX गुणों का एक संग्रह।
type: docs
url: /hi/com.aspose.slides/controlpropertiescollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

ActiveX गुणों का संग्रह।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | संग्रह में एक गुण जोड़ता है। |
| [remove(String name)](#remove-java.lang.String-) | निर्दिष्ट नाम के साथ गुण को हटाता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | गुण को प्राप्त करता या सेट करता है। |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | गुण को प्राप्त करता या सेट करता है। |
| [getNamesOfProperties()](#getNamesOfProperties--) | गुणों के नामों का संग्रह लौटाता है। |
| [clear()](#clear--) | सभी गुणों को हटाता है। |
| [getCount()](#getCount--) | संग्रह में गुणों की संख्या लौटाता है। |
| [iterator()](#iterator--) | एक एन्न्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटरैट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java iterator लौटाता है। |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

संग्रह में एक गुण जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | गुण का नाम। |
| value | java.lang.String | गुण का मान। |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

निर्दिष्ट नाम के साथ गुण को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाने के लिए गुण का नाम। |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

गुण को प्राप्त करता या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | गुण का नाम। |

**रिटर्न:**
java.lang.String - गुण।

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

गुण को प्राप्त करता या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | गुण का नाम। |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

गुणों के नामों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IGenericCollection](../../com.aspose.slides/igenericcollection)।

**रिटर्न:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

सभी गुणों को हटाता है।

### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में गुणों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

एक एन्न्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटरैट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरैट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

पूरे संग्रह के लिए एक java iterator लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - पूरे संग्रह के लिए एक java.util.Iterator।