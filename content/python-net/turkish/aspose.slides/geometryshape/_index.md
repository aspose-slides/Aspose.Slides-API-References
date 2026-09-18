---
title: GeometryShape class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/geometryshape/
---
## GeometryShape sınıfı

Tüm geometrik şekiller için üst sınıfı temsil eder.

**Kalıtım:**[`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

GeometryShape türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/geometryshape/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/geometryshape/placeholder/) | Bir şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt-okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/geometryshape/custom_data/) | Şeklin özel verisini döndürür.<br/>            Salt-okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/geometryshape/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/geometryshape/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/geometryshape/line_format/) | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: çizgi özelliği bulunmayan bazı şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/geometryshape/three_d_format/) | Bir şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özelliği bulunmayan bazı şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/geometryshape/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özelliği bulunmayan bazı şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/geometryshape/fill_format/) | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: dolgu özelliği bulunmayan bazı şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/geometryshape/hyperlink_click/) | Fare tıklaması için tanımlanan bağlantıyı döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/geometryshape/hyperlink_mouse_over/) | Fare üzerine geldiğinde tanımlanan bağlantıyı döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/geometryshape/hyperlink_manager/) | Bağlantı yöneticisini döndürür.<br/>            Salt-okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/geometryshape/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/geometryshape/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt-okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/geometryshape/connection_site_count/) | Şekildeki bağlantı noktalarının sayısını döndürür.<br/>            Salt-okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/geometryshape/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir.<br/>            Okunur/yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/geometryshape/x/) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/geometryshape/y/) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/geometryshape/width/) | Şeklin genişliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/geometryshape/height/) | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/geometryshape/black_white_mode/) | Özet, bir şeklin siyah beyaz görüntüleme modunda nasıl render edileceğini belirtir.<br/>            Okunur/yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/geometryshape/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere sunum ölçeğinde iç bir tanımlayıcı döndürür.<br/>            Bu değer kullanıcı tarafından veya programatik olarak yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır.<br/>            Salt-okunur **int**.<br/>            Ayrıca bkz. [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/geometryshape/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun belge içinde herhangi bir yerden şekle güvenilir şekilde referans vermesini sağlayan slayt ölçeğinde benzersiz bir tanımlayıcı döndürür.<br/>            Salt-okunur **int**.<br/>            Ayrıca bkz. [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/geometryshape/alternative_text/) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/geometryshape/alternative_text_title/) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/geometryshape/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanın.<br/>            Okunur/yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/geometryshape/is_decorative/) | ‘Mark as decorative’ seçeneğini alır veya ayarlar<br/>            Okunur/yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/geometryshape/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IBaseShapeLock`](/slides/python-net/tr/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/geometryshape/is_grouped/) | Şeklin gruplanıp gruplanmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/geometryshape/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt-okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/geometryshape/slide/) | Bir şeklin üst slaytını döndürür.<br/>            Salt-okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/geometryshape/presentation/) | Bir slaytın üst sunumunu döndürür.<br/>            Salt-okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/tr/aspose.slides/geometryshape/shape_style/) | Şeklin stil nesnesini döndürür.<br/>            Salt-okunur [`IShapeStyle`](/slides/python-net/tr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type/) | Geometri ön ayar türünü döndürür veya ayarlar.<br/>            Not: değer değiştiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır.<br/>            Okunur/yazılabilir [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/tr/aspose.slides/geometryshape/adjustments/) | Şeklin ayar değerlerinin bir koleksiyonunu döndürür.<br/>            Salt-okunur [`IAdjustValueCollection`](/slides/python-net/tr/aspose.slides/iadjustvaluecollection). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/geometryshape/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/geometryshape/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/geometryshape/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (mevcut şeklin kalıtıldığı düzen ve/veya ana slayttan gelen şekil).<br/>            Mevcut şekil kalıtılmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/geometryshape/get_visual_bounds/#) | Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır. |
| [`get_geometry_paths(self)`](/slides/python-net/tr/aspose.slides/geometryshape/get_geometry_paths/#) | Geometri şeklinin yolunun kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relatiftir. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/tr/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre relatiftir.<br/>            Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/tr/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre relatiftir.<br/>            Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`create_shape_elements(self)`](/slides/python-net/tr/aspose.slides/geometryshape/create_shape_elements/#) | Şeklin elemanlarının dizisini oluşturur ve döndürür. |

### Ayrıca Bakınız
* sınıf [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)