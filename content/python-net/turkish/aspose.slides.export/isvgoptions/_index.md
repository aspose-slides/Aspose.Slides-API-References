---
title: ISVGOptions class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/isvgoptions/
---
## ISVGOptions sınıfı

SVG seçeneklerini temsil eder.

ISVGOptions türü aşağıdaki üyeleri sunar:

## Özellikler

| Property | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/tr/aspose.slides.export/isvgoptions/vectorize_text/) | Bir slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler.<br/>            Okunur/Yazılır **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/tr/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Metafile rasterleştirmesi için alt çözünürlük sınırını döndürür veya ayarlar.<br/>            Okunur/Yazılır **int**. |
| [`disable_3d_text`](/slides/python-net/tr/aspose.slides.export/isvgoptions/disable_3d_text/) | SVG'de 3B metnin devre dışı bırakılıp bırakılmayacağını belirler.<br/>            Okunur/Yazılır **bool**. |
| [`disable_gradient_split`](/slides/python-net/tr/aspose.slides.export/isvgoptions/disable_gradient_split/) | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır.<br/>            Okunur/Yazılır **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/tr/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1, işaretçiler için iç girintileri tanımlama yeteneğine sahip değildir.<br/>            Aspose.Slides SVG yazma motoru bu sorun için bir geçici çözüm sağlar:<br/>            okla satır sonunu kırpar, böylece satır işaretçilerin üzerine binmez.<br/>            Bu seçenek bu davranışı kapatır.<br/>            Okunur/Yazılır **bool**. |
| [`jpeg_quality`](/slides/python-net/tr/aspose.slides.export/isvgoptions/jpeg_quality/) | JPEG kodlama kalitesini belirler.<br/>            Okunur/Yazılır **int**. |
| [`shape_formatting_controller`](/slides/python-net/tr/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Şekil dönüşümünü kontrol etmesine olanak tanıyan bir geri çağırma arayüzünü döndürür ve ayarlar.<br/>            Okunur/Yazılır [`ISvgShapeFormattingController`](/slides/python-net/tr/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/tr/aspose.slides.export/isvgoptions/pictures_compression/) | Resim sıkıştırma seviyesini temsil eder<br/>            Okunur/Yazılır [`ISVGOptions.pictures_compression`](/slides/python-net/tr/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/tr/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Kırpılmış bölümlerin belgenin bir parçası olarak kalıp kalmayacağını gösteren bir boolean bayrağı. True ise kırpılmış <br/>            bölümler kaldırılır, false ise belgede serileştirilecek (bu daha büyük bir dosyaya yol açabilir)<br/>            Okunur/Yazılır **bool**. |
| [`use_frame_size`](/slides/python-net/tr/aspose.slides.export/isvgoptions/use_frame_size/) | Metin çerçevesinin renderleme alanına dahil edilip edilmeyeceğini belirler.<br/>            Okunur/Yazılır **bool**.<br/>            Varsayılan değer false'tur. |
| [`use_frame_rotation`](/slides/python-net/tr/aspose.slides.export/isvgoptions/use_frame_rotation/) | Renderleme sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler.<br/>            Okunur/Yazılır **bool**.<br/>            Varsayılan değer true'tur. |
| [`external_fonts_handling`](/slides/python-net/tr/aspose.slides.export/isvgoptions/external_fonts_handling/) | Harici yüklenen yazı tiplerinin işlenme şeklini belirler.<br/>            Okunur/Yazılır [`SvgExternalFontsHandling`](/slides/python-net/tr/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/tr/aspose.slides.export/isvgoptions/ink_options/) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar.<br/>            Salt Okunur [`IInkOptions`](/slides/python-net/tr/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/tr/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Metnin ligaturalar kullanılmadan renderlenip renderlenmediğini gösteren bir değeri alır veya ayarlar.<br/>            `true` olarak ayarlandığında, renderlenen çıktıda ligaturalar devre dışı bırakılacaktır. Varsayılan olarak bu özellik `false` değerindedir. |
| [`warning_callback`](/slides/python-net/tr/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/tr/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/tr/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/tr/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/tr/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Bakınız
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)