---
title: PortionCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: Portion का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/portioncollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Portion का एक संग्रह दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCount()](#getCount--) | कलेक्शन में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के केवल-पढ़ने योग्य होने को दर्शाने वाला मान प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | कलेक्शन के अंत में एक Portion जोड़ता है। |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | सूची में किसी विशिष्ट आइटम का सूचकांक निर्धारित करता है। |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | निर्दिष्ट सूचकांक पर कलेक्शन में एक Portion डालता है। |
| [clear()](#clear--) | कलेक्शन से सभी तत्व हटाता है। |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | यह निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं। |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, एक विशिष्ट Array सूचकांक से शुरू करते हुए। |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से किसी विशिष्ट ऑब्जेक्ट की पहली घटना हटाता है। |
| [removeAt(int index)](#removeAt-int-) | कलेक्शन में निर्दिष्ट सूचकांक पर तत्व हटाता है। |
| [iterator()](#iterator--) | एक enumerator लौटाता है जो कलेक्शन के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरी कलेक्शन के लिए एक java iterator लौटाता है। |
### getCount() {#getCount--}
```
public final int getCount()
```

कलेक्शन में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के केवल-पढ़ने योग्य होने को दर्शाने वाला मान प्राप्त करता है। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean - true यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है; अन्यथा, false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

कलेक्शन के अंत में एक Portion जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | कलेक्शन के अंत में जोड़ने के लिए Portion। |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

सूची में किसी विशिष्ट आइटम का सूचकांक निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | सूची में खोजे जाने वाले ऑब्जेक्ट। |

**वापसी:**
int - यदि आइटम सूची में मिला तो उसका सूचकांक; अन्यथा -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

निर्दिष्ट सूचकांक पर कलेक्शन में एक Portion डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित सूचकांक जहाँ Portion डाली जानी चाहिए। |
| value | [IPortion](../../com.aspose.slides/iportion) | डालने के लिए Portion। |
### clear() {#clear--}
```
public final void clear()
```

कलेक्शन से सभी तत्व हटाता है।

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं, यह निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजे जाने वाले ऑब्जेक्ट। |

**वापसी:**
boolean - true यदि आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाया गया; अन्यथा, false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, एक विशिष्ट Array सूचकांक से शुरू करते हुए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों की गंतव्य एक-आयामी Array। Array में शून्य-आधारित अनुक्रमण होना चाहिए। |
| arrayIndex | int | Array में वह शून्य-आधारित सूचकांक जहाँ कॉपी शुरू होती है। |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) से किसी विशिष्ट ऑब्जेक्ट की पहली घटना हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाने के लिए ऑब्जेक्ट। |

**वापसी:**
boolean - true यदि आइटम सफलतापूर्वक [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाया गया; अन्यथा, false। यह मेथड false भी लौटाता है यदि आइटम मूल [IGenericCollection](../../com.aspose.slides/igenericcollection) में नहीं मिला।
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

कलेक्शन में निर्दिष्ट सूचकांक पर तत्व हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित सूचकांक। |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

कलेक्शन के माध्यम से इटररेट करने वाला एक enumerator लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - कलेक्शन के माध्यम से इटररेट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

पूरी कलेक्शन के लिए एक java iterator लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - पूरी कलेक्शन के लिए उपयोग किया जा सकने वाला java.util.Iterator।