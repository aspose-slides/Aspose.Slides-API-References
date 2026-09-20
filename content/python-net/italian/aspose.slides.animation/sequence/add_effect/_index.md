---
title: add_effect method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Aggiungi un nuovo effetto alla fine della sequenza.

### Restituisce

Nuovo oggetto effetto [`IEffect`](/slides/python-net/it/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Oggetto Shape [`IShape`](/slides/python-net/it/aspose.slides/ishape) per aggiungere un effetto |
| effect_type | [`EffectType`](/slides/python-net/it/aspose.slides.animation/effecttype) | Tipo di un effetto di animazione [`EffectType`](/slides/python-net/it/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/it/aspose.slides.animation/effectsubtype) | Sottotipi di effetto di animazione [`EffectSubtype`](/slides/python-net/it/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/it/aspose.slides.animation/effecttriggertype) | Tipo di attivazione dell'effetto [`EffectTriggerType`](/slides/python-net/it/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Aggiungi un nuovo effetto di animazione per il paragrafo alla fine della sequenza.

### Restituisce

Nuovo oggetto effetto [`IEffect`](/slides/python-net/it/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/it/aspose.slides/iparagraph) | Oggetto Paragraph [`IParagraph`](/slides/python-net/it/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/it/aspose.slides.animation/effecttype) | Tipo di un effetto di animazione [`EffectType`](/slides/python-net/it/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/it/aspose.slides.animation/effectsubtype) | Sottotipi di effetto di animazione [`EffectSubtype`](/slides/python-net/it/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/it/aspose.slides.animation/effecttriggertype) | Tipo di attivazione dell'effetto [`EffectTriggerType`](/slides/python-net/it/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Aggiunge il nuovo effetto di animazione del grafico per categoria o serie alla fine della sequenza.

### Restituisce

Nuovo oggetto effetto [`IEffect`](/slides/python-net/it/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart) | Oggetto Chart [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/it/aspose.slides.animation/effectchartmajorgroupingtype) | Tipo di un effetto di animazione [`EffectChartMinorGroupingType`](/slides/python-net/it/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Indice **int** |
| effect_type | [`EffectType`](/slides/python-net/it/aspose.slides.animation/effecttype) | Tipo di un effetto di animazione [`EffectType`](/slides/python-net/it/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/it/aspose.slides.animation/effectsubtype) | Sottotipi di effetto di animazione [`EffectSubtype`](/slides/python-net/it/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/it/aspose.slides.animation/effecttriggertype) | Tipo di attivazione dell'effetto [`EffectTriggerType`](/slides/python-net/it/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Aggiunge il nuovo effetto di animazione del grafico per gli elementi nella categoria o nella serie alla fine della sequenza.

### Restituisce

Nuovo oggetto effetto [`IEffect`](/slides/python-net/it/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart) | Oggetto Chart [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/it/aspose.slides.animation/effectchartminorgroupingtype) | Tipo di un effetto di animazione [`EffectChartMinorGroupingType`](/slides/python-net/it/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Indice della serie del grafico **int** |
| categories_index | **int** | Indice della categoria **int** |
| effect_type | [`EffectType`](/slides/python-net/it/aspose.slides.animation/effecttype) | Tipo di un effetto di animazione [`EffectType`](/slides/python-net/it/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/it/aspose.slides.animation/effectsubtype) | Sottotipi di effetto di animazione [`EffectSubtype`](/slides/python-net/it/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/it/aspose.slides.animation/effecttriggertype) | Tipo di attivazione dell'effetto [`EffectTriggerType`](/slides/python-net/it/aspose.slides.animation/effecttriggertype) |



### Vedi anche
* enumerazione [`EffectChartMajorGroupingType`](/slides/python-net/it/aspose.slides.animation/effectchartmajorgroupingtype)
* enumerazione [`EffectChartMinorGroupingType`](/slides/python-net/it/aspose.slides.animation/effectchartminorgroupingtype)
* enumerazione [`EffectSubtype`](/slides/python-net/it/aspose.slides.animation/effectsubtype)
* enumerazione [`EffectTriggerType`](/slides/python-net/it/aspose.slides.animation/effecttriggertype)
* enumerazione [`EffectType`](/slides/python-net/it/aspose.slides.animation/effecttype)
* classe [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart)
* classe [`IEffect`](/slides/python-net/it/aspose.slides.animation/ieffect)
* classe [`IParagraph`](/slides/python-net/it/aspose.slides/iparagraph)
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* classe [`Sequence`](/slides/python-net/it/aspose.slides.animation/sequence)
* modulo [`aspose.slides.animation`](/slides/python-net/it/aspose.slides.animation)
* libreria [`Aspose.Slides`](/slides/python-net)