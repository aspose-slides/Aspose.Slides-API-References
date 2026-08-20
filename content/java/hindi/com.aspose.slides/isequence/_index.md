---
title: ISequence
second_title: Aspose.Slides के लिए Java API संदर्भ
description: इफ़ेक्ट्स के अनुक्रम संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isequence/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

एक अनुक्रम (इफ़ेक्ट्स का संग्रह) का प्रतिनिधित्व करता है।

## विधियां

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | एक अनुक्रम में इफ़ेक्ट्स की संख्या लौटाता है। |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | किसी संग्रह से निर्दिष्ट इफ़ेक्ट को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | किसी संग्रह से इफ़ेक्ट को हटाता है। |
| [clear()](#clear--) | किसी संग्रह से सभी इफ़ेक्ट्स को हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर इफ़ेक्ट लौटाता है। |
| [getTriggerShape()](#getTriggerShape--) | INTERACTIVE अनुक्रम के लिए shape लक्ष्य को प्राप्त या सेट करता है। |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | INTERACTIVE अनुक्रम के लिए shape लक्ष्य को प्राप्त या सेट करता है। |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | निर्दिष्ट shape के लिए इफ़ेक्ट हटाता है। |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | निर्दिष्ट shape के लिए इफ़ेक्ट्स की एरे लौटाता है। |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | निर्दिष्ट पैराग्राफ के लिए इफ़ेक्ट्स की एरे लौटाता है। |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | निर्दिष्ट shape के लिए इफ़ेक्ट्स की गिनती लौटाता है। |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | अनुक्रम के अंत में नया इफ़ेक्ट जोड़ता है। |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | पैराग्राफ के लिए नया एनीमेशन इफ़ेक्ट अनुक्रम के अंत में जोड़ता है। |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | श्रेणी या श्रृंखला के लिए नया चार्ट एनीमेशन इफ़ेक्ट अनुक्रम के अंत में जोड़ता है। |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | श्रेणी या श्रृंखला में तत्वों के लिए नया चार्ट एनीमेशन इफ़ेक्ट अनुक्रम के अंत में जोड़ता है। |

### getCount() {#getCount--}
```
public abstract int getCount()
```

एक अनुक्रम में इफ़ेक्ट्स की संख्या लौटाता है। केवल पढ़ने योग्य int.

**वापसी:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

किसी संग्रह से निर्दिष्ट इफ़ेक्ट को हटाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | हटाने के लिए इफ़ेक्ट। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

किसी संग्रह से इफ़ेक्ट को हटाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | हटाने के लिए इफ़ेक्ट का इंडेक्स int |

### clear() {#clear--}
```
public abstract void clear()
```

सभी इफ़ेक्ट्स को किसी संग्रह से हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर इफ़ेक्ट लौटाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | तत्व का इंडेक्स। |

**वापसी:**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect) ऑब्जेक्ट।

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

INTERACTIVE अनुक्रम के लिए shape लक्ष्य को प्राप्त या सेट करता है। यदि अनुक्रम इंटरैक्टिव नहीं है तो null लौटाता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**वापसी:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

INTERACTIVE अनुक्रम के लिए shape लक्ष्य को प्राप्त या सेट करता है। यदि अनुक्रम इंटरैक्टिव नहीं है तो null लौटाता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

निर्दिष्ट shape के लिए इफ़ेक्ट हटाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

निर्दिष्ट shape के लिए इफ़ेक्ट्स की एरे लौटाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) |

**वापसी:**
com.aspose.slides.IEffect[] - इफ़ेक्ट्स की एरे [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

निर्दिष्ट पैराग्राफ के लिए इफ़ेक्ट्स की एरे लौटाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph ऑब्जेक्ट [IParagraph](../../com.aspose.slides/iparagraph) |

**वापसी:**
com.aspose.slides.IEffect[] - इफ़ेक्ट्स की एरे [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

निर्दিষ্ট shape के लिए इफ़ेक्ट्स की गिनती लौटाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) |

**वापसी:**
int - इफ़ेक्ट्स की गिनती int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

अनुक्रम के अंत में नया इफ़ेक्ट जोड़ता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | इफ़ेक्ट जोड़ने के लिए Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) |
| effectType | int | एनिमेशन इफ़ेक्ट का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनिमेशन इफ़ेक्ट के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | इफ़ेक्ट का ट्रिगर टाइप [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**वापसी:**
[IEffect](../../com.aspose.slides/ieffect) - नया इफ़ेक्ट ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

पैराग्राफ के लिए नया एनीमेशन इफ़ेक्ट अनुक्रम के अंत में जोड़ता है।

--------------------

> ``` 
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // इफ़ेक्ट जोड़ने के लिए पैराग्राफ चुनें
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // चयनित पैराग्राफ में Fly एनीमेशन इफ़ेक्ट जोड़ें
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph ऑब्जेक्ट [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | एनिमेशन इफ़ेक्ट का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनिमेशन इफ़ेक्ट के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | इफ़ेक्ट का ट्रिगर टाइप [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**वापसी:**
[IEffect](../../com.aspose.slides/ieffect) - नया इफ़ेक्ट ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

श्रेणी या श्रृंखला के लिए नया चार्ट एनीमेशन इफ़ेक्ट अनुक्रम के अंत में जोड़ता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart ऑब्जेक्ट [IChart](../../com.aspose.slides/ichart) |
| type | int | एनिमेशन इफ़ेक्ट का प्रकार [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | इंडेक्स int |
| effectType | int | एनिमेशन इफ़ेक्ट का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनिमेशन इफ़ेक्ट के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | इफ़ेक्ट का ट्रिगर टाइप [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**वापसी:**
[IEffect](../../com.aspose.slides/ieffect) - नया इफ़ेक्ट ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

श्रेणी या श्रृंखला में तत्वों के लिए नया चार्ट एनीमेशन इफ़ेक्ट अनुक्रम के अंत में जोड़ता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart ऑब्जेक्ट [IChart](../../com.aspose.slides/ichart) |
| type | int | एनिमेशन इफ़ेक्ट का प्रकार [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | चार्ट श्रृंखला का इंडेक्स int |
| categoriesIndex | int | श्रेणी का इंडेक्स int |
| effectType | int | एनिमेशन इफ़ेक्ट का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनिमेशन इफ़ेक्ट के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | इफ़ेक्ट का ट्रिगर टाइप [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**वापसी:**
[IEffect](../../com.aspose.slides/ieffect) - नया इफ़ेक्ट ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)