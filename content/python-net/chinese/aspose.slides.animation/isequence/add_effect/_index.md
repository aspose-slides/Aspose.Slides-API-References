---
title: add_effect method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
在序列末尾添加新效果。

### Returns

新的效果对象 [`IEffect`](/slides/python-net/zh/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | Shape 对象 [`IShape`](/slides/python-net/zh/aspose.slides/ishape) 用于添加效果 |
| effect_type | [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype) | 动画效果的类型 [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype) | 动画效果的子类型 [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype) | 效果的触发类型 [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
在序列末尾为段落添加新的动画效果。

### Returns

新的效果对象 [`IEffect`](/slides/python-net/zh/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/zh/aspose.slides/iparagraph) | Paragraph 对象 [`IParagraph`](/slides/python-net/zh/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype) | 动画效果的类型 [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype) | 动画效果的子类型 [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype) | 效果的触发类型 [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
在序列末尾为类别或系列添加新的图表动画效果。

### Returns

新的效果对象 [`IEffect`](/slides/python-net/zh/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart) | Chart 对象 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/zh/aspose.slides.animation/effectchartmajorgroupingtype) | 动画效果的类型 [`EffectChartMinorGroupingType`](/slides/python-net/zh/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | 索引 **int** |
| effect_type | [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype) | 动画效果的类型 [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype) | 动画效果的子类型 [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype) | 效果的触发类型 [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
在序列末尾为类别或系列中的元素添加新的图表动画效果。

### Returns

新的效果对象 [`IEffect`](/slides/python-net/zh/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart) | Chart 对象 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/zh/aspose.slides.animation/effectchartminorgroupingtype) | 动画效果的类型 [`EffectChartMinorGroupingType`](/slides/python-net/zh/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | 图表系列的索引 **int** |
| categories_index | **int** | 类别的索引 **int** |
| effect_type | [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype) | 动画效果的类型 [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype) | 动画效果的子类型 [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype) | 效果的触发类型 [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype) |



### 另请参阅
* 枚举 [`EffectChartMajorGroupingType`](/slides/python-net/zh/aspose.slides.animation/effectchartmajorgroupingtype)
* 枚举 [`EffectChartMinorGroupingType`](/slides/python-net/zh/aspose.slides.animation/effectchartminorgroupingtype)
* 枚举 [`EffectSubtype`](/slides/python-net/zh/aspose.slides.animation/effectsubtype)
* 枚举 [`EffectTriggerType`](/slides/python-net/zh/aspose.slides.animation/effecttriggertype)
* 枚举 [`EffectType`](/slides/python-net/zh/aspose.slides.animation/effecttype)
* 类 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)
* 类 [`IEffect`](/slides/python-net/zh/aspose.slides.animation/ieffect)
* 类 [`IParagraph`](/slides/python-net/zh/aspose.slides/iparagraph)
* 类 [`ISequence`](/slides/python-net/zh/aspose.slides.animation/isequence)
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)