---
title: IShape class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishape/
---
## IShape sınıfı

Bir slayttaki şekli temsil eder.

IShape türü aşağıdaki üyeleri ortaya çıkar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/ishape/is_text_holder/) | Şeklin TextHolder olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/ishape/placeholder/) | Bir şekil için yer tutucuyu döndürür.<br/>            Salt okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/ishape/custom_data/) | Şeklin özel verilerini döndürür.<br/>            Salt okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/ishape/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılır [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/ishape/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılır [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/ishape/line_format/) | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Salt okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/ishape/three_d_format/) | Bir şeklin çizgi biçimlendirme özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Salt okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/ishape/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Salt okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/ishape/fill_format/) | Bir şeklin doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Salt okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/tr/aspose.slides/ishape/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/yazılır **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/ishape/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/ishape/connection_site_count/) | Şekildeki bağlantı noktalarının sayısını döndürür.<br/>            Salt okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/ishape/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif bir değer saat yönünde döndürmeyi; negatif değer saat yönünün tersinde döndürmeyi gösterir.<br/>            Okunur/yazılır **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/ishape/x/) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/ishape/y/) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/ishape/width/) | Şeklin genişliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/ishape/height/) | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/ishape/alternative_text/) | Bir şekille ilişkilendirilmiş alternatif metni döndürür veya ayarlar.<br/>            Okunur/yazılır **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/ishape/alternative_text_title/) | Bir şekille ilişkilendirilmiş alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/yazılır **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/ishape/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            Okunur/yazılır **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/ishape/is_decorative/) | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar<br/>            Okunur/yazılır **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/ishape/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt okunur [`IBaseShapeLock`](/slides/python-net/tr/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/ishape/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, sunuma özgü iç bir tanımlayıcıyı döndürür.<br/>            Bu değer kullanıcı tarafından veya programatik olarak yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`IShape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/ishape/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve slayta özgü benzersiz bir tanımlayıcıyı döndürür; bu sayede PowerPoint veya interop kodu, belgede herhangi bir yerden şekle güvenilir bir şekilde referans verebilir.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`IShape.unique_id`](/slides/python-net/tr/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/ishape/is_grouped/) | Şeklin gruplandırılmış olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/ishape/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir.<br/>            Okunur/yazılır [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/tr/aspose.slides/ishape/parent_group/) | Şekil gruplandırılmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/tr/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/ishape/hyperlink_manager/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/ishape/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/ishape/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/ishape/add_placeholder/#iplaceholder) | Eğer yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/ishape/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/ishape/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil miras alınmadıysa None döndürülür. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)