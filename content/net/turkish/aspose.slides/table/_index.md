---
title: Table
second_title: Aspose.Sildes for .NET API Referansı
description: Bir slayttaki tabloyu temsil eder.
type: docs
weight: 10860
url: /tr/aspose.slides/table/
---
## Table sınıfı

Bir slayttaki tabloyu temsil eder.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Özellikler

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Şekille ilişkili alternatif metni döndürür veya ayarlar. Okunur/Yazılır String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okunur/Yazılır String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntüleme modunda nasıl render edileceğini belirler. Okunur/Yazılır [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Sütunların koleksiyonunu döndürür. Yalnızca okuma [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okuma Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Yalnızca okuma [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan belirli şekil tipleri için null döndürebilir. Yalnızca okuma [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Tablo için dolgu biçimlendirmesini içeren TableFormat.FillFormat nesnesini döndürür. Yalnızca okuma [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunur/Yazılır Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunur/Yazılır Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/Yazılır [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okuma [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okunur/Yazılır Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/Yazılır Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Çift satırların farklı bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunur/Yazılır Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyü döndürür veya ayarlar. Okunur/Yazılır [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca okuma [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlanan köprüyü döndürür veya ayarlar. Okunur/Yazılır [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ seçeneğini alır veya ayarlar. Okunur/Yazılır Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin grup içinde olup olmadığını belirler. Yalnızca okuma Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okuma Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Belirtilen sütun ve satır indekslerindeki hücreyi döndürür. Yalnızca okuma [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunur/Yazılır Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Tablonun son satırının özel bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunur/Yazılır Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özellikleri olmayan belirli şekil türleri için null döndürebilir. Yalnızca okuma [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Null olmamalıdır. Gerekirse boş string değeri kullanın. Okunur/Yazılır String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekli belgenin herhangi bir yerinden güvenilir şekilde referans almasını sağlayan slayt kapsamlı benzersiz tanımlayıcıyı döndürür. Yalnızca okuma UInt32. Ayrıca bkz. [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil grup içinde ise üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okuma [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Yalnızca okuma [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu döndürür. Yalnızca okuma [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okunur/Yazılır [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Tablonun sağdan sola okuma sırasına sahip olup olmadığını belirler. Okunur/Yazılır Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde dönüşü, negatif değer saat yönünün tersine dönüşü gösterir. Okunur/Yazılır Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Satırların koleksiyonunu döndürür. Yalnızca okuma [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okuma [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 özellik) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaydını döndürür. Yalnızca okuma [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Yerleşik tablo stilini alır veya ayarlar. Okunur/Yazılır [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür. Yalnızca okuma [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özellikleri olmayan belirli şekil tipleri için null döndürebilir. Yalnızca okuma [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış içsel, sunum kapsamlı bir tanımlayıcıyı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak ele alınmamalıdır. Yalnızca okuma UInt32. Ayrıca bkz. [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Çift sütunların farklı bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunur/Yazılır Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okunur/Yazılır Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okunur/Yazılır Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okunur/Yazılır Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okuma Int32. |

## Metotlar

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler, eğer mevcut değilse ve yer tutucu özelliklerini belirtilen bir taneye ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan gelen şekil). Geçerli şekil devralınmadıysa null döndürülür. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape küçük resim sınır türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin render'lanmış içeriğinden hesaplanan görsel sınırlarını alır. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Komşu hücreleri birleştirir. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Tanımlı paragraf biçim özelliklerini tüm tablo hücrelerinin paragraflarına ayarlar. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Tanımlı bölüm biçim özelliklerini tüm tablo hücrelerinin bölümlerine ayarlar. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Tanımlı metin çerçevesi biçim özelliklerini tüm tablo hücrelerinin metin çerçevelerine ayarlar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../graphicalobject)
* arayüz [ITable](../itable)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->