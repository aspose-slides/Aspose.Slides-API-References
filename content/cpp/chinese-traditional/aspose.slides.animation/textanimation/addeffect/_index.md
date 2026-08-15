---
title: AddEffect()
second_title: Aspose.Slides for C++ API 參考
description: 將新的效果新增至目前序列的結尾，並加入至群組文字動畫的結尾。僅當文字段落的數量等於或大於此群組效果的計數時才有效！
type: docs
weight: 53
url: /zh-hant/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) 方法


將新的效果新增至目前序列的結尾，並加入至群組文字動畫的結尾。僅當文字段落的數量等於或大於此群組效果的計數時才有效！

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | 動畫效果的類型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 動畫效果的子類型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的觸發類型 [EffectTriggerType](../../effecttriggertype/) |

### 返回值

新的效果物件 [IEffect](../../ieffect/)

## 另見

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IEffect](../../ieffect/)
* 類別 [TextAnimation](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)