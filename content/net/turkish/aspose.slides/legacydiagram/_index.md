---
title: LegacyDiagram
second_title: Aspose.Sildes için .NET API Referansı
description: Legacy diagram nesnesini temsil eder.
type: docs
weight: 7650
url: /tr/aspose.slides/legacydiagram/
---
## LegacyDiagram sınıfı

Legacy diagram nesnesini temsil eder.

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni alır veya ayarlar. Okuma/yazma String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını alır veya ayarlar. Okuma/yazma String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | Temel IGraphicalObject arayüzünü almayı sağlar. Yalnızca okuma [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okuma/yazma [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını alır. Yalnızca okuma Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini alır. Yalnızca okuma [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini alır. Not: efekt özelliklerine sahip olmayan belirli şekil türleri için null dönebilir. Yalnızca okuma [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini alır. Not: dolgu özelliklerine sahip olmayan belirli şekil türleri için null dönebilir. Yalnızca okuma [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okuma/yazma [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini alır. Yalnızca okuma [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okuma/yazma Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi alır veya ayarlar. Okuma/yazma [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini alır. Yalnızca okuma [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyi alır veya ayarlar. Okuma/yazma [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' seçeneğini alır veya ayarlar. Okuma/yazma Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanmış olup olmadığını belirler. Yalnızca okuma Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okuma Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini alır. Not: çizgi özelliklerine sahip olmayan belirli şekil türleri için null dönebilir. Yalnızca okuma [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını alır veya ayarlar. Boş olmamalıdır. Gerekirse boş dize değeri kullanın. Okuma/yazma String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint veya interop kodunun belge içinde herhangi bir yerden şekle güvenilir bir şekilde başvurmasını sağlayan slayt kapsamlı benzersiz tanımlayıcıyı alır. Yalnızca okuma UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini alır. Aksi takdirde null döner. Yalnızca okuma [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şeklin yer tutucusunu alır. Şeklin yer tutucusu yoksa null döner. Yalnızca okuma [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu alır. Yalnızca okuma [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini alır veya ayarlar. Okuma/yazma [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını alır veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer ise saat yönünün tersine döndürmeyi gösterir. Okuma/yazma Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini alır. Yalnızca okuma [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 özellik) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaytını alır. Yalnızca okuma [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini alır. Not: 3D özelliklerine sahip olmayan belirli şekil türleri için null dönebilir. Yalnızca okuma [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcıyı alır. Bu değer kullanıcı veya program tarafından yeniden atanabileceğinden, kalıcı bir benzersiz anahtar olarak değerlendirilmemelidir. Yalnızca okuma UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okuma/yazma Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu alır. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okuma Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler (eğer mevcut değilse) ve yer tutucu özelliklerini belirtilen yere ayarlar. |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | Legacy diyagramı düzenlenebilir grup şekline dönüştürür. Oluşturulan GroupShape nesnesi aynı konumda üst grup şekline eklenir. |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | Legacy diyagramı düzenlenebilir SmartArt nesnesine dönüştürür. Oluşturulan SmartArt nesnesi aynı konumda üst grup şekline eklenir. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı yerleşim ve/veya ana slayttan gelen şekil). Geçerli şekil miras alınmamışsa null döndürülür. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../graphicalobject)
* arayüz [ILegacyDiagram](../ilegacydiagram)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->