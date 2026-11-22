---
title: VideoFrame class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/videoframe/
---
## VideoFrame class

Bir slaytta bir video klibi temsil eder.

**Inheritance:**[`VideoFrame`](/slides/python-net/tr/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/tr/aspose.slides/shape)

VideoFrame türü aşağıdaki üyelere sahiptir:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_text_holder`](/slides/python-net/tr/aspose.slides/videoframe/is_text_holder/) | Şeklin TextHolder_PPT olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`placeholder`](/slides/python-net/tr/aspose.slides/videoframe/placeholder/) | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa None döndürür.<br/>            Salt okunur [`IPlaceholder`](/slides/python-net/tr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/tr/aspose.slides/videoframe/custom_data/) | Şeklin özel verilerini döndürür.<br/>            Salt okunur [`ICustomData`](/slides/python-net/tr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/tr/aspose.slides/videoframe/raw_frame/) | Ham şekil çerçevesinin özelliklerini alır veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/tr/aspose.slides/videoframe/frame/) | Şekil çerçevesinin özelliklerini alır veya ayarlar.<br/>            Okunur/yazılabilir [`IShapeFrame`](/slides/python-net/tr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/tr/aspose.slides/videoframe/line_format/) | Bir şekil için satır biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür.<br/>            Not: satır özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt okunur [`ILineFormat`](/slides/python-net/tr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/tr/aspose.slides/videoframe/three_d_format/) | Bir şekil için 3d efekt özelliklerini içeren ThreeDFormat nesnesini döndürür.<br/>            Not: 3d özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt okunur [`IThreeDFormat`](/slides/python-net/tr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/tr/aspose.slides/videoframe/effect_format/) | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür.<br/>            Not: efekt özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt okunur [`IEffectFormat`](/slides/python-net/tr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/tr/aspose.slides/videoframe/fill_format/) | Bir şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür.<br/>            Not: dolgu özellikleri olmayan bazı şekil türleri için None döndürebilir.<br/>            Salt okunur [`IFillFormat`](/slides/python-net/tr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/tr/aspose.slides/videoframe/hyperlink_click/) | Fare tıklaması için tanımlanan köprüyü alır veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/tr/aspose.slides/videoframe/hyperlink_mouse_over/) | Fare üzerine gelindiğinde tanımlanan köprüyü alır veya ayarlar.<br/>            Okunur/yazılabilir [`IHyperlink`](/slides/python-net/tr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/tr/aspose.slides/videoframe/hyperlink_manager/) | Köprü yöneticisini döndürür.<br/>            Salt okunur [`IHyperlinkManager`](/slides/python-net/tr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/tr/aspose.slides/videoframe/hidden/) | Şeklin gizli olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`z_order_position`](/slides/python-net/tr/aspose.slides/videoframe/z_order_position/) | Şeklin z-sırasındaki konumunu döndürür.<br/>            Shapes[0] z-sırasının arkasındaki şekli döndürür,<br/>            ve Shapes[Shapes.Count - 1] z-sırasının önündeki şekli döndürür.<br/>            Salt okunur **int**. |
| [`connection_site_count`](/slides/python-net/tr/aspose.slides/videoframe/connection_site_count/) | Şeklin bağlantı noktası sayısını döndürür.<br/>            Salt okunur **int**. |
| [`rotation`](/slides/python-net/tr/aspose.slides/videoframe/rotation/) | Belirtilen şeklin z-ekseninde döndürülme derecesini alır veya ayarlar.<br/>            Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersinde döndürmeyi gösterir.<br/>            Okunur/yazılabilir **float**. |
| [`x`](/slides/python-net/tr/aspose.slides/videoframe/x/) | Şeklin sol üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`y`](/slides/python-net/tr/aspose.slides/videoframe/y/) | Şeklin sol üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`width`](/slides/python-net/tr/aspose.slides/videoframe/width/) | Şeklin genişliğini, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`height`](/slides/python-net/tr/aspose.slides/videoframe/height/) | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar.<br/>            Okunur/yazılabilir **float**. |
| [`black_white_mode`](/slides/python-net/tr/aspose.slides/videoframe/black_white_mode/) | Şeklin siyah-beyaz görüntüleme modunda nasıl işleneceğini belirten özellik.<br/>            Okunur/yazılabilir [`BlackWhiteMode`](/slides/python-net/tr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/tr/aspose.slides/videoframe/unique_id/) | Eklentiler veya diğer kodlar tarafından kullanılmak üzere sunum kapsamlı iç kimlik döndürür.<br/>            Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`Shape.office_interop_shape_id`](/slides/python-net/tr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/tr/aspose.slides/videoframe/office_interop_shape_id/) | Şeklin yaşamı boyunca sabit kalan, slayt kapsamlı benzersiz kimliği döndürür; PowerPoint veya interop kodunun belge içinde her yerden şekle güvenilir şekilde başvurmasını sağlar.<br/>            Salt okunur **int**.<br/>            Ayrıca bakınız [`Shape.unique_id`](/slides/python-net/tr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/tr/aspose.slides/videoframe/alternative_text/) | Şekille ilişkili alternatif metni alır veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`alternative_text_title`](/slides/python-net/tr/aspose.slides/videoframe/alternative_text_title/) | Şekille ilişkili alternatif metnin başlığını alır veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`name`](/slides/python-net/tr/aspose.slides/videoframe/name/) | Şeklin adını alır veya ayarlar.<br/>            None olmamalıdır. Gerekirse boş dize kullanılabilir.<br/>            Okunur/yazılabilir **str**. |
| [`is_decorative`](/slides/python-net/tr/aspose.slides/videoframe/is_decorative/) | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar<br/>            Okunur/yazılabilir **bool**. |
| [`shape_lock`](/slides/python-net/tr/aspose.slides/videoframe/shape_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt okunur [`IPictureFrameLock`](/slides/python-net/tr/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/tr/aspose.slides/videoframe/is_grouped/) | Şeklin grup olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`parent_group`](/slides/python-net/tr/aspose.slides/videoframe/parent_group/) | Şekil grup ise üst GroupShape nesnesini döndürür. Aksi takdirde None döndürür.<br/>            Salt okunur [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/tr/aspose.slides/videoframe/slide/) | Şeklin üst slaydını döndürür.<br/>            Salt okunur [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/tr/aspose.slides/videoframe/presentation/) | Slaydın üst sunumunu döndürür.<br/>            Salt okunur [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/tr/aspose.slides/videoframe/shape_style/) | Şeklin stil nesnesini döndürür.<br/>            Salt okunur [`IShapeStyle`](/slides/python-net/tr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/tr/aspose.slides/videoframe/shape_type/) | PictureFrame için AutoShape tipini alır veya ayarlar.<br/>            [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype) kümesindeki tüm öğeler izinlidir,<br/>            ancak aşağıdaki çizgi türleri hariçtir:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Okunur/yazılabilir [`ShapeType`](/slides/python-net/tr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/tr/aspose.slides/videoframe/adjustments/) | Şeklin ayarlama değerlerinin koleksiyonunu döndürür.<br/>            Salt okunur [`IAdjustValueCollection`](/slides/python-net/tr/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/tr/aspose.slides/videoframe/picture_frame_lock/) | Şeklin kilitlerini döndürür.<br/>            Salt okunur [`IPictureFrameLock`](/slides/python-net/tr/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/tr/aspose.slides/videoframe/picture_format/) | Resim çerçevesi için PictureFillFormat nesnesini döndürür.<br/>            Salt okunur [`IPictureFillFormat`](/slides/python-net/tr/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/tr/aspose.slides/videoframe/relative_scale_height/) | Resim çerçevesinin yüksekliğinin (orijinal resim boyutuna göre) ölçeğini alır veya ayarlar. 1.0 değeri %100'e karşılık gelir.<br/>            Okunur/yazılabilir **float**. |
| [`relative_scale_width`](/slides/python-net/tr/aspose.slides/videoframe/relative_scale_width/) | Resim çerçevesinin genişliğinin (orijinal resim boyutuna göre) ölçeğini alır veya ayarlar. 1.0 değeri %100'e karşılık gelir.<br/>            Okunur/yazılabilir **float**. |
| [`is_cameo`](/slides/python-net/tr/aspose.slides/videoframe/is_cameo/) | PictureFrame'in Cameo nesnesi olup olmadığını belirler.<br/>            Salt okunur **bool**. |
| [`rewind_video`](/slides/python-net/tr/aspose.slides/videoframe/rewind_video/) | Video, film oynatımı bittikten hemen sonra otomatik olarak başa sarılıp sarılmayacağını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`play_loop_mode`](/slides/python-net/tr/aspose.slides/videoframe/play_loop_mode/) | Videonun döngüde olup olmayacağını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`hide_at_showing`](/slides/python-net/tr/aspose.slides/videoframe/hide_at_showing/) | VideoFrame'in gizli olup olmadığını belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`volume`](/slides/python-net/tr/aspose.slides/videoframe/volume/) | Ses seviyesini alır veya ayarlar.<br/>            Okunur/yazılabilir [`AudioVolumeMode`](/slides/python-net/tr/aspose.slides/audiovolumemode). |
| [`volume_value`](/slides/python-net/tr/aspose.slides/videoframe/volume_value/) | Kesin video seviyesini yüzde olarak alır veya ayarlar.<br/>             Değer 0 ile 100 arasında yüzde olarak ifade edilir. Bu özelliği, [`VideoFrame.volume`](/slides/python-net/tr/aspose.slides/videoframe/volume) özelliğinde mevcut önceden tanımlı seviyelerden daha hassas ses seviyelerini okuma veya ayarlama için kullanın.<br/>             Okunur/yazılabilir **float**. |
| [`play_mode`](/slides/python-net/tr/aspose.slides/videoframe/play_mode/) | Video oynatma modunu alır veya ayarlar.<br/>            Okunur/yazılabilir [`VideoPlayModePreset`](/slides/python-net/tr/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/tr/aspose.slides/videoframe/full_screen_mode/) | Videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler.<br/>            Okunur/yazılabilir **bool**. |
| [`link_path_long`](/slides/python-net/tr/aspose.slides/videoframe/link_path_long/) | VideoFrame'e bağlanan video dosyasının adını alır veya ayarlar.<br/>            Okunur/yazılabilir **str**. |
| [`embedded_video`](/slides/python-net/tr/aspose.slides/videoframe/embedded_video/) | Gömülü video nesnesini alır veya ayarlar.<br/>            Okunur/yazılabilir [`IVideo`](/slides/python-net/tr/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/tr/aspose.slides/videoframe/trim_from_start/) | Başlangıç kırpma [ms] |
| [`trim_from_end`](/slides/python-net/tr/aspose.slides/videoframe/trim_from_end/) | Bitiş kırpma [ms] |
| [`caption_tracks`](/slides/python-net/tr/aspose.slides/videoframe/caption_tracks/) | Video çerçevesiyle ilişkili kapalı altyazı koleksiyonunu alır.<br/>             Bu özellik salt okunurdur ve tüm altyazı izlerini içeren bir [`ICaptionsCollection`](/slides/python-net/tr/aspose.slides/icaptionscollection) döndürür. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`get_image(self)`](/slides/python-net/tr/aspose.slides/videoframe/get_image/#) | Şekil küçük resmini döndürür.<br/>            ShapeThumbnailBounds.Shape şekil küçük resim sınırları tipi varsayılan olarak kullanılır. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/tr/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Şekil küçük resmini döndürür. |
| [`write_as_svg(self, stream)`](/slides/python-net/tr/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/tr/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [`remove_placeholder(self)`](/slides/python-net/tr/aspose.slides/videoframe/remove_placeholder/#) | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/tr/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [`get_base_placeholder(self)`](/slides/python-net/tr/aspose.slides/videoframe/get_base_placeholder/#) | Temel bir yer tutucu şekli döndürür (şu anki şeklin miras alındığı yerleşim ve/veya ana slayttan şekil).<br/>            Şu anki şekil miras alınmamışsa None döndürülür. |
| [`get_visual_bounds(self)`](/slides/python-net/tr/aspose.slides/videoframe/get_visual_bounds/#) | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [`get_geometry_paths(self)`](/slides/python-net/tr/aspose.slides/videoframe/get_geometry_paths/#) | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relativesir. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/tr/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre relativesir.<br/>             Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/tr/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre relativesir.<br/>             Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir. |
| [`create_shape_elements(self)`](/slides/python-net/tr/aspose.slides/videoframe/create_shape_elements/#) | Şeklin öğelerinin dizisini oluşturur ve döndürür. |

### Ayrıca Bakınız
* sınıf [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape)
* sınıf [`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe)
* sınıf [`Shape`](/slides/python-net/tr/aspose.slides/shape)
* sınıf [`VideoFrame`](/slides/python-net/tr/aspose.slides/videoframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)