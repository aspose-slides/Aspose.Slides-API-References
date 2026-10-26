---
title: TextAnimationCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: पाठ एनीमेशन के संग्रह का प्रतिनिधित्व करता है।
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

पाठ एनीमेशन का संग्रह दर्शाता है।

## निर्माता

| Constructor | Description |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |

## विधियाँ

| Method | Description |
| --- | --- |
| [size()](#size--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [add()](#add--) | संग्रह में नया पाठ एनीमेशन जोड़ता है। |
| [get_Item(int index)](#get-Item-int-) | सूचकांक द्वारा तत्व लौटाता है। |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | सभी तत्व लौटाता है। |
| [iterator()](#iterator--) | एक एन्न्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटेरेटर लौटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समक्रमण जड़ (रूट) लौटाता है। |

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

संग्रह में नया पाठ एनीमेशन जोड़ता है।

**वापसी:**
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)

### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```

सूचकांक द्वारा तत्व लौटाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```

सभी तत्व लौटाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) को हटाने के लिए। |

**वापसी:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) की ऐरे

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```

एक एन्न्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - एक IGenericEnumerator जिसे संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```

पूरे संग्रह के लिए जावा इटेरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - पूरा संग्रह के लिए एक java.util.Iterator।

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

संग्रह से सभी तत्व निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | भरने के लिए एरे। |
| index | int | लक्ष्य एरे में प्रारम्भिक स्थिति। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समक्रमित (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने योग्य boolean.

**वापसी:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समक्रमण जड़ (रूट) लौटाता है। केवल-पढ़ने योग्य Object.

**वापसी:**
java.lang.Object