---
title: add_effect method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.animation/itextanimation/add_effect/
weight: 10
---


## add_effect {#effecttype-effectsubtype-effecttriggertype}
Add new effect to the end of current sequence to end of group text animations.
            Only valid if count of text paragraphs equal or greater of counts effect of this group!

### Returns

New effect object [`IEffect`](/slides/python-net/aspose.slides.animation/ieffect)



```python
def add_effect(self, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| effect_type | [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype) |



### See Also
* enumeration [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype)
* class [`IEffect`](/slides/python-net/aspose.slides.animation/ieffect)
* class [`ITextAnimation`](/slides/python-net/aspose.slides.animation/itextanimation)
* module [`aspose.slides.animation`](/slides/python-net/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)
