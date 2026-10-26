---
title: add_effect method
second_title: Referencia API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Agregar nuevo efecto al final de la secuencia.

### Devuelve

Nuevo objeto de efecto [`IEffect`](/slides/python-net/es/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | Objeto Shape [`IShape`](/slides/python-net/es/aspose.slides/ishape) para agregar un efecto |
| effect_type | [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype) | Tipo de un efecto de animación [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype) | Subtipos de efecto de animación [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype) | Tipo de activación del efecto [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Agregar nuevo efecto de animación para el párrafo al final de la secuencia.

### Devuelve

Nuevo objeto de efecto [`IEffect`](/slides/python-net/es/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/es/aspose.slides/iparagraph) | Objeto Paragraph [`IParagraph`](/slides/python-net/es/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype) | Tipo de un efecto de animación [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype) | Subtipos de efecto de animación [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype) | Tipo de activación del efecto [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Agrega el nuevo efecto de animación de gráfico para categoría o serie al final de la secuencia.

### Devuelve

Nuevo objeto de efecto [`IEffect`](/slides/python-net/es/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart) | Objeto Chart [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/es/aspose.slides.animation/effectchartmajorgroupingtype) | Tipo de un efecto de animación [`EffectChartMinorGroupingType`](/slides/python-net/es/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Índice **int** |
| effect_type | [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype) | Tipo de un efecto de animación [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype) | Subtipos de efecto de animación [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype) | Tipo de activación del efecto [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Agrega el nuevo efecto de animación de gráfico para elementos en categoría o serie al final de la secuencia.

### Devuelve

Nuevo objeto de efecto [`IEffect`](/slides/python-net/es/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart) | Objeto Chart [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/es/aspose.slides.animation/effectchartminorgroupingtype) | Tipo de un efecto de animación [`EffectChartMinorGroupingType`](/slides/python-net/es/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Índice de la serie del gráfico **int** |
| categories_index | **int** | Índice de la categoría **int** |
| effect_type | [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype) | Tipo de un efecto de animación [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype) | Subtipos de efecto de animación [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype) | Tipo de activación del efecto [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype) |



### Ver también
* enumeración [`EffectChartMajorGroupingType`](/slides/python-net/es/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeración [`EffectChartMinorGroupingType`](/slides/python-net/es/aspose.slides.animation/effectchartminorgroupingtype)
* enumeración [`EffectSubtype`](/slides/python-net/es/aspose.slides.animation/effectsubtype)
* enumeración [`EffectTriggerType`](/slides/python-net/es/aspose.slides.animation/effecttriggertype)
* enumeración [`EffectType`](/slides/python-net/es/aspose.slides.animation/effecttype)
* clase [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart)
* clase [`IEffect`](/slides/python-net/es/aspose.slides.animation/ieffect)
* clase [`IParagraph`](/slides/python-net/es/aspose.slides/iparagraph)
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* clase [`Sequence`](/slides/python-net/es/aspose.slides.animation/sequence)
* módulo [`aspose.slides.animation`](/slides/python-net/es/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)