---
title: add_effect method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Tambahkan efek baru ke akhir urutan.

### Mengembalikan

Objek efek baru [`IEffect`](/slides/python-net/id/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/id/aspose.slides/ishape) | Objek Shape [`IShape`](/slides/python-net/id/aspose.slides/ishape) untuk menambahkan efek |
| effect_type | [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) | Tipe efek animasi [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) | Subtipe efek animasi [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) | Tipe pemicu efek [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Tambahkan efek animasi baru untuk paragraf ke akhir urutan.

### Mengembalikan

Objek efek baru [`IEffect`](/slides/python-net/id/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/id/aspose.slides/iparagraph) | Objek Paragraph [`IParagraph`](/slides/python-net/id/aspose.slides/iparagraph) |
| effect_type | [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) | Tipe efek animasi [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) | Subtipe efek animasi [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) | Tipe pemicu efek [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Menambahkan efek animasi bagan baru untuk kategori atau seri ke akhir urutan.

### Mengembalikan

Objek efek baru [`IEffect`](/slides/python-net/id/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) | Objek Chart [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartmajorgroupingtype) | Tipe efek animasi [`EffectChartMinorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | Indeks **int** |
| effect_type | [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) | Tipe efek animasi [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) | Subtipe efek animasi [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) | Tipe pemicu efek [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Menambahkan efek animasi bagan baru untuk elemen dalam kategori atau seri ke akhir urutan.

### Mengembalikan

Objek efek baru [`IEffect`](/slides/python-net/id/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) | Objek Chart [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart) |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartminorgroupingtype) | Tipe efek animasi [`EffectChartMinorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Indeks seri bagan **int** |
| categories_index | **int** | Indeks kategori **int** |
| effect_type | [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) | Tipe efek animasi [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) | Subtipe efek animasi [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) | Tipe pemicu efek [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype) |



### Lihat Juga
* enumerasi [`EffectChartMajorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartmajorgroupingtype)
* enumerasi [`EffectChartMinorGroupingType`](/slides/python-net/id/aspose.slides.animation/effectchartminorgroupingtype)
* enumerasi [`EffectSubtype`](/slides/python-net/id/aspose.slides.animation/effectsubtype)
* enumerasi [`EffectTriggerType`](/slides/python-net/id/aspose.slides.animation/effecttriggertype)
* enumerasi [`EffectType`](/slides/python-net/id/aspose.slides.animation/effecttype)
* kelas [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart)
* kelas [`IEffect`](/slides/python-net/id/aspose.slides.animation/ieffect)
* kelas [`IParagraph`](/slides/python-net/id/aspose.slides/iparagraph)
* kelas [`ISequence`](/slides/python-net/id/aspose.slides.animation/isequence)
* kelas [`IShape`](/slides/python-net/id/aspose.slides/ishape)
* modul [`aspose.slides.animation`](/slides/python-net/id/aspose.slides.animation)
* pustaka [`Aspose.Slides`](/slides/python-net)