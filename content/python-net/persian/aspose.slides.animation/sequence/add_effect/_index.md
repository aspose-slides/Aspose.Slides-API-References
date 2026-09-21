---
title: add_effect method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
اثر جدیدی را به انتهای توالی اضافه می‌کند.

### بازگشت

New effect object [`IEffect`](/slides/python-net/fa/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/fa/aspose.slides/ishape) | Shape object [`IShape`](/slides/python-net/fa/aspose.slides/ishape) for adding an effect |
| effect_type | [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
اثر انیمیشن جدیدی برای پاراگراف به انتهای توالی اضافه می‌کند.

### بازگشت

New effect object [`IEffect`](/slides/python-net/fa/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/fa/aspose.slides/iparagraph) | Paragraph object [`IParagraph`](/slides/python-net/fa/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
اثر انیمیشن جدید نمودار را برای دسته یا سری به انتهای توالی اضافه می‌کند.

### بازگشت

New effect object [`IEffect`](/slides/python-net/fa/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart) | Chart object [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartmajorgroupingtype) | Type of an animation effect [`EffectChartMinorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Index **int** |
| effect_type | [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
اثر انیمیشن جدید نمودار را برای عناصر در دسته یا سری به انتهای توالی اضافه می‌کند.

### بازگشت

New effect object [`IEffect`](/slides/python-net/fa/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart) | Chart object [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartminorgroupingtype) | Type of an animation effect [`EffectChartMinorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Index of chart series **int** |
| categories_index | **int** | Index of category **int** |
| effect_type | [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) |



### موارد مرتبط
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype)
* کلاس [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart)
* کلاس [`IEffect`](/slides/python-net/fa/aspose.slides.animation/ieffect)
* کلاس [`IParagraph`](/slides/python-net/fa/aspose.slides/iparagraph)
* کلاس [`IShape`](/slides/python-net/fa/aspose.slides/ishape)
* کلاس [`Sequence`](/slides/python-net/fa/aspose.slides.animation/sequence)
* ماژول [`aspose.slides.animation`](/slides/python-net/fa/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)