---
title: add_effect method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Přidá nový efekt na konec sekvence.

### Návratová hodnota

Nový objekt efektu [`IEffect`](/slides/python-net/cs/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) | Objekt Shape [`IShape`](/slides/python-net/cs/aspose.slides/ishape) pro přidání efektu |
| effect_type | [`EffectType`](/slides/python-net/cs/aspose.slides.animation/effecttype) | Typ animačního efektu [`EffectType`](/slides/python-net/cs/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/cs/aspose.slides.animation/effectsubtype) | Podtypy animačního efektu [`EffectSubtype`](/slides/python-net/cs/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/cs/aspose.slides.animation/effecttriggertype) | Typ spouštěče efektu [`EffectTriggerType`](/slides/python-net/cs/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Přidá nový animační efekt pro odstavec na konec sekvence.

### Návratová hodnota

Nový objekt efektu [`IEffect`](/slides/python-net/cs/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/cs/aspose.slides/iparagraph) | Objekt Paragraph [`IParagraph`](/slides/python-net/cs/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/cs/aspose.slides.animation/effecttype) | Typ animačního efektu [`EffectType`](/slides/python-net/cs/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/cs/aspose.slides.animation/effectsubtype) | Podtypy animačního efektu [`EffectSubtype`](/slides/python-net/cs/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/cs/aspose.slides.animation/effecttriggertype) | Typ spouštěče efektu [`EffectTriggerType`](/slides/python-net/cs/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Přidá nový animační efekt grafu pro kategorii nebo sérii na konec sekvence.

### Návratová hodnota

Nový objekt efektu [`IEffect`](/slides/python-net/cs/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart) | Objekt Chart [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/cs/aspose.slides.animation/effectchartmajorgroupingtype) | Typ animačního efektu [`EffectChartMinorGroupingType`](/slides/python-net/cs/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Index **int** |
| effect_type | [`EffectType`](/slides/python-net/cs/aspose.slides.animation/effecttype) | Typ animačního efektu [`EffectType`](/slides/python-net/cs/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/cs/aspose.slides.animation/effectsubtype) | Podtypy animačního efektu [`EffectSubtype`](/slides/python-net/cs/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/cs/aspose.slides.animation/effecttriggertype) | Typ spouštěče efektu [`EffectTriggerType`](/slides/python-net/cs/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Přidá nový animační efekt grafu pro prvky v kategorii nebo sérii na konec sekvence.

### Návratová hodnota

Nový objekt efektu [`IEffect`](/slides/python-net/cs/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart) | Objekt Chart [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/cs/aspose.slides.animation/effectchartminorgroupingtype) | Typ animačního efektu [`EffectChartMinorGroupingType`](/slides/python-net/cs/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Index řady grafu **int** |
| categories_index | **int** | Index kategorie **int** |
| effect_type | [`EffectType`](/slides/python-net/cs/aspose.slides.animation/effecttype) | Typ animačního efektu [`EffectType`](/slides/python-net/cs/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/cs/aspose.slides.animation/effectsubtype) | Podtypy animačního efektu [`EffectSubtype`](/slides/python-net/cs/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/cs/aspose.slides.animation/effecttriggertype) | Typ spouštěče efektu [`EffectTriggerType`](/slides/python-net/cs/aspose.slides.animation/effecttriggertype) |



### Viz také
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/cs/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/cs/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/cs/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/cs/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/cs/aspose.slides.animation/effecttype)
* třída [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart)
* třída [`IEffect`](/slides/python-net/cs/aspose.slides.animation/ieffect)
* třída [`IParagraph`](/slides/python-net/cs/aspose.slides/iparagraph)
* třída [`ISequence`](/slides/python-net/cs/aspose.slides.animation/isequence)
* třída [`IShape`](/slides/python-net/cs/aspose.slides/ishape)
* modul [`aspose.slides.animation`](/slides/python-net/cs/aspose.slides.animation)
* knihovna [`Aspose.Slides`](/slides/python-net)