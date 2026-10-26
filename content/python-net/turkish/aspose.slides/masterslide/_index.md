---
title: MasterSlide class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/masterslide/
---
## MasterSlide sınıfı

Bir sunumdaki ana slaytı temsil eder.

**Inheritance:**[`MasterSlide`](/slides/python-net/tr/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)

The MasterSlide type exposes the following members:

## Özellikler

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/tr/aspose.slides/masterslide/shapes/) | Bir slaydın şekillerini döndürür.<br/>            Salt-okunur [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/tr/aspose.slides/masterslide/controls/) | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür.<br/>            Salt-okunur [`IControlCollection`](/slides/python-net/tr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/tr/aspose.slides/masterslide/name/) | Bir ana slaydın adını döndürür veya ayarlar.<br/>            Okunur/yazılır **str**. |
| [`slide_id`](/slides/python-net/tr/aspose.slides/masterslide/slide_id/) | Bir slaydın kimliğini (ID) döndürür.<br/>            Salt-okunur **int**. |
| [`custom_data`](/slides/python-net/tr/aspose.slides/masterslide/custom_data/) | Slaydın özel verisini döndürür.<br/>            Salt-okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/tr/aspose.slides/masterslide/timeline/) | Animasyon zaman çizelgesi nesnesini döndürür.<br/>            Salt-okunur [`IAnimationTimeLine`](/slides/python-net/tr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/masterslide/slide_show_transition/) | Belirtilen slaydın bir slayt gösterisi sırasında nasıl ilerleyeceği hakkında bilgi içeren Geçiş (Transition) nesnesini döndürür.<br/>            Salt-okunur [`ISlideShowTransition`](/slides/python-net/tr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/tr/aspose.slides/masterslide/background/) | Slaydın arka planını döndürür.<br/>            Salt-okunur [`IBackground`](/slides/python-net/tr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/masterslide/hyperlink_queries/) | İçerilen köprü bağlantılarına kolay erişim sağlar.<br/>            Salt-okunur [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/masterslide/show_master_shapes/) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir.<br/>            Ana slayt için bu özellik her zaman `false` değerini döndürür.<br/>            Okunur/yazılır **bool**. |
| [`presentation`](/slides/python-net/tr/aspose.slides/masterslide/presentation/) | IPresentation arayüzünü döndürür.<br/>            Salt-okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/tr/aspose.slides/masterslide/header_footer_manager/) | Ana slaydın HeaderFooter yöneticisini döndürür.<br/>            Salt-okunur [`IMasterSlideHeaderFooterManager`](/slides/python-net/tr/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/tr/aspose.slides/masterslide/title_style/) | Başlık metninin stilini döndürür.<br/>            Salt-okunur [`ITextStyle`](/slides/python-net/tr/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/tr/aspose.slides/masterslide/body_style/) | Gövde metninin stilini döndürür.<br/>            Salt-okunur [`ITextStyle`](/slides/python-net/tr/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/tr/aspose.slides/masterslide/other_style/) | Diğer bir metnin stilini döndürür.<br/>            Salt-okunur [`ITextStyle`](/slides/python-net/tr/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/tr/aspose.slides/masterslide/layout_slides/) | Bu ana slayt için alt düzen slaytlarının koleksiyonunu döndürür.<br/>            Salt-okunur [`IMasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/tr/aspose.slides/masterslide/preserve/) | İlgili ana slaydın, bu ana slaytı izleyen tüm slaytlar silindiğinde silinir olup olmadığını belirler.<br/>            Not: Aspose.Slides hiçbir zaman kendiliğinden kullanılmayan ana slaytı kaldırmaz; kullanılmayan ana slaytları gerçekten kaldırmak için **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Okunur/yazılır **bool**. |
| [`has_depending_slides`](/slides/python-net/tr/aspose.slides/masterslide/has_depending_slides/) | Bu ana slayta bağımlı en az bir slayt varsa true değerini döndürür.<br/>            Salt-okunur **bool**. |
| [`theme_manager`](/slides/python-net/tr/aspose.slides/masterslide/theme_manager/) | Tema yöneticisini döndürür.<br/>            Salt-okunur [`IMasterThemeManager`](/slides/python-net/tr/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/tr/aspose.slides/masterslide/drawing_guides/) | Ana slayt için çizim kılavuzlarının bir koleksiyonunu döndürür.<br/>            Salt-okunur [`IDrawingGuidesCollection`](/slides/python-net/tr/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/tr/aspose.slides/masterslide/slide/) |  |

## Yöntemler

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/tr/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir. |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/masterslide/equals/#ibaseslide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler.<br/>            Dönen değer, slaydın yapısı ve statik içeriğine göre hesaplanır.<br/>            Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, benzersiz tanımlayıcı değerlerini (ör. SlideId) ve dinamik içeriği (ör. Tarih Yer Tutucusundaki geçerli tarih değeri) dikkate almaz. |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/masterslide/create_theme_effective/#) | Bu slayt için geçerli bir temayı döndürür. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Belirtilen alternatif metne sahip şeklin ilk görünümünü bulur. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/tr/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Mevcut ana slayttan yeni bir ana slayt oluşturur, ona harici bir tema uygular <br/>            ve oluşturulan ana slaytı tüm bağımlı slaytlara uygular. |
| [`get_depending_slides(self)`](/slides/python-net/tr/aspose.slides/masterslide/get_depending_slides/#) | Bu ana slayta bağımlı olan tüm slaytları içeren bir dizi döndürür. |


### Ayrıca Bakınız
* sınıf [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)
* sınıf [`MasterSlide`](/slides/python-net/tr/aspose.slides/masterslide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)