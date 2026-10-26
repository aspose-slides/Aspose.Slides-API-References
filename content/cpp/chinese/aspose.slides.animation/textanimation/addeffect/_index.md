---
title: AddEffect()
second_title: Aspose.Slides for C++ API 参考
description: 将新效果添加到当前序列的末尾，以结束组文本动画。仅当文本段落的计数大于或等于该组效果的计数时有效！
type: docs
weight: 53
url: /zh/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) 方法

将新效果添加到当前序列的末尾，以结束组文本动画。仅当文本段落的计数大于或等于该组效果的计数时有效！

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | 动画效果的类型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 动画效果的子类型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的触发类型 [EffectTriggerType](../../effecttriggertype/) |

### 返回值

新的效果对象 [IEffect](../../ieffect/)

## 另见

* 枚举 [EffectType](../../effecttype/)
* 枚举 [EffectSubtype](../../effectsubtype/)
* 枚举 [EffectTriggerType](../../effecttriggertype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IEffect](../../ieffect/)
* 类 [TextAnimation](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)