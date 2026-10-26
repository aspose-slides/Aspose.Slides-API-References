---
title: add_effect method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Προσθέτει νέο εφέ στο τέλος της ακολουθίας.

### Returns

New effect object [`IEffect`](/slides/python-net/el/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/el/aspose.slides/ishape) | Αντικείμενο Shape [`IShape`](/slides/python-net/el/aspose.slides/ishape) για την προσθήκη ενός εφέ |
| effect_type | [`EffectType`](/slides/python-net/el/aspose.slides.animation/effecttype) | Τύπος εφέ κίνησης [`EffectType`](/slides/python-net/el/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/el/aspose.slides.animation/effectsubtype) | Υποτύποι εφέ κίνησης [`EffectSubtype`](/slides/python-net/el/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/el/aspose.slides.animation/effecttriggertype) | Τύπος ενεργοποίησης εφέ [`EffectTriggerType`](/slides/python-net/el/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Προσθέτει νέο εφέ κίνησης για παράγραφο στο τέλος της ακολουθίας.

### Returns

New effect object [`IEffect`](/slides/python-net/el/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/el/aspose.slides/iparagraph) | Αντικείμενο Paragraph [`IParagraph`](/slides/python-net/el/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/el/aspose.slides.animation/effecttype) | Τύπος εφέ κίνησης [`EffectType`](/slides/python-net/el/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/el/aspose.slides.animation/effectsubtype) | Υποτύποι εφέ κίνησης [`EffectSubtype`](/slides/python-net/el/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/el/aspose.slides.animation/effecttriggertype) | Τύπος ενεργοποίησης εφέ [`EffectTriggerType`](/slides/python-net/el/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Προσθέτει το νέο εφέ κίνησης διαγράμματος για κατηγορία ή σειρά στο τέλος της ακολουθίας.

### Returns

New effect object [`IEffect`](/slides/python-net/el/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart) | Αντικείμενο Chart [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/el/aspose.slides.animation/effectchartmajorgroupingtype) | Τύπος εφέ κίνησης [`EffectChartMinorGroupingType`](/slides/python-net/el/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Δείκτης **int** |
| effect_type | [`EffectType`](/slides/python-net/el/aspose.slides.animation/effecttype) | Τύπος εφέ κίνησης [`EffectType`](/slides/python-net/el/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/el/aspose.slides.animation/effectsubtype) | Υποτύποι εφέ κίνησης [`EffectSubtype`](/slides/python-net/el/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/el/aspose.slides.animation/effecttriggertype) | Τύπος ενεργοποίησης εφέ [`EffectTriggerType`](/slides/python-net/el/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Προσθέτει το νέο εφέ κίνησης διαγράμματος για στοιχεία σε κατηγορία ή σειρά στο τέλος της ακολουθίας.

### Returns

New effect object [`IEffect`](/slides/python-net/el/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart) | Αντικείμενο Chart [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/el/aspose.slides.animation/effectchartminorgroupingtype) | Τύπος εφέ κίνησης [`EffectChartMinorGroupingType`](/slides/python-net/el/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Δείκτης σειράς διαγράμματος **int** |
| categories_index | **int** | Δείκτης κατηγορίας **int** |
| effect_type | [`EffectType`](/slides/python-net/el/aspose.slides.animation/effecttype) | Τύπος εφέ κίνησης [`EffectType`](/slides/python-net/el/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/el/aspose.slides.animation/effectsubtype) | Υποτύποι εφέ κίνησης [`EffectSubtype`](/slides/python-net/el/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/el/aspose.slides.animation/effecttriggertype) | Τύπος ενεργοποίησης εφέ [`EffectTriggerType`](/slides/python-net/el/aspose.slides.animation/effecttriggertype) |



### See Also
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/el/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/el/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/el/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/el/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/el/aspose.slides.animation/effecttype)
* κλάση [`IChart`](/slides/python-net/el/aspose.slides.charts/ichart)
* κλάση [`IEffect`](/slides/python-net/el/aspose.slides.animation/ieffect)
* κλάση [`IParagraph`](/slides/python-net/el/aspose.slides/iparagraph)
* κλάση [`ISequence`](/slides/python-net/el/aspose.slides.animation/isequence)
* κλάση [`IShape`](/slides/python-net/el/aspose.slides/ishape)
* μονάδα [`aspose.slides.animation`](/slides/python-net/el/aspose.slides.animation)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)