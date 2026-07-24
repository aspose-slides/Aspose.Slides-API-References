---
title: AddEffect()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen Effekt am Ende der aktuellen Sequenz zur Gruppe von Textanimationen hinzu. Nur gültig, wenn die Anzahl der Textabsätze gleich oder größer ist als die Anzahl der Effekte dieser Gruppe!
type: docs
weight: 53
url: /de/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) Methode

Fügt einen neuen Effekt am Ende der aktuellen Sequenz zur Gruppe von Textanimationen hinzu. Nur gültig, wenn die Anzahl der Textabsätze gleich oder größer ist als die Anzahl der Effekte dieser Gruppe!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Typ eines Animationseffekts [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Untertypen des Animationseffekts [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Auslösetyp des Effekts [EffectTriggerType](../../effecttriggertype/) |

### Rückgabewert

Neues Effektobjekt [IEffect](../../ieffect/)

## Siehe auch

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IEffect](../../ieffect/)
* Klasse [TextAnimation](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)