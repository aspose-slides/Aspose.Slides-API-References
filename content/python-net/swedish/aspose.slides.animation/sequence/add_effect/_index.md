---
title: add_effect method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Lägg till ny effekt i slutet av sekvensen.

### Returnerar

Nytt effektobjekt [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Shape object [`IShape`](/slides/python-net/sv/aspose.slides/ishape) for adding an effect |
| effect_type | [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Lägg till ny animationseffekt för stycke i slutet av sekvensen.

### Returnerar

Nytt effektobjekt [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/sv/aspose.slides/iparagraph) | Paragraph object [`IParagraph`](/slides/python-net/sv/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Lägger till den nya diagramanimationseffekten för kategori eller serie i slutet av sekvensen.

### Returnerar

Nytt effektobjekt [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart) | Chart object [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartmajorgroupingtype) | Type of an animation effect [`EffectChartMinorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Index **int** |
| effect_type | [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Lägger till den nya diagramanimationseffekten för element i kategori eller serie i slutet av sekvensen.

### Returnerar

Nytt effektobjekt [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart) | Chart object [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartminorgroupingtype) | Type of an animation effect [`EffectChartMinorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Index of chart series **int** |
| categories_index | **int** | Index of category **int** |
| effect_type | [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) |



### Se även
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype)
* class [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart)
* class [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)
* class [`IParagraph`](/slides/python-net/sv/aspose.slides/iparagraph)
* class [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* class [`Sequence`](/slides/python-net/sv/aspose.slides.animation/sequence)
* module [`aspose.slides.animation`](/slides/python-net/sv/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)