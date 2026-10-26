---
title: SVGOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/svgoptions/
---
## SVGOptions sınıfı

SVG seçeneklerini temsil eder.

**Kalıtım:**[`SVGOptions`](/slides/python-net/tr/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)

SVGOptions türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.export/svgoptions/__init__/#) | SVGOptions sınıfının yeni bir örneğini başlatır. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/tr/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | SVGOptions sınıfının yeni bir örneğini, bağlantı gömme denetleyici nesnesini belirterek başlatır. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`warning_callback`](/slides/python-net/tr/aspose.slides.export/svgoptions/warning_callback/) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar.<br/>            Okunur/Yazılır [`IWarningCallback`](/slides/python-net/tr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/tr/aspose.slides.export/svgoptions/progress_callback/) | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri çağırma nesnesini temsil eder.<br/>            Bakınız [`IProgressCallback`](/slides/python-net/tr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides.export/svgoptions/default_regular_font/) | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini alır veya ayarlar.<br/>            Okunur/Yazılır **str**. |
| [`gradient_style`](/slides/python-net/tr/aspose.slides.export/svgoptions/gradient_style/) | Gradyanın görsel stilini alır veya ayarlar.<br/>            Okunur/Yazılır [`GradientStyle`](/slides/python-net/tr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/tr/aspose.slides.export/svgoptions/skip_java_script_links/) | Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlanmayacağını belirtir.<br/>            Okunur/Yazılır **bool**. Varsayılan değer **false**. |
| [`ink_options`](/slides/python-net/tr/aspose.slides.export/svgoptions/ink_options/) | Dışa aktarılan belgede Mürekkep nesnelerinin görünümünü kontrol eden seçenekleri sağlar.<br/>            Yalnızca okunur [`IInkOptions`](/slides/python-net/tr/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/tr/aspose.slides.export/svgoptions/use_frame_size/) | Metin çerçevesinin bir renderleme alanına dahil edilip edilmeyeceğini belirler.<br/>            Okunur/Yazılır **bool**.<br/>            Varsayılan değer false. |
| [`use_frame_rotation`](/slides/python-net/tr/aspose.slides.export/svgoptions/use_frame_rotation/) | Renderleme sırasında şeklin belirtilen döndürülmesinin yapılıp yapılmayacağını belirler.<br/>            Okunur/Yazılır **bool**.<br/>            Varsayılan değer true. |
| [`vectorize_text`](/slides/python-net/tr/aspose.slides.export/svgoptions/vectorize_text/) | Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler.<br/>            Okunur/Yazılır **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/tr/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Metadosya rasterleştirmesi için alt çözünürlük sınırını alır veya ayarlar.<br/>            Okunur/Yazılır **int**. |
| [`disable_3d_text`](/slides/python-net/tr/aspose.slides.export/svgoptions/disable_3d_text/) | SVG içinde 3D metnin devre dışı bırakılıp bırakılmayacağını belirler.<br/>            Okunur/Yazılır **bool**. |
| [`disable_gradient_split`](/slides/python-net/tr/aspose.slides.export/svgoptions/disable_gradient_split/) | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır.<br/>            Okunur/Yazılır **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/tr/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1, işaretçiler için girintileri tanımlama yeteneğine sahip değildir.<br/>            Aspose.Slides SVG yazma motoru bu sorun için bir geçici çözüm sağlar:<br/>            oku ile satır sonunu kırpar, böylece satır işaretçilerin üzerine binmez.<br/>            Bu seçenek bu davranışı kapatır.<br/>            Okunur/Yazılır **bool**. |
| [`default`](/slides/python-net/tr/aspose.slides.export/svgoptions/default/) | Varsayılan ayarları döndürür.<br/>            Yalnızca okunur [`SVGOptions`](/slides/python-net/tr/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/tr/aspose.slides.export/svgoptions/simple/) | En basit ve en küçük SVG dosyası üretimi için ayarları döndürür.<br/>            Yalnızca okunur [`SVGOptions`](/slides/python-net/tr/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/tr/aspose.slides.export/svgoptions/wysiwyg/) | En doğru SVG dosyası üretimi için ayarları döndürür.<br/>            Yalnızca okunur [`SVGOptions`](/slides/python-net/tr/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/tr/aspose.slides.export/svgoptions/jpeg_quality/) | JPEG kodlama kalitesini belirler.<br/>            Okunur/Yazılır **int**. |
| [`shape_formatting_controller`](/slides/python-net/tr/aspose.slides.export/svgoptions/shape_formatting_controller/) | Kullanıcının şekil dönüşümünü kontrol etmesine izin veren bir geri çağırma arayüzünü alır ve ayarlar.<br/>            Okunur/Yazılır [`ISvgShapeFormattingController`](/slides/python-net/tr/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/tr/aspose.slides.export/svgoptions/pictures_compression/) | Resim sıkıştırma seviyesini temsil eder |
| [`delete_pictures_cropped_areas`](/slides/python-net/tr/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Kırpılan parçaların belgenin bir parçası olarak kalıp kalmayacağını gösteren bir boolean bayrağı. True ise kırpılan <br/>            parçalar kaldırılacak, false ise belgede seri hale getirilecek (bu daha büyük bir dosyaya yol açabilir). |
| [`external_fonts_handling`](/slides/python-net/tr/aspose.slides.export/svgoptions/external_fonts_handling/) | Dışarıdan yüklenen yazı tiplerinin işlenme şeklini belirler.<br/>            Okunur/Yazılır [`SvgExternalFontsHandling`](/slides/python-net/tr/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/tr/aspose.slides.export/svgoptions/disable_font_ligatures/) | Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar.<br/>            `true` olarak ayarlandığında, render edilen çıktıda ligatürler devre dışı bırakılır. Varsayılan olarak bu özellik `false` olarak ayarlanmıştır. |

### Ayrıca Bakınız
* sınıf [`SaveOptions`](/slides/python-net/tr/aspose.slides.export/saveoptions)
* sınıf [`SVGOptions`](/slides/python-net/tr/aspose.slides.export/svgoptions)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)