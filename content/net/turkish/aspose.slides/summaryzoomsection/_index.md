---
title: SummaryZoomSection
second_title: Aspose.Sildes için .NET API Referansı
description: Summary Zoom çerçevesinde bir Summary Zoom Section nesnesini temsil eder.
type: docs
weight: 10800
url: /tr/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection sınıfı

Represents a Summary Zoom Section object in a Summary Zoom frame.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Özellikler

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Şekille ilişkili alternatif metni döndürür veya ayarlar. Okunabilir/Yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunabilir/Yazılabilir String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okunabilir/Yazılabilir [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlantı noktası sayısını döndürür. Yalnızca okuma Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özelleştirilmiş verisini döndürür. Yalnızca okuma [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Summary Zoom Section nesnesinin metin açıklamasını döndürür. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunabilir/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okuma [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan hiperlinki döndürür veya ayarlar. Okunabilir/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Hiperlink yöneticisini döndürür. Yalnızca okuma [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan hiperlinki döndürür veya ayarlar. Okunabilir/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Bir zoom nesnesinin görüntü tipini alır veya ayarlar. Okunabilir/Yazılabilir [`ZoomImageType`](../zoomimagetype). Varsayılan değer: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okunabilir/Yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Yalnızca okuma Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okuma Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Şekil için satır biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: satır özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş dize kullanılabilir. Okunabilir/Yazılabilir String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Slayt kapsamlı, şeklin ömrü boyunca sabit kalan benzersiz bir tanımlayıcı döndürür ve PowerPoint ya da interop kodunun şekle her yerden güvenilir şekilde referans vermesini sağlar. Yalnızca okuma UInt32. Ayrıca bkz. [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okuma [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Yalnızca okuma [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaytın üst sunumunu döndürür. Yalnızca okuma [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunabilir/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Slayt gösterisinde gezinme davranışını alır veya ayarlar. Okunabilir/Yazılabilir Boolean. Varsayılan değer: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersinde döndürmeyi gösterir. Okunabilir/Yazılabilir Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okuma [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 özellik) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Zoom'un hedef slaytın arka planını kullanıp kullanmayacağını belirten değeri alır veya ayarlar. Okunabilir/Yazılabilir Boolean. Varsayılan değer: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Şeklin üst slaytını döndürür. Yalnızca okuma [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Section Zoom nesnesinin bağlandığı bölüm nesnesini alır veya ayarlar. Okunabilir/Yazılabilir [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Yalnızca okuma [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Summary Zoom Section nesnesinin metin başlığını döndürür. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom ile slayt arasındaki geçiş süresini alır veya ayarlar. Okunabilir/Yazılabilir Single. Varsayılan değer: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, içsel, sunum kapsamlı bir tanımlayıcı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak kullanılmamalıdır. Yalnızca okuma UInt32. Ayrıca bkz. [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Zoom nesnesi için görüntüyü alır veya ayarlar. Okunabilir/Yazılabilir [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okuma Int32. |

## Yöntemler

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler eğer yoksa ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil). Geçerli şekil miras alınmamışsa null döndürülür. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır tipi kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Render edilmiş içeriğinden hesaplanan şeklin görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [SectionZoomFrame](../sectionzoomframe)
* arayüz [ISummaryZoomSection](../isummaryzoomsection)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->