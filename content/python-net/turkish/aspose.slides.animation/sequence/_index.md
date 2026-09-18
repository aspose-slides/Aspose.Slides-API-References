---
title: Sequence class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.animation/sequence/
---
## Sequence sınıfı

Sequence'i temsil eder (efekt koleksiyonu).

Sequence türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`count`](/slides/python-net/tr/aspose.slides.animation/sequence/count/) | Bir sequense içindeki efekt sayısını döndürür.<br/>            Salt okunur **int**. |
| [`trigger_shape`](/slides/python-net/tr/aspose.slides.animation/sequence/trigger_shape/) | INTERACTIVE sequence için şekil hedefini döndürür veya ayarlar.<br/>            Sequence etkileşimli değilse None döndürür.<br/>            Okuma/yazma [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |

Belirtilen indeksdeki bir efekti döndürür.

## Dizinleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides.animation/sequence/__getitem__/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/tr/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Yeni bir efekti sıranın sonuna ekler. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/tr/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Paragraf için yeni bir animasyon efektini sıranın sonuna ekler. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/tr/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Kategori veya seri için yeni bir grafik animasyon efektini sıranın sonuna ekler. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/tr/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Kategori veya serideki öğeler için yeni bir grafik animasyon efektini sıranın sonuna ekler. |
| [`remove(self, item)`](/slides/python-net/tr/aspose.slides.animation/sequence/remove/#ieffect) | Belirtilen efekti bir koleksiyondan kaldırır. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides.animation/sequence/remove_at/#int) | Bir efekti koleksiyondan kaldırır. |
| [`clear(self)`](/slides/python-net/tr/aspose.slides.animation/sequence/clear/#) | Bir koleksiyondaki tüm efektleri kaldırır. |
| [`remove_by_shape(self, shape)`](/slides/python-net/tr/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Belirtilen şekil için efekti kaldırır. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/tr/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Belirtilen şekil için efekt dizisini döndürür. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/tr/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Belirtilen paragraf için efekt dizisini döndürür. |
| [`get_count(self, shape)`](/slides/python-net/tr/aspose.slides.animation/sequence/get_count/#ishape) | Belirtilen şekil için efekt sayısını döndürür. |

### Ayrıca Bakınız
* modül [`aspose.slides.animation`](/slides/python-net/tr/aspose.slides.animation)
* kütüphane [`Aspose.Slides`](/slides/python-net)