---
title: IBaseSlide class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ibaseslide/
---
## IBaseSlide sınıfı

Tüm slayt türleri için ortak verileri temsil eder.

IBaseSlide türü aşağıdaki üyelere erişim sağlar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`shapes`](/slides/python-net/tr/aspose.slides/ibaseslide/shapes/) | Bir slaydın şekillerini döndürür.<br/>            Salt okuma [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/tr/aspose.slides/ibaseslide/controls/) | Bir slayd üzerindeki ActiveX denetimlerinin koleksiyonunu döndürür.<br/>            Salt okuma [`IControlCollection`](/slides/python-net/tr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/tr/aspose.slides/ibaseslide/name/) | Bir slaydın adını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`slide_id`](/slides/python-net/tr/aspose.slides/ibaseslide/slide_id/) | Bir slaydın kimliğini döndürür.<br/>            Salt okuma **int**. |
| [`custom_data`](/slides/python-net/tr/aspose.slides/ibaseslide/custom_data/) | Slaydın özel verilerini döndürür.<br/>            Salt okuma [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/tr/aspose.slides/ibaseslide/timeline/) | Animasyon zaman çizelgesi nesnesini döndürür.<br/>            Salt okuma [`IAnimationTimeLine`](/slides/python-net/tr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/ibaseslide/slide_show_transition/) | TransitionEx nesnesini döndürür; bu nesne<br/>            belirli slaydın bir slayt gösterisi sırasında nasıl ilerlediğine dair bilgileri içerir.<br/>            Salt okuma [`ISlideShowTransition`](/slides/python-net/tr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/tr/aspose.slides/ibaseslide/background/) | Slaydın arka planını döndürür.<br/>            Salt okuma [`IBackground`](/slides/python-net/tr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/ibaseslide/hyperlink_queries/) | İçerilen hipermetin bağlantılarına kolay erişim sağlar.<br/>            Salt okuma [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/ibaseslide/show_master_shapes/) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler.<br/>            Ana slayt kendisi için bu özellik her zaman `false` döndürür.<br/>            Okuma/yazma **bool**. |
| [`slide`](/slides/python-net/tr/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/ibaseslide/presentation/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Kabul edilebilir tüm şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir. |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/ibaseslide/equals/#ibaseslide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler.<br/>            Döndürülen değer, slaydın yapısı ve statik içeriği temel alınarak hesaplanır.<br/>            Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse slaytlar eşittir. Karşılaştırma, SlideId gibi benzersiz kimlik değerlerini ve Tarih Yer Tutucusundaki mevcut tarih değeri gibi dinamik içeriği dikkate almaz. |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### İlgili
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)