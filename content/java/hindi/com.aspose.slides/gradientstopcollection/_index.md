---
title: GradientStopCollection
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: ग्रेडिएंट स्टॉप्स के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/gradientstopcollection/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

ग्रेडिएंट स्टॉप्स का एक संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | एक संग्रह में ग्रेडिएंट स्टॉप्स की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | सूचकांक द्वारा ग्रेडिएंट स्टॉप लौटाता है। |
| [add(float position, Color color)](#add-float-java.awt.Color-) | एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह में निर्दिष्ट अनुक्रमणिका पर सम्मिलित करता है। |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह में निर्दिष्ट अनुक्रमणिका पर सम्मिलित करता है। |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह में निर्दिष्ट अनुक्रमणिका पर सम्मिलित करता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट अनुक्रमणिका पर ग्रेडिएंट स्टॉप को हटाता है। |
| [clear()](#clear--) | एक संग्रह से सभी ग्रेडिएंट स्टॉप्स को हटाता है। |
| [iterator()](#iterator--) | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समकालिक (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिकता रूट लौटाता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने-योग्य long।

**रिटर्न:**  
long

### size() {#size--}
```
public final int size()
```

एक संग्रह में ग्रेडिएंट स्टॉप्स की संख्या लौटाता है। केवल-पढ़ने-योग्य int।

**रिटर्न:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

सूचकांक द्वारा ग्रेडिएंट स्टॉप लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**  
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| color | java.awt.Color | नए ग्रेडिएंट स्टॉप का रंग। |

**रिटर्न:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का अनुक्रमणिका।

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| presetColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

**रिटर्न:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का अनुक्रमणिका।

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह के अंत में जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| schemeColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

**रिटर्न:**  
[IGradientStop](../../com.aspose.slides/igradientstop) - संग्रह में नए ग्रेडिएंट स्टॉप का अनुक्रमणिका।

### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह में निर्दिष्ट अनुक्रमणिका पर सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | संग्रह में वह अनुक्रमणिका जहाँ नया ग्रेडिएंट स्टॉप सम्मिलित किया जायेगा। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| color | java.awt.Color | नए ग्रेडिएंट स्टॉप का रंग। |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह में निर्दिष्ट अनुक्रमणिका पर सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | संग्रह में वह अनुक्रमणिका जहाँ नया ग्रेडिएंट स्टॉप सम्मिलित किया जायेगा। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| presetColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

एक नया ग्रेडिएंट स्टॉप बनाता है और इसे संग्रह में निर्दिष्ट अनुक्रमणिका पर सम्मिलित करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | संग्रह में वह अनुक्रमणिका जहाँ नया ग्रेडिएंट स्टॉप सम्मिलित किया जायेगा। |
| position | float | नए ग्रेडिएंट स्टॉप की स्थिति। |
| schemeColor | int | नए ग्रेडिएंट स्टॉप का रंग। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट अनुक्रमणिका पर ग्रेडिएंट स्टॉप को हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले ग्रेडिएंट स्टॉप की अनुक्रमणिका। |

### clear() {#clear--}
```
public final void clear()
```

एक संग्रह से सभी ग्रेडिएंट स्टॉप्स को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - संग्रह को इटररेट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - पूरे संग्रह के लिए एक java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक अनुक्रमणिका। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समकालिक (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने-योग्य boolean।

**रिटर्न:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालिकता रूट लौटाता है। केवल-पढ़ने-योग्य Object।

**रिटर्न:**  
java.lang.Object