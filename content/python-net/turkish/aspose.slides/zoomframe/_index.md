---
title: ZoomFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/zoomframe/
---
## ZoomFrame sınıfı

Bir slaytta Slide Zoom nesnesini temsil eder.

**Kalıtım:**[`ZoomFrame`](/slides/python-net/tr/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/tr/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

ZoomFrame türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/zoomframe/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/zoomframe/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt-okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/zoomframe/custom_data/) | Şeklin özel verisini döndürür.<br/>            Salt-okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/zoomframe/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/zoomframe/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/zoomframe/line_format/) | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: çizgi özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/zoomframe/three_d_format/) | Bir şekil için 3d efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3d özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/zoomframe/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/zoomframe/fill_format/) | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: dolgu özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/zoomframe/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/zoomframe/hyperlink_mouse_over/) | Fare üzerindeyken tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/zoomframe/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Salt-okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/zoomframe/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/zoomframe/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt-okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/zoomframe/connection_site_count/) | Şekildeki bağlantı noktalarının sayısını döndürür.<br/>            Salt-okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/zoomframe/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde dönüşü, negatif değer saat yönünün tersinde dönüşü gösterir.<br/>            Okunur/Yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/zoomframe/x/) | Şeklin sol-üst köşesinin x koordinatını, nokta biriminde alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/zoomframe/y/) | Şeklin sol-üst köşesinin y koordinatını, nokta biriminde alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/zoomframe/width/) | Şeklin genişliğini, nokta biriminde alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/zoomframe/height/) | Şeklin yüksekliğini, nokta biriminde alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/zoomframe/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirler.<br/>            Okunur/Yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/zoomframe/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere sunum kapsamlı dahili bir tanımlayıcı döndürür.<br/>            Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır.<br/>            Salt-okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/zoomframe/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekli belgede herhangi bir yerden güvenilir şekilde referans almasını sağlayan slayt kapsamlı benzersiz bir tanımlayıcı döndürür.<br/>            Salt-okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/zoomframe/alternative_text/) | Bir şekille ilişkilendirilmiş alternatif metni döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/zoomframe/alternative_text_title/) | Bir şekille ilişkilendirilmiş alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/zoomframe/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanın.<br/>            Okunur/Yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/zoomframe/is_decorative/) | ‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar<br/>            Okunur/Yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/zoomframe/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/zoomframe/is_grouped/) | Şeklin gruplanıp gruplanmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/zoomframe/parent_group/) | Şekil gruplandırılmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt-okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/zoomframe/slide/) | Bir şeklin üst slaytını döndürür.<br/>            Salt-okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/zoomframe/presentation/) | Bir slaydın üst sunumunu döndürür.<br/>            Salt-okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides/zoomframe/graphical_object_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/tr/aspose.slides/zoomframe/image_type/) | Bir zoom nesnesinin görüntü tipini alır veya ayarlar.<br/>            Okunur/Yazılabilir [`ZoomImageType`](/slides/python-net/tr/aspose.slides/zoomimagetype).<br/>            Varsayılan değer: Preview |
| [`return_to_parent`](/slides/python-net/tr/aspose.slides/zoomframe/return_to_parent/) | Slayt gösterisinde gezinme davranışını alır veya ayarlar.<br/>            Okunur/Yazılabilir **bool**.<br/>            Varsayılan değer: false |
| [`show_background`](/slides/python-net/tr/aspose.slides/zoomframe/show_background/) | Zoom'un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar.<br/>            Okunur/Yazılabilir **bool**.<br/>            Varsayılan değer: true |
| [`zoom_image`](/slides/python-net/tr/aspose.slides/zoomframe/zoom_image/) | Zoom nesnesi için görüntüyü alır veya ayarlar.<br/>            Okunur/Yazılabilir [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/tr/aspose.slides/zoomframe/transition_duration/) | Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**.<br/>            Varsayılan değer: 1.0f |
| [`target_slide`](/slides/python-net/tr/aspose.slides/zoomframe/target_slide/) | Slide Zoom nesnesinin bağlandığı slayt nesnesini alır veya ayarlar.<br/>            Okunur/Yazılabilir [`ISlide`](/slides/python-net/tr/aspose.slides/islide). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/zoomframe/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resmi sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/zoomframe/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Eğer yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilene ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/zoomframe/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil miras alınmadıysa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/zoomframe/get_visual_bounds/#) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |

### Ayrıca Bakınız
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* sınıf [`ZoomFrame`](/slides/python-net/tr/aspose.slides/zoomframe)
* sınıf [`ZoomObject`](/slides/python-net/tr/aspose.slides/zoomobject)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)