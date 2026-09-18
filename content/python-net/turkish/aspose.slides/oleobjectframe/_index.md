---
title: OleObjectFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/oleobjectframe/
---
## OleObjectFrame sınıfı

Bir slaytta OLE nesnesini temsil eder.

**Inheritance:**[`OleObjectFrame`](/slides/python-net/tr/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

OleObjectFrame türü aşağıdaki üyeleri sunar:

## Özellikler

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/oleobjectframe/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/oleobjectframe/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt-okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/oleobjectframe/custom_data/) | Şeklin özel verisini döndürür.<br/>            Salt-okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/oleobjectframe/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/oleobjectframe/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/oleobjectframe/line_format/) | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: Çizgi özelliklerine sahip olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt-okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/oleobjectframe/three_d_format/) | Bir şeklin 3D etki özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özelliklerine sahip olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/oleobjectframe/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: Efekt özelliklerine sahip olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/oleobjectframe/fill_format/) | Bir şeklin doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: Doldurma özelliklerine sahip olmayan belirli şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/oleobjectframe/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/oleobjectframe/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Salt-okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/oleobjectframe/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/oleobjectframe/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt-okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/oleobjectframe/connection_site_count/) | Şeklin üzerindeki bağlantı noktalarının sayısını döndürür.<br/>            Salt-okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/oleobjectframe/rotation/) | Belirtilen şeklin z ekseni etrafında döndürülmüş derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde rotasyonu gösterir; negatif değer saat yönünün tersinde rotasyonu gösterir.<br/>            Okunur/yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/oleobjectframe/x/) | Şeklin sol-üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/oleobjectframe/y/) | Şeklin sol-üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/oleobjectframe/width/) | Şeklin genişliğini, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/oleobjectframe/height/) | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/oleobjectframe/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl renderlanacağını belirtir.<br/>            Okunur/yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/oleobjectframe/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, sunum kapsamlı dahili bir tanımlayıcıyı döndürür.<br/>            Bu değer kullanıcının veya programın tarafından yeniden atanabileceği için, kalıcı bir benzersiz anahtar olarak ele alınmamalıdır.<br/>            Salt-okunur **int**.<br/>            Ayrıca bkz. [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/oleobjectframe/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve slayt kapsamlı benzersiz bir tanımlayıcıyı döndürür; bu sayede PowerPoint veya interop kodları belge içindeki herhangi bir yerden şekle güvenilir şekilde referans verebilir.<br/>            Salt-okunur **int**.<br/>            Ayrıca bkz. [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/oleobjectframe/alternative_text/) | Bir şekile bağlı alternatif metni döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/oleobjectframe/alternative_text_title/) | Bir şekile bağlı alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/oleobjectframe/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş dize değeri kullanılabilir.<br/>            Okunur/yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/oleobjectframe/is_decorative/) | Alır veya ayarlar 'Dekoratif olarak işaretle' seçeneğini<br/>            Okunur/yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/oleobjectframe/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/oleobjectframe/is_grouped/) | Şeklin gruplanıp gruplanmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/oleobjectframe/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt-okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/oleobjectframe/slide/) | Bir şeklin üst slaytını döndürür.<br/>            Salt-okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/oleobjectframe/presentation/) | Bir slaytın üst sunumunu döndürür.<br/>            Salt-okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides/oleobjectframe/graphical_object_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/tr/aspose.slides/oleobjectframe/substitute_picture_format/) | OleObject görüntü doldurma özellikleri nesnesini döndürür.<br/>            Salt-okunur [`IPictureFillFormat`](/slides/python-net/tr/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/tr/aspose.slides/oleobjectframe/substitute_picture_title/) | OleObject simgesi için başlığı döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`object_name`](/slides/python-net/tr/aspose.slides/oleobjectframe/object_name/) | Bir nesnenin adını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`object_prog_id`](/slides/python-net/tr/aspose.slides/oleobjectframe/object_prog_id/) | Bir nesnenin ProgID'sini döndürür.<br/>            Salt-okunur **str**. |
| [`link_file_name`](/slides/python-net/tr/aspose.slides/oleobjectframe/link_file_name/) | Bağlı bir dosyanın tam yolunu döndürür. Kısa dosya adı kullanılacaktır.<br/>            Salt-okunur **str**. |
| [`link_path_long`](/slides/python-net/tr/aspose.slides/oleobjectframe/link_path_long/) | Bağlı bir dosyanın tam yolunu döndürür. Uzun dosya adı kullanılacaktır.<br/>            Okunur/yazılabilir **str**. |
| [`link_path_relative`](/slides/python-net/tr/aspose.slides/oleobjectframe/link_path_relative/) | Var ise bağlı bir dosyanın göreli yolunu döndürür, aksi takdirde boş dize döndürür.<br/>             Salt-okunur **str**. |
| [`embedded_file_label`](/slides/python-net/tr/aspose.slides/oleobjectframe/embedded_file_label/) | Gömülü OLE nesnesinin dosya adını döndürür |
| [`embedded_file_name`](/slides/python-net/tr/aspose.slides/oleobjectframe/embedded_file_name/) | Gömülü OLE nesnesinin yolunu döndürür |
| [`embedded_data`](/slides/python-net/tr/aspose.slides/oleobjectframe/embedded_data/) | OLE gömülü verileri hakkında bilgi alır veya ayarlar.<br/>            Okunur/yazılabilir [`IOleEmbeddedDataInfo`](/slides/python-net/tr/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/tr/aspose.slides/oleobjectframe/is_object_icon/) | Bir nesnenin simge olarak görünür olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`is_object_link`](/slides/python-net/tr/aspose.slides/oleobjectframe/is_object_link/) | Bir nesnenin harici bir dosyaya bağlanıp bağlanmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`update_automatic`](/slides/python-net/tr/aspose.slides/oleobjectframe/update_automatic/) | Bağlı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmeyeceğini belirler.<br/>            Okunur/yazılabilir **bool**. |

## Metotlar

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/oleobjectframe/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Şekil içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şekil içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/oleobjectframe/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilene ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/oleobjectframe/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil devralınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/oleobjectframe/get_visual_bounds/#) | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/tr/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | OLE gömülü verileri hakkında bilgi ayarlar.<br/>            <br/>            Bu yöntem, nesnenin özelliklerini yeni verileri yansıtacak şekilde değiştirir ve <br/>            IsObjectLink bayrağını false olarak ayarlar, OLE nesnesinin gömülü olduğunu gösterir. |

### Ayrıca Bakınız
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`OleObjectFrame`](/slides/python-net/tr/aspose.slides/oleobjectframe)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)