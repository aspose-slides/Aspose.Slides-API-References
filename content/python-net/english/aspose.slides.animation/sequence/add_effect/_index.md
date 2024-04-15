---
title: add_effect method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.animation/sequence/add_effect/
weight: 10
---


## add_effect {#ishape-effecttype-effectsubtype-effecttriggertype}
Add new effect to the end of sequence.

### Returns

New effect object [`IEffect`](/slides/python-net/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/aspose.slides/ishape) | Shape object [`IShape`](/slides/python-net/aspose.slides/ishape) for adding an effect |
| effect_type | [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype) |



## add_effect {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Add new animation effect for paragraph to the end of sequence.

### Returns

New effect object [`IEffect`](/slides/python-net/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/aspose.slides/iparagraph) | Paragraph object [`IParagraph`](/slides/python-net/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype) |



## add_effect {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Adds the new chart animation effect for category or series to the end of sequence.

### Returns

New effect object [`IEffect`](/slides/python-net/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/aspose.slides.charts/ichart) | Chart object [`IChart`](/slides/python-net/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/aspose.slides.animation/effectchartmajorgroupingtype) | Type of an animation effect [`EffectChartMinorGroupingType`](/slides/python-net/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Index **int** |
| effect_type | [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype) |



## add_effect {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Adds the new chart animation effect for elements in category or series to the end of sequence.

### Returns

New effect object [`IEffect`](/slides/python-net/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/aspose.slides.charts/ichart) | Chart object [`IChart`](/slides/python-net/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/aspose.slides.animation/effectchartminorgroupingtype) | Type of an animation effect [`EffectChartMinorGroupingType`](/slides/python-net/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Index of chart series **int** |
| categories_index | **int** | Index of category **int** |
| effect_type | [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype) |



### See Also
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/aspose.slides.animation/effecttype)
* class [`IChart`](/slides/python-net/aspose.slides.charts/ichart)
* class [`IEffect`](/slides/python-net/aspose.slides.animation/ieffect)
* class [`IParagraph`](/slides/python-net/aspose.slides/iparagraph)
* class [`IShape`](/slides/python-net/aspose.slides/ishape)
* class [`Sequence`](/slides/python-net/aspose.slides.animation/sequence)
* module [`aspose.slides.animation`](/slides/python-net/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)
