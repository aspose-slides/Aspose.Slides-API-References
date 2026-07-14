---
title: ControlCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: ActiveX नियंत्रणों का संग्रह।
type: docs
url: /hi/com.aspose.slides/controlcollection/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX नियंत्रणों का संग्रह।

## विधियाँ

| Method | Description |
| --- | --- |
| [size()](#size--) | कलेक्शन में ऑब्जेक्ट्स की संख्या लौटाता है। |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | कलेक्शन में एक नया नियंत्रण बनाता और जोड़ता है। |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | कलेक्शन से एक ActiveX नियंत्रण हटाता है। |
| [removeAt(int index)](#removeAt-int-) | कलेक्शन में निर्दिष्ट स्थिति पर संग्रहीत ActiveX नियंत्रण हटाता है। |
| [clear()](#clear--) | कलेक्शन से सभी नियंत्रण हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट स्थिति पर नियंत्रण लौटाता है। |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटरेट करने वाला ए़न्यूमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिए जावा इटरटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | पूरे कलेक्शन को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | कलेक्शन तक पहुँच समकालिक (थ्रेड-सेफ) है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | समकालिकता रूट लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

कलेक्शन में ऑब्जेक्ट्स की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

कलेक्शन में एक नया नियंत्रण बनाता और जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| controlType | int | जोड़ने के लिए नियंत्रण का प्रकार। |
| x | float | आकृति फ्रेम के बाएँ पक्ष के लिए X-निर्देशांक। |
| y | float | आकृति फ्रेम के शीर्ष पक्ष के लिए Y-निर्देशांक। |
| width | float | आकृति फ्रेम की चौड़ाई। |
| height | float | आकृति फ्रेम की ऊँचाई। |

**रिटर्न:**
[IControl](../../com.aspose.slides/icontrol) - बनाया गया नियंत्रण।

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

कलेक्शन से एक ActiveX नियंत्रण हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | हटाने के लिए एक नियंत्रण। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

कलेक्शन में निर्दिष्ट स्थिति पर संग्रहीत ActiveX नियंत्रण हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए नियंत्रण का सूचकांक। |

### clear() {#clear--}
```
public final void clear()
```

कलेक्शन से सभी नियंत्रण हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

निर्दिष्ट स्थिति पर नियंत्रण लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नियंत्रण का सूचकांक। |

**रिटर्न:**
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

कलेक्शन के माध्यम से इटरेट करने वाला ए़न्यूमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

पूरे कलेक्शन के लिए जावा इटरटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

पूरे कलेक्शन को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे |
| index | int | लक्ष्य एरे में सूचकांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

कलेक्शन तक पहुँच समकालिक (थ्रेड-सेफ) है या नहीं, यह दर्शाने वाला मान लौटाता है। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समकालिकता रूट लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject