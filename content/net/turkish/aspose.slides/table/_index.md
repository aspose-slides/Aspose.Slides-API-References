---
title: Table
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slayttaki tabloyu temsil eder.
type: docs
weight: 10880
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
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Özellik, bir şeklin siyah-beyaz görüntü modunda nasıl işleneceğini belirtir. Okunabilir/Yazılabilir [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Sütun koleksiyonunu döndürür. Yalnızca okunabilir [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlantı noktalarının sayısını döndürür. Yalnızca okunabilir Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Yalnızca okunabilir [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özelliği olmayan bazı şekil türleri için null döndürebilir. Yalnızca okunabilir [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Tablo için doldurma biçimlendirmesini içeren TableFormat.FillFormat nesnesini döndürür. Yalnızca okunabilir [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Bir tablonun ilk sütununun özel bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunabilir/Yazılabilir Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Bir tablonun ilk satırının özel bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunabilir/Yazılabilir Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okunabilir/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunabilir [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini (puan cinsinden) alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Çift satırların farklı bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunabilir/Yazılabilir Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyü alır veya ayarlar. Okunabilir/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca okunabilir [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine geldiğinde tanımlanan köprüyü alır veya ayarlar. Okunabilir/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif işaretle' seçeneğini alır veya ayarlar. Okunabilir/Yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Yalnızca okunabilir Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okunabilir Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Belirtilen sütun ve satır indislerindeki hücreyi döndürür. Yalnızca okunabilir [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Bir tablonun son sütununun özel bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunabilir/Yazılabilir Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Bir tablonun son satırının özel bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunabilir/Yazılabilir Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özelliği olmayan bazı şekil türleri için null döndürebilir. Yalnızca okunabilir [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Şeklin adını alır veya ayarlar. Null olmamalıdır. Gerekirse boş dize değeri kullanılabilir. Okunabilir/Yazılabilir String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint ya da interop kodunun şekle belge içinde her yerden güvenilir bir şekilde başvurmasını sağlayan slayt ölçeğinde benzersiz bir tanımlayıcı döndürür. Yalnızca okunabilir UInt32. Ayrıca [`UniqueId`](../shape/uniqueid) bakın. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döndürür. Yalnızca okunabilir [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döndürür. Yalnızca okunabilir [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu döndürür. Yalnızca okunabilir [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini alır veya ayarlar. Okunabilir/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Tablonun sağdan sola okuma düzenine sahip olup olmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürülmüş olduğu derece sayısını alır veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Okunabilir/Yazılabilir Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Satır koleksiyonunu döndürür. Yalnızca okunabilir [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okunabilir [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 özellik) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaydını döndürür. Yalnızca okunabilir [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Yerleşik tablo stilini alır veya ayarlar. Okunabilir/Yazılabilir [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Bu tablo için biçimlendirme özelliklerini içeren TableFormat nesnesini döndürür. Yalnızca okunabilir [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özelliği olmayan bazı şekil türleri için null döndürebilir. Yalnızca okunabilir [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, sunuma özgü dahili bir tanımlayıcı döndürür. Bu değer kullanıcı ya da program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır. Yalnızca okunabilir UInt32. Ayrıca [`OfficeInteropShapeId`](../shape/officeinteropshapeid) bakın. |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Çift sütunların farklı bir biçimlendirme ile çizilip çizilmeyeceğini belirler. Okunabilir/Yazılabilir Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini (puan cinsinden) alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını (puan cinsinden) alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını (puan cinsinden) alır veya ayarlar. Okunabilir/Yazılabilir Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının en arkasındaki şekli, Shapes[Shapes.Count - 1] ise en öndeki şekli döndürür. Yalnızca okunabilir Int32. |

## Yöntemler

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu yoksa ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan şekil). Geçerli şekil miras alınmamışsa null döndürür. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük önizlemesini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük önizleme sınırlama türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük önizlemesini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin işlenmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Komşu hücreleri birleştirir. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Tanımlanan paragraf biçim özelliklerini tüm tablo hücrelerinin paragraflarına uygular. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Tanımlanan bölüm biçim özelliklerini tüm tablo hücrelerinin bölümlerine uygular. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Tanımlanan metin çerçevesi biçim özelliklerini tüm tablo hücrelerinin metin çerçevelerine uygular. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../graphicalobject)
* arayüz [ITable](../itable)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->