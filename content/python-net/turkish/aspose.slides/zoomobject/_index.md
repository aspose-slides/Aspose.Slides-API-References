---
title: ZoomObject class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/zoomobject/
---
## ZoomObject sınıfı

Bir slaytta bir Zoom nesnesini temsil eder.

**Kalıtım:**[`ZoomObject`](/slides/python-net/tr/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

ZoomObject türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/zoomobject/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/zoomobject/placeholder/) | Şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/zoomobject/custom_data/) | Şeklin özel verilerini döndürür.<br/>            Salt okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/zoomobject/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okuma/yazma [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/zoomobject/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okuma/yazma [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/zoomobject/line_format/) | Şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: belirli çizgi özelliklerine sahip olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/zoomobject/three_d_format/) | Şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: belirli 3D özelliklerine sahip olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/zoomobject/effect_format/) | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özelliklerine sahip olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/zoomobject/fill_format/) | Şekil için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: doldurma özelliklerine sahip olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/zoomobject/hyperlink_click/) | Fare tıklaması için tanımlı köprüyü döndürür veya ayarlar.<br/>            Okuma/yazma [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/zoomobject/hyperlink_mouse_over/) | Fare üzerine geldiğinde tanımlı köprüyü döndürür veya ayarlar.<br/>            Okuma/yazma [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/zoomobject/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Salt okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/zoomobject/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okuma/yazma **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/zoomobject/z_order_position/) | Şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/zoomobject/connection_site_count/) | Şekildeki bağlantı noktalarının sayısını döndürür.<br/>            Salt okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/zoomobject/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde; negatif değer saat yönünün tersinde döndürmeyi gösterir.<br/>            Okuma/yazma **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/zoomobject/x/) | Şeklin sol üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/zoomobject/y/) | Şeklin sol üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/zoomobject/width/) | Şeklin genişliğini, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/zoomobject/height/) | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/zoomobject/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir.<br/>            Okuma/yazma [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/zoomobject/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere iç, sunum kapsamlı bir tanımlayıcı döndürür.<br/>            Bu değerin kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/zoomobject/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve belge içindeki herhangi bir yerden şekle güvenilir referans sağlayan slayt kapsamlı benzersiz bir tanımlayıcı döndürür.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/zoomobject/alternative_text/) | Şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/zoomobject/alternative_text_title/) | Şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/zoomobject/name/) | Şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanın.<br/>            Okuma/yazma **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/zoomobject/is_decorative/) | 'Mark as decorative' seçeneğini alır veya ayarlar<br/>            Okuma/yazma **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/zoomobject/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/zoomobject/is_grouped/) | Şeklin gruplandırılmış olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/zoomobject/parent_group/) | Şekil gruplandırılmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/zoomobject/slide/) | Şeklin üst slaydını döndürür.<br/>            Salt okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/zoomobject/presentation/) | Slaydın üst sunumunu döndürür.<br/>            Salt okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides/zoomobject/graphical_object_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/tr/aspose.slides/zoomobject/image_type/) | Zoom nesnesinin görüntü tipini alır veya ayarlar.<br/>            Okuma/yazma [`ZoomImageType`](/slides/python-net/tr/aspose.slides/zoomimagetype).<br/>            Varsayılan değer: Preview |
| [`return_to_parent`](/slides/python-net/tr/aspose.slides/zoomobject/return_to_parent/) | Slayt gösterisinde gezinme davranışını alır veya ayarlar.<br/>            Okuma/yazma **bool**.<br/>            Varsayılan değer: false |
| [`show_background`](/slides/python-net/tr/aspose.slides/zoomobject/show_background/) | Zoom'un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar.<br/>            Okuma/yazma **bool**.<br/>            Varsayılan değer: true |
| [`zoom_image`](/slides/python-net/tr/aspose.slides/zoomobject/zoom_image/) | Zoom nesnesi için görüntüyü alır veya ayarlar.<br/>            Okuma/yazma [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/tr/aspose.slides/zoomobject/transition_duration/) | Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar.<br/>            Okuma/yazma **float**.<br/>            Varsayılan değer: 1.0f |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/zoomobject/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/zoomobject/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/zoomobject/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin kalıtıldığı düzen ve/veya ana slayttan şekil).<br/>            Geçerli şekil kalıtılmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/zoomobject/get_visual_bounds/#) | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |

### Ayrıca Bakınız
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* sınıf [`ZoomObject`](/slides/python-net/tr/aspose.slides/zoomobject)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)