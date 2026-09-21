---
title: add_effect method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
시퀀스 끝에 새 효과를 추가합니다.

### Returns

새 효과 객체 [`IEffect`](/slides/python-net/ko/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 효과를 추가할 Shape 객체 [`IShape`](/slides/python-net/ko/aspose.slides/ishape) |
| effect_type | [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype) | 애니메이션 효과 유형 [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype) | 애니메이션 효과 하위 유형 [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype) | 효과 트리거 유형 [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
시퀀스 끝에 단락에 대한 새 애니메이션 효과를 추가합니다.

### Returns

새 효과 객체 [`IEffect`](/slides/python-net/ko/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/ko/aspose.slides/iparagraph) | Paragraph 객체 [`IParagraph`](/slides/python-net/ko/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype) | 애니메이션 효과 유형 [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype) | 애니메이션 효과 하위 유형 [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype) | 효과 트리거 유형 [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
시퀀스 끝에 카테고리 또는 시리즈에 대한 새 차트 애니메이션 효과를 추가합니다.

### Returns

새 효과 객체 [`IEffect`](/slides/python-net/ko/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart) | Chart 객체 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/ko/aspose.slides.animation/effectchartmajorgroupingtype) | 애니메이션 효과 유형 [`EffectChartMinorGroupingType`](/slides/python-net/ko/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | 인덱스 **int** |
| effect_type | [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype) | 애니메이션 효과 유형 [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype) | 애니메이션 효과 하위 유형 [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype) | 효과 트리거 유형 [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
시퀀스 끝에 카테고리 또는 시리즈의 요소에 대한 새 차트 애니메이션 효과를 추가합니다.

### Returns

새 효과 객체 [`IEffect`](/slides/python-net/ko/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart) | Chart 객체 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/ko/aspose.slides.animation/effectchartminorgroupingtype) | 애니메이션 효과 유형 [`EffectChartMinorGroupingType`](/slides/python-net/ko/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | 차트 시리즈 인덱스 **int** |
| categories_index | **int** | 카테고리 인덱스 **int** |
| effect_type | [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype) | 애니메이션 효과 유형 [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype) | 애니메이션 효과 하위 유형 [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype) | 효과 트리거 유형 [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype) |



### See Also
* 열거형 [`EffectChartMajorGroupingType`](/slides/python-net/ko/aspose.slides.animation/effectchartmajorgroupingtype)
* 열거형 [`EffectChartMinorGroupingType`](/slides/python-net/ko/aspose.slides.animation/effectchartminorgroupingtype)
* 열거형 [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype)
* 열거형 [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype)
* 열거형 [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype)
* 클래스 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart)
* 클래스 [`IEffect`](/slides/python-net/ko/aspose.slides.animation/ieffect)
* 클래스 [`IParagraph`](/slides/python-net/ko/aspose.slides/iparagraph)
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 클래스 [`Sequence`](/slides/python-net/ko/aspose.slides.animation/sequence)
* 모듈 [`aspose.slides.animation`](/slides/python-net/ko/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)