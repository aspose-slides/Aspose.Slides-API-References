---
title: add_effect method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Fügt einen neuen Effekt am Ende der Sequenz hinzu.

### Rückgabewert

New effect object [`IEffect`](/slides/python-net/de/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Shape object [`IShape`](/slides/python-net/de/aspose.slides/ishape) for adding an effect |
| effect_type | [`EffectType`](/slides/python-net/de/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/de/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/de/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/de/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/de/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/de/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Fügt einen neuen Animations-Effekt für einen Absatz am Ende der Sequenz hinzu.

### Rückgabewert

New effect object [`IEffect`](/slides/python-net/de/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/de/aspose.slides/iparagraph) | Paragraph object [`IParagraph`](/slides/python-net/de/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/de/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/de/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/de/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/de/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/de/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/de/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Fügt den neuen Diagramm-Animations-Effekt für Kategorie oder Serie am Ende der Sequenz hinzu.

### Rückgabewert

New effect object [`IEffect`](/slides/python-net/de/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart) | Chart object [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/de/aspose.slides.animation/effectchartmajorgroupingtype) | Type of an animation effect [`EffectChartMinorGroupingType`](/slides/python-net/de/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Index **int** |
| effect_type | [`EffectType`](/slides/python-net/de/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/de/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/de/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/de/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/de/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/de/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Fügt den neuen Diagramm-Animations-Effekt für Elemente in einer Kategorie oder Serie am Ende der Sequenz hinzu.

### Rückgabewert

New effect object [`IEffect`](/slides/python-net/de/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart) | Chart object [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/de/aspose.slides.animation/effectchartminorgroupingtype) | Type of an animation effect [`EffectChartMinorGroupingType`](/slides/python-net/de/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Index of chart series **int** |
| categories_index | **int** | Index of category **int** |
| effect_type | [`EffectType`](/slides/python-net/de/aspose.slides.animation/effecttype) | Type of an animation effect [`EffectType`](/slides/python-net/de/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/de/aspose.slides.animation/effectsubtype) | Subtypes of animation effect [`EffectSubtype`](/slides/python-net/de/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/de/aspose.slides.animation/effecttriggertype) | Trigger type of effect [`EffectTriggerType`](/slides/python-net/de/aspose.slides.animation/effecttriggertype) |



### Siehe auch
* Aufzählung [`EffectChartMajorGroupingType`](/slides/python-net/de/aspose.slides.animation/effectchartmajorgroupingtype)
* Aufzählung [`EffectChartMinorGroupingType`](/slides/python-net/de/aspose.slides.animation/effectchartminorgroupingtype)
* Aufzählung [`EffectSubtype`](/slides/python-net/de/aspose.slides.animation/effectsubtype)
* Aufzählung [`EffectTriggerType`](/slides/python-net/de/aspose.slides.animation/effecttriggertype)
* Aufzählung [`EffectType`](/slides/python-net/de/aspose.slides.animation/effecttype)
* Klasse [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart)
* Klasse [`IEffect`](/slides/python-net/de/aspose.slides.animation/ieffect)
* Klasse [`IParagraph`](/slides/python-net/de/aspose.slides/iparagraph)
* Klasse [`ISequence`](/slides/python-net/de/aspose.slides.animation/isequence)
* Klasse [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* Modul [`aspose.slides.animation`](/slides/python-net/de/aspose.slides.animation)
* Bibliothek [`Aspose.Slides`](/slides/python-net)