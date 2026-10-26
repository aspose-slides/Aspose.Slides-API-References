---
title: AddEffect()
second_title: مرجع API Aspose.Slides للغة C++
description: أضف تأثيرًا جديدًا إلى نهاية التسلسل.
type: docs
weight: 157
url: /ar/aspose.slides.animation/sequence/addeffect/
---
## Sequence::AddEffect(System::SharedPtr\<IShape\>, EffectType, EffectSubtype, EffectTriggerType) طريقة

أضف تأثيرًا جديدًا إلى نهاية التسلسل.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IShape> shape, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) كائن [IShape](../../../aspose.slides/ishape/) لإضافة تأثير |
| effectType | [EffectType](../../effecttype/) | نوع تأثير الرسوم المتحركة [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | أنواع فرعية لتأثير الرسوم المتحركة [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع الزناد للتأثير [EffectTriggerType](../../effecttriggertype/) |

### قيمة الإرجاع

كائن تأثير جديد [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<IParagraph\>, EffectType, EffectSubtype, EffectTriggerType) طريقة

أضف تأثيرًا متحركًا جديدًا للفقرة إلى نهاية التسلسل.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<IParagraph> paragraph, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../../aspose.slides/iparagraph/)\> | [Paragraph](../../../aspose.slides/paragraph/) كائن [IParagraph](../../../aspose.slides/iparagraph/) |
| effectType | [EffectType](../../effecttype/) | نوع تأثير الرسوم المتحركة [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | أنواع فرعية لتأثير الرسوم المتحركة [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع الزناد للتأثير [EffectTriggerType](../../effecttriggertype/) |

### قيمة الإرجاع

كائن تأثير جديد [IEffect](../../ieffect/)
## ملاحظات

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"input.pptx");
// حدد الفقرة لإضافة التأثير
auto autoShape = System::ExplicitCast<Aspose::Slides::IAutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto paragraph = autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0);
// أضف تأثير الحركة Fly إلى الفقرة المختارة
auto effect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->AddEffect(
     paragraph, 
     Aspose::Slides::Animation::EffectType::Fly, 
     Aspose::Slides::Animation::EffectSubtype::Left, 
     Aspose::Slides::Animation::EffectTriggerType::OnClick);
```

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMajorGroupingType, int32_t, EffectType, EffectSubtype, EffectTriggerType) طريقة

يضيف تأثير الرسوم المتحركة للمخطط الجديد للفئة أو السلسلة إلى نهاية التسلسل.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMajorGroupingType type, int32_t index, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | كائن مخطط [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/) | نوع تأثير الرسوم المتحركة [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| index | **int32_t** | المؤشر **int32_t** |
| effectType | [EffectType](../../effecttype/) | نوع تأثير الرسوم المتحركة [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | أنواع فرعية لتأثير الرسوم المتحركة [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع الزناد للتأثير [EffectTriggerType](../../effecttriggertype/) |

### قيمة الإرجاع

كائن تأثير جديد [IEffect](../../ieffect/)

## Sequence::AddEffect(System::SharedPtr\<Aspose::Slides::Charts::IChart\>, EffectChartMinorGroupingType, int32_t, int32_t, EffectType, EffectSubtype, EffectTriggerType) طريقة

يضيف تأثير الرسوم المتحركة للمخطط الجديد للعناصر في الفئة أو السلسلة إلى نهاية التسلسل.

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::Sequence::AddEffect(System::SharedPtr<Aspose::Slides::Charts::IChart> chart, EffectChartMinorGroupingType type, int32_t seriesIndex, int32_t categoriesIndex, EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| chart | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/)\> | كائن مخطط [Aspose::Slides::Charts::IChart](../../../aspose.slides.charts/ichart/) |
| type | [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) | نوع تأثير الرسوم المتحركة [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/) |
| seriesIndex | **int32_t** | مؤشر سلسلة المخطط **int32_t** |
| categoriesIndex | **int32_t** | مؤشر الفئة **int32_t** |
| effectType | [EffectType](../../effecttype/) | نوع تأثير الرسوم المتحركة [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | أنواع فرعية لتأثير الرسوم المتحركة [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع الزناد للتأثير [EffectTriggerType](../../effecttriggertype/) |

### قيمة الإرجاع

كائن تأثير جديد [IEffect](../../ieffect/)

## انظر أيضًا

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Enum [EffectChartMajorGroupingType](../../effectchartmajorgroupingtype/)
* Enum [EffectChartMinorGroupingType](../../effectchartminorgroupingtype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IEffect](../../ieffect/)
* فئة [IShape](../../../aspose.slides/ishape/)
* فئة [Sequence](../)
* فئة [IParagraph](../../../aspose.slides/iparagraph/)
* فئة [IChart](../../../aspose.slides.charts/ichart/)
* نطاق [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)