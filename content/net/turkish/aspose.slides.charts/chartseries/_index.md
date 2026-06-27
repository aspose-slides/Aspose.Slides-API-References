---
title: ChartSeries
second_title: Aspose.Sildes for .NET API Referansı
description: Bir grafik serisini temsil eder.
type: docs
weight: 1420
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
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Bir 3-B çubuk grafik serisinin şekilini belirtir. Bu özelliğin değerinin değiştirilmesi, serinin Türünün otomatik olarak değişmesine neden olabilir. Okunabilir/Yazılabilir [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeRepresentation okunabilir/yazılabilir özelliğini kullanın. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Baloncuk grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeScale okunabilir/yazılabilir özelliğini kullanın. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Üst grafiği döndürür. Salt okunur [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Bu serinin veri noktaları koleksiyonunu döndürür. Salt okunur [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Halkanın delik boyutunu belirtir (çizim alanının %10 ile %90 arasında olabilir). Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.DoughnutHoleSize okunabilir/yazılabilir özelliğini kullanın. Salt okunur Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | X yönünde olan serinin ErrorBars'ını temsil eder. X yönündeki ErrorBars, area, bar, scatter ve bubble tipindeki seriler için kullanılabilir. Diğer grafik tiplerinde bu özellik null döndürür (3D grafikler dahil). Özel değerlerde değeri belirtmek için DataPoints koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliği ile kullanın. Salt okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Y yönünde olan serinin ErrorBars'ını temsil eder. Y yönündeki ErrorBars, area, bar, line, scatter ve bubble tipindeki seriler için kullanılabilir. Diğer grafik tiplerinde bu özellik null döndürür (3D grafikler dahil). Özel değerlerde değeri belirtmek için DataPoints koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliği ile kullanın. Salt okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Açık bir pasta diliminin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzdesi olarak ifade edilir. Okunabilir/Yazılabilir Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | İlk pasta ya da halka grafiği diliminin açısını derece cinsinden belirtir (yukarıdan saat yönünde, 0 ile 360 derece arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.FirstSliceAngle okunabilir/yazılabilir özelliğini kullanın. Salt okunur UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Bir serinin formatını döndürür. Salt okunur [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 3B bir grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapDepth okunabilir/yazılabilir özelliğini kullanın. Salt okunur Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Çubuk ya da sütun kümeleri arasındaki boşluğu, çubuk ya da sütun genişliğinin yüzdesi olarak belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapWidth okunabilir/yazılabilir özelliğini kullanın. Salt okunur Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Bu seri ve ilgili seriler için seri çizgilerinin olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik salt okunurdur. Değeri değiştirmek için ParentSeriesGroup.HasSeriesLines okunabilir/yazılabilir özelliğini kullanın. Seri çizgilerinin formatı için ParentSeriesGroup.SeriesLinesFormat özelliğini kullanın. Salt okunur Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Çizgi ya da Stok grafiğinin yukarı/aşağı çubuklara sahip olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik salt okunurdur. Değeri değiştirmek için ParentSeriesGroup.UpDownBars.HasUpDownBars okunabilir/yazılabilir özelliğini kullanın. Yukarı/aşağı çubukların formatı için ParentSeriesGroup.UpDownBars özelliğini kullanın. Salt okunur Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Seri için ters katı rengi belirtir. Renk ayarını uygulamak için seri formatının FillType özelliğini FillType.Solid olarak ayarlayın. Okunabilir/Yazılabilir [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Değer negatif olduğunda çubuk, sütun veya baloncuk serisinin renklerini tersine çevireceğini belirtir. Okunabilir/Yazılabilir Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Serideki her veri işaretçisinin farklı bir renge sahip olacağını belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Bu nedenle özellik salt okunurdur. Değeri değiştirmek için ParentSeriesGroup.IsColorVaried okunabilir/yazılabilir özelliğini kullanın. Salt okunur Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Bir serinin etiketlerini döndürür. Salt okunur [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | İşaretçi. Salt okunur [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Seri adını döndürür. Salt okunur [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Okunabilir/Yazılabilir String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Okunabilir/Yazılabilir String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Okunabilir/Yazılabilir String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Okunabilir/Yazılabilir String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Bir serinin sırasını döndürür. Okunabilir/Yazılabilir Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 2B grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100 ile %100 arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir. Değeri değiştirmek için !:ParentSeriesGroup.Overlap okunabilir/yazılabilir özelliğini kullanın. Salt okunur SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Üst kategori etiketlerinin düzenini temsil eder. Yalnızca Treemap grafiklerinde uygulanır. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Salt okunur [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubuğun hangi veri noktalarından oluşacağını belirleme şeklini belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okunabilir/yazılabilir özelliğini kullanın. Salt okunur [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Özel bölme bilgisi, pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubukta çizilecek veri noktalarını içerir. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere aittir – bu, ilgili grup özelliğinin bir yansımasıdır. Salt okunur [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Pie-of-pie ya da bar-of-pie grafiğinde ikinci pasta veya çubuğun hangi veri noktalarından oluşacağını belirlemek için kullanılacak bir değeri belirtir. Değeri değiştirmek için ParentSeriesGroup.PieSplitPosition okunabilir/yazılabilir özelliğini kullanın. Salt okunur Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Bu serinin ikincil eksende çizilip çizilmediğini gösterir. Okunabilir/Yazılabilir Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Çeyrek metodunu temsil eder. Yalnızca BoxAndWhisker grafiklerinde uygulanır. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Bu seriyle ilişkili lejand girdisini temsil eder. Salt okunur [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Pie-of-pie grafiğinde veya bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzdesi olarak belirtir ( %5 ile %200 arasında olabilir). Değeri değiştirmek için ParentSeriesGroup.SecondPieSize okunabilir/yazılabilir özelliğini kullanın. Salt okunur UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Bağlayıcı çizgileri temsil eder. Yalnızca Waterfall grafiklerinde uygulanır. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa true olur. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunabilir/Yazılabilir Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Ortalama çizgiyi temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa true olur. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunabilir/Yazılabilir Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Ortalama işaretçileri temsil eder. BoxAndWhisker grafiğinde ortalama işaretçileri gösteriliyorsa true olur. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunabilir/Yazılabilir Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Aykırı noktaları temsil eder. BoxAndWhisker grafiğinde aykırı noktalar gösteriliyorsa true olur. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okunabilir/Yazılabilir Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Eğri yumuşatmayı temsil eder. Çizgi grafiği veya dağılım grafiğinde eğri yumuşatma açıksa true olur. Yalnızca çizgi ve çizgilerle bağlanmış dağılım grafiklerinde uygulanır. Okunabilir/Yazılabilir Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Seri trend çizgilerinin koleksiyonu. Salt okunur [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Bu serinin tipini döndürür. Okunabilir/Yazılabilir [`ChartType`](../charttype). |

## Metotlar

| Ad | Açıklama |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Seri dizini ve grafik stiline göre otomatik bir seri rengi döndürür. Bu renk, FillType NotDefined olduğunda varsayılan olarak kullanılır. |

### Ayrıca Bakınız

* arayüz [IChartSeries](../ichartseries)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->