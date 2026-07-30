---
title: AddEffect()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový efekt na konec aktuální sekvence do konce skupiny textových animací. Platí pouze pokud je počet odstavců textu roven nebo větší než počet efektů v této skupině!
type: docs
weight: 53
url: /cs/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) method

Přidá nový efekt na konec aktuální sekvence do konce skupiny textových animací. Platí pouze pokud je počet odstavců textu roven nebo větší než počet efektů v této skupině!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Typ animačního efektu [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Podtypy animačního efektu [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Typ spouštěče efektu [EffectTriggerType](../../effecttriggertype/) |

### Návratová hodnota

Nový objekt efektu [IEffect](../../ieffect/)

## Viz také

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IEffect](../../ieffect/)
* Třída [TextAnimation](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)