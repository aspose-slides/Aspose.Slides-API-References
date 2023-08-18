---
title: AddEffect()
second_title: Aspose.Slides for C++ API Reference
description: Add new effect to the end of current sequence to end of group text animations. Only valid if count of text paragraphs equal or greater of counts effect of this group!
type: docs
weight: 53
url: /aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) method


Add new effect to the end of current sequence to end of group text animations. Only valid if count of text paragraphs equal or greater of counts effect of this group!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Type of an animation effect [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtypes of animation effect [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Trigger type of effect [EffectTriggerType](../../effecttriggertype/) |

### Return Value

New effect object [IEffect](../../ieffect/)

## See Also

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [TextAnimation](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)