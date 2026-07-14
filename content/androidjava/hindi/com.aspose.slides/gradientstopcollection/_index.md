---
title: GradientStopCollection
second_title: Aspose.Slides Android के लिये Java API संदर्भ
description: ग्रेडिएंट स्टॉप्स का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/gradientstopcollection/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)  
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

ग्रेडिएंट स्टॉप्स का एक संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | संग्रह में ग्रेडिएंट स्टॉप्स की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा ग्रेडिएंट स्टॉप लौटाता है। |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में डालता है। |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में डालता है। |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में डालता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर ग्रेडिएंट स्टॉप हटाता है। |
| [clear()](#clear--) | संग्रह से सभी ग्रेडिएंट स्टॉप हटाता है। |
| [iterator()](#iterator--) | एक एन्यूमरेटर लौटाता है जो संग्रह को दोहराता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java इटररेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | संकेत देता है कि क्या संग्रह तक पहुंच समन्वित (थ्रेड-सुरक्षित) है। |
| [getSyncRoot()](#getSyncRoot--) | एक समन्वयन मूल (सिंकिंग रूट) लौटाता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. केवल पढ़ने योग्य long.

**रिटर्न:**  
long

### size() {#size--}
```
public final int size()
```

संग्रह में ग्रेडिएंट स्टॉप्स की संख्या लौटाता है। केवल पढ़ने योग्य int।

**रिटर्न:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

इंडेक्स द्वारा ग्रेडिएंट स्टॉप लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**  
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| color | java.lang.Integer | नए ग्रेडिएंट स्टॉप का रंग। |

**रिटर्न:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का सूचकांक।

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| presetColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

**रिटर्न:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का सूचकांक।

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| schemeColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

**रिटर्न:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का सूचकांक।

### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जहाँ नया ग्रेडिएंट स्टॉप डाला जाएगा। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| color | java.lang.Integer | नए ग्रेडिएंट स्टॉप का रंग। |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जहाँ नया ग्रेडिएंट स्टॉप डाला जाएगा। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| presetColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

नया ग्रेडिएंट स्टॉप बनाता है और इसे निर्दिष्ट इंडेक्स पर संग्रह में डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जहाँ नया ग्रेडिएंट स्टॉप डाला जाएगा। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| schemeColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर ग्रेडिएंट स्टॉप हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले ग्रेडिएंट स्टॉप का इंडेक्स। |

### clear() {#clear--}
```
public final void clear()
```

सभी ग्रेडिएंट स्टॉप्स को संग्रह से हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

एक एन्यूमरेटर लौटाता है जो संग्रह को दोहराता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - संग्रह को दोहराने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

पूरे संग्रह के लिए एक java इटररेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - पूरे संग्रह के लिए एक java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे। |
| index | int | लक्ष्य ऐरे में प्रारंभिक इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

संकेत देता है कि क्या संग्रह तक पहुंच समन्वित (थ्रेड-सुरक्षित) है। केवल पढ़ने योग्य boolean।

**रिटर्न:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समन्वयन मूल (सिंकिंग रूट) लौटाता है। केवल पढ़ने योग्य Object।

**रिटर्न:**  
java.lang.Object