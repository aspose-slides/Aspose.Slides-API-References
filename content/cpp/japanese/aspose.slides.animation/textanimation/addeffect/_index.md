---
title: AddEffect()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のシーケンスの末尾に新しい効果を追加し、グループのテキストアニメーションの末尾に配置します。この効果は、テキスト段落の数がこのグループの効果数以上である場合にのみ有効です。
type: docs
weight: 53
url: /ja/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) メソッド


現在のシーケンスの最後に新しい効果を追加し、グループのテキストアニメーションの末尾に配置します。テキスト段落の数がこのグループの効果数以上である場合にのみ有効です。

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | アニメーション効果のタイプ [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | アニメーション効果のサブタイプ [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 効果のトリガータイプ [EffectTriggerType](../../effecttriggertype/) |

### 戻り値

新しい効果オブジェクト [IEffect](../../ieffect/)

## 参照

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEffect](../../ieffect/)
* Class [TextAnimation](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)