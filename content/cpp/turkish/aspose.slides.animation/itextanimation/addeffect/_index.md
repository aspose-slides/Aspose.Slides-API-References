---
title: AddEffect()
second_title: Aspose.Slides için C++ API Referansı
description: Mevcut dizinin sonuna yeni bir etki ekler, grup metin animasyonlarının sonuna kadar. Yalnızca metin paragraf sayısı bu grubun etki sayısına eşit ya da daha büyük olduğunda geçerlidir!
type: docs
weight: 53
url: /tr/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) metodu

Mevcut dizinin sonuna yeni bir etki ekler, grup metin animasyonlarının sonuna kadar. Yalnızca metin paragraf sayısı, bu grubun etki sayısına eşit ya da daha büyük olduğunda geçerlidir!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Animasyon etkisinin türü [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animasyon etkisinin alt türleri [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Etkinin tetikleme türü [EffectTriggerType](../../effecttriggertype/) |

### Dönüş Değeri

Yeni etki nesnesi [IEffect](../../ieffect/)

## Ayrıca Bakınız

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [ITextAnimation](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)