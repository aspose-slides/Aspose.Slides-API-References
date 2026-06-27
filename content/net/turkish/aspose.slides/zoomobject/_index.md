---
title: ZoomObject
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slaytta bir Zoom nesnesini temsil eder.
type: docs
weight: 11850
url: /tr/aspose.slides/zoomobject/
---
## ZoomObject sınıfı

Bir slaytta bir Zoom nesnesini temsil eder.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/Yazılır String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/Yazılır String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okunur/Yazılır [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Yalnızca okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Yalnızca okunur [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Yalnızca okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/Yazılır [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunur [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini alır veya ayarlar, puan cinsinden ölçülür. Okunur/Yazılır Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/Yazılır Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar. Okunur/Yazılır [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine geldiğinde tanımlanan köprüyü döndürür veya ayarlar. Okunur/Yazılır [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Bir zoom nesnesinin görüntü tipini alır veya ayarlar. Okunur/Yazılır [`ZoomImageType`](../zoomimagetype). Varsayılan değer: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Alır veya 'Mark as decorative' seçeneğini ayarlar. Okunur/Yazılır Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanmış olup olmadığını belirler. Yalnızca okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Yalnızca okunur [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş string değeri kullanın. Okunur/Yazılır String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun belge içinde herhangi bir yerden şekle güvenilir bir şekilde referans vermesini sağlayan slayt kapsamlı benzersiz bir tanımlayıcıyı döndürür. Yalnızca okunur UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst grup şekil nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Yalnızca okunur [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu döndürür. Yalnızca okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/Yazılır [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Slayt gösterisinde gezinme davranışını alır veya ayarlar. Okunur/Yazılır Boolean. Varsayılan değer: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Okunur/Yazılır Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunur [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 özellik) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Zoom'un hedef slaydın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. Okunur/Yazılır Boolean. Varsayılan değer: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaydını döndürür. Yalnızca okunur [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Yalnızca okunur [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. Okunur/Yazılır Single. Varsayılan değer: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış içsel, sunum kapsamlı bir tanımlayıcıyı döndürür. Bu değer kullanıcı tarafından veya programlı olarak yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır. Yalnızca okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini alır veya ayarlar, puan cinsinden ölçülür. Okunur/Yazılır Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını alır veya ayarlar, puan cinsinden ölçülür. Okunur/Yazılır Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını alır veya ayarlar, puan cinsinden ölçülür. Okunur/Yazılır Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Zoom nesnesi için resmi alır veya ayarlar. Okunur/Yazılır [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli döndürür, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler eğer yoksa ve yer tutucu özelliklerini belirtilen bir taneye ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı yerleşim ve/veya ana slayttan gelen şekil). Geçerli şekil devralınmamışsa null döndürülür. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../graphicalobject)
* arayüz [IZoomObject](../izoomobject)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->