---
title: AddEffect
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 90
url: /net/aspose.slides.animation/sequence/addeffect/
---
## Sequence.AddEffect method (1 of 4)

Add new animation effect for paragraph to the end of sequence.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| parameter | description |
| --- | --- |
| paragraph | Paragraph object [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

## Return Value

New effect object [`IEffect`](../../ieffect)

## Examples

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // select paragraph to add effect
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // add Fly animation effect to selected paragraph
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### See Also

* interface [IEffect](../../ieffect)
* interface [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## Sequence.AddEffect method (2 of 4)

Add new effect to the end of sequence.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| parameter | description |
| --- | --- |
| shape | Shape object [`IShape`](../../../aspose.slides/ishape) for adding an effect |
| effectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

## Return Value

New effect object [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## Sequence.AddEffect method (3 of 4)

Adds the new chart animation effect for category or series to the end of sequence.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| parameter | description |
| --- | --- |
| chart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Index Int32 |
| effectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

## Return Value

New effect object [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

---

## Sequence.AddEffect method (4 of 4)

Adds the new chart animation effect for elements in category or series to the end of sequence.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| parameter | description |
| --- | --- |
| chart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Index of chart series Int32 |
| categoriesIndex | Index of category Int32 |
| effectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

## Return Value

New effect object [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* class [Sequence](../../sequence)
* namespace [Aspose.Slides.Animation](../../sequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
