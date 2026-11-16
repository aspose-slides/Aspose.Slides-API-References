---
title: LegacyDiagram
second_title: Aspose.Sildes için .NET API Referansı
description: Legacy diyagram nesnesini temsil eder.
type: docs
weight: 7690
url: /tr/aspose.slides/legacydiagram/
---
## LegacyDiagram sınıfı

Legacy diyagram nesnesini temsil eder.

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## Özellikler

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okunabilir/Yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunabilir/Yazılabilir String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | Temel IGraphicalObject arayüzüne erişim sağlar. Salt okunur [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz gösterim modunda nasıl işleneceğini belirtir.. Okunabilir/Yazılabilir [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlantı noktası sayısını döndürür. Salt okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verisini döndürür. Salt okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Etki biçimi nesnesini döndürür; şekle uygulanan piksel efektlerini içerir. Not: bazı şekil türleri için etkisi olmayan durumlarda null dönebilir. Salt okunur [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Dolgu biçimi nesnesini döndürür; şekil için dolgu biçimlendirme özelliklerini içerir. Not: bazı şekil türleri için dolgu özelliği olmayan durumlarda null dönebilir. Salt okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunabilir/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Salt okunur [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar. Okunabilir/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Salt okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyi döndürür veya ayarlar. Okunabilir/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okunabilir/Yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Salt okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Salt okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Çizgi biçimi nesnesini döndürür; şekil için çizgi biçimlendirme özelliklerini içerir. Not: bazı şekil türleri için çizgi özelliği olmayan durumlarda null dönebilir. Salt okunur [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Şeklin adını döndürür veya ayarlar. Boş olmamalıdır. Gerekirse boş dize kullanılabilir. Okunabilir/Yazılabilir String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin yaşam süresi boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle her yerden güvenilir şekilde başvurmasını sağlayan slayt-kapsamlı benzersiz tanımlayıcısını döndürür. Salt okunur UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döner. Salt okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döner. Salt okunur [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Slaytın üst sunumunu döndürür. Salt okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunabilir/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z-ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Okunabilir/Yazılabilir Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Salt okunur [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 özellik) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Şeklin üst slaytını döndürür. Salt okunur [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat nesnesini döndürür; şekil için 3D etki özelliklerini içerir. Not: bazı şekil türleri için 3D özelliği olmayan durumlarda null dönebilir. Salt okunur [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, içsel, sunum-kapsamlı bir tanımlayıcı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır. Salt okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol-üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol-üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt okunur Int32. |

## Yöntemler

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler, eğer yoksa, ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | Legacy diyagramı düzenlenebilir grup şekline dönüştürür. Oluşturulan GroupShape nesnesi aynı konumda üst grup şekline eklenir. |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | Legacy diyagramı düzenlenebilir SmartArt nesnesine dönüştürür. Oluşturulan SmartArt nesnesi aynı konumda üst grup şekline eklenir. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin kaldıysa alındığı yerleşim ve/veya ana slayttan şekil). Geçerli şekil miras alınmamışsa null döndürülür. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resmi sınırları türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | İşlenen içeriğinden hesaplanan şeklin görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../graphicalobject)
* arayüz [ILegacyDiagram](../ilegacydiagram)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->