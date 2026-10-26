---
title: ITagCollection
second_title: Aspose.Slides for Android हेतु Java API संदर्भ
description: टैग का संग्रह प्रस्तुत करता है, जो उपयोगकर्ता-परिभाषित स्ट्रिंग जोड़े होते हैं
type: docs
url: /hi/com.aspose.slides/itagcollection/
---
**सभी कार्यान्वित इंटरफ़ेस:**  
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

संग्रह के टैग (उपयोगकर्ता द्वारा परिभाषित स्ट्रिंग जोड़े) का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | संग्रह में एक नया टैग जोड़ता है। |
| [remove(String name)](#remove-java.lang.String-) | निर्दिष्ट नाम वाले टैग को संग्रह से हटाता है। |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | संग्रह में निर्दिष्ट कुंजी का शून्य-आधारित अनुक्रमांक लौटाता है। |
| [contains(String name)](#contains-java.lang.String-) | निर्धारित करता है कि संग्रह में कोई विशिष्ट नाम मौजूद है या नहीं। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट अनुक्रमांक पर टैग को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी टैग हटाता है। |
| [getValueByIndex(int index)](#getValueByIndex-int-) | निर्दिष्ट अनुक्रमांक पर टैग का मान लौटाता है। |
| [getNameByIndex(int index)](#getNameByIndex-int-) | निर्दिष्ट अनुक्रमांक पर टैग की कुंजी लौटाता है। |
| [getNamesOfTags()](#getNamesOfTags--) | टैग के नाम लौटाता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | टैग की कुंजी और मान जोड़ी को लौटाता या सेट करता है। |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | टैग की कुंजी और मान जोड़ी को लौटाता या सेट करता है। |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

संग्रह में एक नया टैग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | टैग का नाम। |
| value | java.lang.String | टैग का मान। |

**रिटर्न:**
int - जोड़े गए टैग का अनुक्रमांक।

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

निर्दिष्ट नाम वाले टैग को संग्रह से हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाए जाने वाले टैग का नाम। |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

संग्रह में निर्दिष्ट कुंजी का शून्य-आधारित अनुक्रमांक लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | संग्रह में खोजने के लिए नाम। |

**रिटर्न:**
int - कुंजी का शून्य-आधारित अनुक्रमांक, यदि कुंजी संग्रह में पाई जाती है; अन्यथा, -1।

### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

निर्धारित करता है कि संग्रह में कोई विशिष्ट नाम मौजूद है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | खोजने के लिए कुंजी। |

**रिटर्न:**
boolean - True यदि संग्रह में निर्दिष्ट कुंजी वाला टैग मौजूद है; अन्यथा, false।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट अनुक्रमांक पर टैग को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | टैग को हटाने के लिए शून्य-आधारित अनुक्रमांक। |

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी टैग हटाता है।

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

निर्दिष्ट अनुक्रमांक पर टैग का मान लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वापसी के लिए टैग का अनुक्रमांक। |

**रिटर्न:**
java.lang.String - टैग का मान।

### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

निर्दिष्ट अनुक्रमांक पर टैग की कुंजी लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वापसी के लिए टैग का अनुक्रमांक। |

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

टैग की कुंजी और मान जोड़ी को लौटाता या सेट करता है।

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

टैग की कुंजी और मान जोड़ी को लौटाता या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | टैग की कुंजी। |
| value | java.lang.String |  |