---
title: add_effect method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.animation/sequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Tambahkan efek baru ke akhir urutan.

### Returns

Objek efek baru [`IEffect`](/slides/python-net/id/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/id/aspose.slides/ishape) | Shape objek [`IShape`](/slides/python-net/id/aspose.slides/ishape) untuk menambahkan efek |
| effect_type | [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) | Jenis efek animasi [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) | Subtipe efek animasi [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) | Tipe pemicu efek [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Tambahkan efek animasi baru untuk paragraf ke akhir urutan.

### Returns

Objek efek baru [`IEffect`](/slides/python-net/id/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/id/aspose.slides/iparagraph) | Paragraph objek [`IParagraph`](/slides/python-net/id/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) | Jenis efek animasi [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) | Subtipe efek animasi [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) | Tipe pemicu efek [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Menambahkan efek animasi chart baru untuk kategori atau seri ke akhir urutan.

### Returns

Objek efek baru [`IEffect`](/slides/python-net/id/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) | Chart objek [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartmajorgroupingtype) | Jenis efek animasi [`EffectChartMinorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Indeks **int** |
| effect_type | [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) | Jenis efek animasi [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) | Subtipe efek animasi [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) | Tipe pemicu efek [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Menambahkan efek animasi chart baru untuk elemen dalam kategori atau seri ke akhir urutan.

### Returns

Objek efek baru [`IEffect`](/slides/python-net/id/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) | Chart objek [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartminorgroupingtype) | Jenis efek animasi [`EffectChartMinorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Indeks seri chart **int** |
| categories_index | **int** | Indeks kategori **int** |
| effect_type | [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) | Jenis efek animasi [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) | Subtipe efek animasi [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) | Tipe pemicu efek [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) |



### See Also
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype)
* class [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart)
* class [`IEffect`](/slides/python-net/id/aspose.slides.animation/ieffect)
* class [`IParagraph`](/slides/python-net/id/aspose.slides/iparagraph)
* class [`IShape`](/slides/python-net/id/aspose.slides/ishape)
* class [`Sequence`](/slides/python-net/id/aspose.slides.animation/sequence)
* module [`aspose.slides.animation`](/slides/python-net/id/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)