---
title: IPortionCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक भागों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/iportioncollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

एक भागों का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। |
| [getCount()](#getCount--) | संग्रह में वास्तविक रूप से निहित तत्वों की संख्या प्राप्त करता है। |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | संग्रह के अंत में एक Portion जोड़ता है। |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | संग्रह में एक विशिष्ट portion का अनुक्रमणिका निर्धारित करता है। |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | निर्दिष्ट अनुक्रमणिका पर संग्रह में एक Portion डालता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं। |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से किसी विशिष्ट वस्तु की पहली घटना को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट अनुक्रमणिका पर तत्व को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


संग्रह में वास्तविक रूप से निहित तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


संग्रह के अंत में एक Portion जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | संग्रह के अंत में जोड़े जाने वाला Portion। |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


संग्रह में एक विशिष्ट portion का अनुक्रमणिका निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | संग्रह में खोजी जाने वाली portion। |

**रिटर्न:**
int - यदि item संग्रह में पाया जाता है तो उसका अनुक्रमणिका; अन्यथा, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


निर्दिष्ट अनुक्रमणिका पर संग्रह में एक Portion डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह शून्य-आधारित अनुक्रमणिका जहाँ Portion को डाला जाना चाहिए। |
| value | [IPortion](../../com.aspose.slides/iportion) | डालने हेतु Portion। |

### clear() {#clear--}
```
public abstract void clear()
```


संग्रह से सभी तत्वों को हटाता है।

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजे जाने वाला ऑब्जेक्ट। |

**रिटर्न:**
boolean - true यदि item [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाया जाता है; अन्यथा, false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) से किसी विशिष्ट वस्तु की पहली घटना को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाए जाने वाला ऑब्जेक्ट। |

**रिटर्न:**
boolean - true यदि item [IGenericCollection](../../com.aspose.slides/igenericcollection) से सफलतापूर्वक हटाया गया हो; अन्यथा, false. यह विधि false भी लौटाती है यदि item मूल [IGenericCollection](../../com.aspose.slides/igenericcollection) में नहीं पाया जाता।
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


संग्रह में निर्दिष्ट अनुक्रमणिका पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित अनुक्रमणिका। |