---
title: SmartArt
second_title: Aspose.Sildes .NET API Referansı
description: SmartArt diyagramını temsil eder
type: docs
weight: 10580
url: /tr/aspose.slides.smartart/smartart/
---
## SmartArt sınıfı

SmartArt diyagramını temsil eder

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | SmartArt nesnesindeki tüm düğümlerin koleksiyonunu döndürür. Salt okunur [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/yazılabilir String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Bu özellik bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirler. Okunur/yazılabilir [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | SmartArt nesnesinin renk stilini döndürür veya ayarlar. Okunur/yazılabilir [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Salt okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verisini döndürür. Salt okunur [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan belirli şekil türleri için null döndürebilir. Salt okunur [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özellikleri olmayan belirli şekil türleri için null döndürebilir. Salt okunur [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılabilir [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Salt okunur [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar. Okunur/yazılabilir Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/yazılabilir Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar. Okunur/yazılabilir [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Salt okunur [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyü döndürür veya ayarlar. Okunur/yazılabilir [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif işaretle' seçeneğini alır veya ayarlar. Okunur/yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Salt okunur Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | SmartArt diyagramının (soldan sağa) LTR veya (sağdan sola) RTL yönündeki durumunu döndürür veya ayarlar, eğer diyagram ters çevirmeyi destekliyorsa. Okunur/yazılabilir Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Salt okunur Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | SmartArt nesnesinin düzenini döndürür veya ayarlar. Okunur/yazılabilir [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özellikleri olmayan belirli şekil türleri için null döndürebilir. Salt okunur [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Null olamaz. Gerekirse boş string değeri kullanılabilir. Okunur/yazılabilir String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | SmartArt nesnesindeki kök düğümlerin koleksiyonunu döndürür. Salt okunur [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belge içinde her yerden güvenilir şekilde başvurmasını sağlayan slayt kapsamlı benzersiz tanımlayıcıyı döndürür. Salt okunur UInt32. Ayrıca bakınız [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Salt okunur [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Salt okunur [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu döndürür. Salt okunur [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | SmartArt nesnesinin hızlı stilini döndürür veya ayarlar. Okunur/yazılabilir [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılabilir [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersinde döndürmeyi gösterir. Okunur/yazılabilir Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Salt okunur [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 özellik) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaydını döndürür. Salt okunur [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özellikleri olmayan belirli şekil türleri için null döndürebilir. Salt okunur [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış içsel, sunum kapsamlı bir tanımlayıcıyı döndürür. Bu değer kullanıcı tarafından ya da programlı olarak yeniden atanabileceğinden kalıcı benzersiz bir anahtar olarak değerlendirilmemelidir. Salt okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, nokta cinsinden alır veya ayarlar. Okunur/yazılabilir Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar. Okunur/yazılabilir Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar. Okunur/yazılabilir Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler (eğer yoksa) ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil). Geçerli şekil devralınmadıysa null döndürülür. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır tipi kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../../aspose.slides/graphicalobject)
* arayüz [ISmartArt](../ismartart)
* ad alanı [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->