---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides for Java API संदर्भ
description: इफ़ेक्ट व्यवहार के लिए टाइमिंग गुणों को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ibehaviorpropertycollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

इफेक्ट व्यवहार के लिए टाइमिंग गुणों को दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | संग्रह में एक नया प्रॉपर्टी जोड़ता है। |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | सूची में प्रॉपर्टी मान के द्वारा विशिष्ट आइटम का सूचकांक निर्धारित करता है। |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | निर्दिष्ट सूचकांक पर संग्रह में नई प्रॉपर्टी (निर्दिष्ट प्रॉपर्टी मान के साथ) सम्मिलित करता है। |
| [remove(String propertyValue)](#remove-java.lang.String-) | संग्रह से निर्दिष्ट प्रॉपर्टी हटाता है। |
| [contains(String propertyValue)](#contains-java.lang.String-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं। |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

संग्रह में एक नया प्रॉपर्टी जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | जोड़ने के लिए प्रॉपर्टी का मान। |
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

सूची में प्रॉपर्टी मान के द्वारा विशिष्ट आइटम का सूचकांक निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | प्रॉपर्टी का मान |

**रिटर्न:**
int - निर्दिष्ट मान वाली प्रॉपर्टी का सूचकांक
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

निर्दिष्ट सूचकांक पर संग्रह में नई प्रॉपर्टी (निर्दिष्ट प्रॉपर्टी मान के साथ) सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह सूचकांक जहाँ नई प्रॉपर्टी सम्मिलित की जानी चाहिए। |
| propertyValue | java.lang.String | जोड़ने के लिए प्रॉपर्टी का मान। |
### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

संग्रह से निर्दिष्ट प्रॉपर्टी हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | हटाने के लिए प्रॉपर्टी का मान। |

**रिटर्न:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो True, अन्यथा false
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजने के लिए प्रॉपर्टी का मान। |

**रिटर्न:**
boolean - यदि propertyValue [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाया जाता है तो true, अन्यथा false