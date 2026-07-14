---
title: ISequenceCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: इंटरैक्टिव अनुक्रमों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isequencecollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

इंटरैक्टिव अनुक्रमों का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCount()](#getCount--) | एक संग्रह में तत्वों की संख्या लौटाता है केवल पढ़ने योग्य int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | नई इंटरैक्टिव अनुक्रम जोड़ें। |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | निर्दिष्ट अनुक्रम को संग्रह से हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट अनुक्रमांक पर अनुक्रम को हटाता है। |
| [clear()](#clear--) | सभी अनुक्रमों को संग्रह से हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर एक अनुक्रम लौटाता है। |

### getCount() {#getCount--}
```
public abstract int getCount()
```

एक संग्रह में तत्वों की संख्या लौटाता है केवल पढ़ने योग्य int.

**वापसी:**
int

### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

नई इंटरैक्टिव अनुक्रम जोड़ें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) |

**वापसी:**
[ISequence](../../com.aspose.slides/isequence) - नई अनुक्रम [ISequence](../../com.aspose.slides/isequence)

### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

निर्दिष्ट अनुक्रम को संग्रह से हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | हटाने के लिए अनुक्रम। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट अनुक्रमांक पर अनुक्रम को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | संग्रह में तत्व का अनुक्रमांक int |

### clear() {#clear--}
```
public abstract void clear()
```

सभी अनुक्रमों को संग्रह से हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर एक अनुक्रम लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का अनुक्रमांक। |

**वापसी:**
[ISequence](../../com.aspose.slides/isequence) - यह [ISequence](../../com.aspose.slides/isequence) ऑब्जेक्ट।