---
title: Connector
second_title: Aspose.Sildes için .NET API Referansı
description: Bir bağlayıcıyı temsil eder.
type: docs
weight: 2690
url: /tr/aspose.slides/connector/
---
## Connector sınıfı

Represents a connector.

```csharp
public class Connector : GeometryShape, IConnector
```

## Özellikler

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Şeklin ayarlama değerlerinin bir koleksiyonunu döndürür. Salt okunur [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/yazılır String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/yazılır String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirten özelliktir. Okunur/yazılır [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlantı noktalarının sayısını döndürür. Salt okunur Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Bağlayıcının kilitlerini döndürür. Salt okunur [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Salt okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özelliklerine sahip olmayan belirli şekil tipleri için null döndürebilir. Salt okunur [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Bağlayıcının ucunu bağlamak için kullanılan şekli döndürür veya ayarlar. Okunur/yazılır [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Uç şekil için bağlantı noktasının dizinini döndürür veya ayarlar. Okunur/yazılır UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özelliklerine sahip olmayan belirli şekil tipleri için null döndürebilir. Salt okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılır [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Nokta cinsinden ölçülen şeklin yüksekliğini alır veya ayarlar. Okunur/yazılır Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/yazılır Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar. Okunur/yazılır [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Salt okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyi döndürür veya ayarlar. Okunur/yazılır [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okunur/yazılır Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Salt okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Salt okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özelliklerine sahip olmayan belirli şekil tipleri için null döndürebilir. Salt okunur [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Şeklin adını döndürür veya ayarlar. Boş olmamalıdır. Gerekirse boş dize kullanılabilir. Okunur/yazılır String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin yaşam süresi boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle her yerden güvenilir başvurmasını sağlayan slayt-kapsamlı benzersiz tanımlayıcıyı döndürür. Salt okunur UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Salt okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döndürür. Salt okunur [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Slaytın üst sunumunu döndürür. Salt okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Çerçevenin ham şekil özelliklerini döndürür veya ayarlar. Okunur/yazılır [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z-ekseninde döndürülme derecesini döndürür veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi belirtir. Okunur/yazılır Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Şeklin kilitlerini döndürür. Salt okunur [`IConnectorLock`](../iconnectorlock). (2 özellik) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Şeklin stil nesnesini döndürür. Salt okunur [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | AutoShape tipini döndürür veya ayarlar. Okunur/yazılır [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Şeklin üst slaytını döndürür. Salt okunur [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Bağlayıcının başlangıcını bağlamak için kullanılan şekli döndürür veya ayarlar. Okunur/yazılır [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar. Okunur/yazılır UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Şeklin 3d efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3d özelliklerine sahip olmayan belirli şekil tipleri için null döndürebilir. Salt okunur [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunuma özgü dahili bir tanımlayıcı döndürür. Kullanıcı ya da program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak kullanılmamalıdır. Salt okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Nokta cinsinden ölçülen şeklin genişliğini alır veya ayarlar. Okunur/yazılır Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Nokta cinsinden ölçülen şeklin sol-üst köşesinin x koordinatını alır veya ayarlar. Okunur/yazılır Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Nokta cinsinden ölçülen şeklin sol-üst köşesinin y koordinatını alır veya ayarlar. Okunur/yazılır Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt okunur Int32. |

## Yöntemler

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler, eğer yoksa ve belirtilen birine yer tutucu özelliklerini ayarlar. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Şeklin öğelerinin dizisini oluşturur ve döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Geçerli şeklin miras aldığı düzen ve/veya ana slayttan bir temel yer tutucu şekli döndürür. Şekil miras alınmamışsa null döndürür. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Geometri şeklinin yolunun kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göredir. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. ShapeThumbnailBounds.Shape şekil küçük resmi sınır tipi varsayılan olarak kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [Reroute](../../aspose.slides/connector/reroute)() | Bağlayıcıyı, bağladığı şekiller arasındaki mümkün olan en kısa yolu alacak şekilde yönlendirir. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) nesnesinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini ([`ShapeType`](../geometryshape/shapetype)) Özel olarak değiştirir. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) dizisinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini ([`ShapeType`](../geometryshape/shapetype)) Özel olarak değiştirir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GeometryShape](../geometryshape)
* arayüz [IConnector](../iconnector)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->