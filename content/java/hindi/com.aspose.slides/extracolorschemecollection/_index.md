---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: अतिरिक्त रंग योजनाओं का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/extracolorschemecollection/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

एक अतिरिक्त रंग योजनाओं के संग्रह का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | कलेक्शन में तत्वों की संख्या लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा एक रंग योजना लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटरेट करने वाला एन्यूमेरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिए एक java इटरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | कलेक्शन के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो यह दर्शाता है कि ArrayList तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक ऑब्जेक्ट लौटाता है जिसका उपयोग कलेक्शन तक पहुँच को सिंक्रनाइज़ करने के लिए किया जा सकता है। |
### size() {#size--}
```
public final int size()
```

कलेक्शन में तत्वों की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**रिटर्न:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

इंडेक्स द्वारा एक रंग योजना लौटाता है। केवल-पढ़ने योग्य [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject.

**रिटर्न:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
``` 
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

कलेक्शन के माध्यम से इटरेट करने वाला एन्यूमेरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

पूरे कलेक्शन के लिए एक java इटरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

कलेक्शन के सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित एरे। |
| index | int | एरे में प्रारंभिक इंडेक्स। |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो यह दर्शाता है कि ArrayList तक पहुँच सिंक्रनाइज़्ड (थ्रेड-सुरक्षित) है या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक ऑब्जेक्ट लौटाता है जिसका उपयोग कलेक्शन तक पहुँच को सिंक्रनाइज़ करने के लिए किया जा सकता है। केवल-पढ़ने योग्य Object.

एक सिंक्रनाइज़ेशन रूट लौटाता है। केवल-पढ़ने योग्य Object.

**रिटर्न:**
java.lang.Object