---
title: AutoShape
second_title: Aspose.Slides için .NET API Referansı
description: Bir AutoShape’i temsil eder.
type: docs
weight: 880
url: /tr/aspose.slides/autoshape/
---
## AutoShape sınıfı

Bir AutoShape’i temsil eder.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Şeklin ayarlama değerlerinin bir koleksiyonunu döndürür. Salt-okunur [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Şekille ilişkili alternatif metni alır veya ayarlar. Okunur/Yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Şekille ilişkili alternatif metnin başlığını alır veya ayarlar. Okunur/Yazılabilir String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | AutoShape’in kilitlerini döndürür. Salt-okunur [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Şeklin siyah-beyaz görüntü modunda nasıl işleneceğini belirten özelliktir. Okunur/Yazılabilir [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlantı noktalarının sayısını döndürür. Salt-okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Salt-okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanmış piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan bazı şekil türleri için null dönebilir. Salt-okunur [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özellikleri olmayan bazı şekil türleri için null dönebilir. Salt-okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okunur/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/Yazılabilir Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi alır veya ayarlar. Okunur/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Salt-okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyü alır veya ayarlar. Okunur/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ seçeneğini alır veya ayarlar. Okunur/Yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Salt-okunur Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | Şeklin bir metin kutusu olup olmadığını belirtir. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Salt-okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özellikleri olmayan bazı şekil türleri için null dönebilir. Salt-okunur [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Şeklin adını alır veya ayarlar. Boş olmamalıdır. Gerekirse boş dize kullanılabilir. Okunur/Yazılabilir String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin yaşam süresi boyunca sabit kalan, slayta özgü benzersiz tanımlayıcısını döndürür; PowerPoint ya da interop kodunun şekle her yerden güvenilir şekilde başvurmasını sağlar. Salt-okunur UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döner. Salt-okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şeklin yer tutucusunu döndürür. Yer tutucu yoksa null döner. Salt-okunur [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slayın üst sunumunu döndürür. Salt-okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini alır veya ayarlar. Okunur/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürülme açısını derece cinsinden alır veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Okunur/Yazılabilir Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | Şeklin kilitlerini döndürür. Salt-okunur [`IAutoShapeLock`](../iautoshapelock). (2 özellik) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Şeklin stil nesnesini döndürür. Salt-okunur [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Geometri ön ayar tipini alır veya ayarlar. Not: değer değiştiğinde tüm ayarlama değerleri varsayılan değerlerine sıfırlanır. Okunur/Yazılabilir [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Şeklin üst slaytını döndürür. Salt-okunur [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | AutoShape için TextFrame nesnesini döndürür. Salt-okunur [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özellikleri olmayan bazı şekil türleri için null dönebilir. Salt-okunur [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunuma özgü iç kimliği döndürür. Bu değer kullanıcı tarafından ya da programca yeniden atanabileceğinden kalıcı bir benzersiz anahtar olarak kullanılmamalıdır. Salt-okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | Bu auto shape’in stil veya dolgu biçimi yerine slaytın arka plan dolgusuyla doldurulup doldurulmayacağını belirler. Okunur/Yazılabilir Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] arka taraftaki şekli, Shapes[Shapes.Count - 1] ise ön taraftaki şekli verir. Salt-okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yer tutucu yoksa yeni bir yer tutucu ekler ve belirtilen bir taneye yer tutucu özelliklerini ayarlar. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | Şekle yeni bir TextFrame ekler. Şeklin zaten TextFrame’i varsa sadece metnini değiştirir. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Şeklin öğelerinin dizisini oluşturur ve döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (şu anki şeklin miras aldığı düzen veya ana slayttan gelen şekil). Şekil miras alınmamışsa null döner. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre görelidir. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şeklin küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape küçük resmi kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şeklin küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Şeklin geometrisini [`IGeometryPath`](../igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre görelidir. Şekil tipini ([`ShapeType`](../geometryshape/shapetype)) Custom’a değiştirir. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Şeklin geometrisini [`IGeometryPath`](../igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre görelidir. Şekil tipini ([`ShapeType`](../geometryshape/shapetype)) Custom’a değiştirir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GeometryShape](../geometryshape)
* arayüz [IAutoShape](../iautoshape)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->