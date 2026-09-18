---
title: TiffOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/tiffoptions/
---
## TiffOptions sınıfı

TIFF formatında bir sunumun nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

**Kalıtım:**[`TiffOptions`](/slides/python-net/tr/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)

TiffOptions türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.export/tiffoptions/__init__/#) | Varsayılan yapıcı. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`warning_callback`](/slides/python-net/tr/aspose.slides.export/tiffoptions/warning_callback/) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar.<br/>            Okuma/yazma [`IWarningCallback`](/slides/python-net/tr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/tr/aspose.slides.export/tiffoptions/progress_callback/) | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri arama nesnesini temsil eder.<br/>            Bkz. [`IProgressCallback`](/slides/python-net/tr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides.export/tiffoptions/default_regular_font/) | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar.<br/>            Okuma-yazma **str**. |
| [`gradient_style`](/slides/python-net/tr/aspose.slides.export/tiffoptions/gradient_style/) | Gradyanın görsel stilini döndürür veya ayarlar.<br/>            Okuma/yazma [`GradientStyle`](/slides/python-net/tr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/tr/aspose.slides.export/tiffoptions/skip_java_script_links/) | Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirtir.<br/>            Okuma/yazma **bool**. Varsayılan değer **false** . |
| [`ink_options`](/slides/python-net/tr/aspose.slides.export/tiffoptions/ink_options/) | Dışa aktarılan belgede Mürekkep nesnelerinin görünümünü kontrol eden seçenekleri sağlar.<br/>            Salt Okunur [`IInkOptions`](/slides/python-net/tr/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/tr/aspose.slides.export/tiffoptions/show_hidden_slides/) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir.<br/>            Varsayılan `false`. |
| [`image_size`](/slides/python-net/tr/aspose.slides.export/tiffoptions/image_size/) | Oluşturulan TIFF görüntüsünün boyutunu belirtir.<br/>            Varsayılan değer 0x0, bu da oluşturulan görüntü boyutlarının sunum slaytı boyutuna göre hesaplanacağı anlamına gelir.<br/>            Okuma/yazma **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/tr/aspose.slides.export/tiffoptions/dpi_x/) | İnç başına nokta cinsinden yatay çözünürlüğü belirtir.<br/>            Okuma/yazma **int**. |
| [`dpi_y`](/slides/python-net/tr/aspose.slides.export/tiffoptions/dpi_y/) | İnç başına nokta cinsinden dikey çözünürlüğü belirtir.<br/>            Okuma/yazma **int**. |
| [`compression_type`](/slides/python-net/tr/aspose.slides.export/tiffoptions/compression_type/) | Sıkıştırma tipini belirtir.<br/>            Okuma/yazma [`TiffCompressionTypes`](/slides/python-net/tr/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/tr/aspose.slides.export/tiffoptions/pixel_format/) | Oluşturulan görüntüler için piksel biçimini belirtir.<br/>            Okuma/yazma [`ImagePixelFormat`](/slides/python-net/tr/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/tr/aspose.slides.export/tiffoptions/slides_layout_options/) | Bir sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu döndürür veya ayarlar [`ISlidesLayoutOptions`](/slides/python-net/tr/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/tr/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Renkli bir görüntüyü siyah beyaza dönüştürmek için kullanılan algoritmayı belirtir.<br/>            Bu seçenek yalnızca [`TiffOptions.compression_type`](/slides/python-net/tr/aspose.slides.export/tiffoptions/compression_type) <br/>            [`TiffCompressionTypes.CCITT4`](/slides/python-net/tr/aspose.slides.export/tiffcompressiontypes/CCITT4) ya da [`TiffCompressionTypes.CCITT3`](/slides/python-net/tr/aspose.slides.export/tiffcompressiontypes/CCITT3) olarak ayarlandığında uygulanır<br/>            Okuma/yazma [`BlackWhiteConversionMode`](/slides/python-net/tr/aspose.slides.export/blackwhiteconversionmode).<br/>            Varsayılan [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/tr/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Ayrıca Bakınız
* sınıf [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)
* sınıf [`TiffOptions`](/slides/python-net/tr/aspose.slides.export/tiffoptions)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)