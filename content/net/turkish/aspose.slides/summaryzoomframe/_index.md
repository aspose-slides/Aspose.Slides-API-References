---
title: SummaryZoomFrame
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slaytta Summary Zoom nesnesini temsil eder.
type: docs
weight: 10750
url: /tr/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame sınıfı

Bir slaytta Summary Zoom nesnesini temsil eder.

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni alır veya ayarlar. Okunur/Yazılır String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını alır veya ayarlar. Okunur/Yazılır String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Bir şeklin siyah-beyaz gösterim modunda nasıl rendere edileceğini belirten özellik. Okunur/Yazılır [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlantı noktalarının sayısını alır. Sadece Okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini alır. Sadece Okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: etki özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Sadece Okunur [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Sadece Okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okunur/Yazılır [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini alır. Sadece Okunur [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan olarak ölçülmüş şekilde alır veya ayarlar. Okunur/Yazılır Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/Yazılır Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi alır veya ayarlar. Okunur/Yazılır [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini alır. Sadece Okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyü alır veya ayarlar. Okunur/Yazılır [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ seçeneğini alır veya ayarlar. Okunur/Yazılır Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplandırılıp gruplandırılmadığını belirler. Sadece Okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Sadece Okunur Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | Çerçevedeki Summary Zoom Bölümlerinin düzenini alır. Varsayılan değer GridLayout. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Sadece Okunur [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını alır veya ayarlar. Null olmamalıdır. Gerekirse boş string kullanılabilir. Okunur/Yazılır String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin yaşam süresi boyunca sabit kalan ve PowerPoint ya da interop kodunun belge içinde herhangi bir yerden şekle güvenilir şekilde referans vermesini sağlayan slayt kapsamlı benzersiz tanımlayıcıyı alır. Sadece Okunur UInt32. Ayrıca bkz. [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplandırılmışsa üst GroupShape nesnesini alır. Aksi takdirde null döndürür. Sadece Okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şeklin yer tutucusunu alır. Şeklin yer tutucusu yoksa null döndürür. Sadece Okunur [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu alır. Sadece Okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini alır veya ayarlar. Okunur/Yazılır [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını alır veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersine döndürmeyi gösterir. Okunur/Yazılır Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini alır. Sadece Okunur [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 özellik) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaydını alır. Sadece Okunur [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) değerini Summary Zoom Frame nesnesi için alır. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3b etkisi özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3b özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Sadece Okunur [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcıyı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabildiği için kalıcı bir benzersiz anahtar olarak değerlendirilemez. Sadece Okunur UInt32. Ayrıca bkz. [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan olarak ölçülmüş şekilde alır veya ayarlar. Okunur/Yazılır Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, puan olarak ölçülmüş şekilde alır veya ayarlar. Okunur/Yazılır Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, puan olarak ölçülmüş şekilde alır veya ayarlar. Okunur/Yazılır Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-dizindeki konumunu döndürür. Shapes[0] z-dizinin arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Sadece Okunur Int32. |

## Metotlar

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler (eğer yoksa) ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil). Geçerli şekil devralınmamışsa null döner. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../graphicalobject)
* arayüz [ISummaryZoomFrame](../isummaryzoomframe)
* isim uzayı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->