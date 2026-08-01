---
title: AddEffect()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuw effect toe aan het einde van de huidige reeks van groepstekstanimaties. Alleen geldig als het aantal tekstparagrafen gelijk is aan of groter is dan het aantal effecten in deze groep!
type: docs
weight: 53
url: /nl/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) methode

Voeg een nieuw effect toe aan het einde van de huidige reeks van groepstekstanimaties. Alleen geldig als het aantal tekstparagrafen gelijk is aan of groter is dan het aantal effecten in deze groep!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Type van een animatie-effect [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtype van animatie-effect [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Triggertype van effect [EffectTriggerType](../../effecttriggertype/) |

### Retourwaarde

Nieuw effectobject [IEffect](../../ieffect/)

## Zie ook

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [TextAnimation](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)