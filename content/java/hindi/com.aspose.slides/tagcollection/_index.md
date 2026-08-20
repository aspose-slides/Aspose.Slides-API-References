---
title: TagCollection
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: टैग्स का संग्रह दर्शाता है जो उपयोगकर्ता द्वारा परिभाषित स्ट्रिंग के जोड़े होते हैं
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

Represents the collection of tags (user defined pairs of strings) का संग्रह दर्शाता है

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

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में टैग्स की संख्या लौटाता है। |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | संग्रह में एक नया टैग जोड़ता है। |
| [remove(String name)](#remove-java.lang.String-) | निर्दिष्ट नाम वाला टैग संग्रह से हटाता है। |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | संग्रह में निर्दिष्ट कुंजी का शून्य-आधारित इंडेक्स लौटाता है। |
| [contains(String name)](#contains-java.lang.String-) | निर्धारित करता है कि संग्रह में कोई विशिष्ट नाम है या नहीं। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर टैग हटाता है। |
| [clear()](#clear--) | संग्रह से सभी टैग हटाता है। |
| [getValueByIndex(int index)](#getValueByIndex-int-) | निर्दिष्ट इंडेक्स पर टैग का मान लौटाता है। |
| [getNameByIndex(int index)](#getNameByIndex-int-) | निर्दिष्ट इंडेक्स पर टैग की कुंजी लौटाता है। |
| [getNamesOfTags()](#getNamesOfTags--) | टैग्स के नाम लौटाता है। |
| [get_Item(String name)](#get-Item-java.lang.String-) | टैग की कुंजी और मान की जोड़ी लौटाता या सेट करता है। |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | टैग की कुंजी और मान की जोड़ी लौटाता या सेट करता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह बताने वाला मान लौटाता है कि संग्रह तक पहुंच संकलित (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | सिंक्रनाइज़ेशन मूल लौटाता है। |
| [iterator()](#iterator--) | एक ऐसा इटररेटर लौटाता है जो संग्रह पर इटेरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है। |
### size() {#size--}
```
public final int size()
```

संग्रह में टैग्स की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

संग्रह में एक नया टैग जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | टैग का नाम। |
| value | java.lang.String | टैग का मान। |

**वापसी:**
int - जोड़ें गए टैग का इंडेक्स।
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

निर्दिष्ट नाम वाला टैग संग्रह से हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | हटाने वाले टैग का नाम। |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

संग्रह में निर्दिष्ट कुंजी का शून्य-आधारित इंडेक्स लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | संग्रह में खोजने वाला नाम। |

**वापसी:**
int - कुंजी का शून्य-आधारित इंडेक्स, यदि कुंजी मिलती है; अन्यथा, -1।
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

निर्धारित करता है कि संग्रह में कोई विशिष्ट नाम है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | खोजने की कुंजी। |

**वापसी:**
boolean - True यदि संग्रह में निर्दिष्ट कुंजी वाला टैग मौजूद है; अन्यथा, false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर टैग हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले टैग का शून्य-आधारित इंडेक्स। |

### clear() {#clear--}
```
public final void clear()
```

सभी टैग्स को संग्रह से हटाता है।

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

निर्दिष्ट इंडेक्स पर टैग का मान लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लौटाए जाने वाले टैग का इंडेक्स। |

**वापसी:**
java.lang.String - टैग का मान।
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

निर्दिष्ट इंडेक्स पर टैग की कुंजी लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लौटाए जाने वाले टैग का इंडेक्स। |

**वापसी:**
java.lang.String - टैग की कुंजी।
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

टैग्स के नाम लौटाता है।

**वापसी:**
java.lang.String[] - टैग्स के नाम।
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

टैग की कुंजी और मान की जोड़ी लौटाता या सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | java.lang.String | टैग की कुंजी। |

**वापसी:**
java.lang.String - टैग का मान।
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

टैग की कुंजी और मान की जोड़ी लौटाता या सेट करता है।

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
| array | com.aspose.ms.System.Array | भरने के लिए एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक स्थिति। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

यह बताने वाला मान लौटाता है कि संग्रह तक पहुंच संकलित (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

सिंक्रीकरण मूल लौटाता है। केवल-पढ़ने योग्य Object।

**वापसी:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

एक ऐसा इटररेटर लौटाता है जो संग्रह पर इटेरेट करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटररेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.