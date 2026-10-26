---
title: AddEffect()
second_title: مرجع API Aspose.Slides للغة C++
description: إضافة تأثير جديد إلى نهاية التسلسل الحالي إلى نهاية مجموعة تحريكات النص. يكون صالحًا فقط إذا كان عدد فقرات النص مساويًا أو أكبر من عدد تأثيرات هذه المجموعة!
type: docs
weight: 53
url: /ar/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) طريقة

إضافة تأثير جديد إلى نهاية التسلسل الحالي إلى نهاية مجموعة تحريكات النص. يكون صالحًا فقط إذا كان عدد فقرات النص مساويًا أو أكبر من عدد تأثيرات هذه المجموعة!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | نوع تأثير التحريك [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | أنواع فرعية لتأثير التحريك [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | نوع تشغيل التأثير [EffectTriggerType](../../effecttriggertype/) |

### قيمة الإرجاع

كائن تأثير جديد [IEffect](../../ieffect/)

## انظر أيضًا

* تعداد [EffectType](../../effecttype/)
* تعداد [EffectSubtype](../../effectsubtype/)
* تعداد [EffectTriggerType](../../effecttriggertype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IEffect](../../ieffect/)
* فئة [ITextAnimation](../)
* نطاق [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)