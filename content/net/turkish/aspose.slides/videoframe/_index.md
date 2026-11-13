---
title: VideoFrame
second_title: Aspose.Sildes .NET için API Referansı
description: Bir slaytta video klibi temsil eder.
type: docs
weight: 11740
url: /tr/aspose.slides/videoframe/
---
## VideoFrame sınıfı

Bir slaytta bir video klibi temsil eder.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Şeklin ayar değerlerinin bir koleksiyonunu döndürür. Yalnızca okuma [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Şekille ilişkili alternatif metni alır veya ayarlar. Okuma/Yazma String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Şekille ilişkili alternatif metnin başlığını alır veya ayarlar. Okuma/Yazma String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl işleneceğini belirtir. Okuma/Yazma [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Video çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik yalnızca okuma olup, tüm altyazı izlerini içeren bir [`ICaptionsCollection`](../icaptionscollection) döndürür. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okuma Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Yalnızca okuma [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan belirli şekil türleri için null döndürebilir. Yalnızca okuma [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Yerleşik video nesnesini alır veya ayarlar. Okuma/Yazma [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Şekle ait doldurma biçimleme özelliklerini içeren FillFormat nesnesini döndürür. Not: doldurma özellikleri olmayan belirli şekil türleri için null döndürebilir. Yalnızca okuma [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okuma/Yazma [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Videonun tam ekran modunda gösterilip gösterilmeyeceğini belirler. Okuma/Yazma Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okuma/Yazma Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | VideoFrame'in gizli olup olmadığını belirler. Okuma/Yazma Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyü alır veya ayarlar. Okuma/Yazma [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca okuma [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlanan köprüyü alır veya ayarlar. Okuma/Yazma [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame'in Cameo nesnesi olup olmadığını belirler. Yalnızca okuma Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okuma/Yazma Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplandığını belirler. Yalnızca okuma Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okuma Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özellikleri olmayan belirli şekil türleri için null döndürebilir. Yalnızca okuma [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | VideoFrame'e bağlı video dosyasının adını alır veya ayarlar. Okuma/Yazma String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Şeklin adını alır veya ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanılabilir. Okuma/Yazma String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin yaşam süresi boyunca sabit kalan, slayt kapsamlı benzersiz tanımlayıcısını döndürür. Yalnızca okuma UInt32. Ayrıca [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplandıysa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okuma [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Resim çerçevesi için PictureFillFormat nesnesini döndürür. Yalnızca okuma [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okuma [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döndürür. Yalnızca okuma [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Videonun döngüde olup olmadığını belirler. Okuma/Yazma Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Video oynatma modunu alır veya ayarlar. Okuma/Yazma [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaytın üst sunumunu döndürür. Yalnızca okuma [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini alır veya ayarlar. Okuma/Yazma [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) alır veya ayarlar. Değer 1.0 %100'e eşittir. Okuma/Yazma Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) alır veya ayarlar. Değer 1.0 %100'e eşittir. Okuma/Yazma Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Video, film oynatımı bittiğinde otomatik olarak başa sarılıp sarılmayacağını belirler. Okuma/Yazma Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürülen derece sayısını alır veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersinde döndürür. Okuma/Yazma Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okuma [`IPictureFrameLock`](../ipictureframelock). (2 özellik) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Şeklin stil nesnesini döndürür. Yalnızca okuma [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame için AutoShape türünü alır veya ayarlar. [`ShapeType`](../shapetype) kümesindeki tüm öğeler izin verilir, çizgi çeşitleri hariç: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Şeklin üst slaydını döndürür. Yalnızca okuma [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özellikleri olmayan belirli şekil türleri için null döndürebilir. Yalnızca okuma [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Trim sonu [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Trim başlangıcı [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, içsel, sunum kapsamlı bir tanımlayıcı döndürür. Bu değer kullanıcı tarafından veya programlı olarak yeniden atanabileceğinden, kalıcı bir benzersiz anahtar olarak değerlendirilmemelidir. Yalnızca okuma UInt32. Ayrıca [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Ses seviyesini alır veya ayarlar. Okuma/Yazma [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/videoframe/volumevalue) { get; set; } | Videonun tam ses seviyesini yüzde olarak alır veya ayarlar. Değer 0 ile 100 arasında yüzde olarak ifade edilir. Bu özelliği, [`Volume`](./volume) özelliği üzerinden mevcut önceden tanımlı seviyelerden daha hassas ses değerlerini okumak veya ayarlamak için kullanın. Okuma/Yazma Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının en arkasındaki şekli, Shapes[Shapes.Count - 1] ise en önündeki şekli döndürür. Yalnızca okuma Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler, eğer yoksa ve belirtilen bir yer tutucuya özelliklerini ayarlar. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Şeklin öğelerinin bir dizisini oluşturur ve döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin kalıtıldığı düzen ve/veya ana slayttan gelen şekil). Geçerli şekil kalıtılmamışsa null döndürülür. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre görecelidir. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şeklin küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şeklin küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Render edilen içeriğinden hesaplanan şeklin görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) nesnesinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin türünü ([`ShapeType`](../geometryshape/shapetype)) Custom olarak değiştirir. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) dizisinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin türünü ([`ShapeType`](../geometryshape/shapetype)) Custom olarak değiştirir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [PictureFrame](../pictureframe)
* arayüz [IVideoFrame](../ivideoframe)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->