---
title: DrawingGuidesCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: समायोज्य ड्राइंग गाइड्स के संग्रह को प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/drawingguidescollection/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

समायोज्य ड्राइंग गाइड्स का संग्रह प्रस्तुत करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा ड्राइंग गाइड को लौटाता है। |
| [add(byte orientation, float position)](#add-byte-float-) | संग्रह के अंत में ड्राइंग गाइड जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर ड्राइंग गाइड को हटाता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [iterator()](#iterator--) | एक इटरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटररेटर लौटाता है। |
| [getCount()](#getCount--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | संग्रह से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है। |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


इंडेक्स द्वारा ड्राइंग गाइड को लौटाता है। केवल पढ़ने योग्य [IDrawingGuide](../../com.aspose.slides/idrawingguide)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


संग्रह के अंत में ड्राइंग गाइड जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| orientation | byte | ड्राइंग गाइड की अभिविन्यास। |
| position | float | ड्राइंग गाइड का स्थिति बिंदुओं में। |

**वापसी:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


निर्दिष्ट इंडेक्स पर ड्राइंग गाइड को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले ड्राइंग गाइड का इंडेक्स। |

### clear() {#clear--}
```
public final void clear()
```


संग्रह से सभी तत्वों को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


एक इटरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - एक IGenericEnumerator जिसे संग्रह के माध्यम से इटररेट करने के लिये उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


पूरे संग्रह के लिए जावा इटररेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - एक java.util.Iterator जिसे पूरे संग्रह के लिये उपयोग किया जा सकता है।
### getCount() {#getCount--}
```
public final int getCount()
```


संग्रह में तत्वों की संख्या लौटाता है। केवल पढ़ने योग्य int।

**वापसी:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


संग्रह से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | लक्षित एरे। |
| index | int | लक्षित एरे में प्रारंभिक इंडेक्स। |