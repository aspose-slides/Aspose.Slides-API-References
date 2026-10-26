---
title: BehaviorCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: व्यवहार प्रभावों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/behaviorcollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

व्यवहार प्रभावों का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में व्यवहारों की संख्या लौटाता है। |
| [isReadOnly()](#isReadOnly--) | एक मान प्राप्त करता है जो दर्शाता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है। |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | संग्रह में नया व्यवहार जोड़ें। |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | सूची में किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है। |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | निर्दिष्ट इंडेक्स पर संग्रह में नया व्यवहार सम्मिलित करता है। |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, विशेष Array इंडेक्स से शुरू करके। |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | संग्रह से निर्दिष्ट व्यवहार को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर संग्रह से व्यवहार हटाता है। |
| [clear()](#clear--) | संग्रह से सभी व्यवहार हटाता है। |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर एक व्यवहार लौटाता है। |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | निर्दिष्ट इंडेक्स पर एक व्यवहार सेट करता है। |
| [iterator()](#iterator--) | एक एन्यूमरटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java इटररेटर लौटाता है। |

### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में व्यवहारों की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

एक मान प्राप्त करता है जो दर्शाता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean - true यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है; अन्यथा false.

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

संग्रह में नया व्यवहार जोड़ें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | जोड़ने के लिए व्यवहार। |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

सूची में किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | सूची में लोकेट करने के लिए ऑब्जेक्ट। |

**रिटर्न:**
int - यदि आइटम सूची में मिला तो उसका इंडेक्स; अन्यथा -1.

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

निर्दिष्ट इंडेक्स पर संग्रह में नया व्यवहार सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | इंडेक्स जहाँ नया व्यवहार सम्मिलित किया जाना चाहिए। |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | सम्मिलित करने के लिए व्यवहार। |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

विशिष्ट Array इंडेक्स से शुरू करके [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | एक-आयामी Array जो [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों का गंतव्य है। Array का शून्य-आधारित अनुक्रमण होना चाहिए। |
| arrayIndex | int | Array में शून्य-आधारित इंडेक्स जहाँ कॉपी शुरू होता है। |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

संग्रह से निर्दिष्ट व्यवहार हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | हटाने के लिए व्यवहार। |

**रिटर्न:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर संग्रह से व्यवहार हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले व्यवहार का इंडेक्स। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी व्यवहार हटाता है।

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | [IGenericCollection](../../com.aspose.slides/igenericcollection) में लोकेट करने के लिए ऑब्जेक्ट। |

**रिटर्न:**
boolean - true यदि आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) में मिला; अन्यथा false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

निर्दिष्ट इंडेक्स पर एक व्यवहार लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वापसी के लिए व्यवहार का इंडेक्स। |

**रिटर्न:**
[IBehavior](../../com.aspose.slides/ibehavior) - एनीमेशन व्यवहार।

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

निर्दिष्ट इंडेक्स पर एक व्यवहार सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वापसी के लिए व्यवहार का इंडेक्स। |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

एक एन्यूमरटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - संग्रह के माध्यम से इटररेट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

पूरे संग्रह के लिए एक java इटररेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - पूरे संग्रह के लिए एक java.util.Iterator।