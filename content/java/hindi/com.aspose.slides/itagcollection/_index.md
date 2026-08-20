---
title: ITagCollection
second_title: Aspose.Slides for Java API संदर्भ
description: टैग के संग्रह का प्रतिनिधित्व करता है जो उपयोगकर्ता द्वारा परिभाषित स्ट्रिंग की जोड़े हैं
type: docs
url: /hi/com.aspose.slides/itagcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

टैग का संग्रह दर्शाता है (उपयोगकर्ता द्वारा परिभाषित स्ट्रिंग की जोड़े)
## विधियां

| विधि | विवरण |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | संग्रह में नया टैग जोड़ता है। |
| [remove(String name)](#remove-java.lang.String-) | संग्रह से निर्दिष्ट नाम वाले टैग को हटाता है। |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | संग्रह में निर्दिष्ट कुंजी का शून्य-आधारित सूचकांक लौटाता है। |
| [contains(String name)](#contains-java.lang.String-) | निर्धारित करता है कि संग्रह में कोई विशिष्ट नाम है या नहीं। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर टैग को हटाता है। |
| [clear()](#clear--) | सभी टैग को संग्रह से हटाता है। |
| [getValueByIndex(int index)](#getValueByIndex-int-) | निर्दिष्ट सूचकांक पर टैग का मान लौटाता है। |
| [getNameByIndex(int index)](#getNameByIndex-int-) | निर्दिष्ट सूचकांक पर टैग की कुंजी लौटाता है। |
| [getNamesOfTags()](#getNamesOfTags--) | टैग के नाम लौटाता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | एक टैग की कुंजी और मान युग्म को लौटाता या सेट करता है। |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | एक टैग की कुंजी और मान युग्म को लौटाता या सेट करता है। |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

संग्रह में नया टैग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | टैग का नाम। |
| value | java.lang.String | टैग का मान। |

**रिटर्न:**
int - जोड़े हुए टैग का सूचकांक।
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

संग्रह से निर्दिष्ट नाम वाले टैग को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाने के लिए टैग का नाम। |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

संग्रह में निर्दिष्ट कुंजी का शून्य-आधारित सूचकांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | संग्रह में खोजने के लिए नाम। |

**रिटर्न:**
int - कुंजी का शून्य-आधारित सूचकांक, यदि कुंजी संग्रह में पाई जाती है; अन्यथा, -1।
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

निर्धारित करता है कि संग्रह में कोई विशिष्ट नाम है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | खोजने के लिए कुंजी। |

**रिटर्न:**
boolean - यदि संग्रह में निर्दिष्ट कुंजी वाला टैग है तो सत्य; अन्यथा असत्य।
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट सूचकांक पर टैग को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए टैग का शून्य-आधारित सूचकांक। |
### clear() {#clear--}
```
public abstract void clear()
```

सभी टैग को संग्रह से हटाता है।
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

निर्दिष्ट सूचकांक पर टैग का मान लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वापसी के लिए टैग का सूचकांक। |

**रिटर्न:**
java.lang.String - टैग का मान।
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

निर्दिष्ट सूचकांक पर टैग की कुंजी लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वापसी के लिए टैग का सूचकांक। |

**रिटर्न:**
java.lang.String - टैग की कुंजी।
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

टैग के नाम लौटाता है।

**रिटर्न:**
java.lang.String[] - टैग के नाम।
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

एक टैग की कुंजी और मान युग्म को लौटाता या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | टैग की कुंजी। |

**रिटर्न:**
java.lang.String - टैग का मान।
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

एक टैग की कुंजी और मान युग्म को लौटाता या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | टैग की कुंजी। |
| value | java.lang.String |  |