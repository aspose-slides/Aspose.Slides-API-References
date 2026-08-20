---
title: IControlPropertiesCollection
second_title: Aspose.Slides for Java API संदर्भ
description: ActiveX नियंत्रणों का संग्रह।
type: docs
url: /hi/com.aspose.slides/icontrolpropertiescollection/
---
**सभी कार्यान्वित इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

ActiveX नियंत्रणों का संग्रह।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में प्रॉपर्टी की संख्या लौटाता है। |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | एक प्रॉपर्टी को संग्रह में जोड़ता है। |
| [remove(String name)](#remove-java.lang.String-) | निर्दिष्ट नाम वाली प्रॉपर्टी को हटाता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | प्रॉपर्टी को प्राप्त या सेट करता है। |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | प्रॉपर्टी को प्राप्त या सेट करता है। |
| [getNamesOfProperties()](#getNamesOfProperties--) | संग्रह में प्रॉपर्टी की संख्या लौटाता है। |
| [clear()](#clear--) | सभी प्रॉपर्टी को हटाता है। |
### getCount() {#getCount--}
```
public abstract int getCount()
```


संग्रह में प्रॉपर्टी की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


एक प्रॉपर्टी को संग्रह में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी का नाम। |
| value | java.lang.String | प्रॉपर्टी का मान। |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


निर्दिष्ट नाम वाली प्रॉपर्टी को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाने के लिए प्रॉपर्टी का नाम। |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


प्रॉपर्टी को प्राप्त या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी का नाम। |

**रिटर्न:**
java.lang.String - प्रॉपर्टी।
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


प्रॉपर्टी को प्राप्त या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | प्रॉपर्टी का नाम। |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


संग्रह में प्रॉपर्टी की संख्या लौटाता है। केवल-पढ़ने योग्य [IGenericCollection](../../com.aspose.slides/igenericcollection)।

**रिटर्न:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


सभी प्रॉपर्टी को हटाता है।