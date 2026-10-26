---
title: HtmlOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/htmloptions/
---
## HtmlOptions sınıf

HTML dışa aktarım seçeneklerini temsil eder.

**Kalıtım:**[`HtmlOptions`](/slides/python-net/tr/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)

HtmlOptions türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/tr/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Yeni bir HtmlOptions nesnesi oluşturur ve geri aramayı belirtir. |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.export/htmloptions/__init__/#) | Yeni bir HtmlOptions nesnesi oluşturur ve tek bir HTML dosyasına kaydetmek için kullanılır. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`warning_callback`](/slides/python-net/tr/aspose.slides.export/htmloptions/warning_callback/) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar.<br/>            Okunur/Yazılır [`IWarningCallback`](/slides/python-net/tr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/tr/aspose.slides.export/htmloptions/progress_callback/) | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri arama nesnesini temsil eder.<br/>            Bkz [`IProgressCallback`](/slides/python-net/tr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides.export/htmloptions/default_regular_font/) | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar.<br/>            Okunur/Yazılır **str**. |
| [`gradient_style`](/slides/python-net/tr/aspose.slides.export/htmloptions/gradient_style/) | Gradyanın görsel stilini döndürür veya ayarlar.<br/>            Okunur/Yazılır [`GradientStyle`](/slides/python-net/tr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/tr/aspose.slides.export/htmloptions/skip_java_script_links/) | Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirler.<br/>            Okunur/Yazılır **bool**. Varsayılan değer **false** dır. |
| [`slides_layout_options`](/slides/python-net/tr/aspose.slides.export/htmloptions/slides_layout_options/) | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır veya ayarlar [`ISlidesLayoutOptions`](/slides/python-net/tr/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/tr/aspose.slides.export/htmloptions/ink_options/) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar.<br/>            Salt Okunur [`IInkOptions`](/slides/python-net/tr/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/tr/aspose.slides.export/htmloptions/show_hidden_slides/) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler.<br/>            Varsayılan `false` dır. |
| [`html_formatter`](/slides/python-net/tr/aspose.slides.export/htmloptions/html_formatter/) | HTML şablonunu döndürür veya ayarlar.<br/>            Okunur/Yazılır [`IHtmlFormatter`](/slides/python-net/tr/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/tr/aspose.slides.export/htmloptions/disable_font_ligatures/) | Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar.<br/>            `true` olarak ayarlandığında, render çıktısında ligatürler devre dışı bırakılır. Varsayılan olarak bu özellik **false** olarak ayarlanmıştır. |
| [`slide_image_format`](/slides/python-net/tr/aspose.slides.export/htmloptions/slide_image_format/) | Slayt görüntü formatı seçeneklerini döndürür veya ayarlar.<br/>            Okunur/Yazılır [`ISlideImageFormat`](/slides/python-net/tr/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/tr/aspose.slides.export/htmloptions/jpeg_quality/) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar.<br/>            Okunur/Yazılır **int**. |
| [`pictures_compression`](/slides/python-net/tr/aspose.slides.export/htmloptions/pictures_compression/) | Resim sıkıştırma seviyesini temsil eder |
| [`delete_pictures_cropped_areas`](/slides/python-net/tr/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Kesilen bölümlerin belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean işareti. `true` ise kesilen bölümler kaldırılır, `false` ise belge içinde serileştirilir (bu daha büyük bir dosyaya yol açabilir). |
| [`svg_responsive_layout`](/slides/python-net/tr/aspose.slides.export/htmloptions/svg_responsive_layout/) | SVG konteynerinden genişlik ve yükseklik özniteliklerini dışlamak için `true` - bu düzeni duyarlı yapar. Aksi takdirde `false`.<br/>            Okunur/Yazılır **bool**. |

### Ayrıca Bakınız
* sınıf [`HtmlOptions`](/slides/python-net/tr/aspose.slides.export/htmloptions)
* sınıf [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)