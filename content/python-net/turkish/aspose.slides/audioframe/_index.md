---
title: AudioFrame class
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/audioframe/
---
## AudioFrame sınıfı

Bir slayttaki ses klibini temsil eder.

**Inheritance:**[`AudioFrame`](/slides/python-net/tr/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

The AudioFrame type exposes the following members:

## Özellikler

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/audioframe/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/audioframe/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/audioframe/custom_data/) | Şeklin özel verilerini döndürür.<br/>            Salt okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/audioframe/raw_frame/) | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/audioframe/frame/) | Şekil çerçevesinin özelliklerini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/audioframe/line_format/) | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: Çizgi özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/audioframe/three_d_format/) | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3D özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/audioframe/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: Efekt özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/audioframe/fill_format/) | Bir şeklin doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: Doldurma özellikleri olmayan belirli şekil tipleri için None döndürebilir.<br/>            Salt okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/audioframe/hyperlink_click/) | Fare tıklaması için tanımlı köprüyi döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/audioframe/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlı köprüyi döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/audioframe/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Salt okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/audioframe/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/audioframe/z_order_position/) | Bir şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/audioframe/connection_site_count/) | Şeklin bağlantı noktası sayısını döndürür.<br/>            Salt okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/audioframe/rotation/) | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar.<br/>            Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir.<br/>            Okunur/yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/audioframe/x/) | Şeklin sol üst köşesinin x koordinatını (puan cinsinden) alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/audioframe/y/) | Şeklin sol üst köşesinin y koordinatını (puan cinsinden) alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/audioframe/width/) | Şeklin genişliğini (puan cinsinden) alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/audioframe/height/) | Şeklin yüksekliğini (puan cinsinden) alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/audioframe/black_white_mode/) | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir.<br/>            Okunur/yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/audioframe/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunum kapsamında iç bir tanımlayıcı döndürür.<br/>            Bu değer kullanıcı tarafından veya programlı olarak yeniden atanabildiği için<br/>            kalıcı benzersiz bir anahtar olarak ele alınmamalıdır.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/audioframe/office_interop_shape_id/) | Şeklin ömrü boyunca sabit kalan ve slayt kapsamlı benzersiz bir tanımlayıcı döndürür; bu sayede PowerPoint veya interop kodu, belgede herhangi bir yerden şekle güvenilir şekilde başvurabilir.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/audioframe/alternative_text/) | Bir şekille ilişkili alternatif metni döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/audioframe/alternative_text_title/) | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/audioframe/name/) | Bir şeklin adını döndürür veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş string değeri kullanın.<br/>            Okunur/yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/audioframe/is_decorative/) | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar<br/>            Okunur/yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/audioframe/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt okunur [`IPictureFrameLock`](/slides/python-net/tr/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/audioframe/is_grouped/) | Şeklin grup içinde olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/audioframe/parent_group/) | Şekil grup içindeyse ana GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/audioframe/slide/) | Bir şeklin ana slaydını döndürür.<br/>            Salt okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/audioframe/presentation/) | Bir slaydın ana sunumunu döndürür.<br/>            Salt okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/tr/aspose.slides/audioframe/shape_style/) | Şeklin stil nesnesini döndürür.<br/>            Salt okunur [`IShapeStyle`](/slides/python-net/tr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/tr/aspose.slides/audioframe/shape_type/) | PictureFrame için AutoShape tipini döndürür veya ayarlar.<br/>            [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) kümesinin tüm öğeleri izinlidir, <br/>            ancak tüm çizgi türleri hariçtir:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Okunur/yazılabilir [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/tr/aspose.slides/audioframe/adjustments/) | Şeklin ayar değerlerinin bir koleksiyonunu döndürür.<br/>            Salt okunur [`IAdjustValueCollection`](/slides/python-net/tr/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/tr/aspose.slides/audioframe/picture_frame_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt okunur [`IPictureFrameLock`](/slides/python-net/tr/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/tr/aspose.slides/audioframe/picture_format/) | Bir resim çerçevesi için PictureFillFormat nesnesini döndürür.<br/>            Salt okunur [`IPictureFillFormat`](/slides/python-net/tr/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/tr/aspose.slides/audioframe/relative_scale_height/) | Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0 %100'e karşılık gelir.<br/>            Okunur/yazılabilir **float**. |
| [`relative_scale_width`](/slides/python-net/tr/aspose.slides/audioframe/relative_scale_width/) | Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0 %100'e karşılık gelir.<br/>            Okunur/yazılabilir **float**. |
| [`is_cameo`](/slides/python-net/tr/aspose.slides/audioframe/is_cameo/) | PictureFrame'in Cameo nesnesi olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`audio_cd_start_track`](/slides/python-net/tr/aspose.slides/audioframe/audio_cd_start_track/) | Başlangıç izleme indeksini döndürür veya ayarlar.<br/>            Okunur/yazılabilir **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/tr/aspose.slides/audioframe/audio_cd_start_track_time/) | Başlangıç izleme zamanını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **int**. |
| [`audio_cd_end_track`](/slides/python-net/tr/aspose.slides/audioframe/audio_cd_end_track/) | Son izleme indeksini döndürür veya ayarlar<br/>            Okunur/yazılabilir **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/tr/aspose.slides/audioframe/audio_cd_end_track_time/) | Son izleme zamanını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **int**. |
| [`volume`](/slides/python-net/tr/aspose.slides/audioframe/volume/) | Ses seviyesini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`AudioVolumeMode`](/slides/python-net/tr/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/tr/aspose.slides/audioframe/play_mode/) | Ses çalma modunu döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`AudioPlayModePreset`](/slides/python-net/tr/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/tr/aspose.slides/audioframe/hide_at_showing/) | Bir AudioFrame'in gizli olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`play_loop_mode`](/slides/python-net/tr/aspose.slides/audioframe/play_loop_mode/) | Sesin döngüde olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`play_across_slides`](/slides/python-net/tr/aspose.slides/audioframe/play_across_slides/) | Sesin slaytlar arasında çalıp çalmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`rewind_audio`](/slides/python-net/tr/aspose.slides/audioframe/rewind_audio/) | Sesin oynatıldıktan sonra otomatik olarak başa sarılıp sarılmayacağını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`embedded`](/slides/python-net/tr/aspose.slides/audioframe/embedded/) | Bir sesin sunuma gömülü olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`link_path_long`](/slides/python-net/tr/aspose.slides/audioframe/link_path_long/) | Bir AudioFrame ile bağlantılı ses dosyasının adını döndürür veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`embedded_audio`](/slides/python-net/tr/aspose.slides/audioframe/embedded_audio/) | Gömülü ses nesnesini döndürür veya ayarlar.<br/>            Okunur/yazılabilir [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/tr/aspose.slides/audioframe/fade_in_duration/) | Medyanın ilk geçiş (fade-in) süresini milisaniye cinsinden belirtir.<br/>            Okunur/yazılabilir **float**. |
| [`fade_out_duration`](/slides/python-net/tr/aspose.slides/audioframe/fade_out_duration/) | Medyanın bitiş geçişi (fade-out) süresini milisaniye cinsinden belirtir.<br/>            Okunur/yazılabilir **float**. |
| [`volume_value`](/slides/python-net/tr/aspose.slides/audioframe/volume_value/) | Ses seviyesini yüzde olarak döndürür veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`trim_from_start`](/slides/python-net/tr/aspose.slides/audioframe/trim_from_start/) | Oynatma sırasında medyanın başından silinecek süreyi milisaniye cinsinden belirtir.<br/>            Okunur/yazılabilir **float**. |
| [`trim_from_end`](/slides/python-net/tr/aspose.slides/audioframe/trim_from_end/) | Oynatma sırasında medyanın sonundan silinecek süreyi milisaniye cinsinden belirtir.<br/>            Okunur/yazılabilir **float**. |
| [`caption_tracks`](/slides/python-net/tr/aspose.slides/audioframe/caption_tracks/) | Audio frame ile ilgili kapalı altyazıların koleksiyonunu alır.<br/>            Bu özellik salt okunurdur ve tüm altyazı izlerini içeren bir [`ICaptionsCollection`](/slides/python-net/tr/aspose.slides/icaptionscollection) döndürür. |

## Yöntemler

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/audioframe/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/audioframe/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/audioframe/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (geçerli şeklin kalıtım aldığı düzen ve/veya ana slayttan gelen şekil).<br/>            Geçerli şekil kalıtım almadıysa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/audioframe/get_visual_bounds/#) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [`get_geometry_paths(self)`](/slides/python-net/tr/aspose.slides/audioframe/get_geometry_paths/#) | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relative'dir. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/tr/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) nesnesinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre relative olmalıdır.<br/>            Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/tr/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre relative olmalıdır.<br/>            Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`create_shape_elements(self)`](/slides/python-net/tr/aspose.slides/audioframe/create_shape_elements/#) | Şeklin öğelerinin bir dizisini oluşturur ve döndürür. |

### Ayrıca Bakınız
* sınıf [`AudioFrame`](/slides/python-net/tr/aspose.slides/audioframe)
* sınıf [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape)
* sınıf [`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)