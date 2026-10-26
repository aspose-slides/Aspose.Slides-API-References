---
title: AddEffect()
second_title: Aspose.Slides for C++ API 參考
description: 將新效果加入目前序列的結尾，以結束群組文字動畫。僅在文字段落數量等於或大於此群組效果數量時有效！
type: docs
weight: 53
url: /zh-hant/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) 方法

將新效果加入目前序列的結尾，以結束群組文字動畫。僅在文字段落數量等於或大於此群組效果數量時有效！

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | 動畫效果的類型 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 動畫效果的子類型 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 效果的觸發類型 [EffectTriggerType](../../effecttriggertype/) |

### 返回值

新的效果物件 [IEffect](../../ieffect/)

## 參見

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IEffect](../../ieffect/)
* 類別 [ITextAnimation](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)