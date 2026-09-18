---
title: MasterNotesSlide class
second_title: Aspose.Slides için .NET aracılığıyla Python API Referansı
description: 
type: docs
url: /tr/aspose.slides/masternotesslide/
---
## MasterNotesSlide sınıfı

Notlar için ana slaytı temsil eder.

**Kalıtım:**[`MasterNotesSlide`](/slides/python-net/tr/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)

The MasterNotesSlide type exposes the following members:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`shapes`](/slides/python-net/tr/aspose.slides/masternotesslide/shapes/) | Bir slaytın şekillerini döndürür.<br/>            Yalnızca okunur [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/tr/aspose.slides/masternotesslide/controls/) | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür.<br/>            Yalnızca okunur [`IControlCollection`](/slides/python-net/tr/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/tr/aspose.slides/masternotesslide/name/) | Bir slaytın adını döndürür veya ayarlar.<br/>            Okunur/Yazılır **str**. |
| [`slide_id`](/slides/python-net/tr/aspose.slides/masternotesslide/slide_id/) | Bir slaytın kimliğini döndürür.<br/>            Yalnızca okunur **int**. |
| [`custom_data`](/slides/python-net/tr/aspose.slides/masternotesslide/custom_data/) | Slaytın özel verilerini döndürür.<br/>            Yalnızca okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/tr/aspose.slides/masternotesslide/timeline/) | Animasyon zaman çizelgesi nesnesini döndürür.<br/>            Yalnızca okunur [`IAnimationTimeLine`](/slides/python-net/tr/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/tr/aspose.slides/masternotesslide/slide_show_transition/) | Belirtilen slaydın slayt gösterisi sırasında nasıl ilerlediği hakkında bilgi içeren Transition nesnesini döndürür.<br/>            Yalnızca okunur [`ISlideShowTransition`](/slides/python-net/tr/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/tr/aspose.slides/masternotesslide/background/) | Slaytın arka planını döndürür.<br/>            Yalnızca okunur [`IBackground`](/slides/python-net/tr/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/masternotesslide/hyperlink_queries/) | İçerilen köprü bağlantılarına kolay erişim sağlar.<br/>            Yalnızca okunur [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/tr/aspose.slides/masternotesslide/show_master_shapes/) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir.<br/>            Ana slayt için bu özellik her zaman `false` döndürür.<br/>            Okunur/Yazılır **bool**. |
| [`presentation`](/slides/python-net/tr/aspose.slides/masternotesslide/presentation/) | IPresentation arayüzünü döndürür.<br/>            Yalnızca okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/tr/aspose.slides/masternotesslide/header_footer_manager/) | Ana not slaydının HeaderFooter yöneticisini döndürür.<br/>            Yalnızca okunur [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/tr/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/tr/aspose.slides/masternotesslide/theme_manager/) | Tema yöneticisini döndürür.<br/>            Yalnızca okunur [`IMasterThemeManager`](/slides/python-net/tr/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/tr/aspose.slides/masternotesslide/notes_style/) | Not metninin stilini döndürür.<br/>            Yalnızca okunur [`ITextStyle`](/slides/python-net/tr/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/tr/aspose.slides/masternotesslide/drawing_guides/) | Ana not slaydı için çizim kılavuzları koleksiyonunu döndürür.<br/>            Yalnızca okunur [`IDrawingGuidesCollection`](/slides/python-net/tr/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/tr/aspose.slides/masternotesslide/slide/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip runları birleştirir. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/tr/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip runları birleştirir. |
| [`equals(self, slide)`](/slides/python-net/tr/aspose.slides/masternotesslide/equals/#ibaseslide) | İki IBaseSlide örneğinin eşit olup olmadığını belirler.<br/>            Döndürülen değer, slaytın yapısı ve statik içeriğine göre hesaplanır.<br/>            Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşit olduğunda iki slayt eşittir. Karşılaştırma, benzersiz tanımlayıcı değerlerini (ör. SlideId) ve dinamik içeriği (ör. Tarih Yer Tutucusundaki mevcut tarih değeri) dikkate almaz. |
| [`create_theme_effective(self)`](/slides/python-net/tr/aspose.slides/masternotesslide/create_theme_effective/#) | Bu slayt için etkin bir temayı döndürür. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/tr/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Belirtilen alternatif metne sahip şeklin ilk örneğini bulur. |

### İlgili
* sınıf [`BaseSlide`](/slides/python-net/tr/aspose.slides/baseslide)
* sınıf [`MasterNotesSlide`](/slides/python-net/tr/aspose.slides/masternotesslide)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)