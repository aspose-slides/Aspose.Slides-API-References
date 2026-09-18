---
title: ITiffOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/itiffoptions/
---
## ITiffOptions sınıf

Sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.

ITiffOptions türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`image_size`](/slides/python-net/tr/aspose.slides.export/itiffoptions/image_size/) | Oluşturulan TIFF görüntüsünün boyutunu belirtir.<br/>            Varsayılan değer 0x0'dır, bu da oluşturulan görüntü boyutlarının sunum slaytı boyut değeri temel alınarak hesaplanacağı anlamına gelir.<br/>            Okunur/yazılır **aspose.slides.Size**. |
| [`dpi_x`](/slides/python-net/tr/aspose.slides.export/itiffoptions/dpi_x/) | Yatay çözünürlüğü inç başına nokta olarak belirtir.<br/>            Okunur/yazılır **int**. |
| [`dpi_y`](/slides/python-net/tr/aspose.slides.export/itiffoptions/dpi_y/) | Düşey çözünürlüğü inç başına nokta olarak belirtir.<br/>            Okunur/yazılır **int**. |
| [`show_hidden_slides`](/slides/python-net/tr/aspose.slides.export/itiffoptions/show_hidden_slides/) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir.<br/>            Varsayılan `false`. |
| [`compression_type`](/slides/python-net/tr/aspose.slides.export/itiffoptions/compression_type/) | Sıkıştırma türünü belirtir.<br/>            Okunur/yazılır [`TiffCompressionTypes`](/slides/python-net/tr/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/tr/aspose.slides.export/itiffoptions/pixel_format/) | Oluşturulan görüntüler için piksel formatını belirtir.<br/>            Okunur/yazılır [`ImagePixelFormat`](/slides/python-net/tr/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/tr/aspose.slides.export/itiffoptions/slides_layout_options/) | Sunum [`ISlidesLayoutOptions`](/slides/python-net/tr/aspose.slides.export/islideslayoutoptions) dışa aktarılırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar. |
| [`bw_conversion_mode`](/slides/python-net/tr/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Renkli bir görüntüyü siyah beyaz bir görüntüye dönüştürmek için kullanılan algoritmayı belirtir.<br/>            Bu seçenek yalnızca [`ITiffOptions.compression_type`](/slides/python-net/tr/aspose.slides.export/itiffoptions/compression_type) <br/>            [`TiffCompressionTypes.CCITT4`](/slides/python-net/tr/aspose.slides.export/tiffcompressiontypes/CCITT4) veya [`TiffCompressionTypes.CCITT3`](/slides/python-net/tr/aspose.slides.export/tiffcompressiontypes/CCITT3) olarak ayarlanmışsa uygulanır.<br/>            Okunur/yazılır [`BlackWhiteConversionMode`](/slides/python-net/tr/aspose.slides.export/blackwhiteconversionmode).<br/>            Varsayılan [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/tr/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/tr/aspose.slides.export/itiffoptions/ink_options/) | Dışa aktarılan belgede Mürekkep nesnelerinin görünümünü kontrol eden seçenekler sağlar.<br/>            Salt okunur [`IInkOptions`](/slides/python-net/tr/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/tr/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/tr/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/tr/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/tr/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Ayrıca Bakınız
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)