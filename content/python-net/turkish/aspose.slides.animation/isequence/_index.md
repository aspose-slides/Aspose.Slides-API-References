---
title: ISequence class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.animation/isequence/
---
## ISequence sınıfı

Represents sequence (collection of effects).

The ISequence type exposes the following members:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`count`](/slides/python-net/tr/aspose.slides.animation/isequence/count/) | Bir dizideki efekt sayısını döndürür.<br/>            Salt-okunur **int**. |
| [`trigger_shape`](/slides/python-net/tr/aspose.slides.animation/isequence/trigger_shape/) | INTERACTIVE dizisi için şekil hedefini döndürür veya ayarlar.<br/>            Dizi etkileşimli değilse None döndürür.<br/>            Okunur/yazılır [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |

Returns an effect at the specified index.

## İndeksleyici

| İsim | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides.animation/isequence/__getitem__/) | İndeks |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/tr/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Dizinin sonuna yeni bir efekt ekler. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/tr/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Paragraf için yeni bir animasyon efektini dizinin sonuna ekler. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/tr/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Kategori ya da seriye yönelik yeni bir grafik animasyon efektini dizinin sonuna ekler. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/tr/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Kategori ya da serideki öğeler için yeni bir grafik animasyon efektini dizinin sonuna ekler. |
| [`remove(self, item)`](/slides/python-net/tr/aspose.slides.animation/isequence/remove/#ieffect) | Belirtilen efekti bir koleksiyondan kaldırır. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides.animation/isequence/remove_at/#int) | Bir efekti bir koleksiyondan kaldırır. |
| [`clear(self)`](/slides/python-net/tr/aspose.slides.animation/isequence/clear/#) | Bir koleksiyondaki tüm efektleri kaldırır. |
| [`remove_by_shape(self, shape)`](/slides/python-net/tr/aspose.slides.animation/isequence/remove_by_shape/#ishape) | Belirtilen şekil için efekti kaldırır. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/tr/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | Belirtilen şekil için efekt dizisini döndürür. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/tr/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | Belirtilen paragraf için efekt dizisini döndürür. |
| [`get_count(self, shape)`](/slides/python-net/tr/aspose.slides.animation/isequence/get_count/#ishape) | Belirtilen şekil için efekt sayısını döndürür. |

### Ayrıca Bakınız
* modül [`aspose.slides.animation`](/slides/python-net/tr/aspose.slides.animation)
* kütüphane [`Aspose.Slides`](/slides/python-net)