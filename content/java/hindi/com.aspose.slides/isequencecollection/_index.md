---
title: ISequenceCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: इंटरैक्टिव अनुक्रमों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isequencecollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

इंटरैक्टिव अनुक्रमों के संग्रह का प्रतिनिधित्व करता है।
## Methods

| मेथड | विवरण |
| --- | --- |
| [getCount()](#getCount--) | केवल पढ़ने योग्य int. संग्रह में तत्वों की संख्या लौटाता है। |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | नया इंटरैक्टिव अनुक्रम जोड़ें। |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | संग्रह से निर्दिष्ट अनुक्रम हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर अनुक्रम हटाता है। |
| [clear()](#clear--) | संग्रह से सभी अनुक्रम हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर एक अनुक्रम लौटाता है। |
### getCount() {#getCount--}
```
public abstract int getCount()
```


केवल पढ़ने योग्य int. संग्रह में तत्वों की संख्या लौटाता है।

**रिटर्न:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


नया इंटरैक्टिव अनुक्रम जोड़ें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) |

**रिटर्न:**
[ISequence](../../com.aspose.slides/isequence) - नया अनुक्रम [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


संग्रह से निर्दिष्ट अनुक्रम हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | हटाने के लिए अनुक्रम। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


निर्दिष्ट सूचकांक पर अनुक्रम हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | संग्रह में तत्व का सूचकांक int |

### clear() {#clear--}
```
public abstract void clear()
```


संग्रह से सभी अनुक्रम हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


निर्दिष्ट सूचकांक पर एक अनुक्रम लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | सूचकांक। |

**रिटर्न:**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence) ऑब्जेक्ट।