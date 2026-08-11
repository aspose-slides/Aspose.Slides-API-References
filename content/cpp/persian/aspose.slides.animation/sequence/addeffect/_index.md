---
title: AddEffect()
second_title: مرجع API Aspose.Slides برای C++
description: افکت جدید را به انتهای دنباله اضافه می‌کند.
type: docs
weight: 157
url: /fa/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) متد

افکت جدید را به انتهای دنباله اضافه می‌کند.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) شی [IShape](../../../aspose.slides/ishape/) برای اضافه کردن یک افکت |
| effectType | [EffectType](../../effecttype/) | نوع یک افکت انیمیشن [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع فراخوانی افکت [EffectTriggerType](../../effecttriggertype/) |

### مقدار بازگشت

شی افکت جدید [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) متد

افکت انیمیشن جدید برای پاراگراف را به انتهای دنباله اضافه می‌کند.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) شی [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | نوع یک افکت انیمیشن [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع فراخوانی افکت [EffectTriggerType](../../effecttriggertype/) |

### مقدار بازگشت

شی افکت جدید [IEffect](../../ieffect/)

## توضیحات

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// پاراگراف را برای اضافه کردن افکت انتخاب کنید
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// افزودن افکت انیمیشن Fly به پاراگراف انتخاب‌شده
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) متد

افکت انیمیشن جدید چارت برای دسته یا سری را به انتهای دنباله اضافه می‌کند.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | شی چارت [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | نوع یک افکت انیمیشن [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | اندیس **int32_t** |
| effectType | [EffectType](../../effecttype/) | نوع یک افکت انیمیشن [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع فراخوانی افکت [EffectTriggerType](../../effecttriggertype/) |

### مقدار بازگشت

شی افکت جدید [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) متد

افکت انیمیشن جدید چارت برای عناصر در دسته یا سری را به انتهای دنباله اضافه می‌کند.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | شی چارت [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | نوع یک افکت انیمیشن [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | اندیس سری چارت **int32_t** |
| categoriesIndex | **int32_t** | اندیس دسته‌بندی **int32_t** |
| effectType | [EffectType](../../effecttype/) | نوع یک افکت انیمیشن [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع فراخوانی افکت [EffectTriggerType](../../effecttriggertype/) |

### مقدار بازگشت

شی افکت جدید [IEffect](../../ieffect/)

## موارد مرتبط

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [Sequence](../)
* Class [IParagraph](../../../aspose.slides/iparagraph/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)