---
title: AddEffect()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá nový efekt na konec aktuální sekvence ke konci skupiny textových animací. Platí pouze, pokud počet textových odstavců je roven nebo větší než počet efektů v této skupině!
type: docs
weight: 53
url: /cs/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) metoda

Přidá nový efekt na konec aktuální sekvence ke konci skupiny textových animací. Platí pouze, pokud počet textových odstavců je roven nebo větší než počet efektů v této skupině!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Typ animačního efektu [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Podtypy animačního efektu [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Typ spouštění efektu [EffectTriggerType](../../effecttriggertype/) |

### Návratová hodnota

Nový objekt efektu [IEffect](../../ieffect/)

## Viz také

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [ITextAnimation](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)