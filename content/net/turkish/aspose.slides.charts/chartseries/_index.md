---
title: ChartSeries
second_title: Aspose.Sildes .NET API Referansı
description: Bir grafik serisini temsil eder.
type: docs
weight: 1450
url: /tr/aspose.slides.charts/chartseries/
---
## ChartSeries sınıfı

Bir grafik serisini temsil eder.

```csharp
public class ChartSeries : IChartSeries
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 3-D çubuk grafiğinin bir serisinin şeklini belirler. Bu özelliğin değerinin değiştirilmesi, serinin Type’ının otomatik olarak değişmesine neden olabilir. Okunur/Yazılabilir [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl gösterileceğini belirler. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeRepresentation okunur/yazılabilir özelliğini kullanın. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Baloncuk grafiği için ölçek faktörünü belirler (varsayılan boyutun %0 ile %300 arasında olabilir). Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeScale okunur/yazılabilir özelliğini kullanın. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Üst grafiği döndürür. Yalnızca okunur [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Bu serinin veri noktaları koleksiyonunu döndürür. Yalnızca okunur [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Halkanın (donut) grafiğindeki deliğin boyutunu belirler (çizim alanının boyutunun %10 ile %90 arasında olabilir). Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.DoughnutHoleSize okunur/yazılabilir özelliğini kullanın. Yalnızca okunur Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | X yönündeki serinin ErrorBars nesnesini temsil eder. X yönündeki ErrorBars, alan, çubuk, dağılım ve baloncuk tipindeki seriler için kullanılabilir. Diğer grafik tipleri için bu özellik null döndürür (3D grafikler dahil). Özel değerlerde değeri belirlemek için DataPoints koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliği ile kullanın. Yalnızca okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Y yönündeki serinin ErrorBars nesnesini temsil eder. Y yönündeki ErrorBars, alan, çubuk, çizgi, dağılım ve baloncuk tipindeki seriler için kullanılabilir. Diğer grafik tipleri için bu özellik null döndürür (3D grafikler dahil). Özel değerlerde değeri belirlemek için DataPoints koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliği ile kullanın. Yalnızca okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Açık bir dilimin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzdesi olarak ifade edilir. Okunur/Yazılabilir Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | İlk pasta veya halka diliminin açısını derece cinsinden (yukarıdan saat yönünde, 0 ile 360 derece arası) belirler. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.FirstSliceAngle okunur/yazılabilir özelliğini kullanın. Yalnızca okunur UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Serinin biçimini döndürür. Yalnızca okunur [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapDepth okunur/yazılabilir özelliğini kullanın. Yalnızca okunur Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak belirler. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapWidth okunur/yazılabilir özelliğini kullanın. Yalnızca okunur Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Bu seri ve ilişkili seriler için seri çizgilerinin olup olmadığını belirler. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.HasSeriesLines okunur/yazılabilir özelliğini kullanın. Seri çizgilerini biçimlendirmek için ParentSeriesGroup.SeriesLinesFormat özelliğini kullanın. Yalnızca okunur Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Çizgi veya hisse grafiğinin yukarı/aşağı çubuklarının olup olmadığını belirler. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.UpDownBars.HasUpDownBars okunur/yazılabilir özelliğini kullanın. Yukarı/aşağı çubukları biçimlendirmek için ParentSeriesGroup.UpDownBars özelliğini kullanın. Yalnızca okunur Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Seri için ters katı rengi belirtir. Renk ayarını uygulamak için seri formatının FillType özelliğini FillType.Solid olarak ayarlayın. Okunur/Yazılabilir [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Bar, sütun veya baloncuk serisinin değeri negatifse renklerini tersine çevireceğini belirtir. Okunur/Yazılabilir Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Serideki her veri işaretleyicisinin farklı bir renge sahip olacağını belirtir. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.IsColorVaried okunur/yazılabilir özelliğini kullanın. Yalnızca okunur Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Bir serinin Etiketlerini döndürür. Yalnızca okunur [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | İşaretleyici. Yalnızca okunur [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Seri adını döndürür. Yalnızca okunur [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Okunur/Yazılabilir String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Okunur/Yazılabilir String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Okunur/Yazılabilir String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Okunur/Yazılabilir String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Bir serinin sırasını döndürür. Okunur/Yazılabilir Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 2D grafiklerde çubuk ve sütunların yüzde olarak ne kadar üst üste geldiğini (-%100 ile %100 arasında) belirtir. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir. Üst seriler grubundaki ilgili özelliğin bir yansımasıdır ve bu nedenle bu özellik yalnızca okunur. Değeri değiştirmek için !:ParentSeriesGroup.Overlap okunur/yazılabilir özelliğini kullanın. Yalnızca okunur SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Üst kategori etiketlerinin düzenini temsil eder. Yalnızca Treemap grafiklerinde uygulanır. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Yalnızca okunur [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğun hangi veri noktalarından oluşacağını belirlemenin yolunu belirtir. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okunur/yazılabilir özelliğini kullanın. Yalnızca okunur [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Özel bölme bilgisi, özel bölmeli bir pie-of-pie veya bar-of-pie grafiği için. İkinci pasta ya da çubukta çizilecek veri noktalarını içerir. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Yalnızca okunur [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğun hangi veri noktalarından oluşacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.PieSplitPosition okunur/yazılabilir özelliğini kullanın. Yalnızca okunur Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Bu serinin ikincil eksende çizilip çizilmediğini gösterir. Okunur/Yazılabilir Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Çeyrek yöntemi temsil eder. Yalnızca BoxAndWhisker grafiklerinde uygulanır. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Bu seriyle ilişkili lejand girdisini temsil eder. Yalnızca okunur [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğun boyutunu, ilk pastanın boyutuna göre yüzde olarak belirtir ( %5 ile %200 arasında olabilir). Bu özellik sadece bu seriye değil, üst seriler grubunun tüm serilerine de aittir — ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.SecondPieSize okunur/yazılabilir özelliğini kullanın. Yalnızca okunur UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Bağlayıcı hatları temsil eder. Yalnızca Waterfall grafiklerinde uygulanır. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa True olur. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/Yazılabilir Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Ortalama çizgiyi temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa True olur. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/Yazılabilir Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Ortalama işaretçileri temsil eder. BoxAndWhisker grafiğinde ortalama işaretçileri gösteriliyorsa True olur. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/Yazılabilir Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Uç değer (outlier) noktalarını temsil eder. BoxAndWhisker grafiğinde uç değer noktaları gösteriliyorsa True olur. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/Yazılabilir Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Eğri yumuşatmayı temsil eder. Çizgi grafiği veya dağılım grafiğinde eğri yumuşatma açıksa True olur. Yalnızca çizgi ve çizgiyle bağlanmış dağılım grafiklerinde uygulanır. Okunur/Yazılabilir Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Seri eğilim çizgileri koleksiyonu. Yalnızca okunur [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Bu serinin tipini döndürür. Okunur/Yazılabilir [`ChartType`](../charttype). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Seri indeksine ve grafik stiline göre serinin otomatik bir rengini döndürür. FillType NotDefined olduğunda bu renk varsayılan olarak kullanılır. |

### Ayrıca Bakınız

* arayüz [IChartSeries](../ichartseries)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->