---
title: add_effect method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Voeg een nieuw effect toe aan het einde van de reeks.

### Retour

Nieuw effectobject [`IEffect`](/slides/python-net/nl/aspose.slides.animation/ieffect)

```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/nl/aspose.slides/ishape) | Shape object [`IShape`](/slides/python-net/nl/aspose.slides/ishape) voor het toevoegen van een effect |
| effect_type | [`EffectType`](/slides/python-net/nl/aspose.slides.animation/effecttype) | Type van een animatie-effect [`EffectType`](/slides/python-net/nl/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/nl/aspose.slides.animation/effectsubtype) | Subtypen van animatie-effect [`EffectSubtype`](/slides/python-net/nl/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/nl/aspose.slides.animation/effecttriggertype) | Trigger-type van effect [`EffectTriggerType`](/slides/python-net/nl/aspose.slides.animation/effecttriggertype) |

## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Voeg een nieuw animatie-effect voor alinea toe aan het einde van de reeks.

### Retour

Nieuw effectobject [`IEffect`](/slides/python-net/nl/aspose.slides.animation/ieffect)

```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/nl/aspose.slides/iparagraph) | Paragraph-object [`IParagraph`](/slides/python-net/nl/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/nl/aspose.slides.animation/effecttype) | Type van een animatie-effect [`EffectType`](/slides/python-net/nl/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/nl/aspose.slides.animation/effectsubtype) | Subtypen van animatie-effect [`EffectSubtype`](/slides/python-net/nl/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/nl/aspose.slides.animation/effecttriggertype) | Trigger-type van effect [`EffectTriggerType`](/slides/python-net/nl/aspose.slides.animation/effecttriggertype) |

## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Voegt het nieuwe diagram-animatie-effect voor categorie of serie toe aan het einde van de reeks.

### Retour

Nieuw effectobject [`IEffect`](/slides/python-net/nl/aspose.slides.animation/ieffect)

```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart) | Chart-object [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/nl/aspose.slides.animation/effectchartmajorgroupingtype) | Type van een animatie-effect [`EffectChartMinorGroupingType`](/slides/python-net/nl/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Index **int** |
| effect_type | [`EffectType`](/slides/python-net/nl/aspose.slides.animation/effecttype) | Type van een animatie-effect [`EffectType`](/slides/python-net/nl/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/nl/aspose.slides.animation/effectsubtype) | Subtypen van animatie-effect [`EffectSubtype`](/slides/python-net/nl/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/nl/aspose.slides.animation/effecttriggertype) | Trigger-type van effect [`EffectTriggerType`](/slides/python-net/nl/aspose.slides.animation/effecttriggertype) |

## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Voegt het nieuwe diagram-animatie-effect toe voor elementen in categorie of serie aan het einde van de reeks.

### Retour

Nieuw effectobject [`IEffect`](/slides/python-net/nl/aspose.slides.animation/ieffect)

```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart) | Chart-object [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/nl/aspose.slides.animation/effectchartminorgroupingtype) | Type van een animatie-effect [`EffectChartMinorGroupingType`](/slides/python-net/nl/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Index van chart-series **int** |
| categories_index | **int** | Index van categorie **int** |
| effect_type | [`EffectType`](/slides/python-net/nl/aspose.slides.animation/effecttype) | Type van een animatie-effect [`EffectType`](/slides/python-net/nl/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/nl/aspose.slides.animation/effectsubtype) | Subtypen van animatie-effect [`EffectSubtype`](/slides/python-net/nl/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/nl/aspose.slides.animation/effecttriggertype) | Trigger-type van effect [`EffectTriggerType`](/slides/python-net/nl/aspose.slides.animation/effecttriggertype) |

### Zie ook
* enumeratie [`EffectChartMajorGroupingType`](/slides/python-net/nl/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeratie [`EffectChartMinorGroupingType`](/slides/python-net/nl/aspose.slides.animation/effectchartminorgroupingtype)
* enumeratie [`EffectSubtype`](/slides/python-net/nl/aspose.slides.animation/effectsubtype)
* enumeratie [`EffectTriggerType`](/slides/python-net/nl/aspose.slides.animation/effecttriggertype)
* enumeratie [`EffectType`](/slides/python-net/nl/aspose.slides.animation/effecttype)
* klasse [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart)
* klasse [`IEffect`](/slides/python-net/nl/aspose.slides.animation/ieffect)
* klasse [`IParagraph`](/slides/python-net/nl/aspose.slides/iparagraph)
* klasse [`IShape`](/slides/python-net/nl/aspose.slides/ishape)
* klasse [`Sequence`](/slides/python-net/nl/aspose.slides.animation/sequence)
* module [`aspose.slides.animation`](/slides/python-net/nl/aspose.slides.animation)
* bibliotheek [`Aspose.Slides`](/slides/python-net)