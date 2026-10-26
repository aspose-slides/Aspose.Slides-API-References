---
title: LayoutSlide class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/layoutslide/
---
## LayoutSlide sınıfı

Bir yerleşim slaytını temsil eder.

**Kalıtım:**[`LayoutSlide`](/slides/python-net/tr/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)

LayoutSlide türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`shapes`](/slides/python-net/tr/aspose.slides/layoutslide/shapes/) | Bir slaytın şekillerini döndürür.<br/>            Yalnızca-okunur [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/tr/aspose.slides/layoutslide/controls/) | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür.<br/>            Yalnızca-okunur [`IControlCollection`](/slides/python-net/tr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/tr/aspose.slides/layoutslide/name/) | Bir slaytın adını döndürür veya ayarlar.<br/>            Okunur/yazılır **str**. |
| [`slide_id`](/slides/python-net/tr/aspose.slides/layoutslide/slide_id/) | Bir slaytın kimliğini döndürür.<br/>            Yalnızca-okunur **int**. |
| [`custom_data`](/slides/python-net/tr/aspose.slides/layoutslide/custom_data/) | Slaytın özel verilerini döndürür.<br/>            Yalnızca-okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/tr/aspose.slides/layoutslide/timeline/) | Animasyon zaman çizelgesi nesnesini döndürür.<br/>            Yalnızca-okunur [`IAnimationTimeLine`](/slides/python-net/tr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/layoutslide/slide_show_transition/) | Belirtilen slaytın bir slayt gösterisi sırasında nasıl ilerlediğiyle ilgili bilgileri içeren Transition nesnesini döndürür.<br/>            Yalnızca-okunur [`ISlideShowTransition`](/slides/python-net/tr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/tr/aspose.slides/layoutslide/background/) | Slaytın arka planını döndürür.<br/>            Yalnızca-okunur [`IBackground`](/slides/python-net/tr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/layoutslide/hyperlink_queries/) | İçerdiği hiperlinklere kolay erişim sağlar.<br/>            Yalnızca-okunur [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/layoutslide/show_master_shapes/) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir.<br/>            Okunur/yazılır **bool**. |
| [`presentation`](/slides/python-net/tr/aspose.slides/layoutslide/presentation/) | IPresentation arayüzünü döndürür.<br/>            Yalnızca-okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/tr/aspose.slides/layoutslide/header_footer_manager/) | Yerleşim slaytının HeaderFooter yöneticisini döndürür.<br/>            Yalnızca-okunur [`ILayoutSlideHeaderFooterManager`](/slides/python-net/tr/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/tr/aspose.slides/layoutslide/placeholder_manager/) | Yerleşim slaytının yer tutucu yöneticisini döndürür.<br/>            Yalnızca-okunur [`ILayoutPlaceholderManager`](/slides/python-net/tr/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/tr/aspose.slides/layoutslide/master_slide/) | Bir yerleşim için ana slaytı döndürür veya ayarlar.<br/>            Okunur/yazılır [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/tr/aspose.slides/layoutslide/theme_manager/) | Geçersiz kılan tema yöneticisini döndürür.<br/>            Yalnızca-okunur [`IOverrideThemeManager`](/slides/python-net/tr/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/tr/aspose.slides/layoutslide/layout_type/) | Bu yerleşim slaytının yerleşim türünü döndürür.<br/>            Yalnızca-okunur [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/tr/aspose.slides/layoutslide/has_depending_slides/) | Bu yerleşim slaytına bağımlı en az bir slayt varsa true döndürür.<br/>            Yalnızca-okunur **bool**. |
| [`drawing_guides`](/slides/python-net/tr/aspose.slides/layoutslide/drawing_guides/) | Yerleşim slaytı için çizim rehberlerinin bir koleksiyonunu döndürür.<br/>            Yalnızca-okunur [`IDrawingGuidesCollection`](/slides/python-net/tr/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/tr/aspose.slides/layoutslide/slide/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Tüm paragraflardaki ve tüm geçerli şekillerde aynı biçimlendirmeye sahip run'ları birleştirir. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/tr/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Tüm paragraflardaki ve tüm geçerli şekillerde aynı biçimlendirmeye sahip run'ları birleştirir. |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/layoutslide/equals/#ibaseslide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler.<br/>            Döndürülen değer, slaytın yapısı ve statik içeriğine dayanarak hesaplanır.<br/>            Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, benzersiz kimlik değerlerini (ör. SlideId) ve dinamik içeriği (ör. Tarih Yer Tutucusundaki geçerli tarih değeri) dikkate almaz. |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/layoutslide/create_theme_effective/#) | Bu slayt için etkili bir temayı döndürür. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Belirtilen alternatif metne sahip şeklin ilk örneğini bulur. |
| [`remove(self)`](/slides/python-net/tr/aspose.slides/layoutslide/remove/#) | Yerleşimi sunumdan kaldırır. |
| [`get_depending_slides(self)`](/slides/python-net/tr/aspose.slides/layoutslide/get_depending_slides/#) | Bu yerleşim slaytına bağımlı tüm slaytları içeren bir dizi döndürür. |

### Ayrıca Bakınız
* sınıf [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)
* sınıf [`LayoutSlide`](/slides/python-net/tr/aspose.slides/layoutslide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)