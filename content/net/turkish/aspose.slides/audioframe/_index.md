---
title: AudioFrame
second_title: Aspose.Sildes .NET API Referansı
description: Bir slayttaki ses klibini temsil eder.
type: docs
weight: 870
url: /tr/aspose.slides/audioframe/
---
## AudioFrame sınıfı

Bir slayttaki ses klibini temsil eder.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Şeklin ayar değerlerinin bir koleksiyonunu döndürür. Yalnızca okunur [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/yazılabilir String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Son parça indeksini döndürür veya ayarlar. Okunur/yazılabilir Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Son parça süresini döndürür veya ayarlar. Okunur/yazılabilir Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Başlangıç parça indeksini döndürür veya ayarlar. Okunur/yazılabilir Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Başlangıç parça süresini döndürür veya ayarlar. Okunur/yazılabilir Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirtir. Okunur/yazılabilir [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Ses çerçevesiyle ilişkili kapalı altyazıların koleksiyonunu alır. Bu özellik yalnızca okunur ve tüm altyazı izlerini içeren bir [`ICaptionsCollection`](../icaptionscollection) döndürür. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Yalnızca okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özelliği olmayan belirli şekil türleri için null döndürebilir. Yalnızca okunur [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Sesin bir sunuma gömülü olup olmadığını belirler. Yalnızca okunur Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Gömülü ses nesnesini döndürür veya ayarlar. Okunur/yazılabilir [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Ortamın ilk fade-in süresini milisaniye olarak belirtir. Okunur/yazılabilir Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Ortamın bitiş fade-out süresini milisaniye olarak belirtir. Okunur/yazılabilir Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şeklin doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: doldurma özelliği olmayan belirli şekil türleri için null döndürebilir. Yalnızca okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılabilir [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini (puan cinsinden) alır veya ayarlar. Okunur/yazılabilir Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/yazılabilir Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | AudioFrame'in gizli olup olmadığını belirler. Okunur/yazılabilir Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi (hyperlink) döndürür veya ayarlar. Okunur/yazılabilir [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlanan köprüyi döndürür veya ayarlar. Okunur/yazılabilir [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame'in Cameo nesnesi olup olmadığını belirler. Yalnızca okunur Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' seçeneğini alır veya ayarlar. Okunur/yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanmış olup olmadığını belirler. Yalnızca okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özelliği olmayan belirli şekil türleri için null döndürebilir. Yalnızca okunur [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | AudioFrame'e bağlı bir ses dosyasının adını döndürür veya ayarlar. Okunur/yazılabilir String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanılabilir. Okunur/yazılabilir String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belge içinde her yerden güvenilir şekilde başvurmasını sağlayan slayt kapsamlı benzersiz bir tanımlayıcı döndürür. Yalnızca okunur UInt32. Ayrıca bkz. [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okunur [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Bir resim çerçevesi için PictureFillFormat nesnesini döndürür. Yalnızca okunur [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunur [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döndürür. Yalnızca okunur [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Sesin slaytlar arasında oynatılıp oynatılmadığını belirler. Okunur/yazılabilir Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Sesin döngüde çalınıp çalınmadığını belirler. Okunur/yazılabilir Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Ses çalma modunu döndürür veya ayarlar. Okunur/yazılabilir [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu döndürür. Yalnızca okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Şekil çerçevesinin ham özelliklerini döndürür veya ayarlar. Okunur/yazılabilir [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0 %100'e karşılık gelir. Okunur/yazılabilir Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0 %100'e karşılık gelir. Okunur/yazılabilir Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Sesin oynatıldıktan sonra otomatik olarak başa sarılıp sarılmayacağını belirler. Okunur/yazılabilir Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürülme derecesini döndürür veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersinde döndürmeyi gösterir. Okunur/yazılabilir Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunur [`IPictureFrameLock`](../ipictureframelock). (2 özellik) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Şeklin stil nesnesini döndürür. Yalnızca okunur [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame için AutoShape türünü döndürür veya ayarlar. [`ShapeType`](../shapetype) kümesinin tüm öğeleri kullanılabilir, ancak tüm çizgi türleri hariç: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaydını döndürür. Yalnızca okunur [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özelliği olmayan belirli şekil türleri için null döndürebilir. Yalnızca okunur [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye olarak belirtir. Okunur/yazılabilir Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye olarak belirtir. Okunur/yazılabilir Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, içsel ve sunum kapsamlı bir tanımlayıcı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır. Yalnızca okunur UInt32. Ayrıca bkz. [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Ses seviyesini döndürür veya ayarlar. Okunur/yazılabilir [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Ses seviyesini yüzde olarak döndürür veya ayarlar. Okunur/yazılabilir Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini (puan cinsinden) alır veya ayarlar. Okunur/yazılabilir Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını (puan cinsinden) alır veya ayarlar. Okunur/yazılabilir Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını (puan cinsinden) alır veya ayarlar. Okunur/yazılabilir Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli döndürür, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yer tutucu yoksa yenisini ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Şeklin öğelerinin bir dizisini oluşturur ve döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil). Geçerli şekil miras alınmamışsa null döndürülür. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Geometri şeklinin yolunun kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre görelidir. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır tipi kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Render edilen içeriğinden hesaplanan şeklin görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Şekil geometrisini [`IGeometryPath`](../igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre görelidir. Şekil tipini ([`ShapeType`](../geometryshape/shapetype)) Custom olarak değiştirir. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Şekil geometrisini [`IGeometryPath`](../igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre görelidir. Şekil tipini ([`ShapeType`](../geometryshape/shapetype)) Custom olarak değiştirir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Örnekler

Aşağıdaki örnekler, Ses Çalma Seçeneklerini nasıl değiştireceğinizi gösterir.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // AudioFrame şekli alır
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Oynatma modunu tıklanınca çalacak şekilde ayarlar
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Ses seviyesini Düşük olarak ayarlar
    audioFrame.Volume = AudioVolumeMode.Low;
    // Sesin slaytlar arasında çalmasını ayarlar
    audioFrame.PlayAcrossSlides = true;
    // Ses için döngüyü devre dışı bırakır
    audioFrame.PlayLoopMode = false;
    // Sunum sırasında AudioFrame'i gizler
    audioFrame.HideAtShowing = true;
    // Oynatmadan sonra sesi başa sarar
    audioFrame.RewindAudio = true;
    // PowerPoint dosyasını diske kaydeder
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Bakınız

* sınıf [PictureFrame](../pictureframe)
* arayüz [IAudioFrame](../iaudioframe)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->