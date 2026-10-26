---
title: IPdfOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/ipdfoptions/
---
## IPdfOptions sınıfı

Bir sunumun Pdf biçiminde nasıl kaydedileceğini kontrol eden seçenekler sağlar.

IPdfOptions türü aşağıdaki üyeleri sunar:

## Özellikler

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/text_compression/) | Belge içindeki tüm metin içerikleri için kullanılacak sıkıştırma türünü belirtir.<br/>            Okuma/Yazma [`PdfTextCompression`](/slides/python-net/tr/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Her görüntü için en etkili sıkıştırmanın (varsayılanın yerine) seçilip seçilmeyeceğini gösterir <br/>            otomatik olarak. **bool**.true olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma <br/>            algoritması seçilir ve bu, sonuç PDF belgesinin daha küçük boyutlu olmasına yol açar. <br/>            En iyi görüntü sıkıştırma oranının seçilmesi işlem açısından maliyetlidir ve <br/>            ek bir RAM miktarı gerektirir; bu seçenek varsayılan olarak **bool**.false'dur. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | ASCII karakterleri 32-127 için True Type yazı tiplerini gömmek amacıyla True.<br/>            127'den büyük karakter kodları için yazı tipleri her zaman gömülür.<br/>            Okuma/Yazma **bool**. |
| [`show_hidden_slides`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir.<br/>            Varsayılan `false`. |
| [`additional_common_font_families`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Aspose.Slides'ın ortak olarak kabul etmesi gereken kullanıcı tanımlı yazı tipi ailesi adlarının bir dizisini döndürür veya ayarlar.<br/>            Okuma/Yazma **str**[]. |
| [`embed_full_fonts`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler.<br/>            Okuma/Yazma **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'ye kaydedilip kaydedilmeyeceğini gösterir.<br/>            Bu yaklaşım, belirli yazı tipleri için sonuç PDF'deki metin kalitesini artırabilir.<br/>            Okuma/Yazma **bool**. |
| [`jpeg_quality`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/jpeg_quality/) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür veya ayarlar.<br/>            Okuma/Yazma **int**. |
| [`compliance`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/compliance/) | Oluşturulan PDF belgesi için istenen uyumluluk seviyesini belirtir.<br/>            Okuma/Yazma [`PdfCompliance`](/slides/python-net/tr/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/password/) | PDF belgesini korumak için kullanıcı şifresi ayarlama.<br/>            Okuma/Yazma **str**. |
| [`access_permissions`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/access_permissions/) | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrak içerir<br/>            [`PdfAccessPermissions`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | Sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için True.<br/>            Okuma/Yazma **bool**. |
| [`sufficient_resolution`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/sufficient_resolution/) | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür veya ayarlar.<br/>            <br/>Özellik dosya boyutunu, dışa aktarma süresini ve görüntü kalitesini etkiler.<br/><br/><br/>Varsayılan değer **96** .<br/><br/><br/>            Okuma/Yazma **float**. |
| [`draw_slides_frame`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/draw_slides_frame/) | Her slaytın etrafına siyah çerçeve çizmek için True.<br/>             Okuma/Yazma **bool**. |
| [`slides_layout_options`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/slides_layout_options/) | Sunumu dışa aktarırken slaytların sayfada hangi modda yerleştirileceğini alır veya ayarlar [`ISlidesLayoutOptions`](/slides/python-net/tr/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/image_transparent_color/) | Görüntünün şeffaf rengini alır veya ayarlar. |
| [`apply_image_transparent`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Belirtilen şeffaf rengi bir görüntüye uygular eğer `true`. |
| [`ink_options`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/ink_options/) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar.<br/>            Yalnızca okunabilir [`IInkOptions`](/slides/python-net/tr/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/include_ole_data/) | Sunumdaki tüm OLE verilerini sonuç PDF'de gömülü dosyalara dönüştürmek için True.<br/>            Okuma/Yazma **bool**. |
| [`warning_callback`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/tr/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Ayrıca Bakınız
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)