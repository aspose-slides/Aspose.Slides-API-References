---
title: IParagraphFormat class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iparagraphformat/
---
## IParagraphFormat sınıfı

Bu sınıf, paragraf biçimlendirme özelliklerini içerir. [`IParagraphFormatEffectiveData`](/slides/python-net/tr/aspose.slides/iparagraphformateffectivedata)'nin aksine, bu sınıfın tüm özellikleri yazılabilir.

IParagraphFormat türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`bullet`](/slides/python-net/tr/aspose.slides/iparagraphformat/bullet/) | Paragrafın madde işareti biçimini döndürür.<br/>            Yalnızca okuma [`IBulletFormat`](/slides/python-net/tr/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/tr/aspose.slides/iparagraphformat/depth/) | Paragrafın derinliğini döndürür veya ayarlar.<br/>            Değer 0, tanımsız değeri ifade eder.<br/>            Okuma/yazma **int**. |
| [`alignment`](/slides/python-net/tr/aspose.slides/iparagraphformat/alignment/) | Kalıtım olmadan bir paragraftaki metin hizalamasını döndürür veya ayarlar.<br/>            Okuma/yazma [`TextAlignment`](/slides/python-net/tr/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/tr/aspose.slides/iparagraphformat/space_within/) | Paragraftaki temel satırlar arasındaki boşluk miktarını döndürür veya ayarlar. Pozitif değer yüzdeyi, negatif değer ise nokta cinsinden boyutu ifade eder. Kalıtım uygulanmaz.<br/>            Okuma/yazma **float**. |
| [`space_before`](/slides/python-net/tr/aspose.slides/iparagraphformat/space_before/) | Kalıtım olmadan bir paragraftaki ilk satırdan önceki boşluk miktarını döndürür veya ayarlar.<br/>            Pozitif değer, boşluk karakterinin yazı tipi boyutunun yüzdesini belirtir.<br/>            Negatif değer, boşluğun nokta cinsinden boyutunu belirtir.<br/>            Okuma/yazma **float**. |
| [`space_after`](/slides/python-net/tr/aspose.slides/iparagraphformat/space_after/) | Kalıtım olmadan bir paragraftaki son satırdan sonraki boşluk miktarını döndürür veya ayarlar.<br/>            Pozitif değer, boşluk karakterinin yazı tipi boyutunun yüzdesini belirtir.<br/>            Negatif değer, boşluğun nokta cinsinden boyutunu belirtir.<br/>            Okuma/yazma **float**. |
| [`east_asian_line_break`](/slides/python-net/tr/aspose.slides/iparagraphformat/east_asian_line_break/) | Paragrafta Doğu Asya satır sonu kullanımını belirler. Kalıtım uygulanmaz.<br/>            Okuma/yazma [`NullableBool`](/slides/python-net/tr/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/tr/aspose.slides/iparagraphformat/right_to_left/) | Paragrafta Sağdan Sola yazımın kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz.<br/>            Okuma/yazma [`NullableBool`](/slides/python-net/tr/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/tr/aspose.slides/iparagraphformat/latin_line_break/) | Paragrafta Latin satır sonu kullanımını belirler. Kalıtım uygulanmaz.<br/>            Okuma/yazma [`NullableBool`](/slides/python-net/tr/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/tr/aspose.slides/iparagraphformat/hanging_punctuation/) | Paragrafta sarkan noktalama işaretlerinin kullanılıp kullanılmadığını belirler. Kalıtım uygulanmaz.<br/>            Okuma/yazma [`NullableBool`](/slides/python-net/tr/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/tr/aspose.slides/iparagraphformat/margin_left/) | Kalıtım olmadan bir paragraftaki sol kenar boşluğunu döndürür veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`margin_right`](/slides/python-net/tr/aspose.slides/iparagraphformat/margin_right/) | Kalıtım olmadan bir paragraftaki sağ kenar boşluğunu döndürür veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`indent`](/slides/python-net/tr/aspose.slides/iparagraphformat/indent/) | Kalıtım olmadan paragrafın İlk Satır Girintisi/Sarkan Girinti değerini döndürür veya ayarlar. Sarkan Girinti negatif değerlerle tanımlanabilir.<br/>            Okuma/yazma **float**. |
| [`default_tab_size`](/slides/python-net/tr/aspose.slides/iparagraphformat/default_tab_size/) | Kalıtım olmadan varsayılan sekme boyutunu döndürür veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`tabs`](/slides/python-net/tr/aspose.slides/iparagraphformat/tabs/) | Paragraf sekmelerini döndürür. Kalıtım uygulanmaz.<br/>            Yalnızca okuma [`ITabCollection`](/slides/python-net/tr/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/tr/aspose.slides/iparagraphformat/font_alignment/) | Kalıtım olmadan bir paragrafta yazı tipi hizalamasını döndürür veya ayarlar.<br/>            Okuma/yazma [`FontAlignment`](/slides/python-net/tr/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/tr/aspose.slides/iparagraphformat/default_portion_format/) | Paragrafın varsayılan bölüm biçimini döndürür. Kalıtım uygulanmaz.<br/>            Yalnızca okuma [`IPortionFormat`](/slides/python-net/tr/aspose.slides/iportionformat). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/tr/aspose.slides/iparagraphformat/get_effective/#) | Kalıtım uygulanan etkili paragraf biçimlendirme verilerini alır. |


### Açıklamalar

Bu sınıf, belirli paragraf için tanımlanan paragraf biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken hiçbir kalıtım uygulanmadığı anlamına gelir; bu yüzden çoğu durumda değerler "tanımsız" anlamına gelir.

Kalıtım dahil etkili biçimlendirme parametre değerlerini almak için [`IParagraphFormat.get_effective`](/slides/python-net/tr/aspose.slides/iparagraphformat/get_effective) yöntemini kullanmanız gerekir,
            bu yöntem bir [`IParagraphFormatEffectiveData`](/slides/python-net/tr/aspose.slides/iparagraphformateffectivedata) örneği döndürür.


### Ayrıca Bakınız
* sınıf [`IParagraphFormatEffectiveData`](/slides/python-net/tr/aspose.slides/iparagraphformateffectivedata)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)