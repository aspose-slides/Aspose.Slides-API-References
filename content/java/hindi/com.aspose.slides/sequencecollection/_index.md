---
title: SequenceCollection
second_title: Aspose.Slides के लिए जावा API रेफ़रेंस
description: इंटरैक्टिव अनुक्रमों का संग्रह दर्शाता है।
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

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCount()](#getCount--) | एक संग्रह में तत्वों की संख्या लौटाता है केवल पढ़ने योग्य int। |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | नया इंटरैक्टिव अनुक्रम जोड़ें। |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | निर्दिष्ट अनुक्रम को संग्रह से हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर अनुक्रम हटाता है। |
| [clear()](#clear--) | सभी अनुक्रमों को संग्रह से हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर एक अनुक्रम लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेट करने वाला एनेउमरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है। |
### getCount() {#getCount--}
```
public final int getCount()
```

एक संग्रह में तत्वों की संख्या लौटाता है केवल पढ़ने योग्य int।

**रिटर्न:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

नया इंटरैक्टिव अनुक्रम जोड़ें। पढ़ने/लिखने योग्य [Sequence](../../com.aspose.slides/sequence)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**रिटर्न:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

निर्दिष्ट अनुक्रम को संग्रह से हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | हटाने के लिए अनुक्रम। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट सूचकांक पर अनुक्रम हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | एक अनुक्रम का सूचकांक जिसे हटाया जाना चाहिए। |

### clear() {#clear--}
```
public final void clear()
```

सभी अनुक्रमों को संग्रह से हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

निर्दिष्ट सूचकांक पर एक अनुक्रम लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का सूचकांक। |

**रिटर्न:**
[ISequence](../../com.aspose.slides/isequence) - यह [ISequence](../../com.aspose.slides/isequence) ऑब्जेक्ट।
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला एनेउमरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - एक IGenericEnumerator जिसे संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटरेटर लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - एक java.util.Iterator जो पूरे संग्रह के लिए उपयोग किया जाता है।