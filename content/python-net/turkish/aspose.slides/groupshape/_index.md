---
title: GroupShape class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/groupshape/
---
## GroupShape sınıfı

Bir slayttaki şekillerin grubunu temsil eder.

**Kalıtım:**[`GroupShape`](/slides/python-net/tr/aspose.slides/groupshape) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

GroupShape türü aşağıdaki üyeleri gösterir:

## Özellikler

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/groupshape/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Yalnızca okuma **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/groupshape/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Yalnızca okuma [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/groupshape/custom_data/) | Şeklin özel verilerini döndürür.<br/>            Yalnızca okuma [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/groupshape/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okuma/yazma [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/groupshape/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okuma/yazma [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/groupshape/line_format/) | Bir şekil için satır biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: GroupShape nesneleri satır özelliklerine sahip olmadığından None döndürür.<br/>            Yalnızca okuma [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/groupshape/three_d_format/) | Bir şekil için 3D etki özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özellikleri olmayan belirli şekil tipleri için None döndürülebilir.<br/>            Yalnızca okuma [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/groupshape/effect_format/) | Bir şekle uygulanan piksel etkilerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özellikleri olmayan belirli şekil tipleri için None döndürülebilir.<br/>            Yalnızca okuma [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/groupshape/fill_format/) | Bir şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: dolgu özellikleri olmayan belirli şekil tipleri için None döndürülebilir.<br/>            Yalnızca okuma [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/groupshape/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okuma/yazma [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/groupshape/hyperlink_mouse_over/) | Fare üzerindeyken tanımlanan köprüyi döndürür veya ayarlar.<br/>            Okuma/yazma [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/groupshape/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Yalnızca okuma [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/groupshape/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okuma/yazma **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/groupshape/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Yalnızca okuma **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/groupshape/connection_site_count/) | Şeklin üzerindeki bağlantı noktası sayısını döndürür.<br/>            Yalnızca okuma **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/groupshape/rotation/) | Belirtilen şeklin z-eksenine göre döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi belirtir.<br/>            Okuma/yazma **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/groupshape/x/) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden döndürür veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/groupshape/y/) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden döndürür veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/groupshape/width/) | Şeklin genişliğini, puan cinsinden döndürür veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/groupshape/height/) | Şeklin yüksekliğini, puan cinsinden döndürür veya ayarlar.<br/>            Okuma/yazma **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/groupshape/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir.<br/>            Okuma/yazma [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/groupshape/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış içsel, sunum kapsamlı bir tanımlayıcıyı döndürür.<br/>            Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır.<br/>            Yalnızca okuma **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/groupshape/office_interop_shape_id/) | Şeklin yaşamı boyunca sabit kalan bir slayt kapsamlı benzersiz tanımlayıcıyı döndürür ve PowerPoint ya da interop kodunun nesneyi belgenin herhangi bir yerinden güvenilir şekilde referans almasını sağlar.<br/>            Yalnızca okuma **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/groupshape/alternative_text/) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/groupshape/alternative_text_title/) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okuma/yazma **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/groupshape/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş dize kullanılabilir.<br/>            Okuma/yazma **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/groupshape/is_decorative/) | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar<br/>            Okuma/yazma **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/groupshape/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnızca okuma [`IGroupShapeLock`](/slides/python-net/tr/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/groupshape/is_grouped/) | Şeklin gruplanmış olup olmadığını belirler.<br/>            Yalnızca okuma **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/groupshape/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Yalnızca okuma [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/groupshape/slide/) | Bir şeklin üst slaydını döndürür.<br/>            Yalnızca okuma [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/groupshape/presentation/) | Bir slaydın üst sunumunu döndürür.<br/>            Yalnızca okuma [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/tr/aspose.slides/groupshape/group_shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Yalnızca okuma [`IGroupShapeLock`](/slides/python-net/tr/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/tr/aspose.slides/groupshape/shapes/) | Grubun içindeki şekil koleksiyonunu döndürür.<br/>            Yalnızca okuma [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection). |

## Metotlar

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/groupshape/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/groupshape/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/groupshape/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (mevcut şeklin devralındığı düzen ve/veya ana slayttan gelen şekil).<br/>            Mevcut şekil devralınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/groupshape/get_visual_bounds/#) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |

### Ayrıca Bakınız
* sınıf [`GroupShape`](/slides/python-net/tr/aspose.slides/groupshape)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)