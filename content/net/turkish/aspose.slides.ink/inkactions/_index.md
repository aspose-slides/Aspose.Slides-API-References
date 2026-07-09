---
title: InkActions
second_title: Aspose.Sildes for .NET API Referansı
description: Mürekkep eylemlerinin kökünü temsil eder.
type: docs
weight: 7560
url: /tr/aspose.slides.ink/inkactions/
---
## InkActions sınıf

Şekil ile ilişkili mürekkep eylemlerinin kökünü temsil eder.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkilendirilmiş alternatif metni alır veya ayarlar. Okuma/yazma String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkilendirilmiş alternatif metnin başlığını alır veya ayarlar. Okuma/yazma String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirler. Okuma/yazma [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlantı noktalarının sayısını alır. Yalnızca okuma Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini alır. Yalnızca okuma [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini alır. Not: efekt özellikleri olmayan bazı şekil türleri için null dönebilir. Yalnızca okuma [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şeklin doldurma biçimlendirme özelliklerini içeren FillFormat nesnesini alır. Not: doldurma özellikleri olmayan bazı şekil türleri için null dönebilir. Yalnızca okuma [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okuma/yazma [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini alır. Yalnızca okuma [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okuma/yazma Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprü bağlantısını alır veya ayarlar. Okuma/yazma [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü bağlantı yöneticisini alır. Yalnızca okuma [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlanan köprü bağlantısını alır veya ayarlar. Okuma/yazma [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okuma/yazma Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Yalnızca okuma Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okuma Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini alır. Not: çizgi özellikleri olmayan bazı şekil türleri için null dönebilir. Yalnızca okuma [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını alır veya ayarlar. Null olamaz. Gerekirse boş dize kullanılabilir. Okuma/yazma String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan, slayt kapsamlı benzersiz tanımlayıcısını alır; PowerPoint ya da interop kodunun şekle güvenilir şekilde referans vermesini sağlar. Yalnızca okuma UInt32. Ayrıca bakınız [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini alır. Aksi takdirde null döner. Yalnızca okuma [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şeklin yer tutucusunu alır. Yer tutucu yoksa null döner. Yalnızca okuma [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Slaytın üst sunumunu alır. Yalnızca okuma [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Şekil çerçevesinin ham özelliklerini alır veya ayarlar. Okuma/yazma [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını alır veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersine döndürür. Okuma/yazma Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini alır. Yalnızca okuma [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 özellik) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaytını alır. Yalnızca okuma [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini alır. Not: 3D özellikleri olmayan bazı şekil türleri için null dönebilir. Yalnızca okuma [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler ya da diğer kodlar tarafından kullanılmak üzere, sunum kapsamlı iç tanımlayıcıyı alır. Bu değer kullanıcı ya da program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak kullanılmamalıdır. Yalnızca okuma UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, nokta cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar. Okuma/yazma Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar. Okuma/yazma Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z sırasındaki konumunu alır. Shapes[0] z sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okuma Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yer tutucu yoksa yenisini ekler ve yer tutucu özelliklerini belirtilen yere ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığını olduğu yerleşim ya da ana slayttan). Geçerli şekil miras almıyorsa null döner. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. ShapeThumbnailBounds.Shape varsayılan olarak kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmi döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../../aspose.slides/graphicalobject)
* arayüz [IInkActions](../iinkactions)
* ad alanı [Aspose.Slides.Ink](../../aspose.slides.ink)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->