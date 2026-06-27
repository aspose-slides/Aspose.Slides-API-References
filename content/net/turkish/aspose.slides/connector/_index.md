---
title: Connector
second_title: Aspose.Sildes için .NET API Referansı
description: Bir bağlayıcıyı temsil eder.
type: docs
weight: 2650
url: /tr/aspose.slides/connector/
---
## Connector sınıfı

Bir bağlayıcıyı temsil eder.

```csharp
public class Connector : GeometryShape, IConnector
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Şeklin ayar değerlerinin bir koleksiyonunu döndürür. Yalnızca okunabilir [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/Yazılır String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/Yazılır String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl gösterileceğini belirler. Okunur/Yazılır [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okunabilir Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Bağlayıcının kilitlerini döndürür. Yalnızca okunabilir [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Yalnızca okunabilir [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan bazı şekil tipleri için null dönebilir. Yalnızca okunabilir [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Bağlayıcının ucunu bağlamak için şekli döndürür veya ayarlar. Okunur/Yazılır [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Son şekil için bağlantı noktasının dizinini döndürür veya ayarlar. Okunur/Yazılır UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özellikleri olmayan bazı şekil tipleri için null dönebilir. Yalnızca okunabilir [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/Yazılır [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okunur/Yazılır Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/Yazılır Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyü döndürür veya ayarlar. Okunur/Yazılır [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca okunabilir [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür veya ayarlar. Okunur/Yazılır [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okunur/Yazılır Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Yalnızca okunabilir Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okunabilir Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özellikleri olmayan bazı şekil tipleri için null dönebilir. Yalnızca okunabilir [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Boş olmamalıdır. Gerekirse boş dize değeri kullanın. Okunur/Yazılır String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Slayt kapsamlı benzersiz bir tanımlayıcıyı döndürür; bu tanımlayıcı şeklin ömrü boyunca sabit kalır ve PowerPoint veya interop kodunun şekli belgenin herhangi bir yerinden güvenilir şekilde referans almasını sağlar. Yalnızca okunabilir UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döner. Yalnızca okunabilir [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döner. Yalnızca okunabilir [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaytın üst sunumunu döndürür. Yalnızca okunabilir [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/Yazılır [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürülen derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersine döndürmeyi gösterir. Okunur/Yazılır Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunabilir [`IConnectorLock`](../iconnectorlock). (2 özellik) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Şeklin stil nesnesini döndürür. Yalnızca okunabilir [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | AutoShape tipini döndürür veya ayarlar. Okunur/Yazılır [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaytını döndürür. Yalnızca okunabilir [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Bağlayıcının başlangıcını bağlamak için şekli döndürür veya ayarlar. Okunur/Yazılır [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar. Okunur/Yazılır UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özellikleri olmayan bazı şekil tipleri için null dönebilir. Yalnızca okunabilir [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | İçsel, sunum kapsamlı bir tanımlayıcıyı döndürür; bu, eklentiler veya diğer kodlar tarafından kullanılmak içindir. Bu değer kullanıcı tarafından veya programlı olarak yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır. Yalnızca okunabilir UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okunur/Yazılır Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okunur/Yazılır Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okunur/Yazılır Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli döndürür, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okunabilir Int32. |

## Metotlar

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler (eğer yoksa) ve yer tutucu özelliklerini belirtilen bir taneye ayarlar. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Şeklin öğelerinin bir dizisini oluşturur ve döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (mevcut şeklin devralındığı düzen ve/veya ana slayttan gelen şekil). Mevcut şekil devralınmamışsa null döner. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göre görecelidir. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [Reroute](../../aspose.slides/connector/reroute)() | Bağlayıcıyı, bağladığı şekiller arasındaki mümkün olan en kısa yolu alacak şekilde yeniden yönlendirir. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Şeklin geometrisini [`IGeometryPath`](../igeometrypath) nesnesinden günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini ([`ShapeType`](../geometryshape/shapetype)) Custom olarak değiştirir. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Şeklin geometrisini [`IGeometryPath`](../igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini ([`ShapeType`](../geometryshape/shapetype)) Custom olarak değiştirir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GeometryShape](../geometryshape)
* arayüz [IConnector](../iconnector)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->