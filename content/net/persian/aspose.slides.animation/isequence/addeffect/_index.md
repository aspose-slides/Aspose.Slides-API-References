---
title: AddEffect
second_title: Aspose.Sildes برای مرجع API .NET
description: افکت جدیدی به انتهای توالی اضافه می‌کند.
type: docs
weight: 50
url: /fa/aspose.slides.animation/isequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

افکت جدیدی به انتهای توالی اضافه می‌کند.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | IShape | شی Shape [`IShape`](../../../aspose.slides/ishape) برای افزودن یک افکت |
| effectType | EffectType | نوع افکت انیمیشن [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع تحریک افکت [`EffectTriggerType`](../../effecttriggertype) |

### مقدار بازگشت

شی افکت جدید [`IEffect`](../../ieffect)

### موارد مرتبط

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

افکت انیمیشن جدید برای پاراگراف به انتهای توالی اضافه می‌کند.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | IParagraph | شی Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | نوع افکت انیمیشن [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع تحریک افکت [`EffectTriggerType`](../../effecttriggertype) |

### مقدار بازگشت

شی افکت جدید [`IEffect`](../../ieffect)

### مثال‌ها

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // پاراگراف را برای افزودن افکت انتخاب کنید
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // افکت انیمیشن Fly را به پاراگراف انتخاب شده اضافه کنید
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### موارد مرتبط

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

افکت انیمیشن جدید نمودار برای دسته یا سری به انتهای توالی اضافه می‌کند.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | IChart | شی Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | نوع افکت انیمیشن [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | اندیس Int32 |
| effectType | EffectType | نوع افکت انیمیشن [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع تحریک افکت [`EffectTriggerType`](../../effecttriggertype) |

### مقدار بازگشت

شی افکت جدید [`IEffect`](../../ieffect)

### موارد مرتبط

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

افکت انیمیشن جدید نمودار برای عناصر در دسته یا سری به انتهای توالی اضافه می‌کند.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | IChart | شی Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | نوع افکت انیمیشن [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | اندیس سری نمودار Int32 |
| categoriesIndex | Int32 | اندیس دسته Int32 |
| effectType | EffectType | نوع افکت انیمیشن [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع تحریک افکت [`EffectTriggerType`](../../effecttriggertype) |

### مقدار بازگشت

شی افکت جدید [`IEffect`](../../ieffect)

### موارد مرتبط

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