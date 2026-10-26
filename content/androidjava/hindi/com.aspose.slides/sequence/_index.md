---
title: Sequence
second_title: Android के लिए Aspose.Slides – Java API संदर्भ
description: प्रभावों के क्रम संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/sequence/
---
**विरासत:**  
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**  
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)  
```
public final class Sequence implements ISequence
```

क्रम का प्रतिनिधित्व करता है (प्रभावों का संग्रह)।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getCount()](#getCount--) | सीक्वेंस में प्रभावों की संख्या लौटाता है। |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | संग्रह से निर्दिष्ट प्रभाव हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह से एक प्रभाव हटाता है। |
| [clear()](#clear--) | संग्रह से सभी प्रभाव हटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर एक प्रभाव लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से इटरेंट करने वाला एनीमेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | संपूर्ण संग्रह के लिए एक java इटरेटर लौटाता है। |
| [getTriggerShape()](#getTriggerShape--) | INTERACTIVE सीक्वेंस के लिए shape लक्ष्य लौटाता है या सेट करता है। |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | INTERACTIVE सीक्वेंस के लिए shape लक्ष्य लौटाता है या सेट करता है। |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | निर्दिष्ट shape के लिए प्रभाव हटाता है। |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | निर्दिष्ट shape के लिए प्रभावों की array लौटाता है। |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | निर्दिष्ट पैराग्राफ के लिए प्रभावों की array लौटाता है। |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | निर्दिष्ट shape के लिए प्रभावों की गिनती लौटाता है। |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | सीक्वेंस के अंत में नया प्रभाव जोड़ता है। |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | सीक्वेंस के अंत में पैराग्राफ के लिए नया एनीमेशन प्रभाव जोड़ता है। |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | क्रम के अंत में श्रेणी या श्रृंखला के लिए नया चार्ट एनीमेशन प्रभाव जोड़ता है। |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | क्रम के अंत में श्रेणी या श्रृंखला में तत्वों के लिए नया चार्ट एनीमेशन प्रभाव जोड़ता है। |

### getCount() {#getCount--}
```
public final int getCount()
```

सीक्वेंस में प्रभावों की संख्या लौटाता है। केवल पढ़ने योग्य int।

**रिटर्न:**  
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

संग्रह से निर्दिष्ट प्रभाव हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | हटाने योग्य प्रभाव। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

संग्रह से एक प्रभाव हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने योग्य प्रभाव का अनुक्रमणिका। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी प्रभाव हटाता है।

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

निर्दिष्ट अनुक्रमणिका पर एक प्रभाव लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व की अनुक्रमणिका। |

**रिटर्न:**  
[IEffect](../../com.aspose.slides/ieffect) – [IEffect](../../com.aspose.slides/ieffect) ऑब्जेक्ट।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

संग्रह के माध्यम से इटरेंट करने वाला एनीमेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> – संग्रह के माध्यम से इटरेंट करने के लिए उपयोग किया जाने वाला IGenericEnumerator।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

संपूर्ण संग्रह के लिए एक java इटरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> – संपूर्ण संग्रह के लिए java.util.Iterator।

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

INTERACTIVE सीक्वेंस के लिए shape लक्ष्य लौटाता है या सेट करता है। यदि सीक्वेंस इंटरैक्टिव नहीं है तो null लौटाता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**रिटर्न:**  
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

INTERACTIVE सीक्वेंस के लिए shape लक्ष्य लौटाता है या सेट करता है। यदि सीक्वेंस इंटरैक्टिव नहीं है तो null लौटाता है। पढ़ने/लिखने योग्य [IShape](../../com.aspose.slides/ishape)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

निर्दिष्ट shape के लिए प्रभाव हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

निर्दिष्ट shape के लिए प्रभावों की array लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**रिटर्न:**  
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

निर्दिष्ट पैराग्राफ के लिए प्रभावों की array लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**रिटर्न:**  
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

निर्दिष्ट shape के लिए प्रभावों की गिनती लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**रिटर्न:**  
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

सीक्वेंस के अंत में नया प्रभाव जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | प्रभाव जोड़ने के लिए Shape ऑब्जेक्ट [IShape](../../com.aspose.slides/ishape) |
| effectType | int | एनीमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनीमेशन प्रभाव के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**रिटर्न:**  
[IEffect](../../com.aspose.slides/ieffect) – नया प्रभाव ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

पैराग्राफ के लिए नया एनीमेशन प्रभाव सीक्वेंस के अंत में जोड़ता है।

---

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // प्रभाव जोड़ने के लिए पैराग्राफ चुनें
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // चयनित पैराग्राफ में Fly एनीमेशन प्रभाव जोड़ें
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | पैराग्राफ ऑब्जेक्ट [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | एनीमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनीमेशन प्रभाव के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**रिटर्न:**  
[IEffect](../../com.aspose.slides/ieffect) – नया प्रभाव ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

क्रम के अंत में श्रेणी या श्रृंखला के लिए नया चार्ट एनीमेशन प्रभाव जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | चार्ट ऑब्जेक्ट [IChart](../../com.aspose.slides/ichart) |
| type | int | एनीमेशन प्रभाव का प्रकार [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | इंडेक्स int |
| effectType | int | एनीमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनीमेशन प्रभाव के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**रिटर्न:**  
[IEffect](../../com.aspose.slides/ieffect) – नया प्रभाव ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

क्रम के अंत में श्रेणी या श्रृंखला में तत्वों के लिए नया चार्ट एनीमेशन प्रभाव जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | चार्ट ऑब्जेक्ट [IChart](../../com.aspose.slides/ichart) |
| type | int | एनीमेशन प्रभाव का प्रकार [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | चार्ट श्रृंखला का इंडेक्स int |
| categoriesIndex | int | श्रेणी का इंडेक्स int |
| effectType | int | एनीमेशन प्रभाव का प्रकार [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | एनीमेशन प्रभाव के उपप्रकार [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | प्रभाव का ट्रिगर प्रकार [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**रिटर्न:**  
[IEffect](../../com.aspose.slides/ieffect) – नया प्रभाव ऑब्जेक्ट [IEffect](../../com.aspose.slides/ieffect)