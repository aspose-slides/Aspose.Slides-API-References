---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides एंड्रॉइड के लिए Java API रेफ़रेंस के माध्यम से
description: इफ़ेक्ट व्यवहार के लिए टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ibehaviorpropertycollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

इफ़ेक्ट व्यवहार के लिए टाइमिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | कलेक्शन में एक नई प्रॉपर्टी जोड़ता है। |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | सूची में प्रॉपर्टी मान के आधार पर किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है। |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | निर्दिष्ट इंडेक्स पर कलेक्शन में निर्दिष्ट प्रॉपर्टी मान के साथ नई प्रॉपर्टी सम्मिलित करता है। |
| [remove(String propertyValue)](#remove-java.lang.String-) | कलेक्शन से निर्दिष्ट प्रॉपर्टी को हटाता है। |
| [contains(String propertyValue)](#contains-java.lang.String-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में विशिष्ट मान है या नहीं। |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```


कलेक्शन में एक नई प्रॉपर्टी जोड़ता है।

**पैरामी터:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | जोड़ने के लिए प्रॉपर्टी का मान। |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```


सूची में प्रॉपर्टी मान के आधार पर किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | प्रॉपर्टी का मान |

**रिटर्न मान:**
int - निर्दिष्ट मान वाली प्रॉपर्टी का इंडेक्स
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```


निर्दिष्ट इंडेक्स पर कलेक्शन में निर्दिष्ट प्रॉपर्टी मान के साथ नई प्रॉपर्टी सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | इंडेक्स जहाँ नई प्रॉपर्टी सम्मिलित की जानी है। |
| propertyValue | java.lang.String | जोड़ने के लिए प्रॉपर्टी का मान। |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```


कलेक्शन से निर्दिष्ट प्रॉपर्टी को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | हटाने के लिए प्रॉपर्टी का मान। |

**रिटर्न मान:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई तो true

### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```


निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में विशिष्ट मान है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजने के लिए प्रॉपर्टी का मान। |

**रिटर्न मान:**
boolean - यदि propertyValue [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाया जाता है तो true; अन्यथा false.