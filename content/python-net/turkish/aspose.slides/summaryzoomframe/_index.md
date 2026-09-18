---
title: SummaryZoomFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame sınıfı

Bir slaytta Summary Zoom nesnesini temsil eder.

**Kalıtım:**[`SummaryZoomFrame`](/slides/python-net/tr/aspose.slides/summaryzoomframe) → [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

SummaryZoomFrame türü aşağıdaki üyeleri gösterir:

## Özellikler

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/summaryzoomframe/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/summaryzoomframe/placeholder/) | Şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt-okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/summaryzoomframe/custom_data/) | Şeklin özel verisini döndürür.<br/>            Salt-okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/summaryzoomframe/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılır [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/summaryzoomframe/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılır [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/summaryzoomframe/line_format/) | Şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: çizgi özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/summaryzoomframe/three_d_format/) | Şeklin 3d efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3d özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/summaryzoomframe/effect_format/) | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/summaryzoomframe/fill_format/) | Şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: dolgu özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/summaryzoomframe/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okunur/yazılır [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/summaryzoomframe/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür veya ayarlar.<br/>            Okunur/yazılır [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/summaryzoomframe/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Salt-okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/summaryzoomframe/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/yazılır **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/summaryzoomframe/z_order_position/) | Şeklin z-düzenindeki konumunu döndürür.<br/>            Shapes[0] z-düzeninin arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-düzeninin önündeki şekli döndürür.<br/>            Salt-okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/summaryzoomframe/connection_site_count/) | Şeklin üzerindeki bağlantı noktalarının sayısını döndürür.<br/>            Salt-okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/summaryzoomframe/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde dönüşü, negatif değer saat yönünün tersine dönüşü gösterir.<br/>            Okunur/yazılır **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/summaryzoomframe/x/) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/summaryzoomframe/y/) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/summaryzoomframe/width/) | Şeklin genişliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/summaryzoomframe/height/) | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılır **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/summaryzoomframe/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirler.<br/>            Okunur/yazılır [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/summaryzoomframe/unique_id/) | Dahili, sunum kapsamlı bir tanımlayıcıyı döndürür; eklentiler veya diğer kodlar tarafından kullanılmak içindir.<br/>            Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak değerlendirilmemelidir.<br/>            Salt-okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/summaryzoomframe/office_interop_shape_id/) | Slayt kapsamlı benzersiz bir tanımlayıcıyı döndürür; bu, şeklin ömrü boyunca sabit kalır ve PowerPoint veya interop kodunun şekli belgede herhangi bir yerden güvenilir şekilde referans almasını sağlar.<br/>            Salt-okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/summaryzoomframe/alternative_text/) | Şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okunur/yazılır **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/summaryzoomframe/alternative_text_title/) | Şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/yazılır **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/summaryzoomframe/name/) | Şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş dize değeri kullanın.<br/>            Okunur/yazılır **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/summaryzoomframe/is_decorative/) | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar<br/>            Okunur/yazılır **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/summaryzoomframe/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/summaryzoomframe/is_grouped/) | Şeklin gruplanmış olup olmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/summaryzoomframe/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt-okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/summaryzoomframe/slide/) | Şeklin üst slaytını döndürür.<br/>            Salt-okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/summaryzoomframe/presentation/) | Slaydın üst sunumunu döndürür.<br/>            Salt-okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides/summaryzoomframe/graphical_object_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`layout`](/slides/python-net/tr/aspose.slides/summaryzoomframe/layout/) | Çerçevedeki Summary Zoom Bölümlerinin düzenini alır.<br/>            Varsayılan değer GridLayout'tir. |
| [`summary_zoom_collection`](/slides/python-net/tr/aspose.slides/summaryzoomframe/summary_zoom_collection/) | Summary Zoom Frame nesnesi için [`ISummaryZoomSectionCollection`](/slides/python-net/tr/aspose.slides/isummaryzoomsectioncollection) alır. |

## Yöntemler

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/summaryzoomframe/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/summaryzoomframe/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/summaryzoomframe/remove_placeholder/#) | Bu şeklin yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/summaryzoomframe/add_placeholder/#iplaceholder) | Eğer yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirli birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/summaryzoomframe/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin kalıtım aldığı yerleşim ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil kalıtım almıyorsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/summaryzoomframe/get_visual_bounds/#) | Render edilmiş içeriğinden hesaplanan şeklin görsel sınırlarını alır. |

### Ayrıca Bakınız
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* sınıf [`SummaryZoomFrame`](/slides/python-net/tr/aspose.slides/summaryzoomframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)