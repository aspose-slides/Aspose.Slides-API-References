---
title: NotesSlide class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/notesslide/
---
## NotesSlide sınıfı

Bir sunumda not slaytını temsil eder.

**Kalıtım:**[`NotesSlide`](/slides/python-net/tr/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)

NotesSlide türü aşağıdaki üyeleri sunar:

## Özellikler

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/tr/aspose.slides/notesslide/shapes/) | Bir slaydın şekillerini döndürür.<br/>            Yalnızca okunur [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/tr/aspose.slides/notesslide/controls/) | Bir slayttaki ActiveX kontrol koleksiyonunu döndürür.<br/>            Yalnızca okunur [`IControlCollection`](/slides/python-net/tr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/tr/aspose.slides/notesslide/name/) | Bir slaydın adını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`slide_id`](/slides/python-net/tr/aspose.slides/notesslide/slide_id/) | Bir slaydın kimliğini döndürür.<br/>            Yalnızca okunur **int**. |
| [`custom_data`](/slides/python-net/tr/aspose.slides/notesslide/custom_data/) | Slaydın özel verilerini döndürür.<br/>            Yalnızca okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/tr/aspose.slides/notesslide/timeline/) | Animasyon zaman çizelgesi nesnesini döndürür.<br/>            Yalnızca okunur [`IAnimationTimeLine`](/slides/python-net/tr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/notesslide/slide_show_transition/) | Belirtilen slaydın bir slayt gösterisi sırasında nasıl ilerlediğine dair bilgileri içeren Transition nesnesini döndürür.<br/>            Yalnızca okunur [`ISlideShowTransition`](/slides/python-net/tr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/tr/aspose.slides/notesslide/background/) | Slaydın arka planını döndürür.<br/>            Yalnızca okunur [`IBackground`](/slides/python-net/tr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/notesslide/hyperlink_queries/) | İçerdiği köprü bağlantılarına kolay erişim sağlar.<br/>            Yalnızca okunur [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/notesslide/show_master_shapes/) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir.<br/>            Okunur/yazılabilir **bool**. |
| [`presentation`](/slides/python-net/tr/aspose.slides/notesslide/presentation/) | IPresentation arabirimini döndürür.<br/>            Yalnızca okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/tr/aspose.slides/notesslide/header_footer_manager/) | Not slaydının HeaderFooter yöneticisini döndürür.<br/>            Yalnızca okunur [`INotesSlideHeaderFooterManager`](/slides/python-net/tr/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/tr/aspose.slides/notesslide/notes_text_frame/) | Varsa not metni içeren bir TextFrame döndürür.<br/>            Yalnızca okunur [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/tr/aspose.slides/notesslide/theme_manager/) | Üstüne yazılan tema yöneticisini döndürür.<br/>            Yalnızca okunur [`IOverrideThemeManager`](/slides/python-net/tr/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/tr/aspose.slides/notesslide/parent_slide/) | Ana slaytı döndürür.<br/>            Yalnızca okunur [`ISlide`](/slides/python-net/tr/aspose.slides/islide). |
| [`slide`](/slides/python-net/tr/aspose.slides/notesslide/slide/) |  |

## Yöntemler

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Tüm paragraflardaki aynı biçimlendirmeye sahip run'ları tüm uygun şekillerde birleştirir. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/tr/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Tüm uygun şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/notesslide/equals/#ibaseslide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler.<br/>            Döndürülen değer, slaydın yapısı ve statik içeriğine dayanarak hesaplanır.<br/>            Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşit olduğunda iki slayt eşittir. Karşılaştırma, benzersiz tanımlayıcı değerleri (ör. SlideId) ve dinamik içeriği (ör. Tarih Yer Tutucusundaki geçerli tarih değeri) dikkate almaz. |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/notesslide/create_theme_effective/#) | Bu slayt için etkili bir temayı döndürür. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur. |

### Ayrıca Bakınız
* sınıf [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)
* sınıf [`NotesSlide`](/slides/python-net/tr/aspose.slides/notesslide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)