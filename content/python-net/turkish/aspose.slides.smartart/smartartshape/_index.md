---
title: SmartArtShape class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.smartart/smartartshape/
---
## SmartArtShape sınıfı

SmartArt şeklini temsil eder

**Inheritance:**[`SmartArtShape`](/slides/python-net/tr/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

SmartArtShape türü aşağıdaki üyeleri ortaya çıkar.

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/custom_data/) | Şeklin özel verilerini döndürür.<br/>            Salt okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılır [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılır [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/line_format/) | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: Çizgi özelliklerine sahip olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/three_d_format/) | Bir şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özelliklere sahip olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: Efekt özelliklerine sahip olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/fill_format/) | Bir şekil için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: Doldurma özelliklerine sahip olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okunur/yazılır [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okunur/yazılır [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Salt okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/yazılır **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/connection_site_count/) | Şekildeki bağlantı noktalarının sayısını döndürür.<br/>            Salt okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde dönüş, negatif değer saat yönünün tersinde dönüş gösterir.<br/>            Okunur/yazılır **float**. |
| [`x`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/x/) | Şeklin sol üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`y`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/y/) | Şeklin sol üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`width`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/width/) | Şeklin genişliğini, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`height`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/height/) | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/black_white_mode/) | Bu özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir.<br/>            Okunur/yazılır [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcıyı döndürür.<br/>            Bu değer kullanıcının veya programın yeniden atayabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan, slayt kapsamında benzersiz bir tanımlayıcı döndürür ve PowerPoint ya da interop kodunun şekli belgede herhangi bir yerden güvenilir şekilde referans almasını sağlar.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/alternative_text/) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okunur/yazılır **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/alternative_text_title/) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/yazılır **str**. |
| [`name`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanın.<br/>            Okunur/yazılır **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/is_decorative/) | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar<br/>            Okunur/yazılır **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt okunur [`IBaseShapeLock`](/slides/python-net/tr/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/is_grouped/) | Şeklin gruplandırılıp gruplandırılmadığını belirler.<br/>            Salt okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/parent_group/) | Şekil gruplandırılmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/slide/) | Bir şeklin üst slaytını döndürür.<br/>            Salt okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/presentation/) | Bir slaytın üst sunumunu döndürür.<br/>            Salt okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/shape_style/) | Şeklin stil nesnesini döndürür.<br/>            Salt okunur [`IShapeStyle`](/slides/python-net/tr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/shape_type/) | Geometri ön ayar tipini döndürür veya ayarlar.<br/>            Not: Değer değiştiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır.<br/>            Okunur/yazılır [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/adjustments/) | Şeklin ayar değerlerinin koleksiyonunu döndürür.<br/>            Salt okunur [`IAdjustValueCollection`](/slides/python-net/tr/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/text_frame/) | SmartArt şeklinin metnini döndürür.<br/>            Salt okunur [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı yerleşim ve/veya ana slayttan şekil). Geçerli şekil devralınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır. |
| [`get_geometry_paths(self)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | Geometri şeklinin yol kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relatifir. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır. Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır. Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`create_shape_elements(self)`](/slides/python-net/tr/aspose.slides.smartart/smartartshape/create_shape_elements/#) | Şeklin öğelerinin dizisini oluşturur ve döndürür. |

### Ayrıca Bakınız
* sınıf [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* sınıf [`SmartArtShape`](/slides/python-net/tr/aspose.slides.smartart/smartartshape)
* modül [`aspose.slides.smartart`](/slides/python-net/tr/aspose.slides.smartart)
* kütüphane [`Aspose.Slides`](/slides/python-net)