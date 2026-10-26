---
title: IBehaviorCollection
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: व्यवहार प्रभावों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ibehaviorcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

व्यवहार प्रभावों का संग्रह दर्शाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर एक व्यवहार लौटाता है। |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | निर्दिष्ट इंडेक्स पर एक व्यवहार लौटाता है। |
| [getCount()](#getCount--) | एक संग्रह में व्यवहारों की संख्या लौटाता है। |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | एक संग्रह में नया व्यवहार जोड़ें। |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | सूची में किसी विशिष्ट वस्तु का इंडेक्स निर्धारित करता है। |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | निर्दिष्ट इंडेक्स पर एक संग्रह में नया व्यवहार सम्मिलित करता है। |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | संग्रह से निर्दिष्ट व्यवहार को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर संग्रह से व्यवहार हटाता है। |
| [clear()](#clear--) | संग्रह से सभी व्यवहार हटाता है। |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशेष मान है या नहीं। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
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
public abstract void set_Item(int index, IBehavior value)
```

निर्दिष्ट इंडेक्स पर एक व्यवहार लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वापसी के लिए व्यवहार का इंडेक्स। |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### getCount() {#getCount--}
```
public abstract int getCount()
```

एक संग्रह में व्यवहारों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

एक संग्रह में नया व्यवहार जोड़ें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | जोड़ने के लिए व्यवहार। |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

सूची में किसी विशिष्ट वस्तु का इंडेक्स निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | सूची में स्थित करने वाला वस्तु। |

**रिटर्न:**
int - यदि सूची में वस्तु पाई जाती है तो उसका इंडेक्स; अन्यथा -1।
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

निर्दिष्ट इंडेक्स पर एक संग्रह में नया व्यवहार सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए व्यवहार को सम्मिलित करने के लिए इंडेक्स। |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | सम्मिलित करने के लिए व्यवहार। |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

संग्रह से निर्दिष्ट व्यवहार को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | हटाने के लिए व्यवहार। |

**रिटर्न:**
boolean - यदि कोई व्यवहार सफलतापूर्वक हटाया गया हो तो True, अन्यथा boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर संग्रह से व्यवहार हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए व्यवहार का इंडेक्स। |
### clear() {#clear--}
```
public abstract void clear()
```

सभी व्यवहारों को संग्रह से हटाता है।
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | वस्तु को [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजने के लिए। |

**रिटर्न:**
boolean - यदि वस्तु [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाई जाती है तो true, अन्यथा false।