---
title: IShape
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slayttaki şekli temsil eder.
type: docs
weight: 6930
url: /tr/aspose.slides/ishape/
---
## IShape arayüzü

Bir slayttaki şekli temsil eder.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/Yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/Yazılabilir String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Temel IHyperlinkContainer arayüzünü elde etmeye izin verir. Sadece okunur [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Temel ISlideComponent arayüzünü elde etmeye izin verir. Sadece okunur [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okunur/Yazılabilir [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Şeklin bağlantı noktası sayısını döndürür. Sadece okunur Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Şeklin özel verilerini döndürür. Sadece okunur [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Sadece okunur [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Sadece okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/Yazılabilir Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okunur/Yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Şeklin gruplandırılmış olup olmadığını belirler. Sadece okunur Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Şeklin TextHolder olup olmadığını belirler. Sadece okunur Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Sadece okunur [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Okunur/Yazılabilir String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Şeklin yaşam süresi boyunca sabit kalan ve PowerPoint ya da interop kodunun belge içinde herhangi bir yerden şekli güvenilir biçimde referans almasını sağlayan slayt kapsamlı benzersiz bir tanımlayıcıyı döndürür. Sadece okunur UInt32. Ayrıca bkz. [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Şekil gruplandırılmış ise üst GroupShape nesnesini döndürür. Aksi takdirde null döndürülür. Sadece okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Bir şekil için yer tutucuyu döndürür. Sadece okunur [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde dönüş, negatif değer saat yönünün tersine dönüş gösterir. Okunur/Yazılabilir Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Şeklin kilitlerini döndürür. Sadece okunur [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren ThreeDFormat nesnesini döndürür. Sadece okunur [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, içsel ve sunum kapsamlı bir tanımlayıcıyı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır. Sadece okunur UInt32. Ayrıca bkz. [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Sadece okunur Int32. |

## Metotlar

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Henüz yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilene ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin kalıtıldığı düzen veya ana slayttan gelen şekil). Geçerli şekil kalıtılmamışsa null döndürülür. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü kullanılır. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* arayüz [IHyperlinkContainer](../ihyperlinkcontainer)
* arayüz [ISlideComponent](../islidecomponent)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->