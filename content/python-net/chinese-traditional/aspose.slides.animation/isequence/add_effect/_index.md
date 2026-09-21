---
title: add_effect method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
將新效果新增至序列的末端。

### 傳回值

新的效果物件 [`IEffect`](/slides/python-net/zh-hant/aspose.slides.animation/ieffect)

```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) | Shape 物件 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape) 用於新增效果 |
| effect_type | [`EffectType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttype) | 動畫效果的類型 [`EffectType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/zh-hant/aspose.slides.animation/effectsubtype) | 動畫效果的子類型 [`EffectSubtype`](/slides/python-net/zh-hant/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttriggertype) | 效果的觸發類型 [`EffectTriggerType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttriggertype) |

## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
為段落新增動畫效果至序列的末端。

### 傳回值

新的效果物件 [`IEffect`](/slides/python-net/zh-hant/aspose.slides.animation/ieffect)

```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/zh-hant/aspose.slides/iparagraph) | Paragraph 物件 [`IParagraph`](/slides/python-net/zh-hant/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttype) | 動畫效果的類型 [`EffectType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/zh-hant/aspose.slides.animation/effectsubtype) | 動畫效果的子類型 [`EffectSubtype`](/slides/python-net/zh-hant/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttriggertype) | 效果的觸發類型 [`EffectTriggerType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttriggertype) |

## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
將新圖表動畫效果（針對類別或系列）新增至序列的末端。

### 傳回值

新的效果物件 [`IEffect`](/slides/python-net/zh-hant/aspose.slides.animation/ieffect)

```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart) | Chart 物件 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/zh-hant/aspose.slides.animation/effectchartmajorgroupingtype) | 動畫效果的類型 [`EffectChartMinorGroupingType`](/slides/python-net/zh-hant/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | 索引 **int** |
| effect_type | [`EffectType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttype) | 動畫效果的類型 [`EffectType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/zh-hant/aspose.slides.animation/effectsubtype) | 動畫效果的子類型 [`EffectSubtype`](/slides/python-net/zh-hant/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttriggertype) | 效果的觸發類型 [`EffectTriggerType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttriggertype) |

## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
將新圖表動畫效果（針對類別或系列中的元素）新增至序列的末端。

### 傳回值

新的效果物件 [`IEffect`](/slides/python-net/zh-hant/aspose.slides.animation/ieffect)

```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart) | Chart 物件 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/zh-hant/aspose.slides.animation/effectchartminorgroupingtype) | 動畫效果的類型 [`EffectChartMinorGroupingType`](/slides/python-net/zh-hant/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | 圖表系列的索引 **int** |
| categories_index | **int** | 類別的索引 **int** |
| effect_type | [`EffectType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttype) | 動畫效果的類型 [`EffectType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/zh-hant/aspose.slides.animation/effectsubtype) | 動畫效果的子類型 [`EffectSubtype`](/slides/python-net/zh-hant/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttriggertype) | 效果的觸發類型 [`EffectTriggerType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttriggertype) |

### 另請參閱
* 列舉 [`EffectChartMajorGroupingType`](/slides/python-net/zh-hant/aspose.slides.animation/effectchartmajorgroupingtype)
* 列舉 [`EffectChartMinorGroupingType`](/slides/python-net/zh-hant/aspose.slides.animation/effectchartminorgroupingtype)
* 列舉 [`EffectSubtype`](/slides/python-net/zh-hant/aspose.slides.animation/effectsubtype)
* 列舉 [`EffectTriggerType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttriggertype)
* 列舉 [`EffectType`](/slides/python-net/zh-hant/aspose.slides.animation/effecttype)
* 類別 [`IChart`](/slides/python-net/zh-hant/aspose.slides.charts/ichart)
* 類別 [`IEffect`](/slides/python-net/zh-hant/aspose.slides.animation/ieffect)
* 類別 [`IParagraph`](/slides/python-net/zh-hant/aspose.slides/iparagraph)
* 類別 [`ISequence`](/slides/python-net/zh-hant/aspose.slides.animation/isequence)
* 類別 [`IShape`](/slides/python-net/zh-hant/aspose.slides/ishape)
* 模組 [`aspose.slides.animation`](/slides/python-net/zh-hant/aspose.slides.animation)
* 函式庫 [`Aspose.Slides`](/slides/python-net)