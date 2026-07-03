---
title: AddEffect
second_title: Aspose.Sildes برای .NET مرجع API
description: افکت جدید را به انتهای توالی اضافه می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides.animation/sequence/addeffect/
---
## AddEffect(IShape, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_3}

افکت جدید را به انتهای توالی اضافه می‌کند.

```csharp
public IEffect AddEffect(IShape shape, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | IShape | شیء Shape [`IShape`](../../../aspose.slides/ishape) برای اضافه کردن افکت |
| effectType | EffectType | نوع افکت انیمیشن [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع فعال‌سازی افکت [`EffectTriggerType`](../../effecttriggertype) |

### مقدار بازگشت

شیء افکت جدید [`IEffect`](../../ieffect)

### موارد مرتبط

* رابط [IEffect](../../ieffect)
* رابط [IShape](../../../aspose.slides/ishape)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* کلاس [Sequence](../../sequence)
* فضای نام [Aspose.Slides.Animation](../../sequence)
* مجوعه [Aspose.Slides](../../../)

---

## AddEffect(IParagraph, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_2}

افکت انیمیشن جدید برای پاراگراف را به انتهای توالی اضافه می‌کند.

```csharp
public IEffect AddEffect(IParagraph paragraph, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | IParagraph | شیء Paragraph [`IParagraph`](../../../aspose.slides/iparagraph) |
| effectType | EffectType | نوع افکت انیمیشن [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع فعال‌سازی افکت [`EffectTriggerType`](../../effecttriggertype) |

### مقدار بازگشت

شیء افکت جدید [`IEffect`](../../ieffect)

### مثال‌ها

```csharp
[C#]
using(Presentation presentation = new Presentation(path + "input.pptx"))
{        
   // پاراگرافی را برای اضافه کردن افکت انتخاب کنید
   IAutoShape autoShape = (IAutoShape)presentation.Slides[0].Shapes[0];
   IParagraph paragraph = autoShape.TextFrame.Paragraphs[0];

   // افکت انیمیشن Fly را به پاراگراف انتخاب شده اضافه می‌کند
   IEffect effect = presentation.Slides[0].Timeline.MainSequence.AddEffect(
   paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
}
```

### موارد مرتبط

* رابط [IEffect](../../ieffect)
* رابط [IParagraph](../../../aspose.slides/iparagraph)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* کلاس [Sequence](../../sequence)
* فضای نام [Aspose.Slides.Animation](../../sequence)
* مجوعه [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMajorGroupingType, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect}

افکت جدید انیمیشن نمودار برای دسته یا سری را به انتهای توالی اضافه می‌کند.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMajorGroupingType type, int index, 
    EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | IChart | شیء Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMajorGroupingType | نوع افکت انیمیشن [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| index | Int32 | اندیس Int32 |
| effectType | EffectType | نوع افکت انیمیشن [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع فعال‌سازی افکت [`EffectTriggerType`](../../effecttriggertype) |

### مقدار بازگشت

شیء افکت جدید [`IEffect`](../../ieffect)

### موارد مرتبط

* رابط [IEffect](../../ieffect)
* رابط [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* کلاس [Sequence](../../sequence)
* فضای نام [Aspose.Slides.Animation](../../sequence)
* مجوعه [Aspose.Slides](../../../)

---

## AddEffect(IChart, EffectChartMinorGroupingType, int, int, EffectType, EffectSubtype, EffectTriggerType) {#addeffect_1}

افکت جدید انیمیشن نمودار برای عناصر در دسته یا سری را به انتهای توالی اضافه می‌کند.

```csharp
public IEffect AddEffect(IChart chart, EffectChartMinorGroupingType type, int seriesIndex, 
    int categoriesIndex, EffectType effectType, EffectSubtype subtype, 
    EffectTriggerType triggerType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | IChart | شیء Chart [`IChart`](../../../aspose.slides.charts/ichart) |
| type | EffectChartMinorGroupingType | نوع افکت انیمیشن [`EffectChartMinorGroupingType`](../../effectchartminorgroupingtype) |
| seriesIndex | Int32 | اندیس سری نمودار Int32 |
| categoriesIndex | Int32 | اندیس دسته Int32 |
| effectType | EffectType | نوع افکت انیمیشن [`EffectType`](../../effecttype) |
| subtype | EffectSubtype | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](../../effectsubtype) |
| triggerType | EffectTriggerType | نوع فعال‌سازی افکت [`EffectTriggerType`](../../effecttriggertype) |

### مقدار بازگشت

شیء افکت جدید [`IEffect`](../../ieffect)

### موارد مرتبط

* رابط [IEffect](../../ieffect)
* رابط [IChart](../../../aspose.slides.charts/ichart)
* enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype)
* enum [EffectType](../../effecttype)
* enum [EffectSubtype](../../effectsubtype)
* enum [EffectTriggerType](../../effecttriggertype)
* کلاس [Sequence](../../sequence)
* فضای نام [Aspose.Slides.Animation](../../sequence)
* مجوعه [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->