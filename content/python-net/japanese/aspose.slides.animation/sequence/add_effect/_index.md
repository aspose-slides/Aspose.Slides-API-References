---
title: add_effect method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
シーケンスの末尾に新しいエフェクトを追加します。

### 戻り値

新しいエフェクト オブジェクト [`IEffect`](/slides/python-net/ja/aspose.slides.animation/ieffect)

```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | エフェクトを追加するための Shape オブジェクト [`IShape`](/slides/python-net/ja/aspose.slides/ishape) |
| effect_type | [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) | アニメーション効果のタイプ [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) | アニメーション効果のサブタイプ [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) | エフェクトのトリガータイプ [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) |

## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
シーケンスの末尾に段落用の新しいアニメーションエフェクトを追加します。

### 戻り値

新しいエフェクト オブジェクト [`IEffect`](/slides/python-net/ja/aspose.slides.animation/ieffect)

```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/ja/aspose.slides/iparagraph) | Paragraph オブジェクト [`IParagraph`](/slides/python-net/ja/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) | アニメーション効果のタイプ [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) | アニメーション効果のサブタイプ [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) | エフェクトのトリガータイプ [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) |

## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
シーケンスの末尾にカテゴリまたはシリーズ用の新しいチャートアニメーションエフェクトを追加します。

### 戻り値

新しいエフェクト オブジェクト [`IEffect`](/slides/python-net/ja/aspose.slides.animation/ieffect)

```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart) | Chart オブジェクト [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartmajorgroupingtype) | アニメーション効果のタイプ [`EffectChartMinorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | インデックス **int** |
| effect_type | [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) | アニメーション効果のタイプ [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) | アニメーション効果のサブタイプ [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) | エフェクトのトリガータイプ [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) |

## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
シーケンスの末尾にカテゴリまたはシリーズ内の要素用の新しいチャートアニメーションエフェクトを追加します。

### 戻り値

新しいエフェクト オブジェクト [`IEffect`](/slides/python-net/ja/aspose.slides.animation/ieffect)

```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart) | Chart オブジェクト [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartminorgroupingtype) | アニメーション効果のタイプ [`EffectChartMinorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | チャートシリーズのインデックス **int** |
| categories_index | **int** | カテゴリのインデックス **int** |
| effect_type | [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) | アニメーション効果のタイプ [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) | アニメーション効果のサブタイプ [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) | エフェクトのトリガータイプ [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) |

### 参照
* 列挙体 [`EffectChartMajorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartmajorgroupingtype)
* 列挙体 [`EffectChartMinorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartminorgroupingtype)
* 列挙体 [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype)
* 列挙体 [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype)
* 列挙体 [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype)
* クラス [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)
* クラス [`IEffect`](/slides/python-net/ja/aspose.slides.animation/ieffect)
* クラス [`IParagraph`](/slides/python-net/ja/aspose.slides/iparagraph)
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* クラス [`Sequence`](/slides/python-net/ja/aspose.slides.animation/sequence)
* モジュール [`aspose.slides.animation`](/slides/python-net/ja/aspose.slides.animation)
* ライブラリ [`Aspose.Slides`](/slides/python-net)