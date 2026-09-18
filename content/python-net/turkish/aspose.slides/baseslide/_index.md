---
title: BaseSlide class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/baseslide/
---
## BaseSlide sınıfı

Represents common data for all slide types.

The BaseSlide type exposes the following members:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`shapes`](/slides/python-net/tr/aspose.slides/baseslide/shapes/) | Bir slaytın şekillerini döndürür.<br/>            Salt okunur [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/tr/aspose.slides/baseslide/controls/) | Bir slayttaki ActiveX kontrollerinin koleksiyonunu döndürür.<br/>            Salt okunur [`IControlCollection`](/slides/python-net/tr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/tr/aspose.slides/baseslide/name/) | Bir slaytın adını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`slide_id`](/slides/python-net/tr/aspose.slides/baseslide/slide_id/) | Bir slaytın kimliğini döndürür.<br/>            Salt okunur **int**. |
| [`custom_data`](/slides/python-net/tr/aspose.slides/baseslide/custom_data/) | Slaytın özel verilerini döndürür.<br/>            Salt okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/tr/aspose.slides/baseslide/timeline/) | Animasyon zaman çizelgesi nesnesini döndürür.<br/>            Salt okunur [`IAnimationTimeLine`](/slides/python-net/tr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/baseslide/slide_show_transition/) | Belirtilen slaytın bir gösteri sırasında nasıl ilerlediğine dair bilgi içeren Transition nesnesini döndürür.<br/>            Salt okunur [`ISlideShowTransition`](/slides/python-net/tr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/tr/aspose.slides/baseslide/background/) | Slaytın arka planını döndürür.<br/>            Salt okunur [`IBackground`](/slides/python-net/tr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/baseslide/hyperlink_queries/) | İçerilen köprü bağlantılarına kolay erişim sağlar.<br/>            Salt okunur [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/baseslide/show_master_shapes/) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir.<br/>            Ana slayt için bu özellik her zaman `false` döndürür.<br/>            Okunur/yazılabilir **bool**. |
| [`presentation`](/slides/python-net/tr/aspose.slides/baseslide/presentation/) | IPresentation arayüzünü döndürür.<br/>            Salt okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/tr/aspose.slides/baseslide/slide/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Tüm paragraflardaki ve tüm uygun şekillerdeki aynı biçimlendirmeye sahip run'ları birleştirir. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/tr/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Tüm paragraflardaki ve tüm uygun şekillerdeki aynı biçimlendirmeye sahip run'ları birleştirir. |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/baseslide/equals/#ibaseslide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler.<br/>            Döndürülen değer, slaytın yapısı ve statik içeriğine göre hesaplanır.<br/>            Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, SlideId gibi benzersiz tanımlayıcı değerleri ve tarih yer tutucusundaki güncel tarih gibi dinamik içeriği dikkate almaz. |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/baseslide/create_theme_effective/#) | Bu slayt için etkili bir temayı döndürür. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Belirtilen alternatif metne sahip şeklin ilk karşılaşımını bulur. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)