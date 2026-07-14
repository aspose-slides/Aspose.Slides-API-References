---
title: SequenceCollection
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: इंटरैक्टिव अनुक्रमों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/sequencecollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

इंटरैक्टिव अनुक्रमों का संग्रह दर्शाता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getCount()](#getCount--) | किसी संग्रह में तत्वों की संख्या लौटाता है केवल-पढ़ने योग्य int। |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | नया इंटरैक्टिव अनुक्रम जोड़ता है। |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | किसी संग्रह से निर्दिष्ट अनुक्रम को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर अनुक्रम को हटाता है। |
| [clear()](#clear--) | किसी संग्रह से सभी अनुक्रमों को हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर एक अनुक्रम लौटाता है। |
| [iterator()](#iterator--) | किसी संग्रह को पार करने वाला एनोमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java इटररेटर लौटाता है। |
### getCount() {#getCount--}
```
public final int getCount()
```

किसी संग्रह में तत्वों की संख्या लौटाता है केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

नया इंटरैक्टिव अनुक्रम जोड़ता है। पढ़ें/लिखें [Sequence](../../com.aspose.slides/sequence)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**रिटर्न:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

किसी संग्रह से निर्दिष्ट अनुक्रम को हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | हटाने के लिए अनुक्रम। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर अनुक्रम को हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले अनुक्रम का इंडेख़्स। |

### clear() {#clear--}
```
public final void clear()
```

किसी संग्रह से सभी अनुक्रमों को हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

निर्दिष्ट इंडेक्स पर एक अनुक्रम लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | तत्व का इंडेख़्स। |

**रिटर्न:**
[ISequence](../../com.aspose.slides/isequence) - यह [ISequence](../../com.aspose.slides/isequence) ऑब्जेक्ट।
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

एक एनोमरेटर लौटाता है जो संग्रह को पार करने के लिए उपयोग किया जा सकता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

एक java इटररेटर लौटाता है जो पूरे संग्रह के लिए है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - एक java.util.Iterator पूरा संग्रह के लिए।