---
title: InkActions
second_title: Aspose.Sildes için .NET API Referansı
description: İnk eylemlerinin kökünü temsil eder.
type: docs
weight: 7580
url: /tr/aspose.slides.ink/inkactions/
---
## InkActions sınıfı

Bir şeklin kök ink eylemlerini temsil eder.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## Özellikler

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/yazılır String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/yazılır String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okunur/yazılır [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlantı noktası sayısını döndürür. Yalnızca okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özelleştirilmiş verisini döndürür. Yalnızca okunur [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Yalnızca okunur [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şekil için doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: doldurma özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Yalnızca okunur [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılır [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunur [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okunur/yazılır Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/yazılır Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlı bağlantıyı döndürür veya ayarlar. Okunur/yazılır [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Bağlantı yöneticisini döndürür. Yalnızca okunur [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine geldiğinde tanımlı bağlantıyı döndürür veya ayarlar. Okunur/yazılır [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Dekoratif işaretle seçeneğini alır veya ayarlar. Okunur/yazılır Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplandırılıp gruplandırılmadığını belirler. Yalnızca okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şekil için satır biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: satır özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Yalnızca okunur [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanın. Okunur/yazılır String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin yaşam süresi boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belge içinde her yerden güvenilir şekilde başvurmasını sağlayan slayt kapsamlı benzersiz tanımlayıcıyı döndürür. Yalnızca okunur UInt32. Ayrıca bakınız [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplandırılmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okunur [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Yalnızca okunur [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaytın üst sunumunu döndürür. Yalnızca okunur [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/yazılır [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersinde döndürmeyi gösterir. Okunur/yazılır Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunur [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 özellik) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaytını döndürür. Yalnızca okunur [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özelliklerine sahip olmayan bazı şekil türleri için null döndürebilir. Yalnızca okunur [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcıyı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak değerlendirilmemelidir. Yalnızca okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okunur/yazılır Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okunur/yazılır Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okunur/yazılır Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okunur Int32. |

## Yöntemler

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler, yoksa ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan şekil). Geçerli şekil miras alınmamışsa null döndürülür. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil thumbnailsını döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil thumbnail sınır tipi kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil thumbnailsını döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin, render edilen içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Diğer Bağlantılar

* sınıf [GraphicalObject](../../aspose.slides/graphicalobject)
* arayüz [IInkActions](../iinkactions)
* ad alanı [Aspose.Slides.Ink](../../aspose.slides.ink)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->