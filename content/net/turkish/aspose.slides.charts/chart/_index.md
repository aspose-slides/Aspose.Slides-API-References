---
title: Chart
second_title: Aspose.Slides for .NET API Referansı
description: Bir slaytta grafik bir çizelgeyi temsil eder.
type: docs
weight: 1260
url: /tr/aspose.slides.charts/chart/
---
## Chart sınıfı

Bir slaytta grafik bir çizelgeyi temsil eder.

```csharp
public class Chart : GraphicalObject, IChart
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni döndürür veya ayarlar. Okuma/Yazma String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını döndürür veya ayarlar. Okuma/Yazma String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Temel IFormattedTextContainer arayüzünü almayı sağlar. Salt Okunur [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Temel IThemeable arayüzünü almayı sağlar. Salt Okunur [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Çizelge eksenlerine erişim sağlar. Salt Okunur [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | 3B çizelgenin arka duvarının biçimini değiştirmeyi sağlayan bir nesneyi döndürür. Salt Okunur [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Bir şeklin siyah-beyaz görüntü modunda nasıl çizileceğini belirten özellik. Okuma/Yazma [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Bir çizelgeyle ilişkili bağlantılı veya gömülü veriler hakkında bilgi döndürür. Salt Okunur [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Bir çizelgenin veri tablosunu döndürür. Salt Okunur [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Bir çizelge başlığını döndürür veya ayarlar. Salt Okunur [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Salt Okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özelleştirilmiş verisini döndürür. Salt Okunur [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Bir çizelgede boş hücrelerin nasıl çizileceğini döndürür veya ayarlar. Okuma/Yazma [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat nesnesini döndürür; bu nesne bir şekle uygulanan piksel etkilerini içerir. Not: etki özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt Okunur [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat nesnesini döndürür; bu nesne bir şeklin doldurma biçim özelliklerini içerir. Not: doldurma özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt Okunur [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | 3B çizelgenin zemininin biçimini değiştirmeyi sağlayan bir nesneyi döndürür. Salt Okunur [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okuma/Yazma [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Salt Okunur [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Bir çizelgenin veri tablosuna sahip olup olmadığını belirler. Okuma/Yazma Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Bir çizelgenin açıklamaya (legend) sahip olup olmadığını belirler. Okuma/Yazma Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Çizelge alanının yuvarlak köşelere sahip olmasını belirtir. Okuma/Yazma Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Bir çizelgenin görünür başlığa sahip olup olmadığını belirler. Okuma/Yazma Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okuma/Yazma Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlı köprüyü döndürür veya ayarlar. Okuma/Yazma [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Salt Okunur [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlı köprüyü döndürür veya ayarlar. Okuma/Yazma [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okuma/Yazma Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanmış olup olmadığını belirler. Salt Okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Salt Okunur Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Bir çizelge için açıklamayı döndürür veya ayarlar. Salt Okunur [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat nesnesini döndürür; bu nesne bir şeklin çizgi biçim özelliklerini içerir. Not: çizgi özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt Okunur [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını döndürür veya ayarlar. Null olamaz. Gerekirse boş dizgi kullanın. Okuma/Yazma String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Bir slayda özgü benzersiz tanımlayıcıyı döndürür; bu tanımlayıcı şeklin ömrü boyunca sabittir ve PowerPoint ya da interop kodunun şekle her yerden güvenilir şekilde başvurmasını sağlar. Salt Okunur UInt32. Ayrıca bakınız [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döner. Salt Okunur [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şeklin yer tutucusunu döndürür. Şeklin yer tutucusu yoksa null döner. Salt Okunur [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Bir çizelgenin grafik alanını temsil eder. Salt Okunur [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Sadece görünür hücrelerin çizilip çizilmeyeceğini belirler. Hem görünür hem gizli hücrelerin çizilmesi için false. Okuma/Yazma Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu döndürür. Salt Okunur [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini döndürür veya ayarlar. Okuma/Yazma [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını döndürür veya ayarlar. Pozitif değer saat yönünde döndürmeyi, negatif değer saat yönünün tersine döndürmeyi gösterir. Okuma/Yazma Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Bir çizelgenin 3B dönüşünü döndürür. Salt Okunur [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Salt Okunur [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 özellik) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Çizelgenin maksimum değerinin üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirtir. Okuma/Yazma Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | 3B çizelgenin yan duvarının biçimini değiştirmeyi sağlayan bir nesneyi döndürür. Salt Okunur [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaydını döndürür. Salt Okunur [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Çizelge stilini döndürür veya ayarlar. Okuma/Yazma [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Çizelge metin biçimini döndürür. Özellik aşağıdaki türler için uygulanamaz: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Salt Okunur [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Tema yöneticisini döndürür. Salt Okunur [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat nesnesini döndürür; bu nesne bir şeklin 3B etki özelliklerini içerir. Not: 3B özellikleri olmayan bazı şekil türleri için null döndürebilir. Salt Okunur [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Çizelge türünü döndürür veya ayarlar. Okuma/Yazma [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunuma özgü dahili bir tanımlayıcı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz bir anahtar olarak ele alınmamalıdır. Salt Okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Çizelgenin üstünde çizilen şekilleri belirtir. Salt Okunur [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Salt Okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler (eğer yoksa) ve yer tutucu özelliklerini belirtilen bir taneye ayarlar. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Bu çizelge için etkili bir temayı döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan gelen şekil). Geçerli şekil miras almıyorsa null döner. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape küçük resim sınırları tipi kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Çizelge öğelerinin gerçek değerlerini hesaplar. Gerçek değerler, IActualLayout arabirimini uygulayan öğelerin konumunu (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) ve gerçek eksen değerlerini (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) içerir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../../aspose.slides/graphicalobject)
* arayüz [IChart](../ichart)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->