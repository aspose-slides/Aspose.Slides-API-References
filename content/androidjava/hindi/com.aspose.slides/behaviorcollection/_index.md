---
title: BehaviorCollection
second_title: Aspose.Slides for Android के लिए जावा API संदर्भ
description: व्यवहार प्रभावों के संग्रह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/behaviorcollection/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेसेज़:**  
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)  
```
public class BehaviorCollection implements IBehaviorCollection
```

व्यवहार प्रभावों का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCount()](#getCount--) | किसी संग्रह में व्यवहारों की संख्या लौटाता है। |
| [isReadOnly()](#isReadOnly--) | एक मान देता है जो दर्शाता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है। |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | संग्रह में नया व्यवहार जोड़ता है। |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | सूची में किसी विशिष्ट आइटम का अनुक्रमांक निर्धारित करता है। |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | निर्दिष्ट अनुक्रमांक पर संग्रह में नया व्यवहार डालता है। |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक ऐरे में कॉपी करता है, जो विशेष ऐरे अनुक्रमांक से शुरू होता है। |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | संग्रह से निर्दिष्ट व्यवहार को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट अनुक्रमांक पर संग्रह से व्यवहार को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी व्यवहारों को हटाता है। |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में विशिष्ट मान है या नहीं। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर एक व्यवहार लौटाता है। |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | निर्दिष्ट अनुक्रमांक पर एक व्यवहार सेट करता है। |
| [iterator()](#iterator--) | एक इटेरेटर लौटाता है जो संग्रह के माध्यम से चलता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटेरेटर लौटाता है। |

### getCount() {#getCount--}
```
public final int getCount()
```

किसी संग्रह में व्यवहारों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

एक मान देता है जो दर्शाता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है। केवल-पढ़ने योग्य boolean।

**वापसी:**  
boolean - यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है तो true; अन्यथा false।

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

संग्रह में नया व्यवहार जोड़ता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | जोड़ने के लिए व्यवहार। |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

सूची में किसी विशिष्ट आइटम का अनुक्रमांक निर्धारित करता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | सूची में खोजे जाने वाला ऑब्जेक्ट। |

**वापसी:**  
int - यदि आइटम सूची में पाया जाता है तो उसका अनुक्रमांक; अन्यथा -1।

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

निर्दिष्ट अनुक्रमांक पर संग्रह में नया व्यवहार डालता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | अनुक्रमांक जहाँ नया व्यवहार डाला जाना चाहिए। |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | डालने के लिए व्यवहार। |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक ऐरे में कॉपी करता है, जो विशेष ऐरे अनुक्रमांक से शुरू होता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | एक-आयामी ऐरे जो [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों का गंतव्य है। ऐरे को शून्य-आधारित अनुक्रमांक होना चाहिए। |
| arrayIndex | int | ऐरे में शून्य-आधारित अनुक्रमांक जहाँ कॉपी शुरू होती है। |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

संग्रह से निर्दिष्ट व्यवहार को हटाता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | हटाने के लिए व्यवहार। |

**वापसी:**  
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट अनुक्रमांक पर संग्रह से व्यवहार को हटाता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | हटाने वाले व्यवहार का अनुक्रमांक। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी व्यवहारों को हटाता है।

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में विशिष्ट मान है या नहीं।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | ऑब्जेक्ट जिसे [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजा जाना है। |

**वापसी:**  
boolean - यदि आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाया जाता है तो true; अन्यथा false।

### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर एक व्यवहार लौटाता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | वापस करने वाले व्यवहार का अनुक्रमांक। |

**वापसी:**  
[IBehavior](../../com.aspose.slides/ibehavior) - एनीमेशन व्यवहार।

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

निर्दिष्ट अनुक्रमांक पर एक व्यवहार सेट करता है।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | वापस करने वाले व्यवहार का अनुक्रमांक। |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

एक इटेरेटर लौटाता है जो संग्रह के माध्यम से इटरैट करता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरैट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

पूरे संग्रह के लिए जावा इटेरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - एक java.util.Iterator पूरे संग्रह के लिए।