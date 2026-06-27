---
title: Chart
second_title: Aspose.Sildes for .NET API Referansı
description: Bir slaytta grafik bir çizelgeyi temsil eder.
type: docs
weight: 1240
url: /tr/aspose.slides.charts/chart/
---
## Chart sınıfı

Bir slaytta bulunan grafik çizelgeyi temsil eder.

```csharp
public class Chart : GraphicalObject, IChart
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Şekille ilişkilendirilmiş alternatif metni alır veya ayarlar. Okuma/Yazma String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Şekille ilişkilendirilmiş alternatif metnin başlığını alır veya ayarlar. Okuma/Yazma String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Temel IFormattedTextContainer arayüzünü almayı sağlar. Yalnızca okuma [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Temel IThemeable arayüzünü almayı sağlar. Yalnızca okuma [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Çizelge eksenlerine erişim sağlar. Yalnızca okuma [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | 3B çizelgenin arka duvarının biçimini değiştirmeyi sağlayan bir nesne döndürür. Yalnızca okuma [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Bir şeklin siyah-beyaz gösterim modunda nasıl render edileceğini belirten özellik. Okuma/Yazma [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Bir çizelgeyle ilişkilendirilmiş bağlı veya gömülü veri hakkında bilgi döndürür. Yalnızca okuma [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Bir çizelgenin veri tablosunu döndürür. Yalnızca okuma [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Çizelge başlığını alır veya ayarlar. Yalnızca okuma [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şekildeki bağlantı noktalarının sayısını döndürür. Yalnızca okuma Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verisini döndürür. Yalnızca okuma [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Çizelgede boş hücrelerin nasıl çizileceğini alır veya ayarlar. Okuma/Yazma [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanan piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özellikleri olmayan bazı şekil türleri için null dönebilir. Yalnızca okuma [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özellikleri olmayan bazı şekil türleri için null dönebilir. Yalnızca okuma [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | 3B bir çizelgenin tabanının biçimini değiştirmeyi sağlayan bir nesneyi döndürür. Yalnızca okuma [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okuma/Yazma [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okuma [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Bir çizelgenin veri tablosuna sahip olup olmadığını belirler. Okuma/Yazma Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Bir çizelgenin lejandına sahip olup olmadığını belirler. Okuma/Yazma Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Çizelge alanının yuvarlak köşelere sahip olmasını belirler. Okuma/Yazma Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Bir çizelgenin görülebilir başlığı olup olmadığını belirler. Okuma/Yazma Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okuma/Yazma Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklaması için tanımlanan köprüyi alır veya ayarlar. Okuma/Yazma [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca okuma [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerine gelindiğinde tanımlanan köprüyü alır veya ayarlar. Okuma/Yazma [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar. Okuma/Yazma Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Yalnızca okuma Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca okuma Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Bir çizelge için lejandı alır veya ayarlar. Yalnızca okuma [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özellikleri olmayan bazı şekil türleri için null dönebilir. Yalnızca okuma [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Bir şeklin adını alır veya ayarlar. Boş olmamalıdır. Gerekirse boş dize değeri kullanın. Okuma/Yazma String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şeklin ömrü boyunca sabit kalan, slayt kapsamlı benzersiz bir tanımlayıcı döndürür ve PowerPoint veya interop kodunun şekle belgede herhangi bir yerden güvenilir şekilde başvurmasını sağlar. Yalnızca okuma UInt32. Ayrıca bakınız [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döner. Yalnızca okuma [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Bir şekil için yer tutucuyu döndürür. Şeklin yer tutucusu yoksa null döner. Yalnızca okuma [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Bir çizelgenin grafik alanını temsil eder. Yalnızca okuma [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Yalnızca görünen hücrelerin çizilip çizilmeyeceğini belirler. Hem görünen hem gizli hücrelerin çizilmesi için false. Okuma/Yazma Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Bir slaydın üst sunumunu döndürür. Yalnızca okuma [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini alır veya ayarlar. Okuma/Yazma [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z ekseni etrafında döndürüldüğü derece sayısını alır veya ayarlar. Pozitif değer saat yönünde dönüşü, negatif değer saat yönünün tersine dönüşü gösterir. Okuma/Yazma Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Bir çizelgenin 3B dönüşünü döndürür. Yalnızca okuma [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca okuma [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 özellik) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Çizelgenin maksimumu üzerindeki veri etiketlerinin gösterilip gösterilmeyeceğini belirler. Okuma/Yazma Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | 3B bir çizelgenin yan duvarının biçimini değiştirmeyi sağlayan bir nesneyi döndürür. Yalnızca okuma [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Bir şeklin üst slaydını döndürür. Yalnızca okuma [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Çizelge stilini alır veya ayarlar. Okuma/Yazma [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Çizelge metin biçimini döndürür. Özellik aşağıdaki türler için geçerli değildir: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Yalnızca okuma [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Tema yöneticisini döndürür. Yalnızca okuma [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Bir şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özellikleri olmayan bazı şekil türleri için null dönebilir. Yalnızca okuma [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Çizelge tipini alır veya ayarlar. Okuma/Yazma [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere tasarlanmış, içsel bir sunum kapsamlı tanımlayıcı döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak kullanılmamalıdır. Yalnızca okuma UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Çizelgenin üzerinde çizilen şekilleri belirtir. Yalnızca okuma [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol-üst köşesinin x koordinatını, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol-üst köşesinin y koordinatını, puan cinsinden alır veya ayarlar. Okuma/Yazma Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Bir şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli döndürür. Yalnızca okuma Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Yeni bir yer tutucu ekler (eğer yoksa) ve yer tutucu özelliklerini belirtilen bir taneye ayarlar. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Bu çizelge için etkili bir temayı döndürür. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir yer tutucu şekli döndürür (düzen ve/veya ana slayttan alınan şekil). Geçerli şekil miras alınmamışsa null döner. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape şekil küçük resim sınırlama türü kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin render edilmiş içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin bir yer tutucu olmadığını tanımlar. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Çizelge öğelerinin gerçek değerlerini hesaplar. Gerçek değerler IActualLayout arayüzünü uygulayan öğelerin konumları (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) ve gerçek eksen değerlerini (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) içerir. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Ayrıca Bakınız

* sınıf [GraphicalObject](../../aspose.slides/graphicalobject)
* arayüz [IChart](../ichart)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->