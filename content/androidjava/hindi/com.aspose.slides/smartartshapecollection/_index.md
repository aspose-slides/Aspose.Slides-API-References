---
title: SmartArtShapeCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: SmartArt शैप्स का एक संग्रह दर्शाता है
type: docs
url: /hi/com.aspose.slides/smartartshapecollection/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)  
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

SmartArt शैप्स का संग्रह प्रतिनिधित्व करता है
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [size()](#size--) | कलेक्शन में वास्तविक रूप से सम्मिलित तत्वों की संख्या प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि कलेक्शन तक पहुंच सिंक्रनाइज़्ड (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक सिंक्रनाइज़ेशन रूट लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | कलेक्शन से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
| [iterator()](#iterator--) | एक एनेमरेटर लौटाता है जो कलेक्शन के माध्यम से इटरिट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे कलेक्शन के लिए एक जावा इटररेटर लौटाता है। |
### size() {#size--}
```
public final int size()
```

कलेक्शन में वास्तविक रूप से सम्मिलित तत्वों की संख्या प्राप्त करता है। केवल- पढ़ने योग्य int.

**वापसी:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल- पढ़ने योग्य [SmartArtShape](../../com.aspose.slides/smartartshape).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | शैप का इंडेक्स |

**वापसी:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - SmartArt शैप
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि कलेक्शन तक पहुंच सिंक्रनाइज़्ड (थ्रेड-सेफ़) है या नहीं। केवल- पढ़ने योग्य boolean.

**वापसी:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक सिंक्रनाइज़ेशन रूट लौटाता है। केवल- पढ़ने योग्य Object.

**वापसी:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

कलेक्शन से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक इंडेक्स। |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

एक एनेमरेटर लौटाता है जो कलेक्शन के माध्यम से इटरिट करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - एक IGenericEnumerator जिसे कलेक्शन के माध्यम से इटरिट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

पूरे कलेक्शन के लिए एक जावा इटररेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - पूरे कलेक्शन के लिए एक java.util.Iterator।