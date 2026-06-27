---
title: VideoFrame
second_title: Aspose.Sildes for .NET API Referansı
description: Bir slayttaki video klibi temsil eder.
type: docs
weight: 11700
url: /tr/aspose.slides/videoframe/
---
## VideoFrame sınıfı

Bir slayttaki video klibi temsil eder.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Şeklin ayar değerlerinin bir koleksiyonunu döndürür. Salt okunur [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okuma/yazma String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okuma/yazma String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl renderlanacağını belirtir. Okuma/yazma [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Video çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik salt okuma ve tüm altyazı izlerini içeren bir [`ICaptionsCollection`](../icaptionscollection) döndürür. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Salt okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Salt okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan bazı şekil tipleri için null döndürebilir. Salt okunur [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Gömülü video nesnesini döndürür veya ayarlar. Okuma/yazma [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özellikleri olmayan bazı şekil tipleri için null döndürebilir. Salt okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okuma/yazma [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Bir videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. Okuma/yazma Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okuma/yazma Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | VideoFrame'in gizli olup olmadığını belirler. Okuma/yazma Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan hiperlinki döndürür veya ayarlar. Okuma/yazma [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Hiperlink yöneticisini döndürür. Salt okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlanan hiperlinki döndürür veya ayarlar. Okuma/yazma [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame'in Cameo nesnesi olup olmadığını belirler. Salt okunur Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar. Okuma/yazma Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Salt okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Salt okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özellikleri olmayan bazı şekil tipleri için null döndürebilir. Salt okunur [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | VideoFrame ile bağlanan bir video dosyasının adını döndürür veya ayarlar. Okuma/yazma String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanın. Okuma/yazma String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Slayt kapsamında benzersiz bir tanımlayıcı döndürür; şeklin ömrü boyunca sabit kalır ve PowerPoint veya interop kodunun şekli belgede herhangi bir yerden güvenilir şekilde referans almasını sağlar. Salt okunur UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Salt okunur [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Bir resim çerçevesi için PictureFillFormat nesnesini döndürür. Salt okunur [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Şeklin kilitlerini döndürür. Salt okunur [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döndürür. Salt okunur [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Videonun döngüde olup olmadığını belirler. Okuma/yazma Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Video oynatma modunu döndürür veya ayarlar. Okuma/yazma [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu döndürür. Salt okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesi özelliklerini döndürür veya ayarlar. Okuma/yazma [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Resim çerçevesinin yüksekliğinin (orijinal resim boyutuna göre) ölçeğini döndürür veya ayarlar. Değer 1.0 %100'e karşılık gelir. Okuma/yazma Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Resim çerçevesinin genişliğinin (orijinal resim boyutuna göre) ölçeğini döndürür veya ayarlar. Değer 1.0 %100'e karşılık gelir. Okuma/yazma Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Film oynatımı bittikten hemen sonra videonun otomatik olarak başa sarılıp sarılmayacağını belirler. Okuma/yazma Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde dönüş, negatif değer saat yönünün tersinde dönüş anlamına gelir. Okuma/yazma Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Şeklin kilitlerini döndürür. Salt okunur [`IPictureFrameLock`](../ipictureframelock). (2 özellik) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Şeklin stil nesnesini döndürür. Salt okunur [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame için AutoShape tipini döndürür veya ayarlar. [`ShapeType`](../shapetype) setinin tüm öğeleri izinlidir, çizgi türleri hariç: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaydını döndürür. Salt okunur [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özellikleri olmayan bazı şekil tipleri için null döndürebilir. Salt okunur [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Kesme sonu [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Kesme başlangıcı [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Dahili, sunuma özgü bir tanımlayıcıyı döndürür; eklentiler veya diğer kodlar için tasarlanmıştır. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için, kalıcı benzersiz bir anahtar olarak ele alınmamalıdır. Salt okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Ses seviyesini döndürür veya ayarlar. Okuma/yazma [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol-üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol-üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Şeklin öğelerinin dizisini oluşturur ve döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil). Geçerli şekil miras alınmamışsa null döndürülür. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre relative'dir. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin yer tutucu olmadığını tanımlar. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Şekil geometrisini [`IGeometryPath`](../igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre relative olmalıdır. Şeklin tipini ([`ShapeType`](../geometryshape/shapetype)) Custom olarak değiştirir. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Şekil geometrisini [`IGeometryPath`](../igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre relative olmalıdır. Şeklin tipini ([`ShapeType`](../geometryshape/shapetype)) Custom olarak değiştirir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca bakınız

* sınıf [PictureFrame](../pictureframe)
* arayüz [IVideoFrame](../ivideoframe)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->