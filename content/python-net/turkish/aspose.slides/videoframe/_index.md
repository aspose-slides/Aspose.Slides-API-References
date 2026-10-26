---
title: VideoFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/videoframe/
---
## VideoFrame sınıfı

Bir slayttaki video klibi temsil eder.

**Kalıtım:**[`VideoFrame`](/slides/python-net/tr/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

VideoFrame türü aşağıdaki üyeleri ortaya koyar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/videoframe/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/videoframe/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt-okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/videoframe/custom_data/) | Şeklin özel verisini döndürür.<br/>            Salt-okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/videoframe/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/videoframe/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/videoframe/line_format/) | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: Çizgi özelliği olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/videoframe/three_d_format/) | Bir şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özelliği olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/videoframe/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: Efekt özelliği olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/videoframe/fill_format/) | Bir şekil için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: Doldurma özelliği olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt-okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/videoframe/hyperlink_click/) | Fare tıklaması için tanımlı köprüyü döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/videoframe/hyperlink_mouse_over/) | Fare üzerine gelme için tanımlı köprüyü döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/videoframe/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Salt-okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/videoframe/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/videoframe/z_order_position/) | Bir şeklin z-dizgisindeki konumunu döndürür.<br/>            Shapes[0] z-dizgisinin arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-dizgisinin önündeki şekli döndürür.<br/>            Salt-okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/videoframe/connection_site_count/) | Şekildeki bağlanma noktalarının sayısını döndürür.<br/>            Salt-okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/videoframe/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde dönüşü, negatif değer saat yönünün tersinde dönüşü ifade eder.<br/>            Okunur/Yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/videoframe/x/) | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/videoframe/y/) | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/videoframe/width/) | Şeklin genişliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/videoframe/height/) | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar.<br/>            Okunur/Yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/videoframe/black_white_mode/) | Bir şeklin siyah-beyaz görüntü kipinde nasıl renderlanacağını belirten özellik.<br/>            Okunur/Yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/videoframe/unique_id/) | Bir sunum kapsamında dahili bir tanımlayıcı döndürür; eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmıştır.<br/>            Bu değer kullanıcı tarafından veya programatik olarak yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır.<br/>            Salt-okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/videoframe/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan, slayt kapsamında benzersiz bir tanımlayıcı döndürür ve PowerPoint ya da interop kodunun şekle belgede her yerden güvenilir şekilde başvurmasını sağlar.<br/>            Salt-okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/videoframe/alternative_text/) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/videoframe/alternative_text_title/) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/videoframe/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanın.<br/>            Okunur/Yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/videoframe/is_decorative/) | ‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar<br/>            Okunur/Yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/videoframe/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IPictureFrameLock`](/slides/python-net/tr/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/videoframe/is_grouped/) | Şeklin gruplanıp gruplanmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/videoframe/parent_group/) | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt-okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/videoframe/slide/) | Bir şeklin üst slaydını döndürür.<br/>            Salt-okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/videoframe/presentation/) | Bir slaydın üst sunumunu döndürür.<br/>            Salt-okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/tr/aspose.slides/videoframe/shape_style/) | Şeklin stil nesnesini döndürür.<br/>            Salt-okunur [`IShapeStyle`](/slides/python-net/tr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/tr/aspose.slides/videoframe/shape_type/) | Bir PictureFrame için AutoShape türünü döndürür veya ayarlar.<br/>            [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) kümesinin tüm öğeleri izinlidir, <br/>            ancak tüm çizgi türleri hariçtir:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Okunur/Yazılabilir [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/tr/aspose.slides/videoframe/adjustments/) | Şeklin ayar değerlerinin koleksiyonunu döndürür.<br/>            Salt-okunur [`IAdjustValueCollection`](/slides/python-net/tr/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/tr/aspose.slides/videoframe/picture_frame_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt-okunur [`IPictureFrameLock`](/slides/python-net/tr/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/tr/aspose.slides/videoframe/picture_format/) | Bir resim çerçevesi için PictureFillFormat nesnesini döndürür.<br/>            Salt-okunur [`IPictureFillFormat`](/slides/python-net/tr/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/tr/aspose.slides/videoframe/relative_scale_height/) | Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0, %100'e karşılık gelir.<br/>            Okunur/Yazılabilir **float**. |
| [`relative_scale_width`](/slides/python-net/tr/aspose.slides/videoframe/relative_scale_width/) | Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0, %100'e karşılık gelir.<br/>            Okunur/Yazılabilir **float**. |
| [`is_cameo`](/slides/python-net/tr/aspose.slides/videoframe/is_cameo/) | PictureFrame'in Cameo nesnesi olup olmadığını belirler.<br/>            Salt-okunur **bool**. |
| [`rewind_video`](/slides/python-net/tr/aspose.slides/videoframe/rewind_video/) | Bir video, oynatma tamamlandığında otomatik olarak başa sarmalayıp sarmalanmayacağını belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`play_loop_mode`](/slides/python-net/tr/aspose.slides/videoframe/play_loop_mode/) | Bir videonun döngüde olup olmadığını belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`hide_at_showing`](/slides/python-net/tr/aspose.slides/videoframe/hide_at_showing/) | VideoFrame'in gizli olup olmadığını belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`volume`](/slides/python-net/tr/aspose.slides/videoframe/volume/) | Ses seviyesini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`AudioVolumeMode`](/slides/python-net/tr/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/tr/aspose.slides/videoframe/play_mode/) | Video oynatma modunu döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`VideoPlayModePreset`](/slides/python-net/tr/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/tr/aspose.slides/videoframe/full_screen_mode/) | Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler.<br/>            Okunur/Yazılabilir **bool**. |
| [`link_path_long`](/slides/python-net/tr/aspose.slides/videoframe/link_path_long/) | Bir VideoFrame'e bağlı video dosyasının adını döndürür veya ayarlar.<br/>            Okunur/Yazılabilir **str**. |
| [`embedded_video`](/slides/python-net/tr/aspose.slides/videoframe/embedded_video/) | Gömülü video nesnesini döndürür veya ayarlar.<br/>            Okunur/Yazılabilir [`IVideo`](/slides/python-net/tr/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/tr/aspose.slides/videoframe/trim_from_start/) | Başlangıç kesmesi [ms] |
| [`trim_from_end`](/slides/python-net/tr/aspose.slides/videoframe/trim_from_end/) | Bitiş kesmesi [ms] |
| [`caption_tracks`](/slides/python-net/tr/aspose.slides/videoframe/caption_tracks/) | Video çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır.<br/>             Bu özellik salt-okunurdur ve tüm altyazı izlerini içeren bir [`ICaptionsCollection`](/slides/python-net/tr/aspose.slides/icaptionscollection) döndürür. |

## Metodlar

| Metod | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/videoframe/get_image/#) | Şekil küçük resmini döndürür.<br/>            Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınırları türü kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/videoframe/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/videoframe/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı yerleşim ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil devralınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/videoframe/get_visual_bounds/#) | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [`get_geometry_paths(self)`](/slides/python-net/tr/aspose.slides/videoframe/get_geometry_paths/#) | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relatifir. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/tr/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır.<br/>             Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/tr/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre relatif olmalıdır.<br/>             Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`create_shape_elements(self)`](/slides/python-net/tr/aspose.slides/videoframe/create_shape_elements/#) | Şeklin öğelerinin dizisini oluşturur ve döndürür. |

### İlgili Bakınız
* sınıf [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape)
* sınıf [`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* sınıf [`VideoFrame`](/slides/python-net/tr/aspose.slides/videoframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)