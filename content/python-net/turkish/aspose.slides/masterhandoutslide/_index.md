---
title: MasterHandoutSlide class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide sınıfı

İş çıkarma notları için ana slaytı temsil eder.

**Kalıtım:**[`MasterHandoutSlide`](/slides/python-net/tr/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)

MasterHandoutSlide tipi aşağıdaki üyeleri ortaya çıkarır:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`shapes`](/slides/python-net/tr/aspose.slides/masterhandoutslide/shapes/) | Bir slaydın şekillerini döndürür.<br/>            Read-only [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/tr/aspose.slides/masterhandoutslide/controls/) | Bir slayd üzerindeki ActiveX denetimlerinin koleksiyonunu döndürür.<br/>            Read-only [`IControlCollection`](/slides/python-net/tr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/tr/aspose.slides/masterhandoutslide/name/) | Bir slaydın adını döndürür veya ayarlar.<br/>            Read/write **str**. |
| [`slide_id`](/slides/python-net/tr/aspose.slides/masterhandoutslide/slide_id/) | Bir slaydın kimliğini döndürür.<br/>            Read-only **int**. |
| [`custom_data`](/slides/python-net/tr/aspose.slides/masterhandoutslide/custom_data/) | Slaydın özel verisini döndürür.<br/>            Read-only [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/tr/aspose.slides/masterhandoutslide/timeline/) | Animasyon zaman çizelgesi nesnesini döndürür.<br/>            Read-only [`IAnimationTimeLine`](/slides/python-net/tr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/masterhandoutslide/slide_show_transition/) | Belirtilen slaydın bir slayt gösterisi sırasında nasıl ilerlediğine dair bilgi içeren Transition nesnesini döndürür.<br/>            Read-only [`ISlideShowTransition`](/slides/python-net/tr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/tr/aspose.slides/masterhandoutslide/background/) | Slaydın arka planını döndürür.<br/>            Read-only [`IBackground`](/slides/python-net/tr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/masterhandoutslide/hyperlink_queries/) | İçerilen bağlantılara kolay erişim sağlar.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/masterhandoutslide/show_master_shapes/) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler.<br/>            Ana slayt için bu özellik her zaman `false` döndürür.<br/>            Read/write **bool**. |
| [`presentation`](/slides/python-net/tr/aspose.slides/masterhandoutslide/presentation/) | IPresentation arayüzünü döndürür.<br/>            Read-only [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/tr/aspose.slides/masterhandoutslide/header_footer_manager/) | Ana el çıkartma slaydının HeaderFooter yöneticisini döndürür.<br/>            Read-only [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/tr/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/tr/aspose.slides/masterhandoutslide/theme_manager/) | Tema yöneticisini döndürür.<br/>            Read-only [`IMasterThemeManager`](/slides/python-net/tr/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/tr/aspose.slides/masterhandoutslide/drawing_guides/) | Ana el çıkartma slaydı için çizim kılavuzlarının bir koleksiyonunu döndürür.<br/>            Read-only [`IDrawingGuidesCollection`](/slides/python-net/tr/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/tr/aspose.slides/masterhandoutslide/slide/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Tüm paragraflarda ve tüm geçerli şekillerde aynı biçimlendirmeye sahip run'ları birleştirir. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/tr/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Tüm paragraflarda ve tüm geçerli şekillerde aynı biçimlendirmeye sahip run'ları birleştirir. |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/masterhandoutslide/equals/#ibaseslide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler.<br/>            Dönen değer slaydın yapısı ve statik içeriğine göre hesaplanır.<br/>            Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, benzersiz kimlik değerleri (ör. SlideId) ve dinamik içerik (ör. Tarih Yer Tutucusundaki geçerli tarih değeri) dikkate alınmaz. |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/masterhandoutslide/create_theme_effective/#) | Bu slayt için etkili bir temayı döndürür. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Belirtilen alternatif metne sahip şeklin ilk örneğini bulur. |

### Ayrıca Bakınız
* sınıf [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)
* sınıf [`MasterHandoutSlide`](/slides/python-net/tr/aspose.slides/masterhandoutslide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)