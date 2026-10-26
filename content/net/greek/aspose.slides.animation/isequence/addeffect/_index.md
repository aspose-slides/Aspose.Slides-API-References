---
title: AddEffect
second_title: Αναφορά API Aspose.Sildes για .NET
description: Προσθέτει νέο εφέ στο τέλος της ακολουθίας.
type: docs
weight: 50
url: /el/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

Προσθέτει νέο εφέ στο τέλος της ακολουθίας.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | IShape | Shape object [`IShape`](../../../aspose.slides/ishape) for adding an effect |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

Προσθέτει νέο εφέ κίνησης για παράγραφο στο τέλος της ακολουθίας.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph object [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [`IEffect`](../../ieffect)

### Examples

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // επιλέξτε παράγραφο για προσθήκη εφέ
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // προσθέστε το εφέ κίνησης Fly στην επιλεγμένη παράγραφο
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
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

Προσθέτει το νέο εφέ κίνησης διαγράμματος για κατηγορία ή σειρά στο τέλος της ακολουθίας.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

Προσθέτει το νέο εφέ κίνησης διαγράμματος για στοιχεία σε κατηγορία ή σειρά στο τέλος της ακολουθίας.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index of chart series Int32 |
| categoriesIndex | Int32 | Index of category Int32 |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### Τιμή Επιστροφής

Νέο αντικείμενο εφέ [`IEffect`](../../ieffect)

### See Also

* interface [IEffect](../../ieffect)
* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* interface [ISequence](../../isequence)
* namespace [Aspose.Slides.Animation](../../isequence)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->