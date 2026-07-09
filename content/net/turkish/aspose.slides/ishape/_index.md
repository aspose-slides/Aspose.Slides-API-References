---
title: IShape
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slaytta bir şekli temsil eder.
type: docs
weight: 6950
url: /tr/aspose.slides/ishape/
---
## IShape arayüzü

Represents a shape on a slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni alır veya ayarlar. Okuma/Yazma String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını alır veya ayarlar. Okuma/Yazma String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Temel IHyperlinkContainer arayüzünü almayı sağlar. Yalnızca okuma [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Temel ISlideComponent arayüzünü almayı sağlar. Yalnızca okuma [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl renderleneceğini belirtir. Okuma/Yazma [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını alır. Yalnızca okuma Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Şeklin özel verilerini alır. Yalnızca okuma [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini alır. Yalnızca okuma [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Bir şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini alır. Yalnızca okuma [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okuma/Yazma [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Şeklin yüksekliğini puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okuma/Yazma Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | 'Mark as decorative' seçeneğini alır veya ayarlar. Okuma/Yazma Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Şeklin gruplandı mı olduğunu belirler. Yalnızca okuma Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Şeklin TextHolder olup olmadığını belirler. Yalnızca okuma Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini alır. Yalnızca okuma [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Bir şeklin adını alır veya ayarlar. Okuma/Yazma String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle güvenilir şekilde referans vermesini sağlayan slayt kapsamında benzersiz bir tanımlayıcıyı alır. Yalnızca okuma UInt32. Ayrıca [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Şekil gruplandıysa üst GroupShape nesnesini, aksi takdirde null döndürür. Yalnızca okuma [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Bir şekil için yer tutucuyu alır. Yalnızca okuma [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini alır veya ayarlar. Okuma/Yazma [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını alır veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersine döndürmeyi gösterir. Okuma/Yazma Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Şeklin kilitlerini alır. Yalnızca okuma [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Bir şekil için çizgi biçimlendirme özelliklerini içeren ThreeDFormat nesnesini alır. Yalnızca okuma [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, içsel ve sunum kapsamında bir tanımlayıcıyı alır. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir anahtar olarak ele alınmamalıdır. Yalnızca okuma UInt32. Ayrıca [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Şeklin genişliğini puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu alır. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okuma Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler (eğer yoksa) ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil). Geçerli şekil devralınmamışsa null döndürülür. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır tipi kullanılır. |
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