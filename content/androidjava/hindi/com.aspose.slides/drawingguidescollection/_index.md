---
title: DrawingGuidesCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: समायोज्य ड्रॉइंग गाइड्स का एक संग्रह प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/drawingguidescollection/
---
**विरासत:**
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Represents a collection of the adjustable drawing guides. → **समायोज्य ड्रॉइंग गाइड्स का संग्रह दर्शाता है।**

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा ड्रॉइंग गाइड लौटाता है। |
| [add(byte orientation, float position)](#add-byte-float-) | संग्रह के अंत में ड्रॉइंग गाइड जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर ड्रॉइंग गाइड हटाता है। |
| [clear()](#clear--) | संग्रह से सभी तत्व हटाता है। |
| [iterator()](#iterator--) | एक एन्यूमरेटर लौटाता है जो संग्रह को इटरिट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटरेटर लौटाता है। |
| [getCount()](#getCount--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है। |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

इंडेक्स द्वारा ड्रॉइंग गाइड लौटाता है। केवल पढ़ने योग्य [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

संग्रह के अंत में ड्रॉइंग गाइड जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| orientation | byte | ड्रॉइंग गाइड की अभिविन्यास। |
| position | float | बिंदुओं में ड्रॉइंग गाइड की स्थिति। |

**वापसी:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर ड्रॉइंग गाइड हटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | ड्रॉइंग गाइड का इंडेक्स जिसे हटाया जाना चाहिए। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी तत्व हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

एक एन्यूमरेटर लौटाता है जो संग्रह को इटरिट करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - एक IGenericEnumerator जो संग्रह को इटरिट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

पूरे संग्रह के लिए जावा इटरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - एक java.util.Iterator पूरे संग्रह के लिए।
### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में तत्वों की संख्या लौटाता है। केवल पढ़ने योग्य int.

**वापसी:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारंभिक इंडेक्स। |