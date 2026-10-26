---
title: PictureFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/pictureframe/
---
## PictureFrame sınıfı

İçinde bir resim bulunan çerçeveyi temsil eder.

**Kalıtım:**[`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

PictureFrame türü aşağıdaki üyeleri sunar:

## Özellikler

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/pictureframe/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/pictureframe/placeholder/) | Bir şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt-okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/pictureframe/custom_data/) | Şeklin özel verilerini döndürür.<br/>            Salt-okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/pictureframe/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/pictureframe/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/pictureframe/line_format/) | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: Çizgi özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/pictureframe/three_d_format/) | Şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/pictureframe/effect_format/) | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: Efekt özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/pictureframe/fill_format/) | Şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: Dolgu özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/pictureframe/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyü döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/pictureframe/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/pictureframe/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Salt-okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/pictureframe/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/pictureframe/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            and Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt-okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/pictureframe/connection_site_count/) | Şeklin bağlantı nokta sayısını döndürür.<br/>            Salt-okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/pictureframe/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif bir değer saat yönünde dönüşü; negatif bir değer saat yönünün tersine dönüşü gösterir.<br/>            Okunur/yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/pictureframe/x/) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/pictureframe/y/) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/pictureframe/width/) | Şeklin genişliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/pictureframe/height/) | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/pictureframe/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir..<br/>            Okunur/yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/pictureframe/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, içsel, sunum kapsamlı bir tanımlayıcı döndürür.<br/>            Bu değer kullanıcı tarafından veya programatik olarak yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır.<br/>            Salt-okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/pictureframe/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan, slayt kapsamlı benzersiz bir tanımlayıcı döndürür ve PowerPoint veya interop kodunun belge içindeki herhangi bir yerden şekle güvenilir şekilde başvurmasını sağlar.<br/>            Salt-okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/pictureframe/alternative_text/) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/pictureframe/alternative_text_title/) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/pictureframe/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanın.<br/>            Okunur/yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/pictureframe/is_decorative/) | Dekoratif olarak işaretle seçeneğini alır veya ayarlar.<br/>            Okunur/yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/pictureframe/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IPictureFrameLock`](/slides/python-net/tr/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/pictureframe/is_grouped/) | Şeklin gruplanıp gruplanmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/pictureframe/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt-okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/pictureframe/slide/) | Bir şeklin üst slaytını döndürür.<br/>            Salt-okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/pictureframe/presentation/) | Bir slaytın üst sunumunu döndürür.<br/>            Salt-okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/tr/aspose.slides/pictureframe/shape_style/) | Şeklin stil nesnesini döndürür.<br/>            Salt-okunur [`IShapeStyle`](/slides/python-net/tr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/tr/aspose.slides/pictureframe/shape_type/) | PictureFrame için AutoShape tipini döndürür veya ayarlar.<br/>            Set [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) içinde izin verilen tüm öğeler vardır, ancak tüm çizgi türleri dışarıdadır:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Okunur/yazılabilir [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/tr/aspose.slides/pictureframe/adjustments/) | Şeklin ayar değerlerinin bir koleksiyonunu döndürür.<br/>            Salt-okunur [`IAdjustValueCollection`](/slides/python-net/tr/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/tr/aspose.slides/pictureframe/picture_frame_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IPictureFrameLock`](/slides/python-net/tr/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/tr/aspose.slides/pictureframe/picture_format/) | Bir resim çerçevesi için PictureFillFormat nesnesini döndürür.<br/>            Salt-okunur [`IPictureFillFormat`](/slides/python-net/tr/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/tr/aspose.slides/pictureframe/relative_scale_height/) | Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0 %100'e karşılık gelir.<br/>            Okunur/yazılabilir **float**. |
| [`relative_scale_width`](/slides/python-net/tr/aspose.slides/pictureframe/relative_scale_width/) | Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0 %100'e karşılık gelir.<br/>            Okunur/yazılabilir **float**. |
| [`is_cameo`](/slides/python-net/tr/aspose.slides/pictureframe/is_cameo/) | PictureFrame'in Cameo nesnesi olup olmadığını belirler.<br/>            Salt-okunur **bool**. |

## Yöntemler

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/pictureframe/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/pictureframe/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen bir taneye ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/pictureframe/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin kalıtıldığı düzen ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil kalıtılmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/pictureframe/get_visual_bounds/#) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [`get_geometry_paths(self)`](/slides/python-net/tr/aspose.slides/pictureframe/get_geometry_paths/#) | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre görecelidir. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/tr/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır.<br/>             Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/tr/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır.<br/>             Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`create_shape_elements(self)`](/slides/python-net/tr/aspose.slides/pictureframe/create_shape_elements/#) | Şeklin elemanlarından bir dizi oluşturur ve döndürür. |

### Ayrıca Bakınız
* sınıf [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape)
* sınıf [`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)