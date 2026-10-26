---
title: add_effect method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
シーケンスの末尾に新しいエフェクトを追加します。

### 戻り値

新しいエフェクトオブジェクト [`IEffect`](/slides/python-net/ja/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | エフェクトを追加するための Shape オブジェクト [`IShape`](/slides/python-net/ja/aspose.slides/ishape) |
| effect_type | [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) | アニメーションエフェクトのタイプ [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) | アニメーションエフェクトのサブタイプ [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) | エフェクトのトリガータイプ [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
シーケンスの末尾に段落用の新しいアニメーションエフェクトを追加します。

### 戻り値

新しいエフェクトオブジェクト [`IEffect`](/slides/python-net/ja/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/ja/aspose.slides/iparagraph) | Paragraph オブジェクト [`IParagraph`](/slides/python-net/ja/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) | アニメーションエフェクトのタイプ [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) | アニメーションエフェクトのサブタイプ [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) | エフェクトのトリガータイプ [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
シーケンスの末尾にカテゴリまたは系列用の新しいチャートアニメーションエフェクトを追加します。

### 戻り値

新しいエフェクトオブジェクト [`IEffect`](/slides/python-net/ja/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart) | Chart オブジェクト [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartmajorgroupingtype) | アニメーションエフェクトのタイプ [`EffectChartMinorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | インデックス **int** |
| effect_type | [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) | アニメーションエフェクトのタイプ [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) | アニメーションエフェクトのサブタイプ [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) | エフェクトのトリガータイプ [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
シーケンスの末尾にカテゴリまたは系列内の要素用の新しいチャートアニメーションエフェクトを追加します。

### 戻り値

新しいエフェクトオブジェクト [`IEffect`](/slides/python-net/ja/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart) | Chart オブジェクト [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartminorgroupingtype) | アニメーションエフェクトのタイプ [`EffectChartMinorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | チャートシリーズのインデックス **int** |
| categories_index | **int** | カテゴリのインデックス **int** |
| effect_type | [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) | アニメーションエフェクトのタイプ [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) | アニメーションエフェクトのサブタイプ [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) | エフェクトのトリガータイプ [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype) |



### 参照
* 列挙型 [`EffectChartMajorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartmajorgroupingtype)
* 列挙型 [`EffectChartMinorGroupingType`](/slides/python-net/ja/aspose.slides.animation/effectchartminorgroupingtype)
* 列挙型 [`EffectSubtype`](/slides/python-net/ja/aspose.slides.animation/effectsubtype)
* 列挙型 [`EffectTriggerType`](/slides/python-net/ja/aspose.slides.animation/effecttriggertype)
* 列挙型 [`EffectType`](/slides/python-net/ja/aspose.slides.animation/effecttype)
* クラス [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)
* クラス [`IEffect`](/slides/python-net/ja/aspose.slides.animation/ieffect)
* クラス [`IParagraph`](/slides/python-net/ja/aspose.slides/iparagraph)
* クラス [`ISequence`](/slides/python-net/ja/aspose.slides.animation/isequence)
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* モジュール [`aspose.slides.animation`](/slides/python-net/ja/aspose.slides.animation)
* ライブラリ [`Aspose.Slides`](/slides/python-net)