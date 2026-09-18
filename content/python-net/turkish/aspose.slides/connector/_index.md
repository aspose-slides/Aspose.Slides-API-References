---
title: Connector class
second_title: Aspose.Slides için Python .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/connector/
---
## Connector sınıfı

Bir bağlayıcıyı temsil eder.

**Kalıtım:**[`Connector`](/slides/python-net/tr/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

Connector türü aşağıdaki üyeleri ortaya çıkar.

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/connector/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/connector/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/connector/custom_data/) | Şeklin özel verisini döndürür.<br/>            Salt okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/connector/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/connector/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/connector/line_format/) | Bir şekil için satır biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: satır özellikleri olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/connector/three_d_format/) | Bir şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özellikleri olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/connector/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özellikleri olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/connector/fill_format/) | Bir şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: dolgu özellikleri olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/connector/hyperlink_click/) | Fare tıklaması için tanımlanan bağlantıyı döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/connector/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlanan bağlantıyı döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/connector/hyperlink_manager/) | Bağlantı yöneticisini döndürür.<br/>            Salt okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/connector/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/connector/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/connector/connection_site_count/) | Şekildeki bağlantı noktası sayısını döndürür.<br/>            Salt okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/connector/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde rotasyonu gösterir; negatif değer<br/>            saat yönünün tersinde rotasyonu gösterir.<br/>            Okunur/yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/connector/x/) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/connector/y/) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/connector/width/) | Şeklin genişliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/connector/height/) | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/connector/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirler.<br/>            Okunur/yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/connector/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunum kapsamlı dahili bir tanımlayıcı döndürür.<br/>            Bu değer kullanıcı tarafından veya programlı olarak yeniden atanabileceği için,<br/>            kalıcı benzersiz bir anahtar olarak ele alınmamalıdır.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/connector/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan, slayt kapsamlı benzersiz bir tanımlayıcı döndürür ve<br/>            PowerPoint veya interop kodunun şekle belgenin herhangi bir yerinden güvenilir şekilde başvurmasını sağlar.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/connector/alternative_text/) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/connector/alternative_text_title/) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/connector/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş dize değeri kullanın.<br/>            Okunur/yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/connector/is_decorative/) | 'Mark as decorative' seçeneğini alır veya ayarlar<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/connector/shape_lock/) | Şeklin kilitlemelerini döndürür.<br/>            Salt okunur [`IConnectorLock`](/slides/python-net/tr/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/connector/is_grouped/) | Şeklin gruplandığını belirler.<br/>            Salt okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/connector/parent_group/) | Şekil gruplandırılmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/connector/slide/) | Bir şeklin üst slaytını döndürür.<br/>            Salt okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/connector/presentation/) | Bir slaytın üst sunumunu döndürür.<br/>            Salt okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/tr/aspose.slides/connector/shape_style/) | Şeklin stil nesnesini döndürür.<br/>            Salt okunur [`IShapeStyle`](/slides/python-net/tr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/tr/aspose.slides/connector/shape_type/) | AutoShape türünü döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/tr/aspose.slides/connector/adjustments/) | Şeklin ayar değerlerinin bir koleksiyonunu döndürür.<br/>            Salt okunur [`IAdjustValueCollection`](/slides/python-net/tr/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/tr/aspose.slides/connector/connector_lock/) | Bağlayıcının kilitlemelerini döndürür.<br/>            Salt okunur [`IConnectorLock`](/slides/python-net/tr/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/tr/aspose.slides/connector/start_shape_connected_to/) | Bağlayıcının başlangıcının bağlanacağı şekli döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/tr/aspose.slides/connector/end_shape_connected_to/) | Bağlayıcının sonunun bağlanacağı şekli döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/tr/aspose.slides/connector/start_shape_connection_site_index/) | Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar.<br/>            Okunur/yazılabilir **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/tr/aspose.slides/connector/end_shape_connection_site_index/) | Bitiş şekli için bağlantı noktasının dizinini döndürür veya ayarlar.<br/>            Okunur/yazılabilir **int**. |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/connector/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resmi sınırlama türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/connector/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/connector/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/connector/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirli bir tane olarak ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/connector/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan şekil).<br/>            Geçerli şekil miras almamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/connector/get_visual_bounds/#) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [`get_geometry_paths(self)`](/slides/python-net/tr/aspose.slides/connector/get_geometry_paths/#) | Geometri şeklinin yol kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relatiftir. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/tr/aspose.slides/connector/set_geometry_path/#igeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol<br/>             üst köşesine göre relatiftir.<br/>             Şeklin türünü ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/tr/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar şeklin sol<br/>             üst köşesine göre relatiftir.<br/>             Şeklin türünü ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`create_shape_elements(self)`](/slides/python-net/tr/aspose.slides/connector/create_shape_elements/#) | Şeklin öğelerinin bir dizisini oluşturur ve döndürür. |
| [`reroute(self)`](/slides/python-net/tr/aspose.slides/connector/reroute/#) | Bağlayıcıyı, bağladığı şekiller arasındaki mümkün olan en kısa yolu alacak şekilde yeniden yönlendirir. |

### Ayrıca Bakınız
* sınıf [`Connector`](/slides/python-net/tr/aspose.slides/connector)
* sınıf [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)