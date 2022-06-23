## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Add new effect to the end of sequence.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shape | IShape | Shape object [`IShape`](../../../aspose.slides/ishape) for adding an effect |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

New effect object [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../aspose.slides)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Add new animation effect for paragraph to the end of sequence.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph object [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

New effect object [`IEffect`](../../ieffect)

### Examples

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
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../aspose.slides)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Adds the new chart animation effect for category or series to the end of sequence.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

New effect object [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../aspose.slides)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Adds the new chart animation effect for elements in category or series to the end of sequence.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index of chart series Int32 |
| categoriesIndex | Int32 | Index of category Int32 |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Return Value

New effect object [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../aspose.slides)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
