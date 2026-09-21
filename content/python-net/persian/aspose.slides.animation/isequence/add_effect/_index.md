---
title: add_effect method
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
افکت جدید را به انتهای دنباله اضافه می‌کند.

### بازگشت

شیء افکت جدید [`IEffect`](/slides/python-net/fa/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/fa/aspose.slides/ishape) | Shape object [`IShape`](/slides/python-net/fa/aspose.slides/ishape) برای اضافه کردن افکت |
| effect_type | [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) | نوع افکت انیمیشن [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) | نوع فعال‌ساز افکت [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
افکت انیمیشن جدید برای پاراگراف را به انتهای دنباله اضافه می‌کند.

### بازگشت

شیء افکت جدید [`IEffect`](/slides/python-net/fa/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/fa/aspose.slides/iparagraph) | Paragraph object [`IParagraph`](/slides/python-net/fa/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) | نوع افکت انیمیشن [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) | نوع فعال‌ساز افکت [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
افکت انیمیشن جدید چارت را برای دسته یا سری به انتهای دنباله اضافه می‌کند.

### بازگشت

شیء افکت جدید [`IEffect`](/slides/python-net/fa/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart) | Chart object [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartmajorgroupingtype) | نوع افکت انیمیشن [`EffectChartMinorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | شاخص **int** |
| effect_type | [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) | نوع افکت انیمیشن [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) | نوع فعال‌ساز افکت [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
افکت انیمیشن جدید چارت را برای عناصر در دسته یا سری به انتهای دنباله اضافه می‌کند.

### بازگشت

شیء افکت جدید [`IEffect`](/slides/python-net/fa/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart) | Chart object [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartminorgroupingtype) | نوع افکت انیمیشن [`EffectChartMinorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | شاخص سری چارت **int** |
| categories_index | **int** | شاخص دسته **int** |
| effect_type | [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) | نوع افکت انیمیشن [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) | زیرنوع‌های افکت انیمیشن [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) | نوع فعال‌ساز افکت [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype) |



### موارد مرتبط
* شمارش [`EffectChartMajorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartmajorgroupingtype)
* شمارش [`EffectChartMinorGroupingType`](/slides/python-net/fa/aspose.slides.animation/effectchartminorgroupingtype)
* شمارش [`EffectSubtype`](/slides/python-net/fa/aspose.slides.animation/effectsubtype)
* شمارش [`EffectTriggerType`](/slides/python-net/fa/aspose.slides.animation/effecttriggertype)
* شمارش [`EffectType`](/slides/python-net/fa/aspose.slides.animation/effecttype)
* کلاس [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart)
* کلاس [`IEffect`](/slides/python-net/fa/aspose.slides.animation/ieffect)
* کلاس [`IParagraph`](/slides/python-net/fa/aspose.slides/iparagraph)
* کلاس [`ISequence`](/slides/python-net/fa/aspose.slides.animation/isequence)
* کلاس [`IShape`](/slides/python-net/fa/aspose.slides/ishape)
* ماژول [`aspose.slides.animation`](/slides/python-net/fa/aspose.slides.animation)
* کتابخانه [`Aspose.Slides`](/slides/python-net)