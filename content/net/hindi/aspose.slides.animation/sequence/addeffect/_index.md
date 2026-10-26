---
title: AddEffect
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: क्रम के अंत में नया प्रभाव जोड़ें।
type: docs
weight: 40
url: /hi/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

अनुक्रम के अंत में नया प्रभाव जोड़ें।

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shape | IShape | प्रभाव जोड़ने के लिए Shape वस्तु [`IShape`](../../../aspose.slides/ishape) |
| effectType | EffectType | एनिमेशन प्रभाव का प्रकार [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | एनिमेशन प्रभाव के उपप्रकार [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | प्रभाव का ट्रिगर प्रकार [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

नया प्रभाव वस्तु [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

अनुक्रम के अंत में पैराग्राफ के लिए नया एनिमेशन प्रभाव जोड़ें।

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph वस्तु [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | एनिमेशन प्रभाव का प्रकार [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | एनिमेशन प्रभाव के उपप्रकार [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | प्रभाव का ट्रिगर प्रकार [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

नया प्रभाव वस्तु [`IEffect`](../../ieffect)

### Examples

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // प्रभाव जोड़ने के लिए पैराग्राफ का चयन करें
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // चयनित पैराग्राफ में Fly एनीमेशन प्रभाव जोड़ें
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### See Also

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

अनुक्रम के अंत में श्रेणी या श्रृंखला के लिए नया चार्ट एनिमेशन प्रभाव जोड़ता है।

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chart | IChart | चार्ट वस्तु [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | एनिमेशन प्रभाव का प्रकार [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | एनिमेशन प्रभाव का प्रकार [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | एनिमेशन प्रभाव के उपप्रकार [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | प्रभाव का ट्रिगर प्रकार [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

नया प्रभाव वस्तु [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

अनुक्रम के अंत में श्रेणी या श्रृंखला में तत्वों के लिए नया चार्ट एनिमेशन प्रभाव जोड़ता है।

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chart | IChart | चार्ट वस्तु [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | एनिमेशन प्रभाव का प्रकार [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | चार्ट श्रृंखला का Index Int32 |
| categoriesIndex | Int32 | श्रेणी का Index Int32 |
| effectType | EffectType | एनिमेशन प्रभाव का प्रकार [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | एनिमेशन प्रभाव के उपप्रकार [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | प्रभाव का ट्रिगर प्रकार [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

नया प्रभाव वस्तु [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->