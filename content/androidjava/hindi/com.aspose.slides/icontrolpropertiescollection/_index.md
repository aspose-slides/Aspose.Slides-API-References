---
title: IControlPropertiesCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: ActiveX नियंत्रणों का एक संग्रह।
type: docs
url: /hi/com.aspose.slides/icontrolpropertiescollection/
---
**सभी कार्यान्वित इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

ActiveX नियंत्रणों का एक संग्रह।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में गुणों की संख्या लौटाता है। |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | संग्रह में एक गुण जोड़ता है। |
| [remove(String name)](#remove-java.lang.String-) | निर्दिष्ट नाम वाले गुण को हटाता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | गुण को लौटाता है या सेट करता है। |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | गुण को लौटाता है या सेट करता है। |
| [getNamesOfProperties()](#getNamesOfProperties--) | संग्रह में गुणों की संख्या लौटाता है। |
| [clear()](#clear--) | सभी गुणों को हटाता है। |
### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में गुणों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

संग्रह में एक गुण जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | गुण का नाम। |
| value | java.lang.String | गुण का मान। |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

निर्दिष्ट नाम वाले गुण को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाने के लिए गुण का नाम। |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

गुण को लौटाता है या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | गुण का नाम। |

**वापसी:**
java.lang.String - गुण.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

गुण को लौटाता है या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | गुण का नाम। |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

संग्रह में गुणों की संख्या लौटाता है। केवल-पढ़ने योग्य [IGenericCollection](../../com.aspose.slides/igenericcollection)।

**वापसी:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

सभी गुणों को हटाता है।