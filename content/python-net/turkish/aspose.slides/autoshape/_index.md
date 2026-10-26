---
title: AutoShape class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/autoshape/
---
## AutoShape sınıfı

Represents an AutoShape.

**Inheritance:**[`AutoShape`](/slides/python-net/tr/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

The AutoShape type exposes the following members:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/autoshape/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Yalnızca okuma **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/autoshape/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Yalnızca okuma [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/autoshape/custom_data/) | Şeklin özel verilerini döndürür.<br/>            Yalnızca okuma [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/autoshape/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okuma/yazma [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/autoshape/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okuma/yazma [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/autoshape/line_format/) | Şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: Çizgi özelliği olmayan belirli şekil türleri için None döndürebilir.<br/>            Yalnızca okuma [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/autoshape/three_d_format/) | Şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özelliği olmayan belirli şekil türleri için None döndürebilir.<br/>            Yalnızca okuma [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/autoshape/effect_format/) | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: Efekt özelliği olmayan belirli şekil türleri için None döndürebilir.<br/>            Yalnızca okuma [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/autoshape/fill_format/) | Şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: Dolgu özelliği olmayan belirli şekil türleri için None döndürebilir.<br/>            Yalnızca okuma [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/autoshape/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okuma/yazma [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/autoshape/hyperlink_mouse_over/) | Fare üzerindeyken tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okuma/yazma [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/autoshape/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Yalnızca okuma [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/autoshape/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okuma/yazma **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/autoshape/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Yalnızca okuma **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/autoshape/connection_site_count/) | Şeklin üzerindeki bağlantı noktalarının sayısını döndürür.<br/>            Yalnızca okuma **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/autoshape/rotation/) | Belirtilen şeklin z-ekseni etrafında döndürülme derecesini döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir.<br/>            Okuma/yazma **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/autoshape/x/) | Şeklin sol üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/autoshape/y/) | Şeklin sol üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/autoshape/width/) | Şeklin genişliğini, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/autoshape/height/) | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/autoshape/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirler.<br/>            Okuma/yazma [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/autoshape/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere sunum kapsamlı iç bir tanımlayıcı döndürür.<br/>            Bu değer kullanıcı tarafından veya program yoluyla yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak değerlendirilmemelidir.<br/>            Yalnızca okuma **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/autoshape/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun belge içinde her yerden şekle güvenilir şekilde başvurmasını sağlayan slayt kapsamlı benzersiz bir tanımlayıcı döndürür.<br/>            Yalnızca okuma **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/autoshape/alternative_text/) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/autoshape/alternative_text_title/) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/autoshape/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanın.<br/>            Okuma/yazma **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/autoshape/is_decorative/) | Alır veya 'Mark as decorative' seçeneğini ayarlar<br/>            Okuma/yazma **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/autoshape/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnızca okuma [`IAutoShapeLock`](/slides/python-net/tr/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/autoshape/is_grouped/) | Şeklin gruplanıp gruplanmadığını belirler.<br/>            Yalnızca okuma **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/autoshape/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Yalnızca okuma [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/autoshape/slide/) | Bir şeklin üst slaydını döndürür.<br/>            Yalnızca okuma [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/autoshape/presentation/) | Bir slaydın üst sunumunu döndürür.<br/>            Yalnızca okuma [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/tr/aspose.slides/autoshape/shape_style/) | Şeklin stil nesnesini döndürür.<br/>            Yalnızca okuma [`IShapeStyle`](/slides/python-net/tr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/tr/aspose.slides/autoshape/shape_type/) | Geometri ön ayar tipini döndürür veya ayarlar.<br/>            Not: Değer değiştirildiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır.<br/>            Okuma/yazma [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/tr/aspose.slides/autoshape/adjustments/) | Şeklin ayar değerlerinin koleksiyonunu döndürür.<br/>            Yalnızca okuma [`IAdjustValueCollection`](/slides/python-net/tr/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/tr/aspose.slides/autoshape/auto_shape_lock/) | Otoshape'in kilitlerini döndürür.<br/>            Yalnızca okuma [`IAutoShapeLock`](/slides/python-net/tr/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/tr/aspose.slides/autoshape/text_frame/) | AutoShape için TextFrame nesnesini döndürür.<br/>            Yalnızca okuma [`ITextFrame`](/slides/python-net/tr/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/tr/aspose.slides/autoshape/use_background_fill/) | Bu otoshape'in stil veya dolgu formatı yerine slaytın arka plan doldurmasıyla doldurulup doldurulmayacağını belirler.<br/>            Okuma/yazma **bool**. |
| [`is_text_box`](/slides/python-net/tr/aspose.slides/autoshape/is_text_box/) | Şeklin bir metin kutusu olup olmadığını belirler. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/autoshape/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınır tipi varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/autoshape/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/autoshape/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan şekil).<br/>            Geçerli şekil devralınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/autoshape/get_visual_bounds/#) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [`get_geometry_paths(self)`](/slides/python-net/tr/aspose.slides/autoshape/get_geometry_paths/#) | Geometri şeklinin yolunun kopyasını döndürür. Koordinatlar şeklin sol üst köşesine görecelidir. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/tr/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göreceli olmalıdır.<br/>             Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/tr/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göreceli olmalıdır.<br/>             Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`create_shape_elements(self)`](/slides/python-net/tr/aspose.slides/autoshape/create_shape_elements/#) | Şeklin elemanlarının dizisini oluşturur ve döndürür. |
| [`add_text_frame(self, text)`](/slides/python-net/tr/aspose.slides/autoshape/add_text_frame/#str) | Şekle yeni bir TextFrame ekler.<br/>            Şeklin zaten TextFrame'i varsa sadece metnini değiştirir. |

### İlgili
* sınıf [`AutoShape`](/slides/python-net/tr/aspose.slides/autoshape)
* sınıf [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)