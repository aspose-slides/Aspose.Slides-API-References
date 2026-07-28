---
title: AddEffect()
second_title: Aspose.Slides C++ API referencia
description: Új effektust ad a jelenlegi sorozat végéhez, a csoport szöveganimációinak végéhez. Csak akkor érvényes, ha a szöveges bekezdések száma egyenlő vagy nagyobb, mint a csoport effektusainak száma!
type: docs
weight: 53
url: /hu/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) metódus


Új effektust ad a jelenlegi sorozat végéhez, a csoport szöveges animációinak végéhez. Csak akkor érvényes, ha a szöveges bekezdések száma egyenlő vagy nagyobb, mint a csoport effektusainak száma!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Animációs effektus típusa [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Animációs effektus altípusai [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Effektus aktiválási típusa [EffectTriggerType](../../effecttriggertype/) |

### Visszatérési érték

Új effektus objektum [IEffect](../../ieffect/)

## Lásd még

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IEffect](../../ieffect/)
* Osztály [ITextAnimation](../)
* Névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)