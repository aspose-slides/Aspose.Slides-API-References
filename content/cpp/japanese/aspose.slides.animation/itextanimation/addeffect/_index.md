---
title: AddEffect()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のシーケンスの末尾に新しい効果を追加し、グループテキストアニメーションの末尾に配置します。この操作は、テキスト段落の数がこのグループの効果数以上である場合にのみ有効です。
type: docs
weight: 53
url: /ja/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) メソッド


現在のシーケンスの末尾に新しい効果を追加し、テキストアニメーションのグループの末尾に配置します。この操作は、テキスト段落の数がこのグループの効果数以上である場合にのみ有効です！

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | アニメーション効果のタイプ [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | アニメーション効果のサブタイプ [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 効果のトリガータイプ [EffectTriggerType](../../effecttriggertype/) |

### 戻り値

新しい効果オブジェクト [IEffect](../../ieffect/)

## 参照

* 列挙体 [EffectType](../../effecttype/)
* 列挙体 [EffectSubtype](../../effectsubtype/)
* 列挙体 [EffectTriggerType](../../effecttriggertype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IEffect](../../ieffect/)
* クラス [ITextAnimation](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)