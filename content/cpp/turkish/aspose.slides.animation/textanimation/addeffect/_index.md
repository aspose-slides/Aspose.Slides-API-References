---
title: AddEffect()
second_title: Aspose.Slides için C++ API Referansı
description: Mevcut dizinin sonuna, grup metin animasyonlarının sonuna yeni bir efekt ekler. Yalnızca metin paragrafı sayısı bu grubun efekt sayısına eşit veya daha büyük olduğunda geçerlidir.
type: docs
weight: 53
url: /tr/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) metodu

Mevcut dizinin sonuna, grup metin animasyonlarının sonuna yeni bir efekt ekler. Bu, yalnızca metin paragrafı sayısı bu grup içindeki efekt sayısına eşit veya daha büyük ise geçerlidir!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Animasyon efektinin türü [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animasyon efektinin alt türleri [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Efektin tetikleme türü [EffectTriggerType](../../effecttriggertype/) |

### Dönüş Değeri

Yeni efekt nesnesi [IEffect](../../ieffect/)

## İlgili

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [TextAnimation](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)