---
title: Ink class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.ink/ink/
---
## Ink sınıfı

Bir slaytta mürekkep nesnesini temsil eder.

**Kalıtım:**[`Ink`](/slides/python-net/tr/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

The Ink type exposes the following members:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides.ink/ink/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides.ink/ink/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Read-only [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides.ink/ink/custom_data/) | Şeklin özel verisini döndürür.<br/>            Read-only [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides.ink/ink/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Read/write [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides.ink/ink/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Read/write [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides.ink/ink/line_format/) | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: çizgi özelliklerine sahip olmayan bazı şekil türleri için None döndürebilir.<br/>            Read-only [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides.ink/ink/three_d_format/) | Şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özelliklerine sahip olmayan bazı şekil türleri için None döndürebilir.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides.ink/ink/effect_format/) | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özelliklerine sahip olmayan bazı şekil türleri için None döndürebilir.<br/>            Read-only [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides.ink/ink/fill_format/) | Bir şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: dolgu özelliklerine sahip olmayan bazı şekil türleri için None döndürebilir.<br/>            Read-only [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides.ink/ink/hyperlink_click/) | Fare tıklaması için tanımlanan hiperlinki döndürür veya ayarlar.<br/>            Read/write [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides.ink/ink/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlanan hiperlinki döndürür veya ayarlar.<br/>            Read/write [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides.ink/ink/hyperlink_manager/) | Hiperlink yöneticisini döndürür.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides.ink/ink/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides.ink/ink/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides.ink/ink/connection_site_count/) | Şekildeki bağlantı noktalarının sayısını döndürür.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides.ink/ink/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde dönüşü, negatif değer saat yönünün tersinde dönüşü gösterir.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/tr/aspose.slides.ink/ink/x/) | Şeklin sol üst köşesinin x koordinatını, nokta biriminde alır veya ayarlar.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/tr/aspose.slides.ink/ink/y/) | Şeklin sol üst köşesinin y koordinatını, nokta biriminde alır veya ayarlar.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/tr/aspose.slides.ink/ink/width/) | Şeklin genişliğini, nokta biriminde alır veya ayarlar.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/tr/aspose.slides.ink/ink/height/) | Şeklin yüksekliğini, nokta biriminde alır veya ayarlar.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides.ink/ink/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir.<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides.ink/ink/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, sunum kapsamlı bir iç tanımlayıcı döndürür.<br/>            Bu değer kullanıcı tarafından veya programlama yoluyla yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak kabul edilmemelidir.<br/>            Read-only **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides.ink/ink/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun belge içinde herhangi bir yerden şekle güvenilir şekilde referans vermesini sağlayan, slayt kapsamlı benzersiz bir tanımlayıcı döndürür.<br/>            Read-only **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides.ink/ink/alternative_text/) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides.ink/ink/alternative_text_title/) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/tr/aspose.slides.ink/ink/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanın.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides.ink/ink/is_decorative/) | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides.ink/ink/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides.ink/ink/is_grouped/) | Şeklin gruplanıp gruplanmadığını belirler.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides.ink/ink/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Read-only [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides.ink/ink/slide/) | Bir şeklin üst slaydını döndürür.<br/>            Read-only [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides.ink/ink/presentation/) | Bir slaydın üst sunumunu döndürür.<br/>            Read-only [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides.ink/ink/graphical_object_lock/) | Şeklin kilitlerini döndürür.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/tr/aspose.slides.ink/ink/traces/) | [`IInkTrace`](/slides/python-net/tr/aspose.slides.ink/iinktrace) IInk öğesinde bulunan tüm izleri alır.<br/>            Read-only. |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides.ink/ink/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides.ink/ink/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Eğer yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides.ink/ink/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil miras alınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides.ink/ink/get_visual_bounds/#) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/tr/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Mürekkep fırçaları için görsel efektleri taklit etmek amacıyla kullanılan özel görüntü koleksiyonuna bir görüntü kaydeder.<br/>            Bu görüntüler, belirli [`InkEffectType`](/slides/python-net/tr/aspose.slides.ink/inkeffecttype) değerleriyle mürekkep render edildiğinde kullanılır,<br/>            örneğin Galaxy, Rainbow vb. Kendi görüntülerinizi sağlayarak her mürekkep efektinin nasıl görüneceğini kontrol edebilirsiniz. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/tr/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Mürekkep fırçaları için görsel efektleri taklit etmek amacıyla kullanılan özel görüntü koleksiyonundan bir görüntünün kaydını siler<br/>            daha önce **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide** aracılığıyla kaydedilen görüntüler. |

### İlgili
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`Ink`](/slides/python-net/tr/aspose.slides.ink/ink)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides.ink`](/slides/python-net/tr/aspose.slides.ink)
* kütüphane [`Aspose.Slides`](/slides/python-net)