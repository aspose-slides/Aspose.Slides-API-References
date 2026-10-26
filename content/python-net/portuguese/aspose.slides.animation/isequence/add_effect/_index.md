---
title: add_effect method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Adiciona um novo efeito ao final da sequência.

### Retorna

Novo objeto de efeito [`IEffect`](/slides/python-net/pt/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | objeto Shape [`IShape`](/slides/python-net/pt/aspose.slides/ishape) para adicionar um efeito |
| effect_type | [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) | Tipo de um efeito de animação [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) | Subtipos de efeito de animação [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) | Tipo de gatilho do efeito [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Adiciona um novo efeito de animação para o parágrafo ao final da sequência.

### Retorna

Novo objeto de efeito [`IEffect`](/slides/python-net/pt/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/pt/aspose.slides/iparagraph) | objeto Paragraph [`IParagraph`](/slides/python-net/pt/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) | Tipo de um efeito de animação [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) | Subtipos de efeito de animação [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) | Tipo de gatilho do efeito [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Adiciona o novo efeito de animação de gráfico para categoria ou série ao final da sequência.

### Retorna

Novo objeto de efeito [`IEffect`](/slides/python-net/pt/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart) | objeto Chart [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/pt/aspose.slides.animation/effectchartmajorgroupingtype) | Tipo de um efeito de animação [`EffectChartMinorGroupingType`](/slides/python-net/pt/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Índice **int** |
| effect_type | [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) | Tipo de um efeito de animação [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) | Subtipos de efeito de animação [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) | Tipo de gatilho do efeito [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Adiciona o novo efeito de animação de gráfico para elementos em categoria ou série ao final da sequência.

### Retorna

Novo objeto de efeito [`IEffect`](/slides/python-net/pt/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart) | objeto Chart [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/pt/aspose.slides.animation/effectchartminorgroupingtype) | Tipo de um efeito de animação [`EffectChartMinorGroupingType`](/slides/python-net/pt/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Índice da série de chart **int** |
| categories_index | **int** | Índice da categoria **int** |
| effect_type | [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) | Tipo de um efeito de animação [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) | Subtipos de efeito de animação [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) | Tipo de gatilho do efeito [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype) |



### Veja Também
* enumeração [`EffectChartMajorGroupingType`](/slides/python-net/pt/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeração [`EffectChartMinorGroupingType`](/slides/python-net/pt/aspose.slides.animation/effectchartminorgroupingtype)
* enumeração [`EffectSubtype`](/slides/python-net/pt/aspose.slides.animation/effectsubtype)
* enumeração [`EffectTriggerType`](/slides/python-net/pt/aspose.slides.animation/effecttriggertype)
* enumeração [`EffectType`](/slides/python-net/pt/aspose.slides.animation/effecttype)
* classe [`IChart`](/slides/python-net/pt/aspose.slides.charts/ichart)
* classe [`IEffect`](/slides/python-net/pt/aspose.slides.animation/ieffect)
* classe [`IParagraph`](/slides/python-net/pt/aspose.slides/iparagraph)
* classe [`ISequence`](/slides/python-net/pt/aspose.slides.animation/isequence)
* classe [`IShape`](/slides/python-net/pt/aspose.slides/ishape)
* módulo [`aspose.slides.animation`](/slides/python-net/pt/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)