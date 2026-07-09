---
title: ChartSeries
second_title: Aspose.Sildes .NET API Referansı
description: Bir grafik serisini temsil eder.
type: docs
weight: 1440
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
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 3-D çubuk grafiğinin bir serisinin şeklini belirtir. Bu özelliğin değerinin değiştirilmesi, serinin Type'ının otomatik olarak değişmesine neden olabilir. Okunur/Yazılabilir [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Baloncuk boyutu değerlerinin baloncuk grafiğinde nasıl temsil edildiğini belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir – ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeRepresentation okunur/yazılabilir özelliğini kullanın. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Baloncuk grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir – ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeScale okunur/yazılabilir özelliğini kullanın. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Üst grafiği döndürür. Yalnızca okunur [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Bu serinin veri nokta koleksiyonunu döndürür. Yalnızca okunur [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Donut grafiğinde deliğin boyutunu (grafik alanının %10 ile %90 arasında) belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir – ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.DoughnutHoleSize okunur/yazılabilir özelliğini kullanın. Yalnızca okunur Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Serinin X yönündeki ErrorBars'larını temsil eder. X yönündeki ErrorBars, area, bar, scatter ve bubble tipindeki seriler için mevcuttur. Diğer grafik tiplerinde bu özellik null döndürür (3D grafikler dahil). Özel değerlerde, veri noktaları koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliği ile değeri belirlemek için kullanın. Yalnızca okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Serinin Y yönündeki ErrorBars'larını temsil eder. Y yönündeki ErrorBars, area, bar, line, scatter ve bubble tipindeki seriler için mevcuttur. Diğer grafik tiplerinde bu özellik null döndürür (3D grafikler dahil). Özel değerlerde, veri noktaları koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliği ile değeri belirlemek için kullanın. Yalnızca okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Bir dilim açılmış pie diliminin merkezden uzaklığı, pie çapının yüzdesi olarak ifade edilir. Okunur/Yazılabilir Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | İlk pie veya doughnut diliminin açısını derece cinsinden belirtir (yukarıdan saat yönünde, 0 ile 360 derece arası). Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir – ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.FirstSliceAngle okunur/yazılabilir özelliğini kullanın. Yalnızca okunur UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Serinin formatını döndürür. Yalnızca okunur [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Bir 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir – ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapDepth okunur/yazılabilir özelliğini kullanın. Yalnızca okunur Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Bar veya sütun kümeleri arasındaki boşluğu, bar veya sütun genişliğinin yüzdesi olarak belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir – ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapWidth okunur/yazılabilir özelliğini kullanın. Yalnızca okunur Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Bu serinin ve aynı serideki diğer serilerin seriler çizgileri olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir – ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.HasSeriesLines okunur/yazılabilir özelliğini kullanın. Seriler çizgilerinin biçimlendirmesi için ParentSeriesGroup.SeriesLinesFormat özelliğini kullanın. Yalnızca okunur Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Line- veya Stok-grafiğinde up/down barların olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir – ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.UpDownBars.HasUpDownBars okunur/yazılabilir özelliğini kullanın. Up/down barların biçimlendirmesi için ParentSeriesGroup.UpDownBars özelliğini kullanın. Yalnızca okunur Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Seri için ters katı rengi belirtir. Renk ayarını uygulamak için seri formatının FillType'ını FillType.Solid olarak ayarlayın. Okunur/Yazılabilir [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Değer negatif ise bar, sütun veya baloncuk serisinin renklerini tersine çevirir. Okunur/Yazılabilir Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir – ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.IsColorVaried okunur/yazılabilir özelliğini kullanın. Yalnızca okunur Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Serinin Etiketlerini döndürür. Yalnızca okunur [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | İşaretçi. Yalnızca okunur [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Seri adını döndürür. Yalnızca okunur [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Okunur/Yazılabilir String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Okunur/Yazılabilir String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Okunur/Yazılabilir String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Okunur/Yazılabilir String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Serinin sırasını döndürür. Okunur/Yazılabilir Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 2-D grafiklerde çubuk ve sütunların ne kadar üst üste bindiğini yüzde olarak belirtir ( -%100 ile %100 arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir. İlgili grup özelliğinin bir yansısıdır ve bu nedenle yalnızca okunur. Değeri değiştirmek için !:ParentSeriesGroup.Overlap okunur/yazılabilir özelliğini kullanın. Yalnızca okunur SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Üst kategori etiketlerinin düzenini temsil eder. Yalnızca Treemap grafiklerinde uygulanır. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Yalnızca okunur [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | İkinci dilim veya barın bir pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının olacağını belirlemek için kullanılır. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir - ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okunur/yazılabilir özelliğini kullanın. Yalnızca okunur [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Özel bölme bilgisi, bir pie-of-pie veya bar-of-pie grafiğinde özel bölme ile ikinci dilim veya bar için çizilecek veri noktalarını içerir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir - ilgili grup özelliğinin bir yansısıdır. Yalnızca okunur [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | İkinci dilim veya barın bir pie-of-pie veya bar-of-pie grafiğinde hangi veri noktalarının olacağını belirlemek için kullanılan değeri belirtir. PieSplitBy özelliği ile birlikte kullanılır. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir - ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Değeri değiştirmek için ParentSeriesGroup.PieSplitPosition okunur/yazılabilir özelliğini kullanın. Yalnızca okunur Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Bu serinin ikincil eksende çizilip çizilmediğini gösterir. Okunur/Yazılabilir Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Çeyrek yöntemi temsil eder. Yalnızca BoxAndWhisker grafiklerinde uygulanır. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Bu seriyle ilgili gösterge girişi temsil eder. Yalnızca okunur [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Pie-of-pie veya bar-of-pie grafiğinin ikinci dilim veya barının boyutunu, ilk pie'nin boyutunun yüzdesi olarak belirtir ( %5 ile %200 arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine aittir - ilgili grup özelliğinin bir yansısıdır. Bu nedenle bu özellik yalnızca okunur. Değeri değiştirmek için ParentSeriesGroup.SecondPieSize okunur/yazılabilir özelliğini kullanın. Yalnızca okunur UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Bağlayıcı çizgileri temsil eder. Yalnızca Waterfall grafiklerinde uygulanır. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa true döner. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/Yazılabilir Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Ortalama çizgiyi temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa true döner. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/Yazılabilir Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama işaretçileri gösteriliyorsa true döner. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/Yazılabilir Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Uç değer noktalarını temsil eder. BoxAndWhisker grafiğinde uç değer noktaları gösteriliyorsa true döner. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunur/Yazılabilir Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Eğri düzleştirmeyi temsil eder. Çizgi grafiği veya dağınık grafik, çizgilerle bağlanmış, için eğri düzleştirme açık ise true olur. Yalnızca çizgi ve dağınık bağlanmış grafiklerde uygulanır. Okunur/Yazılabilir Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Seri trend çizgileri koleksiyonunu döndürür. Yalnızca okunur [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Bu serinin tipini döndürür. Okunur/Yazılabilir [`ChartType`](../charttype). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Serinin indeksine ve grafik stiline göre otomatik bir renk döndürür. FillType NotDefined olduğunda bu renk varsayılan olarak kullanılır. |

### Ayrıca Bakınız

* arayüz [IChartSeries](../ichartseries)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->