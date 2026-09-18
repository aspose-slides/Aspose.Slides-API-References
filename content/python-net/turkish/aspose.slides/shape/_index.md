---
title: Shape class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shape/
---
## Shape sınıfı

Bir slayttaki şekli temsil eder.

The Shape type exposes the following members:

## Özellikler

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/shape/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Yalnızca okuma **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/shape/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Yalnızca okuma [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/shape/custom_data/) | Şeklin özel verisini döndürür.<br/>            Yalnızca okuma [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/shape/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okuma/Yazma [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/shape/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okuma/Yazma [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/shape/line_format/) | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: çizgi özelliği olmayan belirli şekil tipleri için None dönebilir.<br/>            Yalnızca okuma [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/shape/three_d_format/) | Bir şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özelliği olmayan belirli şekil tipleri için None dönebilir.<br/>            Yalnızca okuma [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/shape/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özelliği olmayan belirli şekil tipleri için None dönebilir.<br/>            Yalnızca okuma [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/shape/fill_format/) | Bir şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: dolgu özelliği olmayan belirli şekil tipleri için None dönebilir.<br/>            Yalnızca okuma [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/shape/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyü döndürür veya ayarlar.<br/>            Okuma/Yazma [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/shape/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür veya ayarlar.<br/>            Okuma/Yazma [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/shape/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Yalnızca okuma [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/shape/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okuma/Yazma **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/shape/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Yalnızca okuma **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/shape/connection_site_count/) | Şeklin üzerindeki bağlantı noktası sayısını döndürür.<br/>            Yalnızca okuma **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/shape/rotation/) | Belirtilen şeklin z-ekseninde döndürüldüğü açı derecesini döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde dönüş, negatif değer saat yönünün tersine dönüş gösterir.<br/>            Okuma/Yazma **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/shape/x/) | Şeklin sol üst köşesinin x-koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okuma/Yazma **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/shape/y/) | Şeklin sol üst köşesinin y-koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okuma/Yazma **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/shape/width/) | Şeklin genişliğini, puan cinsinden alır veya ayarlar.<br/>            Okuma/Yazma **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/shape/height/) | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar.<br/>            Okuma/Yazma **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/shape/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl işleneceğini belirtir.<br/>            Okuma/Yazma [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere sunum kapsamlı iç bir tanımlayıcı döndürür.<br/>            Bu değer kullanıcı veya program tarafından yeniden atanabileceği için<br/>            sürekli bir benzersiz anahtar olarak ele alınmamalıdır.<br/>            Yalnızca okuma **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun belge içindeki herhangi bir yerden şekle güvenilir şekilde referans vermesini sağlayan slayt kapsamlı benzersiz bir tanımlayıcı döndürür.<br/>            Yalnızca okuma **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/shape/alternative_text/) | Bir şekil ile ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okuma/Yazma **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/shape/alternative_text_title/) | Bir şekil ile ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okuma/Yazma **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/shape/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş dize değeri kullanın.<br/>            Okuma/Yazma **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/shape/is_decorative/) | ‘Mark as decorative’ seçeneğini alır veya ayarlar<br/>            Okuma/Yazma **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/shape/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnızca okuma [`IBaseShapeLock`](/slides/python-net/tr/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/shape/is_grouped/) | Şeklin gruplanıp gruplanmadığını belirler.<br/>            Yalnızca okuma **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/shape/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Yalnızca okuma [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/shape/slide/) | Bir şeklin üst slaytını döndürür.<br/>            Yalnızca okuma [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/shape/presentation/) | Bir slaydın üst sunumunu döndürür.<br/>            Yalnızca okuma [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |

## Yöntemler

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/shape/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/shape/write_as_svg/#iorawiobase) | Shape içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/shape/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/shape/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/shape/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı yerleşim ve/veya ana slayttan alınan şekil).<br/>            Geçerli şekil miras alınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/shape/get_visual_bounds/#) | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |

### Ayrıca Bakınız
* module [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)