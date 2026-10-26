---
title: BehaviorPropertyCollection
second_title: Aspose.Slides के लिए Java API रेफ़रेंस
description: इफ़ेक्ट व्यवहार के लिए टाइमिंग प्रॉपर्टी का प्रतिनिधित्व करता है।
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

इफ़ेक्ट व्यवहार के लिए टाइमिंग प्रॉपर्टी का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | कलेक्शन में संग्रहीत प्रॉपर्टी की संख्या लौटाता है। |
| [isReadOnly()](#isReadOnly--) | एक मान प्राप्त करता है जो यह दर्शाता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है या नहीं। |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | कलेक्शन में एक नई प्रॉपर्टी जोड़ता है। |
| [add(String propertyValue)](#add-java.lang.String-) | कलेक्शन में एक नई प्रॉपर्टी जोड़ता है। |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | सूची में किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है। |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | सूची में प्रॉपर्टी मान के आधार पर किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है। |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | निर्दिष्ट इंडेक्स पर कलेक्शन में एक नई प्रॉपर्टी डालता है। |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | निर्दिष्ट इंडेक्स पर कलेक्शन में एक नई प्रॉपर्टी (निर्दिष्ट प्रॉपर्टी मान के साथ) डालता है। |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक ऐरे में कॉपी करता है, विशेष ऐरे इंडेक्स से शुरू करके। |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | कलेक्शन से निर्दिष्ट प्रॉपर्टी हटाता है। |
| [remove(String propertyValue)](#remove-java.lang.String-) | कलेक्शन से निर्दिष्ट प्रॉपर्टी हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर प्रॉपर्टी हटाता है। |
| [clear()](#clear--) | कलेक्शन से सभी प्रॉपर्टी हटाता है। |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान मौजूद है या नहीं। |
| [contains(String propertyValue)](#contains-java.lang.String-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान मौजूद है या नहीं। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर एक प्रॉपर्टी लौटाता है। |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | निर्दिष्ट इंडेक्स पर एक प्रॉपर्टी सेट करता है। |
| [iterator()](#iterator--) | एक इटरेटर लौटाता है जो कलेक्शन के माध्यम से इटरेट करता है। |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | पूरी कलेक्शन के लिए एक java इटरेटर लौटाता है। |

### size() {#size--}
```
public final int size()
```

कलेक्शन में संग्रहीत प्रॉपर्टी की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

एक मान प्राप्त करता है जो यह दर्शाता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean - यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है तो true; अन्यथा false।

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

कलेक्शन में एक नई प्रॉपर्टी जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | जोड़ने के लिए प्रॉपर्टी। |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

कलेक्शन में एक नई प्रॉपर्टी जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | जोड़ने के लिए प्रॉपर्टी का मान। |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

सूची में किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | सूची में वस्तु को खोजने के लिए। |

**रिटर्न:**  
int - यदि आइटम सूची में मिला तो उसका इंडेक्स; अन्यथा -1।

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

सूची में प्रॉपर्टी मान के आधार पर किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | प्रॉपर्टी का मान |

**रिटर्न:**  
int - निर्दिष्ट मान वाली प्रॉपर्टी का इंडेक्स।

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

निर्दिष्ट इंडेक्स पर कलेक्शन में एक नई प्रॉपर्टी डालता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | नयी प्रॉपर्टी डालने के लिए इंडेक्स। |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | जोड़ने के लिए प्रॉपर्टी। |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

निर्दिष्ट इंडेक्स पर कलेक्शन में एक नई प्रॉपर्टी (निर्दिष्ट प्रॉपर्टी मान के साथ) डालता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | नयी प्रॉपर्टी डालने के लिए इंडेक्स। |
| propertyValue | java.lang.String | जोड़ने के लिए प्रॉपर्टी का मान। |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक ऐरे में कॉपी करता है, विशेष ऐरे इंडेक्स से शुरू करके।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | एक-आयामी ऐरे जो [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों का गंतव्य है। ऐरे का शून्य-आधारित इंडेक्स होना चाहिए। |
| arrayIndex | int | ऐरे में शून्य-आधारित इंडेक्स जहाँ से कॉपी शुरू होती है। |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

कलेक्शन से निर्दिष्ट प्रॉपर्टी हटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | हटाने के लिए प्रॉपर्टी। |

**रिटर्न:**  
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

कलेक्शन से निर्दिष्ट प्रॉपर्टी हटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | हटाने के लिए प्रॉपर्टी का मान। |

**रिटर्न:**  
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर प्रॉपर्टी हटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाली प्रॉपर्टी का इंडेक्स। |

### clear() {#clear--}
```
public final void clear()
```

कलेक्शन से सभी प्रॉपर्टी हटाता है।

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान मौजूद है या नहीं।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | खोजने के लिए प्रॉपर्टी [IGenericCollection](../../com.aspose.slides/igenericcollection) में। |

**रिटर्न:**  
boolean - यदि आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाया जाता है तो true; अन्यथा false।

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान मौजूद है या नहीं।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | खोजने के लिए प्रॉपर्टी का मान [IGenericCollection](../../com.aspose.slides/igenericcollection) में। |

**रिटर्न:**  
boolean - यदि propertyValue [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाया जाता है तो true; अन्यथा false।

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

निर्दिष्ट इंडेक्स पर एक प्रॉपर्टी लौटाता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | लौटाने के लिए प्रॉपर्टी का इंडेक्स। |

**रिटर्न:**  
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - एनिमेशन व्यवहार प्रॉपर्टी।

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

निर्दिष्ट इंडेक्स पर एक प्रॉपर्टी सेट करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | सेट करने के लिए प्रॉपर्टी का इंडेक्स। |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

एक इटरेटर लौटाता है जो कलेक्शन के माध्यम से इटरेट करता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - एक IGenericEnumerator जिसे कलेक्शन के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**रिटर्न:**  
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**रिटर्न:**  
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**रिटर्न:**  
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

पूरी कलेक्शन के लिए एक java इटरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - एक java.util.Iterator जो पूरी कलेक्शन के लिए है।