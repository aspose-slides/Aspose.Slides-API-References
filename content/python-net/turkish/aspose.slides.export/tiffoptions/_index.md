---
title: TiffOptions class
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/tiffoptions/
---
## TiffOptions sınıfı

Bir sunumun TIFF formatında kaydedilmesini kontrol eden seçenekleri sağlar.

**Kalıtım:**[`TiffOptions`](/slides/python-net/tr/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)

TiffOptions türü aşağıdaki üyeleri ortaya çıkarır:

## Yapıcılar

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.export/tiffoptions/__init__/#) | Varsayılan yapıcı. |

## Özellikler

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/tr/aspose.slides.export/tiffoptions/warning_callback/) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar.<br/>            Okunur/yazılır [`IWarningCallback`](/slides/python-net/tr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/tr/aspose.slides.export/tiffoptions/progress_callback/) | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri çağırma nesnesini temsil eder.<br/>            Bakınız [`IProgressCallback`](/slides/python-net/tr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides.export/tiffoptions/default_regular_font/) | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar.<br/>            Okunur-yazılır **str**. |
| [`gradient_style`](/slides/python-net/tr/aspose.slides.export/tiffoptions/gradient_style/) | Gradyanın görsel stilini döndürür veya ayarlar.<br/>            Okunur/yazılır [`GradientStyle`](/slides/python-net/tr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/tr/aspose.slides.export/tiffoptions/skip_java_script_links/) | Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirtir. <br/>            Okunur/yazılır **bool**. Varsayılan değer **false** . |
| [`ink_options`](/slides/python-net/tr/aspose.slides.export/tiffoptions/ink_options/) | Dışa aktarılan belgede Mürekkep nesnelerinin görünümünü kontrol eden seçenekleri sağlar.<br/>            Salt okunur [`IInkOptions`](/slides/python-net/tr/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/tr/aspose.slides.export/tiffoptions/show_hidden_slides/) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler.<br/>            Varsayılan `false`. |
| [`image_size`](/slides/python-net/tr/aspose.slides.export/tiffoptions/image_size/) | Oluşturulan TIFF görüntüsünün boyutunu belirtir.<br/>            Varsayılan değer 0x0, bu da oluşturulan görüntü boyutlarının sunum slaytı boyutuna göre hesaplanacağı anlamına gelir.<br/>            Okunur/yazılır [`Size`](/slides/python-net/tr/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/tr/aspose.slides.export/tiffoptions/dpi_x/) | İnç başına düşen nokta sayısı (dpi) olarak yatay çözünürlüğü belirtir.<br/>            Okunur/yazılır **int**. |
| [`dpi_y`](/slides/python-net/tr/aspose.slides.export/tiffoptions/dpi_y/) | İnç başına düşen nokta sayısı (dpi) olarak dikey çözünürlüğü belirtir.<br/>            Okunur/yazılır **int**. |
| [`compression_type`](/slides/python-net/tr/aspose.slides.export/tiffoptions/compression_type/) | Sıkıştırma tipini belirtir.<br/>            Okunur/yazılır [`TiffCompressionTypes`](/slides/python-net/tr/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/tr/aspose.slides.export/tiffoptions/pixel_format/) | Oluşturulan görüntüler için piksel formatını belirtir.<br/>            Okunur/yazılır [`ImagePixelFormat`](/slides/python-net/tr/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/tr/aspose.slides.export/tiffoptions/slides_layout_options/) | Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır veya ayarlar [`ISlidesLayoutOptions`](/slides/python-net/tr/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/tr/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Renkli bir resmi siyah beyaza dönüştürmek için kullanılan algoritmayı belirtir.<br/>            Bu seçenek yalnızca [`TiffOptions.compression_type`](/slides/python-net/tr/aspose.slides.export/tiffoptions/compression_type) <br/>            [`TiffCompressionTypes.CCITT4`](/slides/python-net/tr/aspose.slides.export/tiffcompressiontypes/CCITT4) ya da [`TiffCompressionTypes.CCITT3`](/slides/python-net/tr/aspose.slides.export/tiffcompressiontypes/CCITT3) olarak ayarlandığında uygulanır<br/>            Okunur/yazılır [`BlackWhiteConversionMode`](/slides/python-net/tr/aspose.slides.export/blackwhiteconversionmode).<br/>            Varsayılan [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/tr/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |


### Bakınız
* sınıf [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)
* sınıf [`TiffOptions`](/slides/python-net/tr/aspose.slides.export/tiffoptions)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)