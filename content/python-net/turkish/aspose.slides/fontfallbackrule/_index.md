---
title: FontFallBackRule class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/fontfallbackrule/
---
## FontFallBackRule sınıfı

Yazı tipi geri dönüş kuralını temsil eder

FontFallBackRule türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/tr/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Yeni bir örnek oluşturur. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/tr/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Yeni bir örnek oluşturur. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`range_start_index`](/slides/python-net/tr/aspose.slides/fontfallbackrule/range_start_index/) | Sürekli Unicode aralığının ilk indeksini alır. |
| [`range_end_index`](/slides/python-net/tr/aspose.slides/fontfallbackrule/range_end_index/) | Sürekli Unicode aralığının son indeksini alır. |
| [`count`](/slides/python-net/tr/aspose.slides/fontfallbackrule/count/) | Aralık için gerçekten tanımlanmış yazı tiplerinin sayısını alır.<br/>            Salt okunur **int**. |

Belirtilen indeksteki yazı tipi adını alır.
            Salt okunur [`IFontFallBackRule`](/slides/python-net/tr/aspose.slides/ifontfallbackrule).

## İndeksleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/tr/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Yeni bir yazı tipini (yazı tiplerini) FallBack yazı tipleri listesine ekler. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/tr/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Yeni bir yazı tipini FallBack yazı tipleri listesine ekler. |
| [`to_array(self)`](/slides/python-net/tr/aspose.slides/fontfallbackrule/to_array/#) | Bu kural için tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür. |
| [`to_array(self, start_index, count)`](/slides/python-net/tr/aspose.slides/fontfallbackrule/to_array/#int-int) | Listedeki belirtilen aralıktaki tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür. |
| [`clear(self)`](/slides/python-net/tr/aspose.slides/fontfallbackrule/clear/#) | Listedeki tüm yazı tiplerini kaldırır. |
| [`remove(self, font_name)`](/slides/python-net/tr/aspose.slides/fontfallbackrule/remove/#str) | Listedeki belirli bir FallBack yazı tipinin ilk ocorrasını kaldırır. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides/fontfallbackrule/remove_at/#int) | Listedeki belirtilen indeksteki FallBack yazı tipini kaldırır. |
| [`index_of(self, font_name)`](/slides/python-net/tr/aspose.slides/fontfallbackrule/index_of/#str) | Koleksiyondaki belirtilen kuralın indeksini döndürür. |


### Ayrıca Bakınız
* sınıf [`IFontFallBackRule`](/slides/python-net/tr/aspose.slides/ifontfallbackrule)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)