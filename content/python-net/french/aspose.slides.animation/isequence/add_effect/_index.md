---
title: add_effect method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Ajoute un nouvel effet à la fin de la séquence.

### Renvoie

Nouvel objet d'effet [`IEffect`](/slides/python-net/fr/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/fr/aspose.slides/ishape) | Objet Shape [`IShape`](/slides/python-net/fr/aspose.slides/ishape) pour ajouter un effet |
| effect_type | [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype) | Type d'un effet d'animation [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype) | Sous-types d'un effet d'animation [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype) | Type de déclenchement de l'effet [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Ajoute un nouvel effet d'animation pour le paragraphe à la fin de la séquence.

### Renvoie

Nouvel objet d'effet [`IEffect`](/slides/python-net/fr/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/fr/aspose.slides/iparagraph) | Objet Paragraph [`IParagraph`](/slides/python-net/fr/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype) | Type d'un effet d'animation [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype) | Sous-types d'un effet d'animation [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype) | Type de déclenchement de l'effet [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Ajoute le nouvel effet d'animation de graphique pour une catégorie ou une série à la fin de la séquence.

### Renvoie

Nouvel objet d'effet [`IEffect`](/slides/python-net/fr/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart) | Objet Chart [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/fr/aspose.slides.animation/effectchartmajorgroupingtype) | Type d'un effet d'animation [`EffectChartMinorGroupingType`](/slides/python-net/fr/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Index **int** |
| effect_type | [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype) | Type d'un effet d'animation [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype) | Sous-types d'un effet d'animation [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype) | Type de déclenchement de l'effet [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Ajoute le nouvel effet d'animation de graphique pour les éléments d'une catégorie ou d'une série à la fin de la séquence.

### Renvoie

Nouvel objet d'effet [`IEffect`](/slides/python-net/fr/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart) | Objet Chart [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/fr/aspose.slides.animation/effectchartminorgroupingtype) | Type d'un effet d'animation [`EffectChartMinorGroupingType`](/slides/python-net/fr/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Index de la série de graphique **int** |
| categories_index | **int** | Index de la catégorie **int** |
| effect_type | [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype) | Type d'un effet d'animation [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype) | Sous-types d'un effet d'animation [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype) | Type de déclenchement de l'effet [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype) |



### Voir aussi
* énumération [`EffectChartMajorGroupingType`](/slides/python-net/fr/aspose.slides.animation/effectchartmajorgroupingtype)
* énumération [`EffectChartMinorGroupingType`](/slides/python-net/fr/aspose.slides.animation/effectchartminorgroupingtype)
* énumération [`EffectSubtype`](/slides/python-net/fr/aspose.slides.animation/effectsubtype)
* énumération [`EffectTriggerType`](/slides/python-net/fr/aspose.slides.animation/effecttriggertype)
* énumération [`EffectType`](/slides/python-net/fr/aspose.slides.animation/effecttype)
* classe [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart)
* classe [`IEffect`](/slides/python-net/fr/aspose.slides.animation/ieffect)
* classe [`IParagraph`](/slides/python-net/fr/aspose.slides/iparagraph)
* classe [`ISequence`](/slides/python-net/fr/aspose.slides.animation/isequence)
* classe [`IShape`](/slides/python-net/fr/aspose.slides/ishape)
* module [`aspose.slides.animation`](/slides/python-net/fr/aspose.slides.animation)
* bibliothèque [`Aspose.Slides`](/slides/python-net)