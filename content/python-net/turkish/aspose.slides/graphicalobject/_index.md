---
title: GraphicalObject class
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/graphicalobject/
---
## GraphicalObject sınıfı

Şekil nesnesini temsil eden soyut grafik nesnesi.

**Kalıtım:**[`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

GraphicalObject türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/graphicalobject/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Yalnız okunabilir **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/graphicalobject/placeholder/) | Şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Yalnız okunabilir [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/graphicalobject/custom_data/) | Şeklin özel verisini döndürür.<br/>            Yalnız okunabilir [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/graphicalobject/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/graphicalobject/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/graphicalobject/line_format/) | Şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: Çizgi özelliği olmayan bazı şekil türleri için None döndürebilir.<br/>            Yalnız okunabilir [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/graphicalobject/three_d_format/) | Şekil için 3d efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3d özelliği olmayan bazı şekil türleri için None döndürebilir.<br/>            Yalnız okunabilir [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/graphicalobject/effect_format/) | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: Efekt özelliği olmayan bazı şekil türleri için None döndürebilir.<br/>            Yalnız okunabilir [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/graphicalobject/fill_format/) | Şekil için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: Doldurma özelliği olmayan bazı şekil türleri için None döndürebilir.<br/>            Yalnız okunabilir [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/graphicalobject/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/graphicalobject/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/graphicalobject/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Yalnız okunabilir [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/graphicalobject/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunabilir/Yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/graphicalobject/z_order_position/) | Şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Yalnız okunabilir **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/graphicalobject/connection_site_count/) | Şeklin bağlantı noktası sayısını döndürür.<br/>            Yalnız okunabilir **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/graphicalobject/rotation/) | Belirtilen şeklin z ekseni etrafında döndürülme derecesini döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersinde döndürmeyi gösterir.<br/>            Okunabilir/Yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/graphicalobject/x/) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunabilir/Yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/graphicalobject/y/) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunabilir/Yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/graphicalobject/width/) | Şeklin genişliğini puan cinsinden alır veya ayarlar.<br/>            Okunabilir/Yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/graphicalobject/height/) | Şeklin yüksekliğini puan cinsinden alır veya ayarlar.<br/>            Okunabilir/Yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/graphicalobject/black_white_mode/) | Özellik, şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirler.<br/>            Okunabilir/Yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/graphicalobject/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunuma özgü dahili bir tanımlayıcı döndürür.<br/>            Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar gibi kullanılmamalıdır.<br/>            Yalnız okunabilir **int**.<br/>            Ayrıca bkz. [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/graphicalobject/office_interop_shape_id/) | Şekil ömrü boyunca sabit kalan, slayta özgü benzersiz bir tanımlayıcı döndürür; bu, PowerPoint veya interop kodunun belge içinde her yerden şekle güvenilir şekilde başvurmasını sağlar.<br/>            Yalnız okunabilir **int**.<br/>            Ayrıca bkz. [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/graphicalobject/alternative_text/) | Şekille ilişkilendirilmiş alternatif metni döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/graphicalobject/alternative_text_title/) | Şekille ilişkilendirilmiş alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunabilir/Yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/graphicalobject/name/) | Şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş dize değeri kullanın.<br/>            Okunabilir/Yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/graphicalobject/is_decorative/) | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar<br/>            Okunabilir/Yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/graphicalobject/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnız okunabilir [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/graphicalobject/is_grouped/) | Şeklin gruplandırılmış olup olmadığını belirler.<br/>            Yalnız okunabilir **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/graphicalobject/parent_group/) | Şekil gruplandırılmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Yalnız okunabilir [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/graphicalobject/slide/) | Şeklin üst slaytını döndürür.<br/>            Yalnız okunabilir [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/graphicalobject/presentation/) | Slaytın üst sunumunu döndürür.<br/>            Yalnız okunabilir [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides/graphicalobject/graphical_object_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnız okunabilir [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/graphicalobject/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınır türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/graphicalobject/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/graphicalobject/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (mevcut şeklin devralındığı düzen ve/veya üst slayttan gelen şekil).<br/>            Şekil devralınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/graphicalobject/get_visual_bounds/#) | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |


### İlgili
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)