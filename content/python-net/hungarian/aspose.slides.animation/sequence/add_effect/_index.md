---
title: add_effect method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Új hatást ad a sorozat végéhez.

### Visszatérési érték

New effect object [`IEffect`](/slides/python-net/hu/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | Shape objektum [`IShape`](/slides/python-net/hu/aspose.slides/ishape) egy hatás hozzáadásához |
| effect_type | [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) | Animációs hatás típusa [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) | Animációs hatás alosztályai [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) | Hatás aktiválási típusa [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Új animációs hatást ad a bekezdéshez a sorozat végén.

### Visszatérési érték

New effect object [`IEffect`](/slides/python-net/hu/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/hu/aspose.slides/iparagraph) | Paragraph objektum [`IParagraph`](/slides/python-net/hu/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) | Animációs hatás típusa [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) | Animációs hatás alosztályai [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) | Hatás aktiválási típusa [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Új diagramanimációs hatást ad a kategória vagy sorozat végéhez.

### Visszatérési érték

New effect object [`IEffect`](/slides/python-net/hu/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart) | Chart objektum [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/hu/aspose.slides.animation/effectchartmajorgroupingtype) | Animációs hatás típusa [`EffectChartMinorGroupingType`](/slides/python-net/hu/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Index **int** |
| effect_type | [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) | Animációs hatás típusa [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) | Animációs hatás alosztályai [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) | Hatás aktiválási típusa [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Új diagramanimációs hatást ad a kategória vagy sorozat elemeihez a sorozat végén.

### Visszatérési érték

New effect object [`IEffect`](/slides/python-net/hu/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart) | Chart objektum [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/hu/aspose.slides.animation/effectchartminorgroupingtype) | Animációs hatás típusa [`EffectChartMinorGroupingType`](/slides/python-net/hu/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Diagram sorozat indexe **int** |
| categories_index | **int** | Kategória indexe **int** |
| effect_type | [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) | Animációs hatás típusa [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) | Animációs hatás alosztályai [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) | Hatás aktiválási típusa [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) |



### Lásd még
* felsorolás [`EffectChartMajorGroupingType`](/slides/python-net/hu/aspose.slides.animation/effectchartmajorgroupingtype)
* felsorolás [`EffectChartMinorGroupingType`](/slides/python-net/hu/aspose.slides.animation/effectchartminorgroupingtype)
* felsorolás [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype)
* felsorolás [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype)
* felsorolás [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype)
* osztály [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart)
* osztály [`IEffect`](/slides/python-net/hu/aspose.slides.animation/ieffect)
* osztály [`IParagraph`](/slides/python-net/hu/aspose.slides/iparagraph)
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* osztály [`Sequence`](/slides/python-net/hu/aspose.slides.animation/sequence)
* modul [`aspose.slides.animation`](/slides/python-net/hu/aspose.slides.animation)
* könyvtár [`Aspose.Slides`](/slides/python-net)