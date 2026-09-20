---
title: add_effect method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.animation/textanimation/add_effect/
weight: 20
---
## add_effect(self, effect_type, subtype, trigger_type) {#effecttype-effectsubtype-effecttriggertype}
Lägg till en ny effekt i slutet av den aktuella sekvensen till slutet av gruppens textanimationer.  
Gäller endast om antalet textparagrafer är lika med eller större än antalet effekter i den här gruppen!

### Returnerar

Nytt effektobjekt [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)



```python
def add_effect(self, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| effect_type | [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) | Typ av en animationseffekt [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) | Subtyper av animationseffekt [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) | Utlösningstyp för effekt [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) |



### Se även
* enumeration [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype)
* klass [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)
* klass [`TextAnimation`](/slides/python-net/sv/aspose.slides.animation/textanimation)
* modul [`aspose.slides.animation`](/slides/python-net/sv/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)