---
title: add_effect method
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Új hatás hozzáadása a sorozat végéhez.

### Returns
Új hatás objektum [`IEffect`](/slides/python-net/hu/aspose.slides.animation/ieffect)

```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | Shape objektum [`IShape`](/slides/python-net/hu/aspose.slides/ishape) egy hatás hozzáadásához |
| effect_type | [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) | Animációs hatás típusa [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) | Animációs hatás altípusai [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) | Hatás indítási típusa [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) |

## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Új animációs hatás hozzáadása a bekezdéshez a sorozat végéhez.

### Returns
Új hatás objektum [`IEffect`](/slides/python-net/hu/aspose.slides.animation/ieffect)

```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/hu/aspose.slides/iparagraph) | Paragraph objektum [`IParagraph`](/slides/python-net/hu/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) | Animációs hatás típusa [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) | Animációs hatás altípusai [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) | Hatás indítási típusa [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) |

## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Új diagram animációs hatás hozzáadása kategóriához vagy sorozathoz a sorozat végére.

### Returns
Új hatás objektum [`IEffect`](/slides/python-net/hu/aspose.slides.animation/ieffect)

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
| subtype | [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) | Animációs hatás altípusai [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) | Hatás indítási típusa [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) |

## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Új diagram animációs hatás hozzáadása elemhez a kategóriában vagy sorozatban a sorozat végére.

### Returns
Új hatás objektum [`IEffect`](/slides/python-net/hu/aspose.slides.animation/ieffect)

```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart) | Chart objektum [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/hu/aspose.slides.animation/effectchartminorgroupingtype) | Animációs hatás típusa [`EffectChartMinorGroupingType`](/slides/python-net/hu/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Diagram sorozat index **int** |
| categories_index | **int** | Kategória index **int** |
| effect_type | [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) | Animációs hatás típusa [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) | Animációs hatás altípusai [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) | Hatás indítási típusa [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype) |

### See Also
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/hu/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/hu/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/hu/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/hu/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/hu/aspose.slides.animation/effecttype)
* class [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart)
* class [`IEffect`](/slides/python-net/hu/aspose.slides.animation/ieffect)
* class [`IParagraph`](/slides/python-net/hu/aspose.slides/iparagraph)
* class [`ISequence`](/slides/python-net/hu/aspose.slides.animation/isequence)
* class [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* module [`aspose.slides.animation`](/slides/python-net/hu/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)