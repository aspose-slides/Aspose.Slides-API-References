---
title: TextAnimationCollection
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: टेक्स्ट एनीमेशन के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/textanimationcollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

टेक्स्ट एनीमेशन के संग्रह का प्रतिनिधित्व करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## विधियां

| विधि | विवरण |
| --- | --- |
| [size()](#size--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [add()](#add--) | संग्रह में नया टेक्स्ट एनीमेशन जोड़ता है। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा तत्व लौटाता है। |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | सभी तत्व लौटाता है |
| [iterator()](#iterator--) | एक एनोमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृत्ति करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटर्रेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट ऐरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समक्रमण मूल लौटाता है। |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


संग्रह में तत्वों की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**वापसी:**
int
### add() {#add--}
```
public final TextAnimation add()
```


संग्रह में नया टेक्स्ट एनीमेशन जोड़ता है।

**वापसी:**
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


इंडेक्स द्वारा तत्व लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


सभी तत्व लौटाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) to remove. |

**वापसी:**
com.aspose.slides.ITextAnimation[] - Array of [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


एक एनोमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृत्ति करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


पूरे संग्रह के लिए जावा इटर्रेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


संग्रह से सभी तत्व निर्दिष्ट ऐरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | भरण के लिए Array। |
| index | int | लक्ष्य Array में प्रारंभिक स्थिति। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सुरक्षित) है या नहीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


एक समक्रमण मूल लौटाता है। केवल-पढ़ने योग्य Object.

**वापसी:**
java.lang.Object