---
title: AddEffect()
second_title: Aspose.Slides C++ API referenciája
description: Új effektust ad a jelenlegi szekvencia végéhez a csoport szöveges animációinak végéhez. Csak akkor érvényes, ha a szöveges bekezdések száma egyenlő vagy nagyobb, mint a csoport hatásainak száma!
type: docs
weight: 53
url: /hu/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) metódus

Új effektust ad hozzá a jelenlegi szekvencia végéhez a csoport szöveges animációinak végéhez. Csak akkor érvényes, ha a szöveges bekezdések száma egyenlő vagy nagyobb, mint ennek a csoportnak a hatásainak száma!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Type of an animation effect [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtypes of animation effect [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Trigger type of effect [EffectTriggerType](../../effecttriggertype/) |

### Visszatérési érték

Új effektus objektum [IEffect](../../ieffect/)

## Lásd még

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IEffect](../../ieffect/)
* Osztály [TextAnimation](../)
* Névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)