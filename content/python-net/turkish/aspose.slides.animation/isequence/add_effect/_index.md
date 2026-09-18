---
title: add_effect method
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.animation/isequence/add_effect/
weight: 10
---
## add_effect(self, shape, effect_type, subtype, trigger_type) {#ishape-effecttype-effectsubtype-effecttriggertype}
Yeni efekti dizinin sonuna ekle.

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](/slides/python-net/tr/aspose.slides.animation/ieffect)



```python
def add_effect(self, shape, effect_type, subtype, trigger_type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shape | [`IShape`](/slides/python-net/tr/aspose.slides/ishape) | Efekt eklemek için [`IShape`](/slides/python-net/tr/aspose.slides/ishape) Şekil nesnesi |
| effect_type | [`EffectType`](/slides/python-net/tr/aspose.slides.animation/effecttype) | Animasyon efekti türü [`EffectType`](/slides/python-net/tr/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/tr/aspose.slides.animation/effectsubtype) | Animasyon efekti alt türleri [`EffectSubtype`](/slides/python-net/tr/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/tr/aspose.slides.animation/effecttriggertype) | Efektin tetikleme türü [`EffectTriggerType`](/slides/python-net/tr/aspose.slides.animation/effecttriggertype) |


## add_effect(self, paragraph, effect_type, subtype, trigger_type) {#iparagraph-effecttype-effectsubtype-effecttriggertype}
Paragraf için yeni animasyon efektini dizinin sonuna ekle.

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](/slides/python-net/tr/aspose.slides.animation/ieffect)



```python
def add_effect(self, paragraph, effect_type, subtype, trigger_type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| paragraph | [`IParagraph`](/slides/python-net/tr/aspose.slides/iparagraph) | [`IParagraph`](/slides/python-net/tr/aspose.slides/iparagraph) Paragraf nesnesi |
| effect_type | [`EffectType`](/slides/python-net/tr/aspose.slides.animation/effecttype) | Animasyon efekti türü [`EffectType`](/slides/python-net/tr/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/tr/aspose.slides.animation/effectsubtype) | Animasyon efekti alt türleri [`EffectSubtype`](/slides/python-net/tr/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/tr/aspose.slides.animation/effecttriggertype) | Efektin tetikleme türü [`EffectTriggerType`](/slides/python-net/tr/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype}
Kategori ya da seri için yeni grafik animasyon efektini dizinin sonuna ekler.

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](/slides/python-net/tr/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, index, effect_type, subtype, trigger_type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart) | [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart) Chart nesnesi |
| type | [`EffectChartMajorGroupingType`](/slides/python-net/tr/aspose.slides.animation/effectchartmajorgroupingtype) | Animasyon efekti türü [`EffectChartMinorGroupingType`](/slides/python-net/tr/aspose.slides.animation/effectchartminorgroupingtype) |
| index | **int** | İndeks **int** |
| effect_type | [`EffectType`](/slides/python-net/tr/aspose.slides.animation/effecttype) | Animasyon efekti türü [`EffectType`](/slides/python-net/tr/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/tr/aspose.slides.animation/effectsubtype) | Animasyon efekti alt türleri [`EffectSubtype`](/slides/python-net/tr/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/tr/aspose.slides.animation/effecttriggertype) | Efektin tetikleme türü [`EffectTriggerType`](/slides/python-net/tr/aspose.slides.animation/effecttriggertype) |


## add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type) {#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype}
Kategori ya da serideki öğeler için yeni grafik animasyon efektini dizinin sonuna ekler.

### Dönüş Değeri

Yeni efekt nesnesi [`IEffect`](/slides/python-net/tr/aspose.slides.animation/ieffect)



```python
def add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| chart | [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart) | [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart) Chart nesnesi |
| type | [`EffectChartMinorGroupingType`](/slides/python-net/tr/aspose.slides.animation/effectchartminorgroupingtype) | Animasyon efekti türü [`EffectChartMinorGroupingType`](/slides/python-net/tr/aspose.slides.animation/effectchartminorgroupingtype) |
| series_index | **int** | Chart serisinin indeksi **int** |
| categories_index | **int** | Kategori indeksi **int** |
| effect_type | [`EffectType`](/slides/python-net/tr/aspose.slides.animation/effecttype) | Animasyon efekti türü [`EffectType`](/slides/python-net/tr/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/tr/aspose.slides.animation/effectsubtype) | Animasyon efekti alt türleri [`EffectSubtype`](/slides/python-net/tr/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/tr/aspose.slides.animation/effecttriggertype) | Efektin tetikleme türü [`EffectTriggerType`](/slides/python-net/tr/aspose.slides.animation/effecttriggertype) |



### Ayrıca Bakınız
* enumeration [`EffectChartMajorGroupingType`](/slides/python-net/tr/aspose.slides.animation/effectchartmajorgroupingtype)
* enumeration [`EffectChartMinorGroupingType`](/slides/python-net/tr/aspose.slides.animation/effectchartminorgroupingtype)
* enumeration [`EffectSubtype`](/slides/python-net/tr/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/tr/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/tr/aspose.slides.animation/effecttype)
* class [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart)
* class [`IEffect`](/slides/python-net/tr/aspose.slides.animation/ieffect)
* class [`IParagraph`](/slides/python-net/tr/aspose.slides/iparagraph)
* class [`ISequence`](/slides/python-net/tr/aspose.slides.animation/isequence)
* class [`IShape`](/slides/python-net/tr/aspose.slides/ishape)
* module [`aspose.slides.animation`](/slides/python-net/tr/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)