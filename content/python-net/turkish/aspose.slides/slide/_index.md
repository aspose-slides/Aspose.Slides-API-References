---
title: Slide class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/slide/
---
## Slide sınıfı

Bir sunumdaki slaytı temsil eder.

**Inheritance:**[`Slide`](/slides/python-net/tr/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)

The Slide type exposes the following members:

## Özellikler

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/tr/aspose.slides/slide/shapes/) | Bir slaytın şekillerini döndürür.<br/>            Salt okunur [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/tr/aspose.slides/slide/controls/) | Bir slaytta bulunan ActiveX denetimlerinin koleksiyonunu döndürür.<br/>            Salt okunur [`IControlCollection`](/slides/python-net/tr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/tr/aspose.slides/slide/name/) | Bir slaytın adını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`slide_id`](/slides/python-net/tr/aspose.slides/slide/slide_id/) | Bir slaytın kimliğini döndürür.<br/>            Salt okunur **int**. |
| [`custom_data`](/slides/python-net/tr/aspose.slides/slide/custom_data/) | Slaytın özel verilerini döndürür.<br/>            Salt okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/tr/aspose.slides/slide/timeline/) | Animasyon zaman çizelgesi nesnesini döndürür.<br/>            Salt okunur [`IAnimationTimeLine`](/slides/python-net/tr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/slide/slide_show_transition/) | Geçiş nesnesini döndürür; bu nesne, belirtilen slaytın bir slayt gösterisi sırasında nasıl ilerlediği hakkında bilgi içerir.<br/>            Salt okunur [`ISlideShowTransition`](/slides/python-net/tr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/tr/aspose.slides/slide/background/) | Slaytın arka planını döndürür.<br/>            Salt okunur [`IBackground`](/slides/python-net/tr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/slide/hyperlink_queries/) | İçerdiği hiperlinklere kolay erişim sağlar.<br/>            Salt okunur [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/slide/show_master_shapes/) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir.<br/>            Okunur/yazılabilir **bool**. |
| [`presentation`](/slides/python-net/tr/aspose.slides/slide/presentation/) | IPresentation arabirimini döndürür.<br/>            Salt okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/tr/aspose.slides/slide/header_footer_manager/) | Slaytın HeaderFooter yöneticisini döndürür.<br/>            Salt okunur [`ISlideHeaderFooterManager`](/slides/python-net/tr/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/tr/aspose.slides/slide/theme_manager/) | Geçerli temayı geçersiz kılan yöneticiyi döndürür.<br/>            Salt okunur [`IOverrideThemeManager`](/slides/python-net/tr/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/tr/aspose.slides/slide/slide_number/) | Bir slaytın numarasını döndürür.<br/>            [`Presentation.slides`](/slides/python-net/tr/aspose.slides/presentation/slides) koleksiyonundaki slayt indeksi her zaman SlideNumber - Presentation.FirstSlideNumber değerine eşittir.<br/>            Okunur/yazılabilir **int**. |
| [`hidden`](/slides/python-net/tr/aspose.slides/slide/hidden/) | Belirtilen slaytın bir slayt gösterisi sırasında gizli olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`layout_slide`](/slides/python-net/tr/aspose.slides/slide/layout_slide/) | Geçerli slayt için düzen slaytını döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/tr/aspose.slides/slide/notes_slide_manager/) | Not slaytına erişime izin verir, ekler ve kaldırır.<br/>            Salt okunur [`INotesSlideManager`](/slides/python-net/tr/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/tr/aspose.slides/slide/slide/) |  |

## Yöntemler

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/slide/join_portions_with_same_formatting/#) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/tr/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/slide/get_image/#float-float) | Özel ölçekleme ile bir Thumbnail Image nesnesi döndürür. |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/slide/get_image/#) | Gerçek boyutun %20'si kadar bir Thumbnail Image nesnesi döndürür. |
| [`get_image(self, image_size)`](/slides/python-net/tr/aspose.slides/slide/get_image/#asposepydrawingsize) | Belirtilen boyutta bir Thumbnail Image nesnesi döndürür. |
| [`get_image(self, options)`](/slides/python-net/tr/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Belirtilen parametrelerle bir Thumbnail tiff image nesnesi döndürür. |
| [`get_image(self, options)`](/slides/python-net/tr/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Bir Thumbnail Image nesnesi döndürür. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Özel ölçekleme ile bir Thumbnail Image nesnesi döndürür. |
| [`get_image(self, options, image_size)`](/slides/python-net/tr/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Belirtilen boyutta bir Thumbnail Image nesnesi döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/slide/write_as_svg/#iorawiobase) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/slide/equals/#ibaseslide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler.<br/>            Dönen değer, slaytın yapısı ve statik içeriğine göre hesaplanır.<br/>            Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, benzersiz kimlik değerlerini (ör. SlideId) ve dinamik içeriği (ör. Tarih Yer Tutucusundaki geçerli tarih değeri) dikkate almaz. |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/slide/create_theme_effective/#) | Bu slayt için etkili bir temayı döndürür. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/slide/find_shape_by_alt_text/#str) | Belirtilen alternatif metne sahip şeklin ilk örneğini bulur. |
| [`write_as_emf(self, stream)`](/slides/python-net/tr/aspose.slides/slide/write_as_emf/#iorawiobase) | Slayt içeriğini bir EMF dosyası olarak kaydeder. |
| [`remove(self)`](/slides/python-net/tr/aspose.slides/slide/remove/#) | Slaytı sunumdan kaldırır. |
| [`reset(self)`](/slides/python-net/tr/aspose.slides/slide/reset/#) | LayoutSlide üzerinde bir prototipi olan her şeklin konum, boyut ve biçimini sıfırlar. |
| [`get_slide_comments(self, author)`](/slides/python-net/tr/aspose.slides/slide/get_slide_comments/#icommentauthor) | Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür. |

### Ayrıca Bakınız
* sınıf [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)
* sınıf [`Slide`](/slides/python-net/tr/aspose.slides/slide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)