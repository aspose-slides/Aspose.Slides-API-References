---
title: IPortionCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक हिस्सों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iportioncollection/
---
**सभी कार्यान्वित इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

एक हिस्सों का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [getCount()](#getCount--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | संग्रह के अंत में एक Portion जोड़ता है। |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | संग्रह में एक विशिष्ट Portion का इंडेक्स निर्धारित करता है। |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | निर्दिष्ट इंडेक्स पर संग्रह में एक Portion डालता है। |
| [clear()](#clear--) | संग्रह से सभी तत्व हटाता है। |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान मौजूद है या नहीं। |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | विशिष्ट वस्तु की पहली घटना को [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर संग्रह के तत्व को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न मान:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न मान:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

संग्रह के अंत में एक Portion जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | संग्रह के अंत में जोड़ने के लिए Portion। |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

संग्रह में एक विशिष्ट Portion का इंडेक्स निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | संग्रह में खोजने के लिए Portion। |

**रिटर्न मान:**
int - यदि संग्रह में आइटम मिलता है तो उसका इंडेक्स; अन्यथा -1।
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

निर्दिष्ट इंडेक्स पर संग्रह में एक Portion डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शून्य-आधारित इंडेक्स जहाँ Portion डाली जानी चाहिए। |
| value | [IPortion](../../com.aspose.slides/iportion) | डाली जाने वाली Portion। |
### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्व हटाता है।

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान मौजूद है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | वस्तु को [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजने के लिए। |

**रिटर्न मान:**
boolean - यदि आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाया जाता है तो true; अन्यथा false।
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

विशिष्ट वस्तु की पहली घटना को [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | वस्तु को [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाने के लिए। |

**रिटर्न मान:**
boolean - यदि आइटम को [IGenericCollection](../../com.aspose.slides/igenericcollection) से सफलतापूर्वक हटाया गया तो true; अन्यथा false। यह मेथड भी false लौटाता है यदि आइटम मूल [IGenericCollection](../../com.aspose.slides/igenericcollection) में नहीं मिला।
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट इंडेक्स पर तत्व हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने वाले तत्व का शून्य-आधारित इंडेक्स। |