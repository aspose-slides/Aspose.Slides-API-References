---
title: Shape
second_title: Aspose.Slides için .NET API Referansı
description: Bir slayttaki şekli temsil eder.
type: docs
weight: 9850
url: /tr/aspose.slides/shape/
---
## Shape sınıfı

Represents a shape on a slide.

```csharp
public class Shape : IShape
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okuma/Yazma String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okuma/Yazma String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Bu özellik, bir şeklin siyah-beyaz görüntü modunda nasıl renderleneceğini belirtir. Okuma/Yazma [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Salt-okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Salt-okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Salt-okunur [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şeklin doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: doldurma özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Salt-okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okuma/Yazma [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini (puan cinsinden) alır veya ayarlar. Okuma/Yazma Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okuma/Yazma Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlı köprüyi döndürür veya ayarlar. Okuma/Yazma [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Salt-okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlı köprüyi döndürür veya ayarlar. Okuma/Yazma [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okuma/Yazma Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Salt-okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Salt-okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Salt-okunur [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş string değeri kullanın. Okuma/Yazma String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint veya interop kodunun şekle belgede herhangi bir yerden güvenle başvurmasını sağlayan slayt kapsamında benzersiz bir tanımlayıcı döndürür. Salt-okunur UInt32. Ayrıca bakınız [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa ana GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Salt-okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Salt-okunur [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaytın ana sunumunu döndürür. Salt-okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Kaynak şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okuma/Yazma [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Okuma/Yazma Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Şeklin kilitlerini döndürür. Salt-okunur [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin ana slaytını döndürür. Salt-okunur [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Salt-okunur [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya başka kodlar tarafından kullanılmak üzere sunum kapsamında dahili bir tanımlayıcı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır. Salt-okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini (puan cinsinden) alır veya ayarlar. Okuma/Yazma Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını (puan cinsinden) alır veya ayarlar. Okuma/Yazma Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını (puan cinsinden) alır veya ayarlar. Okuma/Yazma Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt-okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler eğer yoksa ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekil döndürür (düzen ve/veya ana slayttan gelen ve mevcut şeklin miras aldığı şekil). Mevcut şekil miras alınmamışsa null döndürülür. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | Şeklin küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resim sınır türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Şeklin küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* arayüz [IShape](../ishape)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->