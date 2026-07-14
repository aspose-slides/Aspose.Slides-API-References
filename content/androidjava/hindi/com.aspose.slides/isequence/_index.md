---
title: ISequence
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: प्रभावों के क्रम संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isequence/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

सीक्वेंस (प्रभावों का संग्रह) का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCount()](#getCount--) | सीक्वेंस में प्रभावों की संख्या लौटाता है। |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | कलेक्शन से निर्दिष्ट प्रभाव हटाता है। |
| [removeAt(int index)](#removeAt-int-) | कलेक्शन से एक प्रभाव हटाता है। |
| [clear()](#clear--) | कलेक्शन से सभी प्रभाव हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर एक प्रभाव लौटाता है। |
| [getTriggerShape()](#getTriggerShape--) | INTERACTIVE सीक्वेंस के लिए shape टारगेट को लौटाता या सेट करता है। |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | INTERACTIVE सीक्वेंस के लिए shape टारगेट को लौटाता या सेट करता है। |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | निर्दिष्ट shape के लिए प्रभाव हटाएं। |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | निर्दिष्ट shape के लिए प्रभावों की ऐरे लौटाता है। |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | निर्दिष्ट पैराग्राफ के लिए प्रभावों की ऐरे लौटाता है। |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | निर्दिष्ट shape के लिए प्रभावों की गिनती लौटाता है। |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | सीक्वेंस के अंत में नया प्रभाव जोड़ता है। |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | सीक्वेंस के अंत में पैराग्राफ के लिए नया एनीमेशन प्रभाव जोड़ता है। |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | सीक्वेंस के अंत में श्रेणी या श्रृंखला के लिए नया चार्ट एनीमेशन प्रभाव जोड़ता है। |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | सीक्वेंस के अंत में श्रेणी या श्रृंखला में तत्वों के लिए नया चार्ट एनीमेशन प्रभाव जोड़ता है। |

### getCount() {#getCount--}
```
public abstract int getCount()
```

सीक्वेंस में प्रभावों की संख्या लौटाता है। केवल-पढ़ने योग्य int.

**वापसी:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

कलेक्शन से निर्दिष्ट प्रभाव हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | हटाने के लिए प्रभाव। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

कलेक्शन से एक प्रभाव हटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए प्रभाव का इंडेक्स। |

### clear() {#clear--}
```
public abstract void clear()
```

कलेक्शन से सभी प्रभाव हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

निर्दिष्ट इंडेक्स पर एक प्रभाव लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int | तत्व का इंडेक्स। |

**वापसी:**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect) ऑब्जेक्ट

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

INTERACTIVE सीक्वेंस के लिए shape टारगेट को लौटाता या सेट करता है। यदि सीक्वेंस इंटरएक्टिव नहीं है तो null लौटाता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**वापसी:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

INTERACTIVE सीक्वेंस के लिए shape टारगेट को लौटाता या सेट करता है। यदि सीक्वेंस इंटरएक्टिव नहीं है तो null लौटाता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

निर्दिष्ट shape के लिए प्रभाव हटाएं।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

निर्दिष्ट shape के लिए प्रभावों की ऐरे लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) |

**वापसी:**
com.aspose.slides.IEffect[] - प्रभावों की ऐरे [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

निर्दिष्ट पैराग्राफ के लिए प्रभावों की ऐरे लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph ऑब्जेक्ट [IParagraph](../../com.aspose.slides/iparagraph) |

**वापसी:**
com.aspose.slides.IEffect[] - प्रभावों की ऐरे [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

निर्दिष्ट shape के लिए प्रभावों की गिनती लौटाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) |

**वापसी:**
int - प्रभावों की गिनती

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

सीक्वेंस के अंत में नया प्रभाव जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) प्रभाव जोड़ने के लिए |
| effectType | int | एनीमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनीमेशन प्रभाव के सबटाइप [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**वापसी:**
[IEffect](../../com.aspose.slides/ieffect) - नया प्रभाव ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

सीक्वेंस के अंत में पैराग्राफ के लिए नया एनीमेशन प्रभाव जोड़ता है।

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // प्रभाव जोड़ने के लिए पैराग्राफ चुनें
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // चयनित पैराग्राफ में Fly एनीमेशन प्रभाव जोड़ें
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph ऑब्जेक्ट [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | एनीमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनीमेशन प्रभाव के सबटाइप [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**वापसी:**
[IEffect](../../com.aspose.slides/ieffect) - नया प्रभाव ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

सीक्वेंस के अंत में श्रेणी या श्रृंखला के लिए नया चार्ट एनीमेशन प्रभाव जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart ऑब्जेक्ट [IChart](../../com.aspose.slides/ichart) |
| type | int | एनीमेशन प्रभाव का प्रकार [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | इंडेक्स int |
| effectType | int | एनीमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनीमेशन प्रभाव के सबटाइप [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**वापसी:**
[IEffect](../../com.aspose.slides/ieffect) - नया प्रभाव ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

सीक्वेंस के अंत में श्रेणी या श्रृंखला में तत्वों के लिए नया चार्ट एनीमेशन प्रभाव जोड़ता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart ऑब्जेक्ट [IChart](../../com.aspose.slides/ichart) |
| type | int | एनीमेशन प्रभाव का प्रकार [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | चार्ट श्रृंखला का इंडेक्स int |
| categoriesIndex | int | श्रेणी का इंडेक्स int |
| effectType | int | एनीमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनीमेशन प्रभाव के सबटाइप [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**वापसी:**
[IEffect](../../com.aspose.slides/ieffect) - नया प्रभाव ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)