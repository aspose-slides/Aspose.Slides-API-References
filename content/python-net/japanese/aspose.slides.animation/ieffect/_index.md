---
title: IEffect class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.animation/ieffect/
---
## IEffect クラス

アニメーションエフェクトを表します。

IEffect 型は次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`sequence`](/slides/python-net/ja/aspose.slides.animation/ieffect/sequence/) | エフェクトのシーケンスを返します。<br/>            読み取り専用 [`ISequence`](/slides/python-net/ja/aspose.slides.animation/isequence). |
| [`text_animation`](/slides/python-net/ja/aspose.slides.animation/ieffect/text_animation/) | テキストアニメーションを返します。<br/>            読み取り専用 [`ITextAnimation`](/slides/python-net/ja/aspose.slides.animation/itextanimation). |
| [`preset_class_type`](/slides/python-net/ja/aspose.slides.animation/ieffect/preset_class_type/) | エフェクトのクラスを定義します。<br/>            読み書き可能 [`EffectPresetClassType`](/slides/python-net/ja/aspose.slides.animation/effectpresetclasstype). |
| [`type`](/slides/python-net/ja/aspose.slides.animation/ieffect/type/) | エフェクトのタイプを定義します。<br/>            読み書き可能 [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype). |
| [`subtype`](/slides/python-net/ja/aspose.slides.animation/ieffect/subtype/) | エフェクトのサブタイプを定義します。<br/>            読み書き可能 [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype). |
| [`behaviors`](/slides/python-net/ja/aspose.slides.animation/ieffect/behaviors/) | エフェクトのビヘイビアコレクションを返します。<br/>            読み書き可能 [`IBehaviorCollection`](/slides/python-net/ja/aspose.slides.animation/ibehaviorcollection). |
| [`timing`](/slides/python-net/ja/aspose.slides.animation/ieffect/timing/) | エフェクトのタイミング値を定義します。<br/>            読み書き可能 [`ITiming`](/slides/python-net/ja/aspose.slides.animation/itiming). |
| [`target_shape`](/slides/python-net/ja/aspose.slides.animation/ieffect/target_shape/) | エフェクトのターゲットシェイプを返します。<br/>            読み取り専用 [`IShape`](/slides/python-net/ja/aspose.slides/ishape). |
| [`sound`](/slides/python-net/ja/aspose.slides.animation/ieffect/sound/) | エフェクトの埋め込みサウンドを定義します。<br/>            読み書き可能 [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio). |
| [`stop_previous_sound`](/slides/python-net/ja/aspose.slides.animation/ieffect/stop_previous_sound/) | この属性は、アニメーションエフェクトが前のサウンドを停止するかどうかを指定します。<br/>            読み書き可能 **bool**. |
| [`after_animation_type`](/slides/python-net/ja/aspose.slides.animation/ieffect/after_animation_type/) | エフェクトのアフターアニメーションタイプを定義します。<br/>            読み書き可能 [`IEffect.after_animation_type`](/slides/python-net/ja/aspose.slides.animation/ieffect/after_animation_type). |
| [`after_animation_color`](/slides/python-net/ja/aspose.slides.animation/ieffect/after_animation_color/) | エフェクトのアフターアニメーションカラーを定義します。<br/>            読み書き可能 [`IColorFormat`](/slides/python-net/ja/aspose.slides/icolorformat). |
| [`animate_text_type`](/slides/python-net/ja/aspose.slides.animation/ieffect/animate_text_type/) | エフェクトのテキストアニメーションタイプを定義します。 <br/>            シェイプのテキストは文字単位、単語単位、または一括でアニメーション化できます。<br/>            読み書き可能 [`IEffect.animate_text_type`](/slides/python-net/ja/aspose.slides.animation/ieffect/animate_text_type). |
| [`delay_between_text_parts`](/slides/python-net/ja/aspose.slides.animation/ieffect/delay_between_text_parts/) | アニメーションテキストの各部分（単語または文字）間の遅延を定義します。<br/>            正の値はエフェクトの期間の割合を指定します。<br/>            負の値は秒単位で遅延を指定します。<br/>            読み書き可能 **float**. |

### 参照
* モジュール [`aspose.slides.animation`](/slides/python-net/ja/aspose.slides.animation)
* ライブラリ [`Aspose.Slides`](/slides/python-net)