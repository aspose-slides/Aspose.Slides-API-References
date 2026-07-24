---
title: AddEffect()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen Effekt am Ende der aktuellen Sequenz zu den Textanimationen der Gruppe hinzu. Nur gültig, wenn die Anzahl der Textabsätze gleich oder größer ist als die Anzahl der Effekte dieser Gruppe!
type: docs
weight: 53
url: /de/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) Methode

Füge einen neuen Effekt am Ende der aktuellen Sequenz zu den Textanimationen der Gruppe hinzu. Nur gültig, wenn die Anzahl der Textabsätze gleich oder größer ist als die Anzahl der Effekte dieser Gruppe!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Typ eines Animationseffekts [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Untertypen des Animationseffekts [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Auslösetyp des Effekts [EffectTriggerType](../../effecttriggertype/) |

### Return Value

Neues Effektobjekt [IEffect](../../ieffect/)

## See Also

* Aufzählung [EffectType](../../effecttype/)
* Aufzählung [EffectSubtype](../../effectsubtype/)
* Aufzählung [EffectTriggerType](../../effecttriggertype/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IEffect](../../ieffect/)
* Klasse [ITextAnimation](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)