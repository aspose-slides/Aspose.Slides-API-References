---
title: AddEffect
second_title: Aspose.Sildes لـ .NET مرجع API
description: إضافة تأثير جديد إلى نهاية التسلسل.
type: docs
weight: 40
url: /ar/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

إضافة تأثير جديد إلى نهاية التسلسل.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | IShape | Shape object [`IShape`](../../../aspose.slides/ishape) for adding an effect |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### قيمة الإرجاع

كائن التأثير الجديد [`IEffect`](../../ieffect)

### انظر أيضًا

* الواجهة [IEffect](../../ieffect)
* الواجهة [IShape](../../../aspose.slides/ishape)
* تعداد [EffectType](../../effecttype)
* تعداد [EffectSubtype](../../effectsubtype)
* تعداد [EffectTriggerType](../../effecttriggertype)
* فئة [Sequence](../../sequence)
* مساحة الاسم [Aspose.Slides.Animation](../../sequence)
* تجميع [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

إضافة تأثير حركة جديد للفقرة إلى نهاية التسلسل.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| paragraph | IParagraph | Paragraph object [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### قيمة الإرجاع

كائن التأثير الجديد [`IEffect`](../../ieffect)

### أمثلة

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // اختيار الفقرة لإضافة تأثير
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // إضافة تأثير الحركة Fly إلى الفقرة المحددة
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### انظر أيضًا

* الواجهة [IEffect](../../ieffect)
* الواجهة [IParagraph](../../../aspose.slides/iparagraph)
* تعداد [EffectType](../../effecttype)
* تعداد [EffectSubtype](../../effectsubtype)
* تعداد [EffectTriggerType](../../effecttriggertype)
* فئة [Sequence](../../sequence)
* مساحة الاسم [Aspose.Slides.Animation](../../sequence)
* تجميع [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

إضافة تأثير الحركة الجديد للمخطط للفئة أو السلسلة إلى نهاية التسلسل.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | Index Int32 |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### قيمة الإرجاع

كائن التأثير الجديد [`IEffect`](../../ieffect)

### انظر أيضًا

* الواجهة [IEffect](../../ieffect)
* الواجهة [IChart](../../../aspose.slides.charts/ichart)
* تعداد [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* تعداد [EffectType](../../effecttype)
* تعداد [EffectSubtype](../../effectsubtype)
* تعداد [EffectTriggerType](../../effecttriggertype)
* فئة [Sequence](../../sequence)
* مساحة الاسم [Aspose.Slides.Animation](../../sequence)
* تجميع [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

إضافة تأثير الحركة الجديد للمخطط للعناصر في الفئة أو السلسلة إلى نهاية التسلسل.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chart | IChart | Chart object [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | Type of an animation effect [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | Index of chart series Int32 |
| categoriesIndex | Int32 | Index of category Int32 |
| effectType | EffectType | Type of an animation effect [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | Subtypes of animation effect [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | Trigger type of effect [`EffectTriggerType`](../../effecttriggertype) |

### قيمة الإرجاع

كائن التأثير الجديد [`IEffect`](../../ieffect)

### انظر أيضًا

* الواجهة [IEffect](../../ieffect)
* الواجهة [IChart](../../../aspose.slides.charts/ichart)
* تعداد [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* تعداد [EffectType](../../effecttype)
* تعداد [EffectSubtype](../../effectsubtype)
* تعداد [EffectTriggerType](../../effecttriggertype)
* فئة [Sequence](../../sequence)
* مساحة الاسم [Aspose.Slides.Animation](../../sequence)
* تجميع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->