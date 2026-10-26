---
title: AddEffect()
second_title: Aspose.Slides برای مرجع API C++
description: افکت جدیدی را به انتهای توالی اضافه می‌کند.
type: docs
weight: 144
url: /fa/aspose.slides.animation/isequence/addeffect/
---
## ISequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) متد

افکت جدیدی به انتهای دنباله اضافه می‌کند.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) شیء [IShape](../../../aspose.slides/ishape/) برای اضافه کردن یک افکت |
| effectType | [EffectType](../../effecttype/) | نوع افکت انیمیشن [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع تحریک افکت [EffectTriggerType](../../effecttriggertype/) |

### مقدار بازگشت

شیء افکت جدید [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) متد

افکت انیمیشن جدیدی برای پاراگراف به انتهای دنباله اضافه می‌کند.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) شیء [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | نوع افکت انیمیشن [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع تحریک افکت [EffectTriggerType](../../effecttriggertype/) |

### مقدار بازگشت

شیء افکت جدید [IEffect](../../ieffect/)

## توضیحات

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// انتخاب پاراگراف برای اضافه کردن افکت
auto autoShape = System::ExplicitCast<IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// افزودن افکت انیمیشن Fly به پاراگراف انتخاب شده
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Animation::EffectType::Fly, 
     Animation::EffectSubtype::Left, 
     Animation::EffectTriggerType::OnClick);
```

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) متد

افکت انیمیشن جدیدی برای دسته یا سری به انتهای دنباله اضافه می‌کند.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | شیء نمودار [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | نوع افکت انیمیشن [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | شاخص **int32_t** |
| effectType | [EffectType](../../effecttype/) | نوع افکت انیمیشن [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع تحریک افکت [EffectTriggerType](../../effecttriggertype/) |

### مقدار بازگشت

شیء افکت جدید [IEffect](../../ieffect/)

## ISequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) متد

افکت انیمیشن جدیدی برای عناصر در دسته یا سری به انتهای دنباله اضافه می‌کند.

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ISequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | شیء نمودار [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | نوع افکت انیمیشن [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | شاخص سری نمودار **int32_t** |
| categoriesIndex | **int32_t** | شاخص دسته **int32_t** |
| effectType | [EffectType](../../effecttype/) | نوع افکت انیمیشن [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع تحریک افکت [EffectTriggerType](../../effecttriggertype/) |

### مقدار بازگشت

شیء افکت جدید [IEffect](../../ieffect/)

## مراجع

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [ISequence](../)
* Class [IParagraph](../../../aspose.slides/iparagraph/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)