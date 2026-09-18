---
title: PdfOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/pdfoptions/
---
## PdfOptions sınıfı

Sunumun Pdf formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

**Inheritance:**[`PdfOptions`](/slides/python-net/tr/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)

PdfOptions tipi aşağıdaki üyeleri ortaya çıkar.

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.export/pdfoptions/__init__/#) | Varsayılan yapıcı. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`warning_callback`](/slides/python-net/tr/aspose.slides.export/pdfoptions/warning_callback/) | Uyarıları alıp yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IWarningCallback`](/slides/python-net/tr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/tr/aspose.slides.export/pdfoptions/progress_callback/) | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri çağırma nesnesini temsil eder.<br/>            Bkz [`IProgressCallback`](/slides/python-net/tr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides.export/pdfoptions/default_regular_font/) | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`gradient_style`](/slides/python-net/tr/aspose.slides.export/pdfoptions/gradient_style/) | Gradyanın görsel stilini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`GradientStyle`](/slides/python-net/tr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/tr/aspose.slides.export/pdfoptions/skip_java_script_links/) | Sunumu kaydederken JavaScript çağrıları içeren bağlantıların atlanıp atlanmayacağını belirtir. <br/>            Okunur/Yazılabilir **bool**. Varsayılan değer **false**. |
| [`slides_layout_options`](/slides/python-net/tr/aspose.slides.export/pdfoptions/slides_layout_options/) | Sunumu dışa aktarırken slaytların sayfada nasıl yerleştirileceği modunu alır veya ayarlar [`ISlidesLayoutOptions`](/slides/python-net/tr/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/tr/aspose.slides.export/pdfoptions/ink_options/) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar.<br/>            Yalnızca okunabilir [`IInkOptions`](/slides/python-net/tr/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/tr/aspose.slides.export/pdfoptions/show_hidden_slides/) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir.<br/>            Varsayılan **false**. |
| [`text_compression`](/slides/python-net/tr/aspose.slides.export/pdfoptions/text_compression/) | Belgedeki tüm metin içeriği için kullanılacak sıkıştırma türünü belirtir.<br/>            Okunur/Yazılabilir [`PdfTextCompression`](/slides/python-net/tr/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/tr/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Her görüntü için en etkili sıkıştırmanın (varsayılanın yerine) otomatik olarak seçilip seçilmeyeceğini gösterir<br/>            otomatik olarak. **bool**.true olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma <br/>            algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasına yol açar.<br/>            En iyi görüntü sıkıştırma oranını seçmek hesap açısından maliyetlidir ve ek bir RAM miktarı gerektirir; bu seçenek varsayılan olarak **bool**.false'tur. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/tr/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Aspose.Slides'in ASCII (33..127 kod aralığı) metin için ortak yazı tiplerini gömmesini belirler.<br/>            127'den büyük karakter kodları için yazı tipleri her zaman gömülür.<br/>            Ortak yazı tipleri listesi PDF'in temel 14 yazı tipini ve ek kullanıcı belirlediği yazı tiplerini içerir.<br/>            Okunur/Yazılabilir **bool**. |
| [`additional_common_font_families`](/slides/python-net/tr/aspose.slides.export/pdfoptions/additional_common_font_families/) | Aspose.Slides'in ortak olarak kabul etmesi gereken kullanıcı tanımlı yazı tipi aile adlarının bir dizisini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**[]. |
| [`embed_full_fonts`](/slides/python-net/tr/aspose.slides.export/pdfoptions/embed_full_fonts/) | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/tr/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir.<br/>            Bu yaklaşım belirli yazı tipleri için sonuç PDF'deki metin kalitesini artırabilir.<br/>            Okunur/Yazılabilir **bool**. |
| [`jpeg_quality`](/slides/python-net/tr/aspose.slides.export/pdfoptions/jpeg_quality/) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **int**. |
| [`compliance`](/slides/python-net/tr/aspose.slides.export/pdfoptions/compliance/) | Oluşturulan PDF belgesi için istenen uyumluluk düzeyini belirler.<br/>            Okunur/Yazılabilir [`PdfCompliance`](/slides/python-net/tr/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/tr/aspose.slides.export/pdfoptions/password/) | PDF belgesini korumak için kullanıcı şifresi ayarlanması.<br/>            Okunur/Yazılabilir **str**. |
| [`access_permissions`](/slides/python-net/tr/aspose.slides.export/pdfoptions/access_permissions/) | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir bayrak kümesi içerir.<br/>            Bkz [`PdfAccessPermissions`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/tr/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | Sunumda kullanılan tüm metafile'ların PNG görüntülerine dönüştürülmesi için **true**.<br/>            Okunur/Yazılabilir **bool**. |
| [`sufficient_resolution`](/slides/python-net/tr/aspose.slides.export/pdfoptions/sufficient_resolution/) | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar.<br/>            <br/>Bu özellik dosya boyutunu, dışa aktarma süresini ve görüntü kalitesini etkiler.<br/><br/><br/>Varsayılan değer **96**.<br/><br/><br/>            Okunur/Yazılabilir **float**. |
| [`draw_slides_frame`](/slides/python-net/tr/aspose.slides.export/pdfoptions/draw_slides_frame/) | Her slaytın etrafına siyah çerçeve çizmek için **true**.<br/>             Okunur/Yazılabilir **bool**. |
| [`image_transparent_color`](/slides/python-net/tr/aspose.slides.export/pdfoptions/image_transparent_color/) | Görüntünün saydam rengini alır veya ayarlar. |
| [`apply_image_transparent`](/slides/python-net/tr/aspose.slides.export/pdfoptions/apply_image_transparent/) | Belirtilen saydam rengi `true` ise bir görüntüye uygular. |
| [`include_ole_data`](/slides/python-net/tr/aspose.slides.export/pdfoptions/include_ole_data/) | Sunumdan gelen tüm OLE verilerini sonuç PDF'de gömülü dosyalara dönüştürmek için **true**.<br/>            Okunur/Yazılabilir **bool**. |

### Ayrıca Bakınız
* sınıf [`PdfOptions`](/slides/python-net/tr/aspose.slides.export/pdfoptions)
* sınıf [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)