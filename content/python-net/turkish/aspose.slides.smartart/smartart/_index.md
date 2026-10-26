---
title: SmartArt class
second_title: Aspose.Slides for Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.smartart/smartart/
---
## SmartArt sınıfı

Bir SmartArt diyagramını temsil eder

**Kalıtım:**[`SmartArt`](/slides/python-net/tr/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

SmartArt türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides.smartart/smartart/is_text_holder/) | Belirler şeklin TextHolder_PPT olup olmadığını.<br/>            Yalnızca okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides.smartart/smartart/placeholder/) | Şekil için yer tutucusunu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Yalnızca okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides.smartart/smartart/custom_data/) | Şeklin özel verisini döndürür.<br/>            Yalnızca okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides.smartart/smartart/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides.smartart/smartart/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides.smartart/smartart/line_format/) | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: çizgi özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Yalnızca okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides.smartart/smartart/three_d_format/) | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Yalnızca okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides.smartart/smartart/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Yalnızca okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides.smartart/smartart/fill_format/) | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: dolgu özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Yalnızca okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides.smartart/smartart/hyperlink_click/) | Fare tıklaması için tanımlı köprüyi döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | Fare üzerindeyken tanımlı köprüyi döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides.smartart/smartart/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Yalnızca okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides.smartart/smartart/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides.smartart/smartart/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Yalnızca okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides.smartart/smartart/connection_site_count/) | Şeklin bağlantı noktalarının sayısını döndürür.<br/>            Yalnızca okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides.smartart/smartart/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde dönüşü; negatif değer saat yönünün tersinde dönüşü gösterir.<br/>            Okunur/yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides.smartart/smartart/x/) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides.smartart/smartart/y/) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides.smartart/smartart/width/) | Şeklin genişliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides.smartart/smartart/height/) | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides.smartart/smartart/black_white_mode/) | Özelik, bir şeklin siyah-beyaz görüntü modunda nasıl işleneceğini belirtir.<br/>            Okunur/yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides.smartart/smartart/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere sunum kapsamlı iç bir tanımlayıcı döndürür.<br/>            Bu değer kullanıcı tarafından veya programatik olarak yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır.<br/>            Yalnızca okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides.smartart/smartart/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belgede herhangi bir yerden güvenilir bir şekilde başvurmasını sağlayan slayt kapsamlı benzersiz tanımlayıcı döndürür.<br/>            Yalnızca okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides.smartart/smartart/alternative_text/) | Şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides.smartart/smartart/alternative_text_title/) | Şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides.smartart/smartart/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanınız.<br/>            Okunur/yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides.smartart/smartart/is_decorative/) | ‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar<br/>            Okunur/yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides.smartart/smartart/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnızca okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides.smartart/smartart/is_grouped/) | Şeklin gruplanmış olup olmadığını belirler.<br/>            Yalnızca okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides.smartart/smartart/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Yalnızca okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides.smartart/smartart/slide/) | Bir şeklin üst slaytını döndürür.<br/>            Yalnızca okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides.smartart/smartart/presentation/) | Bir slaydın üst sunumunu döndürür.<br/>            Yalnızca okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides.smartart/smartart/graphical_object_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnızca okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/tr/aspose.slides.smartart/smartart/all_nodes/) | SmartArt nesnesindeki tüm düğümlerin koleksiyonlarını döndürür.<br/>            Yalnızca okunur [`ISmartArtNodeCollection`](/slides/python-net/tr/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/tr/aspose.slides.smartart/smartart/nodes/) | SmartArt nesnesindeki kök düğümlerin koleksiyonlarını döndürür.<br/>            Yalnızca okunur [`ISmartArtNodeCollection`](/slides/python-net/tr/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/tr/aspose.slides.smartart/smartart/layout/) | SmartArt nesnesinin düzenini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`SmartArtLayoutType`](/slides/python-net/tr/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/tr/aspose.slides.smartart/smartart/quick_style/) | SmartArt nesnesinin hızlı stilini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`SmartArtQuickStyleType`](/slides/python-net/tr/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/tr/aspose.slides.smartart/smartart/color_style/) | SmartArt nesnesinin renk stilini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`SmartArtColorType`](/slides/python-net/tr/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/tr/aspose.slides.smartart/smartart/is_reversed/) | SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL durumunu, diyagram ters çevirmeyi destekliyorsa döndürür veya ayarlar.<br/>            Okunur/yazılabilir **bool**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides.smartart/smartart/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resmi sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides.smartart/smartart/remove_placeholder/#) | Bu şeklin yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen bir tane olarak ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides.smartart/smartart/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil miras alınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides.smartart/smartart/get_visual_bounds/#) | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |

### Ayrıca Bakınız
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* sınıf [`SmartArt`](/slides/python-net/tr/aspose.slides.smartart/smartart)
* modül [`aspose.slides.smartart`](/slides/python-net/tr/aspose.slides.smartart)
* kütüphane [`Aspose.Slides`](/slides/python-net)