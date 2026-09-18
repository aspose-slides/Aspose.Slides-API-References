---
title: Table class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/table/
---
## Table sınıfı

Bir slayttaki tabloyu temsil eder.

**Inheritance:**[`Table`](/slides/python-net/tr/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

Table tipi aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/table/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/table/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt-okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/table/custom_data/) | Şeklin özel verilerini döndürür.<br/>            Salt-okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/table/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/table/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/table/line_format/) | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: Çizgi özellikleri bulunmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/table/three_d_format/) | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özellikleri bulunmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/table/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: Efekt özellikleri bulunmayan bazı şekil türleri için None döndürebilir.<br/>            Salt-okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/table/fill_format/) | Tablo için doldurma biçimlendirmesini içeren bir TableFormat.FillFormat nesnesini döndürür.<br/>            Salt-okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/table/hyperlink_click/) | Fare tıklaması için tanımlanan hiperlinki döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/table/hyperlink_mouse_over/) | Fare üzerindeyken tanımlanan hiperlinki döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/table/hyperlink_manager/) | Hiperlink yöneticisini döndürür.<br/>            Salt-okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/table/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/table/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt-okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/table/connection_site_count/) | Şeklin bağlantı noktası sayısını döndürür.<br/>            Salt-okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/table/rotation/) | Belirtilen şeklin z-ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde dönüş, negatif değer saat yönünün tersine dönüş anlamına gelir.<br/>            Okunur/Yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/table/x/) | Şeklin sol üst köşesinin x koordinatını (puan cinsinden) alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/table/y/) | Şeklin sol üst köşesinin y koordinatını (puan cinsinden) alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/table/width/) | Şeklin genişliğini (puan cinsinden) alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/table/height/) | Şeklin yüksekliğini (puan cinsinden) alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/table/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir.<br/>            Okunur/Yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/table/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, sunum kapsamlı iç bir tanımlayıcı döndürür.<br/>            Bu değer kullanıcı veya programatik olarak yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır.<br/>            Salt-okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/table/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan, slayt kapsamlı benzersiz bir tanımlayıcı döndürür ve PowerPoint veya interop kodunun şekle belge içinde her yerden güvenilir şekilde referans vermesini sağlar.<br/>            Salt-okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/table/alternative_text/) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/table/alternative_text_title/) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/table/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanın.<br/>            Okunur/Yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/table/is_decorative/) | ‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar<br/>            Okunur/Yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/table/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/table/is_grouped/) | Şeklin gruplanmış olup olmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/table/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt-okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/table/slide/) | Bir şeklin üst slaydını döndürür.<br/>            Salt-okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/table/presentation/) | Bir slaydın üst sunumunu döndürür.<br/>            Salt-okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/tr/aspose.slides/table/graphical_object_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IGraphicalObjectLock`](/slides/python-net/tr/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/tr/aspose.slides/table/rows/) | Satırların koleksiyonunu döndürür.<br/>            Salt-okunur [`IRowCollection`](/slides/python-net/tr/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/tr/aspose.slides/table/columns/) | Sütunların koleksiyonunu döndürür.<br/>            Salt-okunur [`IColumnCollection`](/slides/python-net/tr/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/tr/aspose.slides/table/table_format/) | Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür.<br/>            Salt-okunur [`ITableFormat`](/slides/python-net/tr/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/tr/aspose.slides/table/style_preset/) | Yerleşik tablo stilini alır veya ayarlar.<br/>            Okunur/Yazılabilir [`TableStylePreset`](/slides/python-net/tr/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/tr/aspose.slides/table/right_to_left/) | Tablonun sağdan sola okuma sırasına sahip olup olmadığını belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`first_row`](/slides/python-net/tr/aspose.slides/table/first_row/) | Tablonun ilk satırının özel bir biçimle çizilmesi gerekip gerekmediğini belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`first_col`](/slides/python-net/tr/aspose.slides/table/first_col/) | Tablonun ilk sütununun özel bir biçimle çizilmesi gerekip gerekmediğini belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`last_row`](/slides/python-net/tr/aspose.slides/table/last_row/) | Tablonun son satırının özel bir biçimle çizilmesi gerekip gerekmediğini belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`last_col`](/slides/python-net/tr/aspose.slides/table/last_col/) | Tablonun son sütununun özel bir biçimle çizilmesi gerekip gerekmediğini belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`horizontal_banding`](/slides/python-net/tr/aspose.slides/table/horizontal_banding/) | Çift satırların farklı bir biçimle çizilmesi gerekip gerekmediğini belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`vertical_banding`](/slides/python-net/tr/aspose.slides/table/vertical_banding/) | Çift sütunların farklı bir biçimle çizilmesi gerekip gerekmediğini belirler.<br/>            Okunur/Yazılabilir **bool**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/table/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resmi sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/table/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`set_text_format(self, source)`](/slides/python-net/tr/aspose.slides/table/set_text_format/#iportionformat) | Tanımlı bölüm biçim özelliklerini tüm tablo hücrelerinin bölümlerine ayarlar. |
| [`set_text_format(self, source)`](/slides/python-net/tr/aspose.slides/table/set_text_format/#iparagraphformat) | Tanımlı paragraf biçim özelliklerini tüm tablo hücrelerinin paragraflarına ayarlar. |
| [`set_text_format(self, source)`](/slides/python-net/tr/aspose.slides/table/set_text_format/#itextframeformat) | Tanımlı metin çerçevesi biçim özelliklerini tüm tablo hücrelerinin metin çerçevelerine ayarlar. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/table/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/table/add_placeholder/#iplaceholder) | Yer tutucu yoksa yenisini ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/table/get_base_placeholder/#) | Temel bir yer tutucu şekil döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil devralınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/table/get_visual_bounds/#) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/tr/aspose.slides/table/merge_cells/#icell-icell-bool) | Komşu hücreleri birleştirir. |

### Ayrıca Bakınız
* sınıf [`GraphicalObject`](/slides/python-net/tr/aspose.slides/graphicalobject)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* sınıf [`Table`](/slides/python-net/tr/aspose.slides/table)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)