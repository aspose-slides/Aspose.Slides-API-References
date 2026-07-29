---
title: AddEffect()
second_title: Aspose.Slides för C++ API-referens
description: Lägg till en ny effekt i slutet av den aktuella sekvensen till slutet av gruppens textanimationer. Endast giltig om antalet textparagrafer är lika med eller större än antalet effekter i den här gruppen!
type: docs
weight: 53
url: /sv/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) metod

Lägg till en ny effekt i slutet av den aktuella sekvensen till slutet av gruppens textanimationer. Endast giltig om antalet textparagrafer är lika med eller större än antalet effekter i den här gruppen!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Typ av en animeringseffekt [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Underkategorier av animeringseffekt [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Utlösningstyp för effekt [EffectTriggerType](../../effecttriggertype/) |

### Returvärde

Nytt effektsobjekt [IEffect](../../ieffect/)

## Se även

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IEffect](../../ieffect/)
* Klass [TextAnimation](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)