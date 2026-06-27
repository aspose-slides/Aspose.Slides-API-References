---
title: GeometryShape
second_title: Aspose.Sildes için .NET API Referansı
description: Tüm geometrik şekiller için üst sınıfı temsil eder.
type: docs
weight: 4950
url: /tr/aspose.slides/geometryshape/
---
## GeometryShape sınıfı

Tüm geometrik şekiller için üst sınıfı temsil eder.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Şeklin ayar değerlerinin bir koleksiyonunu döndürür. Yalnızca-okunur [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Şekille ilişkilendirilmiş alternatif metni döndürür veya ayarlar. Okunabilir/Yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Şekille ilişkilendirilmiş alternatif metnin başlığını döndürür veya ayarlar. Okunabilir/Yazılabilir String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okunabilir/Yazılabilir [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca-okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Yalnızca-okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan belirli şekil türleri için null döndürebilir. Yalnızca-okunur [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özellikleri olmayan belirli şekil türleri için null döndürebilir. Yalnızca-okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunabilir/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini (puan cinsinden) alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Şekil için fare tıklamasında tanımlanan köprüyü döndürür veya ayarlar. Okunabilir/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca-okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür veya ayarlar. Okunabilir/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar. Okunabilir/Yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplandırılıp gruplandırılmadığını belirler. Yalnızca-okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca-okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özellikleri olmayan belirli şekil türleri için null döndürebilir. Yalnızca-okunur [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanın. Okunabilir/Yazılabilir String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint veya interop kodunun şekle her yerden güvenilir şekilde başvurmasını sağlayan slayt kapsamlı benzersiz kimliği döndürür. Yalnızca-okunur UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplandırılmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca-okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döndürür. Yalnızca-okunur [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Slaytın üst sunumunu döndürür. Yalnızca-okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Şekil çerçevesinin ham özelliklerini döndürür veya ayarlar. Okunabilir/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersine döndürülür. Okunabilir/Yazılabilir Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca-okunur [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Şeklin stil nesnesini döndürür. Yalnızca-okunur [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Geometri ön ayar tipini döndürür veya ayarlar. Not: değer değiştiğinde tüm ayar değerleri varsayılan değerlerine sıfırlanır. Okunabilir/Yazılabilir [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Şeklin üst slaytını döndürür. Yalnızca-okunur [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Şeklin 3d efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3d özellikleri olmayan belirli şekil türleri için null döndürebilir. Yalnızca-okunur [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış içsel, sunum kapsamlı bir tanımlayıcı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak kullanılmamalıdır. Yalnızca-okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini (puan cinsinden) alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını (puan cinsinden) alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını (puan cinsinden) alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının en arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca-okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler (eğer mevcut değilse) ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Şeklin öğelerinin bir dizisini oluşturur ve döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin kalıtıldığı düzen ve/veya ana slayttan bir şekil). Geçerli şekil kalıtılmamışsa null döndürür. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Geometri şeklinin yolunun bir kopyasını döndürür. Koordinatlar şeklin sol üst köşesine göredir. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü varsayılan olarak kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin işlenen içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) nesnesinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre olmalıdır. Şeklin tipini ([`ShapeType`](./shapetype)) Custom olarak değiştirir. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) dizisinden şekil geometrisini günceller. Koordinatlar şeklin sol üst köşesine göre olmalıdır. Şeklin tipini ([`ShapeType`](./shapetype)) Custom olarak değiştirir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [Shape](../shape)
* arayüz [IGeometryShape](../igeometryshape)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->