---
title: Chart
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slaytta grafik bir çizelgeyi temsil eder.
type: docs
weight: 1270
url: /tr/aspose.slides.charts/chart/
---
## Chart sınıfı

Bir slayt üzerindeki grafiksel bir çizelgeyi temsil eder.

```csharp
public class Chart : GraphicalObject, IChart
```

## Özellikler

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni alır veya ayarlar. Okunur/Yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını alır veya ayarlar. Okunur/Yazılabilir String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Temel IFormattedTextContainer arayüzünü almayı sağlar. Sadece Okunur [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Temel IThemeable arayüzünü almayı sağlar. Sadece Okunur [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Çizelge eksenlerine erişim sağlar. Sadece Okunur [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | 3D çizelgenin arka duvarının biçimini değiştirmeye izin veren bir nesneyi döndürür. Sadece Okunur [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Bir şeklin siyah-beyaz görüntü modunda nasıl işleneceğini belirten özellik. Okunur/Yazılabilir [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Bir çizelge ile ilişkili bağlı veya gömülü veri hakkında bilgi döndürür. Sadece Okunur [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Bir çizelgenin veri tablosunu döndürür. Sadece Okunur [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Çizelge başlığını alır veya ayarlar. Sadece Okunur [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlanma noktalarının sayısını döndürür. Sadece Okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verisini döndürür. Sadece Okunur [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Çizelgede boş hücrelerin nasıl çizileceğini alır veya ayarlar. Okunur/Yazılabilir [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan bazı şekil türleri için null dönebilir. Sadece Okunur [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şekil için dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özellikleri olmayan bazı şekil türleri için null dönebilir. Sadece Okunur [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | 3D çizelgenin zemininin biçimini değiştirmeye izin veren bir nesneyi döndürür. Sadece Okunur [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okunur/Yazılabilir [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Sadece Okunur [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Bir çizelgenin veri tablosuna sahip olup olmadığını belirler. Okunur/Yazılabilir Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Bir çizelgenin gösterge tablosuna sahip olup olmadığını belirler. Okunur/Yazılabilir Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Çizelge alanının yuvarlak köşelere sahip olmasını belirtir. Okunur/Yazılabilir Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Bir çizelgenin görünür bir başlığa sahip olup olmadığını belirler. Okunur/Yazılabilir Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/Yazılabilir Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyü alır veya ayarlar. Okunur/Yazılabilir [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Sadece Okunur [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlanan köprüyü alır veya ayarlar. Okunur/Yazılabilir [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Dekoratif olarak işaretle' seçeneğini alır veya ayarlar. Okunur/Yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanmış olup olmadığını belirler. Sadece Okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Sadece Okunur Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Bir çizelge için gösterge tablosunu alır veya ayarlar. Sadece Okunur [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şekil için çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özellikleri olmayan bazı şekil türleri için null dönebilir. Sadece Okunur [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını alır veya ayarlar. Null olmamalıdır. Gerekirse boş string değeri kullanın. Okunur/Yazılabilir String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan ve PowerPoint veya interop kodunun şekle belge içinde her yerden güvenilir şekilde referans vermesini sağlayan slayt kapsamlı benzersiz tanımlayıcıyı döndürür. Sadece Okunur UInt32. Ayrıca bkz. [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döner. Sadece Okunur [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döner. Sadece Okunur [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Bir çizelgenin grafik alanını temsil eder. Sadece Okunur [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Yalnızca görünen hücrelerin çizilip çizilmeyeceğini belirler. Hem görünen hem gizli hücrelerin çizilmesi için false. Okunur/Yazılabilir Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu döndürür. Sadece Okunur [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini alır veya ayarlar. Okunur/Yazılabilir [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını alır veya ayarlar. Pozitif değer saat yönünde döndürmeyi; negatif değer saat yönünün tersine döndürmeyi gösterir. Okunur/Yazılabilir Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Bir çizelgenin 3D dönüşünü döndürür. Sadece Okunur [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Sadece Okunur [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 özellik) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Çizelgenin maksimum üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirtir. Okunur/Yazılabilir Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | 3D çizelgenin yan duvarının biçimini değiştirmeye izin veren bir nesneyi döndürür. Sadece Okunur [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaytını döndürür. Sadece Okunur [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Çizelge stilini alır veya ayarlar. Okunur/Yazılabilir [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Çizelge metin biçimini döndürür. Özellik aşağıdaki türler için uygulanamaz: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Sadece Okunur [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Tema yöneticisini döndürür. Sadece Okunur [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şekil için 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özellikleri olmayan bazı şekil türleri için null dönebilir. Sadece Okunur [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Çizelge tipini alır veya ayarlar. Okunur/Yazılabilir [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, içsel, sunum kapsamlı bir tanımlayıcıyı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı benzersiz anahtar olarak ele alınmamalıdır. Sadece Okunur UInt32. Ayrıca bkz. [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Çizelgenin üzerine çizilen şekilleri belirtir. Sadece Okunur [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, nokta cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Sadece Okunur Int32. |

## Yöntemler

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Hiç yoksa yeni bir yer tutucu ekler ve yer tutucu özelliklerini belirtilen birine ayarlar. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Bu çizelge için etkili bir temayı döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (geçerli şeklin devralındığı düzen ve/veya ana slayttan şekil). Geçerli şekil devralınmamışsa null döner. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. ShapeThumbnailBounds.Shape şekil küçük resmi sınır türü varsayılan olarak kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin işlenen içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Çizelge öğelerinin gerçek değerlerini hesaplar. Gerçek değerler, IActualLayout arayüzünü uygulayan öğelerin konumunu (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) ve gerçek eksen değerlerini (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) içerir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../../aspose.slides/graphicalobject)
* arayüz [IChart](../ichart)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->