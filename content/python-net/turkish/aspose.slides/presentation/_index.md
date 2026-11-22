---
title: Presentation class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/presentation/
---
## Presentation sınıfı

Microsoft PowerPoint sunumunu temsil eder.

Presentation türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides/presentation/__init__/#) | Bu yapıcı, yeni bir sunumu sıfırdan oluşturur.<br/>            Oluşturulan sunumda bir boş slayt bulunur. |
| [`__init__(self, load_options)`](/slides/python-net/tr/aspose.slides/presentation/__init__/#loadoptions) | Bu yapıcı, yeni bir sunumu sıfırdan oluşturur.<br/>            Oluşturulan sunumda bir boş slayt bulunur. |
| [`__init__(self, stream)`](/slides/python-net/tr/aspose.slides/presentation/__init__/#iorawiobase) | Bu yapıcı, mevcut bir Presentation'ı okumanın birincil mekanizmasıdır. |
| [`__init__(self, stream, load_options)`](/slides/python-net/tr/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Bu yapıcı, mevcut bir Presentation'ı okumanın birincil mekanizmasıdır. |
| [`__init__(self, file)`](/slides/python-net/tr/aspose.slides/presentation/__init__/#str) | Bu yapıcı, Presentation içeriğinin okunduğu bir kaynak dosya yolunu alır.<br/>             |
| [`__init__(self, file, load_options)`](/slides/python-net/tr/aspose.slides/presentation/__init__/#str-loadoptions) | Bu yapıcı, Presentation içeriğinin okunduğu bir kaynak dosya yolunu alır.<br/>            |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`current_date_time`](/slides/python-net/tr/aspose.slides/presentation/current_date_time/) | Tarih ve saat değerini döndürür veya ayarlar; bu, datetime alanlarının içeriğinin yerine geçecektir.<br/>            Varsayılan olarak bu Presentation nesnesinin oluşturulma zamanı.<br/>            Okunur/yazılabilir **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/tr/aspose.slides/presentation/header_footer_manager/) | Gerçek HeaderFooter yöneticisini döndürür.<br/>            Yalnızca okunur [`IPresentationHeaderFooterManager`](/slides/python-net/tr/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/tr/aspose.slides/presentation/protection_manager/) | Bu sunum için izin yöneticisini alır.<br/>            Yalnızca okunur [`IProtectionManager`](/slides/python-net/tr/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/tr/aspose.slides/presentation/slides/) | Sunumda tanımlı tüm slaytların listesini döndürür.<br/tr/>            Yalnızca okunur [`ISlideCollection`](/slides/python-net/tr/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/tr/aspose.slides/presentation/sections/) | Sunumda tanımlı tüm slayt bölümlerinin listesini döndürür.<br/>            Yalnızca okunur [`ISectionCollection`](/slides/python-net/tr/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/tr/aspose.slides/presentation/slide_size/) | Slayt boyutu nesnesini döndürür.<br/>            Yalnızca okunur [`ISlideSize`](/slides/python-net/tr/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/tr/aspose.slides/presentation/notes_size/) | Not slaytı boyutu nesnesini döndürür.<br/>            Yalnızca okunur [`INotesSize`](/slides/python-net/tr/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/tr/aspose.slides/presentation/layout_slides/) | Sunumda tanımlı tüm yerleşim slaytlarının listesini döndürür.<br/>            Yalnızca okunur [`IGlobalLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/tr/aspose.slides/presentation/masters/) | Sunumda tanımlı tüm ana slaytların listesini döndürür.<br/>            Yalnızca okunur [`IMasterSlideCollection`](/slides/python-net/tr/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/tr/aspose.slides/presentation/master_notes_slide_manager/) | Not ana yöneticisini döndürür.<br/>            Yalnızca okunur [`IMasterNotesSlideManager`](/slides/python-net/tr/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/tr/aspose.slides/presentation/master_handout_slide_manager/) | El ilanı ana yöneticisini döndürür.<br/>            Yalnızca okunur [`IMasterHandoutSlideManager`](/slides/python-net/tr/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/tr/aspose.slides/presentation/fonts_manager/) | Yazı tipleri yöneticisini döndürür.<br/>            Yalnızca okunur [`IFontsManager`](/slides/python-net/tr/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/tr/aspose.slides/presentation/default_text_style/) | Şekiller için varsayılan metin stilini döndürür.<br/>            Yalnızca okunur [`ITextStyle`](/slides/python-net/tr/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/tr/aspose.slides/presentation/comment_authors/) | Yorum yazarlarının koleksiyonunu döndürür.<br/>            Yalnızca okunur [`ICommentAuthorCollection`](/slides/python-net/tr/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/tr/aspose.slides/presentation/document_properties/) | Standart ve özel belge özelliklerini içeren DocumentProperties nesnesini döndürür.<br/>            Yalnızca okunur [`IDocumentProperties`](/slides/python-net/tr/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/tr/aspose.slides/presentation/images/) | Sunumdaki tüm görsellerin koleksiyonunu döndürür.<br/>            Yalnızca okunur [`IImageCollection`](/slides/python-net/tr/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/tr/aspose.slides/presentation/audios/) | Sunumdaki tüm gömülü ses dosyalarının koleksiyonunu döndürür.<br/>            Yalnızca okunur [`IAudioCollection`](/slides/python-net/tr/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/tr/aspose.slides/presentation/videos/) | Sunumdaki tüm gömülü video dosyalarının koleksiyonunu döndürür.<br/>            Yalnızca okunur [`IVideoCollection`](/slides/python-net/tr/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/tr/aspose.slides/presentation/slide_show_settings/) | Sunum için slayt gösterisi ayarlarını döndürür. |
| [`digital_signatures`](/slides/python-net/tr/aspose.slides/presentation/digital_signatures/) | Sunumu imzalamak için kullanılan imzaların koleksiyonunu döndürür.<br/>            Yalnızca okunur [`IDigitalSignatureCollection`](/slides/python-net/tr/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/presentation/custom_data/) | Sunumun özel verilerini döndürür.<br/>            Yalnızca okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/tr/aspose.slides/presentation/all_custom_xml_parts/) | Sunumdaki tüm özel veri parçalarını döndürür.<br/>            Yalnızca okunur [`ICustomXmlPart`](/slides/python-net/tr/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/tr/aspose.slides/presentation/vba_project/) | Sunum makroları içeren VBA projesini alır veya ayarlar.<br/>            Okunur/yazılabilir [`IVbaProject`](/slides/python-net/tr/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/tr/aspose.slides/presentation/hyperlink_queries/) | Tüm sunum slaytlarındaki (ana, yerleşim, not slaytlarında olmayan) tüm köprüleri kolay erişim sağlar.<br/>            Yalnızca okunur [`IHyperlinkQueries`](/slides/python-net/tr/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/tr/aspose.slides/presentation/view_properties/) | Sunum genelinde görünüm özelliklerini alır.<br/>            Yalnızca okunur [`IViewProperties`](/slides/python-net/tr/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/tr/aspose.slides/presentation/first_slide_number/) | Sunumdaki ilk slayt numarasını temsil eder |
| [`sensitivity_labels`](/slides/python-net/tr/aspose.slides/presentation/sensitivity_labels/) | Sunum belgesine uygulanan hassasiyet etiketlerinin koleksiyonunu döndürür.<br/>            Yalnızca okunur [`ISensitivityLabelCollection`](/slides/python-net/tr/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/tr/aspose.slides/presentation/source_format/) | Sunumun hangi biçimden yüklendiğine dair bilgiyi döndürür.<br/>            Yalnızca okunur [`SourceFormat`](/slides/python-net/tr/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/tr/aspose.slides/presentation/master_theme/) | Ana temayı döndürür.<br/>            Yalnızca okunur [`IMasterTheme`](/slides/python-net/tr/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/tr/aspose.slides/presentation/presentation/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/tr/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Bir sunumun tüm slaytlarını belirtilen biçimde bir dosyaya kaydeder. |
| [`save(self, stream, format)`](/slides/python-net/tr/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Bir sunumun tüm slaytlarını belirtilen biçimde bir akışa kaydeder. |
| [`save(self, fname, format, options)`](/slides/python-net/tr/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/tr/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Bir sunumun tüm slaytlarını belirtilen biçimde ve ek seçeneklerle bir akışa kaydeder. |
| [`save(self, options)`](/slides/python-net/tr/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Bir sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dosya setine kaydeder. |
| [`save(self, fname, slides, format)`](/slides/python-net/tr/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Belirtilen slaytları, sayfa numarası korunarak, belirtilen biçimde bir dosyaya kaydeder. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/tr/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Belirtilen slaytları, sayfa numarası korunarak, belirtilen biçimde bir dosyaya kaydeder. |
| [`save(self, stream, slides, format)`](/slides/python-net/tr/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Belirtilen slaytları, sayfa numarası korunarak, belirtilen biçimde bir akışa kaydeder. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/tr/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Belirtilen slaytları, sayfa numarası korunarak, belirtilen biçimde bir akışa kaydeder. |
| [`get_images(self, options)`](/slides/python-net/tr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Bir sunumun tüm slaytları için Image nesnelerini döndürür. |
| [`get_images(self, options, slides)`](/slides/python-net/tr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Bir sunumun belirtilen slaytları için Thumbnail Image nesnelerini döndürür. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Bir sunumun tüm slaytları için özel ölçekleme ile Thumbnail Image nesnelerini döndürür. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Bir sunumun belirtilen slaytları için özel ölçekleme ile Thumbnail Image nesnelerini döndürür. |
| [`get_images(self, options, image_size)`](/slides/python-net/tr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Bir sunumun tüm slaytları için belirtilen boyutta Thumbnail Image nesnelerini döndürür. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/tr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Bir sunumun belirtilen slaytları için belirtilen boyutta Thumbnail Image nesnelerini döndürür. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/tr/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/tr/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`get_slide_by_id(self, id)`](/slides/python-net/tr/aspose.slides/presentation/get_slide_by_id/#int) | Id'ye göre bir Slide, MasterSlide veya LayoutSlide döndürür. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/tr/aspose.slides/presentation/join_portions_with_same_formatting/#) | Tüm slaytlardaki, kabul edilebilir tüm şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip runları birleştirir. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/tr/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Düzenli ifadelerin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/tr/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Belirtilen metnin tüm tekrarlarını başka bir belirtilen metinle değiştirir. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/tr/aspose.slides/presentation/replace_regex/#str-str) | Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir. |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/tr/aspose.slides/presentation/refresh_charts_data/#bool) | Sunumdaki tüm grafiklerin verilerini kaynak çalışma kitaplarından yeniden yükler. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)