---
title: AddEffect()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en ny effekt i slutet av den aktuella sekvensen till slutet av gruppens textanimationer. Giltig endast om antalet textparagrafer är lika med eller större än antalet effekter i denna grupp!
type: docs
weight: 53
url: /sv/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) metod


Lägg till en ny effekt i slutet av den aktuella sekvensen till slutet av gruppens textanimationer. Giltig endast om antalet textparagrafer är lika med eller större än antalet effekter i denna grupp!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Typ av en animeringseffekt [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtyper av animeringseffekt [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Utlösningstyp för effekt [EffectTriggerType](../../effecttriggertype/) |

### Returvärde

Nytt effektobjekt [IEffect](../../ieffect/)

## Se också

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IEffect](../../ieffect/)
* Klass [ITextAnimation](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)