---
title: add_effect method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.animation/textanimation/add_effect/
weight: 20
---
## add_effect(self, effect_type, subtype, trigger_type) {#effecttype-effectsubtype-effecttriggertype}
将新效果添加到当前序列的末尾，以结束组文本动画。
仅当文本段落的计数大于或等于该组效果的计数时有效！

### 返回
新效果对象 [`IEffect`](/slides/python-net/zh/aspose.slides.animation/ieffect)

```python
def add_effect(self, effect_type, subtype, trigger_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| effect_type | [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype) | 动画效果的类型 [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype) | 动画效果的子类型 [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype) | 效果的触发类型 [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype) |

### 另请参见
* 枚举 [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype)
* 枚举 [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype)
* 枚举 [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype)
* 类 [`IEffect`](/slides/python-net/zh/aspose.slides.animation/ieffect)
* 类 [`TextAnimation`](/slides/python-net/zh/aspose.slides.animation/textanimation)
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)