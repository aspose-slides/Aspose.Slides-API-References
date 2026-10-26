---
title: ControlCollection
second_title: Aspose.Slides for Java API संदर्भ
description: ActiveX कंट्रोल्स का संग्रह।
type: docs
url: /hi/com.aspose.slides/controlcollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX कंट्रोल्स का संग्रह।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | कलेक्शन में वस्तुओं की संख्या लौटाता है। |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | एक नया कंट्रोल बनाकर कलेक्शन में जोड़ता है। |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | कलेक्शन से एक ActiveX कंट्रोल हटाता है। |
| [removeAt(int index)](#removeAt-int-) | कलेक्शन में निर्दिष्ट स्थिति पर संग्रहीत ActiveX कंट्रोल को हटाता है। |
| [clear()](#clear--) | कलेक्शन से सभी कंट्रोल हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट स्थिति पर कंट्रोल लौटाता है। |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटररेट करने वाला एक enumerator लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिए एक java iterator लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | पूरे कलेक्शन को निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि कलेक्शन तक पहुंच समक्रमित (थ्रेड-सेफ) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक synchronization root लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


कलेक्शन में वस्तुओं की संख्या लौटाता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```


एक नया कंट्रोल बनाकर कलेक्शन में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| controlType | int | जोड़ने के लिए कंट्रोल का प्रकार। |
| x | float | शेप के फ्रेम के बाएं पक्ष का X-निर्देशांक। |
| y | float | शेप के फ्रेम के शीर्ष पक्ष का Y-निर्देशांक। |
| width | float | शेप के फ्रेम की चौड़ाई। |
| height | float | शेप के फ्रेम की ऊँचाई। |

**रिटर्न:**
[IControl](../../com.aspose.slides/icontrol) - बनाया गया कंट्रोल।
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```


कलेक्शन से एक ActiveX कंट्रोल हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | हटाने के लिए कंट्रोल। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


कलेक्शन में निर्दिष्ट स्थिति पर संग्रहीत ActiveX कंट्रोल को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए कंट्रोल का इंडेक्स। |

### clear() {#clear--}
```
public final void clear()
```


कलेक्शन से सभी कंट्रोल हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```


निर्दिष्ट स्थिति पर कंट्रोल लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | कंट्रोल का इंडेक्स। |

**रिटर्न:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```


कलेक्शन के माध्यम से इटररेट करने वाला एक enumerator लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - कलेक्शन के माध्यम से इटररेट करने के लिए उपयोग किया जा सकने वाला IGenericEnumerator।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```


पूरे कलेक्शन के लिए एक java iterator लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - पूरे कलेक्शन के लिए एक java.util.Iterator।
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


पूरे कलेक्शन को निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य ऐरे |
| index | int | लक्ष्य ऐरे में इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि कलेक्शन तक पहुंच समक्रमित (थ्रेड-सेफ) है या नहीं। केवल पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक synchronization root लौटाता है। केवल पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject