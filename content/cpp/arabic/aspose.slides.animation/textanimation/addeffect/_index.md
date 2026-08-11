---
title: AddEffect()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: أضف تأثيرًا جديدًا إلى نهاية التسلسل الحالي إلى نهاية مجموعة الرسوم المتحركة للنص. يكون صالحًا فقط إذا كان عدد فقرات النص مساويًا أو أكبر من عدد تأثيرات هذه المجموعة!
type: docs
weight: 53
url: /ar/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) method

أضف تأثيرًا جديدًا إلى نهاية التسلسل الحالي إلى نهاية مجموعة الرسوم المتحركة للنص. يكون صالحًا فقط إذا كان عدد فقرات النص مساويًا أو أكبر من عدد تأثيرات هذه المجموعة!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Type of an animation effect [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtypes of animation effect [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Trigger type of effect [EffectTriggerType](../../effecttriggertype/) |

### قيمة الإرجاع

New effect object [IEffect](../../ieffect/)

## انظر أيضًا

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IEffect](../../ieffect/)
* فئة [TextAnimation](../)
* نطاق [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)