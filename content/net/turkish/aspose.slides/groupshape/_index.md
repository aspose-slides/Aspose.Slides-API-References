---
title: GroupShape
second_title: Aspose.Sildes for .NET API Referansı
description: Bir slayttaki şekil grubunu temsil eder.
type: docs
weight: 5110
url: /tr/aspose.slides/groupshape/
---
## GroupShape sınıfı

Represents a group of shapes on a slide.

```csharp
public class GroupShape : Shape, IGroupShape
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni alır veya ayarlar. Okunur/Yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını alır veya ayarlar. Okunur/Yazılabilir String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | Temel IShape arayüzünü almayı sağlar. Yalnızca okunur [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Bir şeklin siyah-beyaz görüntü modunda nasıl görüneceğini belirten özellik. Okunur/Yazılabilir [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Yalnızca okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan belirli şekil tipleri için null dönebilir. Yalnızca okunur [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Şeklin doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: doldurma özellikleri olmayan belirli şekil tipleri için null dönebilir. Yalnızca okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okunur/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunur [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/Yazılabilir Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi alır veya ayarlar. Okunur/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyi alır veya ayarlar. Okunur/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okunur/Yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin grup içinde olup olmadığını belirler. Yalnızca okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okunur Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | Şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: Grup şekilleri için null döner çünkü çizgi özellikleri yoktur. Yalnızca okunur [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını alır veya ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanın. Okunur/Yazılabilir String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan, slayt kapsamlı benzersiz bir tanımlayıcıyı döndürür ve PowerPoint ya da interop kodunun şekle belgede her yerden güvenilir bir şekilde başvurmasını sağlar. Yalnızca okunur UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil grup içindeyse üst GroupShape nesnesini döndürür. Aksi takdirde null döner. Yalnızca okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döner. Yalnızca okunur [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaytın üst sunumunu döndürür. Yalnızca okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini alır veya ayarlar. Okunur/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını alır veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Okunur/Yazılabilir Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunur [`IGroupShapeLock`](../igroupshapelock). (2 özellik) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | Grup içindeki şekillerin koleksiyonunu döndürür. Yalnızca okunur [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaytını döndürür. Yalnızca okunur [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3B efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3B özellikleri olmayan belirli şekil tipleri için null dönebilir. Yalnızca okunur [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, içsel bir sunum kapsamlı tanımlayıcıyı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak değerlendirilmemelidir. Yalnızca okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol-üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol-üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise öndeki şekli döndürür. Yalnızca okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Henüz yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan alınan şekil). Geçerli şekil devralınmamışsa null döner. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin işlenen içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [Shape](../shape)
* arayüz [IGroupShape](../igroupshape)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->