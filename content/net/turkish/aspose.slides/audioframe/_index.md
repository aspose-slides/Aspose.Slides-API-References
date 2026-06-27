---
title: AudioFrame
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slayttaki ses klibini temsil eder.
type: docs
weight: 850
url: /tr/aspose.slides/audioframe/
---
## AudioFrame sınıfı

Bir slaytta ses klibini temsil eder.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Şeklin ayarlama değerlerinin bir koleksiyonunu döndürür. Yalnızca okuma [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okuma/yazma String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okuma/yazma String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Son iz indeksini döndürür veya ayarlar. Okuma/yazma Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Son iz süresini döndürür veya ayarlar. Okuma/yazma Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Başlangıç iz indeksini döndürür veya ayarlar. Okuma/yazma Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Başlangıç iz süresini döndürür veya ayarlar. Okuma/yazma Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl işleneceğini belirtir. Okuma/yazma [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Ses çerçevesiyle ilişkili kapalı altyazıların bir koleksiyonunu döndürür. Bu özellik yalnızca okuma özelliğine sahiptir ve tüm altyazı izlerini içeren bir [`ICaptionsCollection`](../icaptionscollection) döndürür. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlantı noktalarının sayısını döndürür. Yalnızca okuma Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Yalnızca okuma [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat nesnesini döndürür; şekle uygulanmış piksel efektlerini içerir. Not: belirli şekil türleri için null dönebilir. Yalnızca okuma [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Sesin bir sunuma gömülü olup olmadığını belirler. Yalnızca okuma Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Gömülü ses nesnesini döndürür veya ayarlar. Okuma/yazma [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Medyanın başlangıçta solma giriş süresini milisaniye olarak belirtir. Okuma/yazma Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Medyanın sonundaki solma çıkış süresini milisaniye olarak belirtir. Okuma/yazma Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat nesnesini döndürür; bir şeklin doldurma biçimlendirme özelliklerini içerir. Not: belirli şekil türleri için null dönebilir. Yalnızca okuma [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okuma/yazma [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okuma/yazma Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | AudioFrame'in gizli olup olmadığını belirler. Okuma/yazma Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlı köprüyi döndürür veya ayarlar. Okuma/yazma [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca okuma [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlı köprüyü döndürür veya ayarlar. Okuma/yazma [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame'in Cameo nesnesi olup olmadığını belirler. Yalnızca okuma Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif işaretle' seçeneğini alır veya ayarlar. Okuma/yazma Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Yalnızca okuma Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okuma Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat nesnesini döndürür; bir şeklin çizgi biçimlendirme özelliklerini içerir. Not: belirli şekil türleri için null dönebilir. Yalnızca okuma [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | AudioFrame ile ilişkilendirilmiş bir ses dosyasının adını döndürür veya ayarlar. Okuma/yazma String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş dize kullanılabilir. Okuma/yazma String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Slayda özgü benzersiz bir tanımlayıcı döndürür; şeklin ömrü boyunca sabit kalır ve PowerPoint ya da interop kodunun şekle her yerden güvenilir şekilde başvurmasını sağlar. Yalnızca okuma UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GrupShape nesnesini döndürür. Aksi takdirde null döner. Yalnızca okuma [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Resim çerçevesi için PictureFillFormat nesnesini döndürür. Yalnızca okuma [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okuma [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döner. Yalnızca okuma [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Sesin slaytlar arasında çalınıp çalınmadığını belirler. Okuma/yazma Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Sesin döngü yapıp yapmadığını belirler. Okuma/yazma Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Ses oynatma modunu döndürür veya ayarlar. Okuma/yazma [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu döndürür. Yalnızca okuma [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesi özelliklerini döndürür veya ayarlar. Okuma/yazma [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Resim çerçevesinin yüksekliğinin (orijinal resim boyutuna göre) ölçeğini döndürür veya ayarlar. Değer 1.0 %100'e karşılık gelir. Okuma/yazma Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Resim çerçevesinin genişliğinin (orijinal resim boyutuna göre) ölçeğini döndürür veya ayarlar. Değer 1.0 %100'e karşılık gelir. Okuma/yazma Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Sesin oynatıldıktan sonra otomatik olarak başa sarılıp sarılmayacağını belirler. Okuma/yazma Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürülen derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde döndürmeyi; negatif değer saat yönünün tersine döndürmeyi gösterir. Okuma/yazma Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okuma [`IPictureFrameLock`](../ipictureframelock). (2 özellik) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Şeklin stil nesnesini döndürür. Yalnızca okuma [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame için AutoShape türünü döndürür veya ayarlar. [`ShapeType`](../shapetype) kümesindeki tüm öğeler kabul edilebilir, çizgi türleri hariç: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Şeklin üst slaydını döndürür. Yalnızca okuma [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat nesnesini döndürür; bir şeklin 3D etki özelliklerini içerir. Not: belirli şekil türleri için null dönebilir. Yalnızca okuma [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Oynatma sırasında medyanın sonundan kaldırılacak süreyi milisaniye olarak belirtir. Okuma/yazma Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Oynatma sırasında medyanın başlangıcından kaldırılacak süreyi milisaniye olarak belirtir. Okuma/yazma Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere sunuma özgü iç tanımlayıcı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz anahtar olarak kullanılmamalıdır. Yalnızca okuma UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Ses seviyesini döndürür veya ayarlar. Okuma/yazma [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Ses seviyesini yüzde olarak döndürür veya ayarlar. Okuma/yazma Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-order içindeki konumunu döndürür. Shapes[0] z-order arkasındaki şekli döndürür, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okuma Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler, eğer yoksa ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Şeklin öğelerinin bir dizisini oluşturur ve döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil). Geçerli şekil devralınmamışsa null döner. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre görecelidir. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınırları türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Şekil geometrisini [`IGeometryPath`](../igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şekil tipini ([`ShapeType`](../geometryshape/shapetype)) Özel olarak değiştirir. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Şekil geometrisini [`IGeometryPath`](../igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şekil tipini ([`ShapeType`](../geometryshape/shapetype)) Özel olarak değiştirir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Örnekler

Aşağıdaki örnekler, Ses Oynatma Seçeneklerini nasıl değiştireceğinizi gösterir.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // AudioFrame şekli alınır
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Oynatma modunu tıklanınca oynat olarak ayarlar
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Ses seviyesini Düşük olarak ayarlar
    audioFrame.Volume = AudioVolumeMode.Low;
    // Sesin slaytlar arasında çalınmasını ayarlar
    audioFrame.PlayAcrossSlides = true;
    // Ses için döngüyü devre dışı bırakır
    audioFrame.PlayLoopMode = false;
    // Slayt gösterisi sırasında AudioFrame'i gizler
    audioFrame.HideAtShowing = true;
    // Oynatıldıktan sonra sesi başlangıca geri sarar
    audioFrame.RewindAudio = true;
    // PowerPoint dosyasını diske kaydeder
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Ayrıca bakınız

* sınıf [PictureFrame](../pictureframe)
* arayüz [IAudioFrame](../iaudioframe)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->