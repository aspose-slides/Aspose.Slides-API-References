---
title: BehaviorPropertyCollection
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API संदर्भ
description: इफ़ेक्ट व्यवहार के लिए टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/behaviorpropertycollection/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

इफ़ेक्ट व्यवहार के लिए टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | कॉलेशन में संग्रहीत प्रॉपर्टीज़ की संख्या लौटाता है। |
| [isReadOnly()](#isReadOnly--) | एक मान प्राप्त करता है जो यह दर्शाता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-रीड है। |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | कॉलेशन में एक नई प्रॉपर्टी जोड़ता है। |
| [add(String propertyValue)](#add-java.lang.String-) | कॉलेशन में एक नई प्रॉपर्टी जोड़ता है। |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | सूची में एक विशिष्ट आइटम का इंडेक्स निर्धारित करता है। |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | सूची में प्रॉपर्टी मान द्वारा एक विशिष्ट आइटम का इंडेक्स निर्धारित करता है। |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | निर्दिष्ट इंडेक्स पर कॉलेशन में एक नई प्रॉपर्टी डालता है। |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | निर्दिष्ट इंडेक्स पर (निर्दिष्ट प्रॉपर्टी मान के साथ) कॉलेशन में एक नई प्रॉपर्टी डालता है। |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | विशिष्ट ऐरे इंडेक्स से शुरू करके [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक एरे में कॉपी करता है। |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | कॉलेशन से निर्दिष्ट प्रॉपर्टी को हटाता है। |
| [remove(String propertyValue)](#remove-java.lang.String-) | कॉलेशन से निर्दिष्ट प्रॉपर्टी को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर प्रॉपर्टी को हटाता है। |
| [clear()](#clear--) | कॉलेशन से सभी प्रॉपर्टीज़ को हटाता है। |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | निर्धारित करता है कि क्या [IGenericCollection](../../com.aspose.slides/igenericcollection) में एक विशिष्ट मान है। |
| [contains(String propertyValue)](#contains-java.lang.String-) | निर्धारित करता है कि क्या [IGenericCollection](../../com.aspose.slides/igenericcollection) में एक विशिष्ट मान है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर एक प्रॉपर्टी लौटाता है। |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | निर्दिष्ट इंडेक्स पर एक प्रॉपर्टी सेट करता है। |
| [iterator()](#iterator--) | कॉलेशन के माध्यम से इटररेट करने वाला एन्ह्यूमरेटर लौटाता है। |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | पूरी कॉलेशन के लिए एक जावा इटररेटर लौटाता है। |

### size() {#size--}
```
public final int size()
```

कॉलेशन में संग्रहीत प्रॉपर्टीज़ की संख्या लौटाता है। केवल-रीड int.

**वापसी:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

एक मान प्राप्त करता है जो यह दर्शाता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-रीड है। केवल-रीड boolean.

**वापसी:**  
boolean - true यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-रीड है; अन्यथा false.

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

कॉलेशन में एक नई प्रॉपर्टी जोड़ता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | जोड़ने वाली प्रॉपर्टी। |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

कॉलेशन में एक नई प्रॉपर्टी जोड़ता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | जोड़ने वाली प्रॉपर्टी का मान। |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

सूची में एक विशिष्ट आइटम का इंडेक्स निर्धारित करता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | सूची में खोजा जाने वाला ऑब्जेक्ट। |

**वापसी:**  
int - यदि आइटम सूची में पाया गया तो उसका इंडेक्स; अन्यथा -1.

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

सूची में प्रॉपर्टी मान द्वारा एक विशिष्ट आइटम का इंडेक्स निर्धारित करता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | प्रॉपर्टी का मान |

**वापसी:**  
int - निर्दिष्ट मान वाली प्रॉपर्टी का इंडेक्स

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

कॉलेशन में निर्दिष्ट इंडेक्स पर एक नई प्रॉपर्टी डालता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जहाँ नई प्रॉपर्टी डाली जानी है। |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | जोड़ने वाली प्रॉपर्टी। |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

निर्दिष्ट इंडेक्स पर (निर्दिष्ट प्रॉपर्टी मान के साथ) कॉलेशन में एक नई प्रॉपर्टी डालता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जहाँ नई प्रॉपर्टी डाली जानी है। |
| propertyValue | java.lang.String | जोड़ने वाली प्रॉपर्टी का मान। |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक एरे में कॉपी करता है, विशेष एरे इंडेक्स से शुरू करते हुए।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | वह एक-आयामी एरे जो [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों का गंतव्य है। एरे का शून्य-आधारित इंडेक्सिंग होना चाहिए। |
| arrayIndex | int | एरे में वह शून्य-आधारित इंडेक्स जहाँ कॉपी शुरू होती है। |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

कॉलेशन से निर्दिष्ट प्रॉपर्टी को हटाता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | हटाने वाली प्रॉपर्टी। |

**वापसी:**  
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

कॉलेशन से निर्दिष्ट प्रॉपर्टी को हटाता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | हटाने वाली प्रॉपर्टी का मान। |

**वापसी:**  
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर प्रॉपर्टी को हटाता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जिसके तहत प्रॉपर्टी हटाई जानी है। |

### clear() {#clear--}
```
public final void clear()
```

कॉलेशन से सभी प्रॉपर्टीज़ को हटाता है।

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

निर्धारित करता है कि क्या [IGenericCollection](../../com.aspose.slides/igenericcollection) में एक विशिष्ट मान है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजी जाने वाली प्रॉपर्टी। |

**वापसी:**  
boolean - true यदि आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाया जाता है; अन्यथा false.

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

निर्धारित करता है कि क्या [IGenericCollection](../../com.aspose.slides/igenericcollection) में एक विशिष्ट मान है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजी जाने वाली प्रॉपर्टी का मान। |

**वापसी:**  
boolean - true यदि propertyValue [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाया जाता है; अन्यथा false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

निर्दिष्ट इंडेक्स पर एक प्रॉपर्टी लौटाता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | लौटाने के लिए प्रॉपर्टी का इंडेक्स। |

**वापसी:**  
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - एनीमेशन व्यवहार प्रॉपर्टी।

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

निर्दिष्ट इंडेक्स पर एक प्रॉपर्टी सेट करता है।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जहाँ प्रॉपर्टी सेट की जानी है। |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

कॉलेशन के माध्यम से इटररेट करने वाला एन्ह्यूमरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - एक IGenericEnumerator जो कॉलेशन के माध्यम से इटररेट करने के लिए उपयोग किया जा सकता है।

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**वापसी:**  
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**वापसी:**  
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**वापसी:**  
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

पूरे कॉलेशन के लिए एक जावा इटररेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - पूरे कॉलेशन के लिए एक java.util.Iterator।