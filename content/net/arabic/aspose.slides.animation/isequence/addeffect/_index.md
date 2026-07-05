---
title: AddEffect
second_title: Aspose.Sildes ل .NET مرجع API
description: إضافة تأثير جديد إلى نهاية التسلسل.
type: docs
weight: 50
url: /ar/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

إضافة تأثير جديد إلى نهاية التسلسل.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | IShape | كائن Shape [`IShape`](../../../aspose.slides/ishape) لإضافة تأثير |
| effectType | EffectType | نوع تأثير الرسوم المتحركة [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | الأنواع الفرعية لتأثير الرسوم المتحركة [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع الزناد للتأثير [`EffectTriggerType`](../../effecttriggertype) |

### قيمة الإرجاع

كائن تأثير جديد [`IEffect`](../../ieffect)

### انظر أيضًا

* واجهة [IEffect](../../ieffect)
* واجهة [IShape](../../../aspose.slides/ishape)
* تعداد [EffectType](../../effecttype)
* تعداد [EffectSubtype](../../effectsubtype)
* تعداد [EffectTriggerType](../../effecttriggertype)
* واجهة [ISequence](../../isequence)
* مساحة الأسماء [Aspose.Slides.Animation](../../isequence)
* تجميع [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

إضافة تأثير رسوم متحركة جديد للفقرة إلى نهاية التسلسل.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| paragraph | IParagraph | كائن Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | نوع تأثير الرسوم المتحركة [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | الأنواع الفرعية لتأثير الرسوم المتحركة [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع الزناد للتأثير [`EffectTriggerType`](../../effecttriggertype) |

### قيمة الإرجاع

كائن تأثير جديد [`IEffect`](../../ieffect)

### أمثلة

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // اختيار الفقرة لإضافة التأثير
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // إضافة تأثير Fly للفقرة المحددة
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### انظر أيضًا

* واجهة [IEffect](../../ieffect)
* واجهة [IParagraph](../../../aspose.slides/iparagraph)
* تعداد [EffectType](../../effecttype)
* تعداد [EffectSubtype](../../effectsubtype)
* تعداد [EffectTriggerType](../../effecttriggertype)
* واجهة [ISequence](../../isequence)
* مساحة الأسماء [Aspose.Slides.Animation](../../isequence)
* تجميع [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

يضيف تأثير الرسوم المتحركة للمخطط الجديد للفئة أو السلسلة إلى نهاية التسلسل.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chart | IChart | كائن Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | نوع تأثير الرسوم المتحركة [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | فهرس Int32 |
| effectType | EffectType | نوع تأثير الرسوم المتحركة [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | الأنواع الفرعية لتأثير الرسوم المتحركة [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع الزناد للتأثير [`EffectTriggerType`](../../effecttriggertype) |

### قيمة الإرجاع

كائن تأثير جديد [`IEffect`](../../ieffect)

### انظر أيضًا

* واجهة [IEffect](../../ieffect)
* واجهة [IChart](../../../aspose.slides.charts/ichart)
* تعداد [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* تعداد [EffectType](../../effecttype)
* تعداد [EffectSubtype](../../effectsubtype)
* تعداد [EffectTriggerType](../../effecttriggertype)
* واجهة [ISequence](../../isequence)
* مساحة الأسماء [Aspose.Slides.Animation](../../isequence)
* تجميع [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

يضيف تأثير الرسوم المتحركة للمخطط الجديد للعناصر في الفئة أو السلسلة إلى نهاية التسلسل.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chart | IChart | كائن Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | نوع تأثير الرسوم المتحركة [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | فهرس سلسلة المخطط Int32 |
| categoriesIndex | Int32 | فهرس الفئة Int32 |
| effectType | EffectType | نوع تأثير الرسوم المتحركة [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | الأنواع الفرعية لتأثير الرسوم المتحركة [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع الزناد للتأثير [`EffectTriggerType`](../../effecttriggertype) |

### قيمة الإرجاع

كائن تأثير جديد [`IEffect`](../../ieffect)

### انظر أيضًا

* واجهة [IEffect](../../ieffect)
* واجهة [IChart](../../../aspose.slides.charts/ichart)
* تعداد [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* تعداد [EffectType](../../effecttype)
* تعداد [EffectSubtype](../../effectsubtype)
* تعداد [EffectTriggerType](../../effecttriggertype)
* واجهة [ISequence](../../isequence)
* مساحة الأسماء [Aspose.Slides.Animation](../../isequence)
* تجميع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->