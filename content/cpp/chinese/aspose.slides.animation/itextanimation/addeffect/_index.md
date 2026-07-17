---
title: AddEffect()
second_title: Aspose.Slides for C++ API 参考
description: 将新效果添加到当前序列的末尾，以结束组文本动画。仅在文本段落的计数等于或大于该组效果的计数时有效！
type: docs
weight: 53
url: /zh/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) 方法


在当前序列的末尾向组文本动画的末尾添加新效果。仅在文本段落的数量等于或大于该组效果的计数时有效！

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | 动画效果的类型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 动画效果的子类型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的触发类型 [EffectTriggerType](../../effecttriggertype/) |

### 返回值

新的效果对象 [IEffect](../../ieffect/)

## 另请参见

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IEffect](../../ieffect/)
* 类 [ITextAnimation](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)