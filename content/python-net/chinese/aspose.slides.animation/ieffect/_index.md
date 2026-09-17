---
title: IEffect class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.animation/ieffect/
---
## IEffect 类

表示动画效果。

IEffect 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`sequence`](/slides/python-net/zh/aspose.slides.animation/ieffect/sequence/) | Returns a sequence for an effect.<br/>            只读 [`ISequence`](/slides/python-net/zh/aspose.slides.animation/isequence). |
| [`text_animation`](/slides/python-net/zh/aspose.slides.animation/ieffect/text_animation/) | Returns text animation.<br/>            只读 [`ITextAnimation`](/slides/python-net/zh/aspose.slides.animation/itextanimation). |
| [`preset_class_type`](/slides/python-net/zh/aspose.slides.animation/ieffect/preset_class_type/) | Defines class of effect.<br/>            可读写 [`EffectPresetClassType`](/slides/python-net/zh/aspose.slides.animation/effectpresetclasstype). |
| [`type`](/slides/python-net/zh/aspose.slides.animation/ieffect/type/) | Defines type of effect.<br/>            可读写 [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype). |
| [`subtype`](/slides/python-net/zh/aspose.slides.animation/ieffect/subtype/) | Defines subtype of effect.<br/>            可读写 [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype). |
| [`behaviors`](/slides/python-net/zh/aspose.slides.animation/ieffect/behaviors/) | Returns collection of behavior for effect.<br/>            可读写 [`IBehaviorCollection`](/slides/python-net/zh/aspose.slides.animation/ibehaviorcollection). |
| [`timing`](/slides/python-net/zh/aspose.slides.animation/ieffect/timing/) | Defines timing value for effect.<br/>            可读写 [`ITiming`](/slides/python-net/zh/aspose.slides.animation/itiming). |
| [`target_shape`](/slides/python-net/zh/aspose.slides.animation/ieffect/target_shape/) | Returns target shape for effect.<br/>            只读 [`IShape`](/slides/python-net/zh/aspose.slides/ishape). |
| [`sound`](/slides/python-net/zh/aspose.slides.animation/ieffect/sound/) | Defined embedded sound for effect.<br/>            可读写 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio). |
| [`stop_previous_sound`](/slides/python-net/zh/aspose.slides.animation/ieffect/stop_previous_sound/) | This attribute specifies if the animation effect stops the previous sound.<br/>            可读写 **bool**. |
| [`after_animation_type`](/slides/python-net/zh/aspose.slides.animation/ieffect/after_animation_type/) | Defined an after animation type for effect.<br/>            可读写 [`IEffect.after_animation_type`](/slides/python-net/zh/aspose.slides.animation/ieffect/after_animation_type). |
| [`after_animation_color`](/slides/python-net/zh/aspose.slides.animation/ieffect/after_animation_color/) | Defined an after animation color for effect.<br/>            可读写 [`IColorFormat`](/slides/python-net/zh/aspose.slides/icolorformat). |
| [`animate_text_type`](/slides/python-net/zh/aspose.slides.animation/ieffect/animate_text_type/) | Defines an animate text type for effect. <br/>            The shape text can be animated by letter, by word or all at once.<br/>            可读写 [`IEffect.animate_text_type`](/slides/python-net/zh/aspose.slides.animation/ieffect/animate_text_type). |
| [`delay_between_text_parts`](/slides/python-net/zh/aspose.slides.animation/ieffect/delay_between_text_parts/) | Defines a delay between animated text parts (words or letters).<br/>            A positive value specifies the percentage of effect duration.<br/>            A negative value specifies the delay in seconds.<br/>            可读写 **float**. |


### 另见
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)