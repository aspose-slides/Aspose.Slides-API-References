---
title: PortionCollection
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: Portion का एक संग्रह प्रस्तुत करता है।
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

Portion का एक संग्रह प्रस्तुत करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [isReadOnly()](#isReadOnly--) | यह दर्शाने वाला मान प्राप्त करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है या नहीं। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Portion को संग्रह के अंत में जोड़ता है। |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | सूची में विशिष्ट आइटम का सूचकांक निर्धारित करता है। |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | निर्दिष्ट सूचकांक पर Portion को संग्रह में सम्मिलित करता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटा देता है। |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | यह निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में विशिष्ट मान मौजूद है या नहीं। |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, जो किसी विशिष्ट Array सूचकांक से शुरू होता है। |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से विशिष्ट वस्तु की पहली उपस्थिति को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है। |
| [iterator()](#iterator--) | संग्रह पर क्रमिक रूप से इटरेट करने के लिये एक enumerator लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरी संग्रह के लिये एक java iterator लौटाता है। |

### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**वापसी:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

यह दर्शाने वाला मान प्राप्त करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है या नहीं। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean - सत्य यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है; अन्यथा असत्य।

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

Portion को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | संग्रह के अंत में जोड़ी जाने वाली Portion। |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

सूची में विशिष्ट आइटम का सूचकांक निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | सूची में खोजी जाने वाली वस्तु। |

**वापसी:**
int - यदि आइटम सूची में मिला तो उसका सूचकांक; अन्यथा -1।

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

निर्दिष्ट सूचकांक पर Portion को संग्रह में सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित सूचकांक जहाँ Portion सम्मिलित किया जाना चाहिए। |
| value | [IPortion](../../com.aspose.slides/iportion) | सम्मिलित की जाने वाली Portion। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी तत्वों को हटा देता है।

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) में विशिष्ट मान मौजूद है या नहीं, यह निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजी जाने वाली वस्तु। |

**वापसी:**
boolean - सत्य यदि आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) में मिला; अन्यथा असत्य।

### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, जो किसी विशिष्ट Array सूचकांक से शुरू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | एक-आयामी Array जो [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों का गंतव्य है। Array में शून्य-आधारित अनुक्रमण होना चाहिए। |
| arrayIndex | int | वह शून्य-आधारित सूचकांक जहाँ प्रतिलिपि शुरू होती है। |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) से विशिष्ट वस्तु की पहली उपस्थिति को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटायी जाने वाली वस्तु। |

**वापसी:**
boolean - सत्य यदि आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) से सफलतापूर्वक हटाया गया; अन्यथा असत्य। यह विधि तब भी असत्य लौटाती है जब मूल [IGenericCollection](../../com.aspose.slides/igenericcollection) में आइटम नहीं मिला।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिये तत्व का शून्य-आधारित सूचकांक। |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

संग्रह पर क्रमिक रूप से इटरेट करने के लिये एक enumerator लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - एक IGenericEnumerator जिसे संग्रह पर इटरै�� करने के लिये प्रयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

पूरे संग्रह के लिये एक java iterator लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - पूरी संग्रह के लिये एक java.util.Iterator।