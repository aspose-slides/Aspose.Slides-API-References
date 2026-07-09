---
title: GraphicalObject
second_title: Aspose.Sildes için .NET API Referansı
description: Soyut grafiksel nesneyi temsil eder.
type: docs
weight: 5070
url: /tr/aspose.slides/graphicalobject/
---
## GraphicalObject sınıfı

Soyut grafiksel nesneyi temsil eder.

```csharp
public class GraphicalObject : Shape, IGraphicalObject
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okuma/yazma String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okuma/yazma String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirtir. Okuma/yazma [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Salt-okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Salt-okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat nesnesini döndürür; bu nesne bir şeye uygulanan piksel efektlerini içerir. Not: efekt özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Salt-okunur [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat nesnesini döndürür; bu nesne bir şekil için dolgu biçimlendirme özelliklerini içerir. Not: dolgu özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Salt-okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okuma/yazma [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Salt-okunur [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini (puan cinsinden) alır veya ayarlar. Okuma/yazma Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okuma/yazma Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi döndürür veya ayarlar. Okuma/yazma [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Salt-okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlanan köprüyi döndürür veya ayarlar. Okuma/yazma [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okuma/yazma Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplandırılıp gruplandırılmadığını belirler. Salt-okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Salt-okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat nesnesini döndürür; bu nesne bir şekil için çizgi biçimlendirme özelliklerini içerir. Not: çizgi özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Salt-okunur [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanılabilir. Okuma/yazma String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint veya interop kodunun şekli belgede herhangi bir yerden güvenilir bir şekilde referans almasını sağlayan slayt kapsamlı benzersiz tanımlayıcısını döndürür. Salt-okunur UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplandırılmışsa ebeveyn GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Salt-okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döndürür. Salt-okunur [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın ebeveyn sunumunu döndürür. Salt-okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okuma/yazma [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde rotasyonu, negatif değer saat yönünün tersinde rotasyonu gösterir. Okuma/yazma Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Salt-okunur [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 özellik) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin ebeveyn slaydını döndürür. Salt-okunur [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat nesnesini döndürür; bu nesne bir şekil için 3D efekt özelliklerini içerir. Not: 3D özelliklerine sahip olmayan belirli şekil türleri için null döndürebilir. Salt-okunur [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış dahili, sunum kapsamlı bir tanımlayıcıyı döndürür. Çünkü bu değer kullanıcı tarafından veya programlı olarak yeniden atanabilir, kalıcı bir benzersiz anahtar olarak değerlendirilmemelidir. Salt-okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini (puan cinsinden) alır veya ayarlar. Okuma/yazma Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını (puan cinsinden) alır veya ayarlar. Okuma/yazma Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını (puan cinsinden) alır veya ayarlar. Okuma/yazma Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt-okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler (var yoksa) ve yer tutucu özelliklerini belirtilen bir taneye ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin kalıtıldığı düzen veya/veya ana slayttan gelen şekil). Geçerli şekil kalıtılmadıysa null döndürülür. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resim sınırları türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Bakınız

* sınıf [Shape](../shape)
* arayüz [IGraphicalObject](../igraphicalobject)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->