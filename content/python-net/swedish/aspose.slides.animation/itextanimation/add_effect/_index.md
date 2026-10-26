---
title: add_effect method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.animation/itextanimation/add_effect/
weight: 10
---
## add_effect(self, effect_type, subtype, trigger_type) {#effecttype-effectsubtype-effecttriggertype}
Lägg till en ny effekt i slutet av den aktuella sekvensen till slutet av gruppens textanimationer.
Endast giltig om antalet textparagrafer är lika med eller större än antalet effekter i denna grupp!

### Returns
Nytt effektobjekt [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)

```python
def add_effect(self, effect_type, subtype, trigger_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| effect_type | [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) |

### See Also
* enumeration [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype)
* class [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)
* class [`ITextAnimation`](/slides/python-net/sv/aspose.slides.animation/itextanimation)
* module [`aspose.slides.animation`](/slides/python-net/sv/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)