---
title: add_effect method
second_title: Aspose.Slides dla Pythona via .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Dodaj nowy efekt na koniec sekwencji.

### Zwraca

Nowy obiekt efektu [`IEffect`](/slides/python-net/pl/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) | Obiekt Shape [`IShape`](/slides/python-net/pl/aspose.slides/ishape) do dodawania efektu |
| effect_type | [`EffectType`](/slides/python-net/pl/aspose.slides.animation/effecttype) | Typ efektu animacji [`EffectType`](/slides/python-net/pl/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/pl/aspose.slides.animation/effectsubtype) | Podtypy efektu animacji [`EffectSubtype`](/slides/python-net/pl/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/pl/aspose.slides.animation/effecttriggertype) | Typ wyzwalania efektu [`EffectTriggerType`](/slides/python-net/pl/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Dodaj nowy efekt animacji dla akapitu na koniec sekwencji.

### Zwraca

Nowy obiekt efektu [`IEffect`](/slides/python-net/pl/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/pl/aspose.slides/iparagraph) | Obiekt Paragraph [`IParagraph`](/slides/python-net/pl/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/pl/aspose.slides.animation/effecttype) | Typ efektu animacji [`EffectType`](/slides/python-net/pl/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/pl/aspose.slides.animation/effectsubtype) | Podtypy efektu animacji [`EffectSubtype`](/slides/python-net/pl/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/pl/aspose.slides.animation/effecttriggertype) | Typ wyzwalania efektu [`EffectTriggerType`](/slides/python-net/pl/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Dodaje nowy efekt animacji wykresu dla kategorii lub serii na koniec sekwencji.

### Zwraca

Nowy obiekt efektu [`IEffect`](/slides/python-net/pl/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart) | Obiekt Chart [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/pl/aspose.slides.animation/effectchartmajorgroupingtype) | Typ efektu animacji [`EffectChartMinorGroupingType`](/slides/python-net/pl/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Indeks **int** |
| effect_type | [`EffectType`](/slides/python-net/pl/aspose.slides.animation/effecttype) | Typ efektu animacji [`EffectType`](/slides/python-net/pl/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/pl/aspose.slides.animation/effectsubtype) | Podtypy efektu animacji [`EffectSubtype`](/slides/python-net/pl/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/pl/aspose.slides.animation/effecttriggertype) | Typ wyzwalania efektu [`EffectTriggerType`](/slides/python-net/pl/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Dodaje nowy efekt animacji wykresu dla elementów w kategorii lub serii na koniec sekwencji.

### Zwraca

Nowy obiekt efektu [`IEffect`](/slides/python-net/pl/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart) | Obiekt Chart [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/pl/aspose.slides.animation/effectchartminorgroupingtype) | Typ efektu animacji [`EffectChartMinorGroupingType`](/slides/python-net/pl/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Indeks serii wykresu **int** |
| categories_index | **int** | Indeks kategorii **int** |
| effect_type | [`EffectType`](/slides/python-net/pl/aspose.slides.animation/effecttype) | Typ efektu animacji [`EffectType`](/slides/python-net/pl/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/pl/aspose.slides.animation/effectsubtype) | Podtypy efektu animacji [`EffectSubtype`](/slides/python-net/pl/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/pl/aspose.slides.animation/effecttriggertype) | Typ wyzwalania efektu [`EffectTriggerType`](/slides/python-net/pl/aspose.slides.animation/effecttriggertype) |



### Zobacz także
* enumeracja [`EffectChartMajorGroupingType`](/slides/python-net/pl/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeracja [`EffectChartMinorGroupingType`](/slides/python-net/pl/aspose.slides.animation/effectchartminorgroupingtype)
* enumeracja [`EffectSubtype`](/slides/python-net/pl/aspose.slides.animation/effectsubtype)
* enumeracja [`EffectTriggerType`](/slides/python-net/pl/aspose.slides.animation/effecttriggertype)
* enumeracja [`EffectType`](/slides/python-net/pl/aspose.slides.animation/effecttype)
* klasa [`IChart`](/slides/python-net/pl/aspose.slides.charts/ichart)
* klasa [`IEffect`](/slides/python-net/pl/aspose.slides.animation/ieffect)
* klasa [`IParagraph`](/slides/python-net/pl/aspose.slides/iparagraph)
* klasa [`IShape`](/slides/python-net/pl/aspose.slides/ishape)
* klasa [`Sequence`](/slides/python-net/pl/aspose.slides.animation/sequence)
* moduł [`aspose.slides.animation`](/slides/python-net/pl/aspose.slides.animation)
* biblioteka [`Aspose.Slides`](/slides/python-net)