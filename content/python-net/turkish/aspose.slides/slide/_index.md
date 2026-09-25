---
title: Slide class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/slide/
---
## Slide sınıfı

Bir sunumdaki slaytı temsil eder.

**Kalıtım:**[`Slide`](/slides/python-net/tr/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)

Slide türü aşağıdaki üyeleri ortaya çıkarır.

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`shapes`](/slides/python-net/tr/aspose.slides/slide/shapes/) | Bir slaytın şekillerini döndürür.<br/>            Yalnızca okunabilir [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/tr/aspose.slides/slide/controls/) | Bir slaytta bulunan ActiveX denetimlerinin koleksiyonunu döndürür.<br/>            Yalnızca okunabilir [`IControlCollection`](/slides/python-net/tr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/tr/aspose.slides/slide/name/) | Bir slaytın adını döndürür veya ayarlar.<br/>            Okunabilir/yazılabilir **str**. |
| [`slide_id`](/slides/python-net/tr/aspose.slides/slide/slide_id/) | Bir slaytın kimliğini döndürür.<br/>            Yalnızca okunabilir **int**. |
| [`custom_data`](/slides/python-net/tr/aspose.slides/slide/custom_data/) | Slaytın özel verilerini döndürür.<br/>            Yalnızca okunabilir [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/tr/aspose.slides/slide/timeline/) | Animasyon zaman çizelgesi nesnesini döndürür.<br/>            Yalnızca okunabilir [`IAnimationTimeLine`](/slides/python-net/tr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/slide/slide_show_transition/) | Belirtilen slaytın slayt gösterisi sırasında nasıl ilerlediğine dair bilgileri içeren Transition nesnesini döndürür.<br/>            Yalnızca okunabilir [`ISlideShowTransition`](/slides/python-net/tr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/tr/aspose.slides/slide/background/) | Slaytın arka planını döndürür.<br/>            Yalnızca okunabilir [`IBackground`](/slides/python-net/tr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/slide/hyperlink_queries/) | İçerilen hiperlinklere kolay erişim sağlar.<br/>            Yalnızca okunabilir [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/slide/show_master_shapes/) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler.<br/>            Okunabilir/yazılabilir **bool**. |
| [`presentation`](/slides/python-net/tr/aspose.slides/slide/presentation/) | IPresentation arayüzünü döndürür.<br/>            Yalnızca okunabilir [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/tr/aspose.slides/slide/header_footer_manager/) | Slaytın HeaderFooter yöneticisini döndürür.<br/>            Yalnızca okunabilir [`ISlideHeaderFooterManager`](/slides/python-net/tr/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/tr/aspose.slides/slide/theme_manager/) | Geçersiz kılan tema yöneticisini döndürür.<br/>            Yalnızca okunabilir [`IOverrideThemeManager`](/slides/python-net/tr/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/tr/aspose.slides/slide/slide_number/) | Bir slaytın numarasını döndürür.<br/>            [`Presentation.slides`](/slides/python-net/tr/aspose.slides/presentation/slides) koleksiyonundaki slayt indeksi, her zaman SlideNumber - Presentation.FirstSlideNumber değerine eşit olur.<br/>            Okunabilir/yazılabilir **int**. |
| [`hidden`](/slides/python-net/tr/aspose.slides/slide/hidden/) | Belirtilen slaytın slayt gösterisi sırasında gizli olup olmadığını belirler.<br/>            Okunabilir/yazılabilir **bool**. |
| [`layout_slide`](/slides/python-net/tr/aspose.slides/slide/layout_slide/) | Mevcut slayt için yerleşim slaytını döndürür veya ayarlar.<br/>            Okunabilir/yazılabilir [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/tr/aspose.slides/slide/notes_slide_manager/) | Not slaytına erişim sağlar, ekler ve kaldırır.<br/>            Yalnızca okunabilir [`INotesSlideManager`](/slides/python-net/tr/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/tr/aspose.slides/slide/slide/) |  |

## Yöntemler

| Metot | Açıklama |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/slide/join_portions_with_same_formatting/#) | Kabul edilebilir tüm şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşu parçalarını birleştirir. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/tr/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Kabul edilebilir tüm şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşu parçalarını birleştirir. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/slide/get_image/#float-float) | Özel ölçekleme ile bir Küçük Resim nesnesi döndürür. |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/slide/get_image/#) | Gerçek boyutunun %20'si kadar bir Küçük Resim nesnesi döndürür. |
| [`get_image(self, image_size)`](/slides/python-net/tr/aspose.slides/slide/get_image/#asposeslidessize) | Belirtilen boyutta bir Küçük Resim nesnesi döndürür. |
| [`get_image(self, options)`](/slides/python-net/tr/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Belirtilen parametrelerle bir Küçük tiff görüntü nesnesi döndürür. |
| [`get_image(self, options)`](/slides/python-net/tr/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Bir Küçük Resim nesnesi döndürür. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Özel ölçekleme ile bir Küçük Resim nesnesi döndürür. |
| [`get_image(self, options, image_size)`](/slides/python-net/tr/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Belirtilen boyutta bir Küçük Resim nesnesi döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/slide/write_as_svg/#iorawiobase) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/slide/equals/#ibaseslide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler.<br/>            Dönüş değeri, slaytın yapısı ve statik içeriği temel alınarak hesaplanır.<br/>            Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse slaytlar eşittir. Karşılaştırma, SlideId gibi benzersiz tanımlayıcı değerlerini ve dinamik içerikleri (ör. tarih tutucu içindeki geçerli tarih) dikkate almaz. |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/slide/create_theme_effective/#) | Bu slayt için etkili bir temayı döndürür. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/slide/find_shape_by_alt_text/#str) | Belirtilen alternatif metne sahip şeklin ilk gerçekleşmesini bulur. |
| [`write_as_emf(self, stream)`](/slides/python-net/tr/aspose.slides/slide/write_as_emf/#iorawiobase) | Slayt içeriğini bir EMF dosyası olarak kaydeder. |
| [`remove(self)`](/slides/python-net/tr/aspose.slides/slide/remove/#) | Slaytı sunumdan kaldırır. |
| [`reset(self)`](/slides/python-net/tr/aspose.slides/slide/reset/#) | LayoutSlide üzerinde prototipi olan her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar. |
| [`get_slide_comments(self, author)`](/slides/python-net/tr/aspose.slides/slide/get_slide_comments/#icommentauthor) | Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür. |

### Ayrıca Bakınız
* sınıf [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)
* sınıf [`Slide`](/slides/python-net/tr/aspose.slides/slide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)