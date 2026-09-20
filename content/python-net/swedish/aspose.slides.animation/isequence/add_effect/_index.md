---
title: add_effect method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Lägg till en ny effekt i slutet av sekvensen.

### Returnerar

Nytt effektobjekt [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Shape-objekt [`IShape`](/slides/python-net/sv/aspose.slides/ishape) för att lägga till en effekt |
| effect_type | [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) | Typ av en animeringseffekt [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) | Undertyper av animeringseffekt [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) | Utlösningstyp för effekt [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Lägg till en ny animeringseffekt för stycket i slutet av sekvensen.

### Returnerar

Nytt effektobjekt [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/sv/aspose.slides/iparagraph) | Paragraph-objekt [`IParagraph`](/slides/python-net/sv/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) | Typ av en animeringseffekt [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) | Undertyper av animeringseffekt [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) | Utlösningstyp för effekt [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Lägger till den nya chart-animations-effekten för kategori eller serie i slutet av sekvensen.

### Returnerar

Nytt effektobjekt [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart) | Chart-objekt [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartmajorgroupingtype) | Typ av en animeringseffekt [`EffectChartMinorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Index **int** |
| effect_type | [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) | Typ av en animeringseffekt [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) | Undertyper av animeringseffekt [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) | Utlösningstyp för effekt [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Lägger till den nya chart-animations-effekten för element i kategori eller serie i slutet av sekvensen.

### Returnerar

Nytt effektobjekt [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart) | Chart-objekt [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartminorgroupingtype) | Typ av en animeringseffekt [`EffectChartMinorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Index för diagramserie **int** |
| categories_index | **int** | Index för kategori **int** |
| effect_type | [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) | Typ av en animeringseffekt [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) | Undertyper av animeringseffekt [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) | Utlösningstyp för effekt [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype) |



### Se även
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/sv/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/sv/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/sv/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/sv/aspose.slides.animation/effecttype)
* klass [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart)
* klass [`IEffect`](/slides/python-net/sv/aspose.slides.animation/ieffect)
* klass [`IParagraph`](/slides/python-net/sv/aspose.slides/iparagraph)
* klass [`ISequence`](/slides/python-net/sv/aspose.slides.animation/isequence)
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* modul [`aspose.slides.animation`](/slides/python-net/sv/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)