---
title: IChartSeries
second_title: Aspose.Sildes için .NET API Referansı
description: Bir grafik serisini temsil eder.
type: docs
weight: 1910
url: /tr/aspose.slides.charts/ichartseries/
---
## IChartSeries arayüz

Bir grafik serisini temsil eder.

```csharp
public interface IChartSeries : IChartComponent
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Temel IChartComponent arayüzünü almayı sağlar. Salt okunur [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 3B çubuk grafik serisinin şeklini belirtir. Bu özelliğin değerinin değiştirilmesi, serinin Türünün otomatik olarak değişmesine neden olabilir. Okunur/yazılır [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl temsil edileceğini belirtir. Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir - ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik salt okunurdur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeRepresentation okunur/yazılır özelliğini kullanın. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Baloncuk grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir - ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik salt okunurdur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeScale okunur/yazılır özelliğini kullanın. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Bu serinin veri noktaları koleksiyonunu döndürür. Salt okunur [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Halka grafikindeki deliğin boyutunu belirtir (çizim alanının %10 ile %90 arasında olabilir). Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir - ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik salt okunurdur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.DoughnutHoleSize okunur/yazılır özelliğini kullanın. Salt okunur Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | X yönünde olan serinin ErrorBars'ını temsil eder. X yönündeki ErrorBars, area, bar, scatter ve bubble tipindeki seriler için kullanılabilir. Diğer grafik tiplerinde bu özellik null döndürür (3D grafikler dahil). Özelleştirilmiş değerlerde, değeri belirtmek için DataPoints koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliği ile kullanın. Salt okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Y yönünde olan serinin ErrorBars'ını temsil eder. Y yönündeki ErrorBars, area, bar, line, scatter ve bubble tipindeki seriler için kullanılabilir. Diğer grafik tiplerinde bu özellik null döndürür (3D grafikler dahil). Özelleştirilmiş değerlerde, değeri belirtmek için DataPoints koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliği ile kullanın. Salt okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Açık bir pasta diliminin pasta grafiğinin merkezinden uzaklığı, pasta çapının yüzdesi olarak ifade edilir. Okunur/yazılır Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | İlk pasta veya halka grafik diliminin açısını derece cinsinden belirtir (yukarıdan saat yönünde, 0 ile 360 derece arasında). Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir - ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik salt okunurdur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.FirstSliceAngle okunur/yazılır özelliğini kullanın. Salt okunur UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Bir serinin biçimini döndürür. Salt okunur [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak döndürür veya ayarlar. Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir - ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik salt okunurdur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapDepth okunur/yazılır özelliğini kullanın. Salt okunur Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk ya da sütun genişliğinin yüzdesi olarak belirtir. Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir - ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik salt okunurdur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapWidth okunur/yazılır özelliğini kullanın. Salt okunur Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Bu seri ve ilişkili seriler için seri çizgilerinin olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir - ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik salt okunurdur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.HasSeriesLines okunur/yazılır özelliğini kullanın. Seri çizgilerini biçimlendirmek için ParentSeriesGroup.SeriesLinesFormat özelliğini kullanın. Salt okunur Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Çizgi veya hisse senedi grafiğinin yukarı/aşağı çubukları olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir - ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik salt okunurdur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.UpDownBars.HasUpDownBars okunur/yazılır özelliğini kullanın. Up/down çubuklarını biçimlendirmek için ParentSeriesGroup.UpDownBars özelliğini kullanın. Salt okunur Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Seri için ters katı rengi belirtir. Renk ayarını uygulamak için seri biçiminin FillType değerini FillType.Solid olarak ayarlayın. Okunur/yazılır [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Değer negatifse çubuk, sütun veya baloncuk serisinin renklerini ters çevirmesini belirtir. Okunur/yazılır Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir - ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik salt okunurdur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.IsColorVaried okunur/yazılır özelliğini kullanın. Salt okunur Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Bir serinin Etiketlerini döndürür. Salt okunur [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Seri işaretçisini döndürür. Salt okunur [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Seri adını döndürür. Salt okunur [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Seri baloncuk boyutları için sayı biçimini döndürür veya ayarlar. Okunur/yazılır String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Seri değerleri için sayı biçimini döndürür veya ayarlar. Okunur/yazılır String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Seri x değerleri için sayı biçimini döndürür veya ayarlar. Okunur/yazılır String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Seri y değerleri için sayı biçimini döndürür veya ayarlar. Okunur/yazılır String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Bir serinin sırasını döndürür. Okunur/yazılır Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 2B grafiklerde çubuk ve sütunların ne kadar üst üste geldiğini yüzde olarak belirtir (-%100'den %100'e). Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir. Üst seri grubundaki ilgili özelliğin bir yansımasıdır ve bu nedenle bu özellik salt okunurdur. Değeri değiştirmek için ParentSeriesGroup.Overlap okunur/yazılır özelliğini kullanın. Salt okunur SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Üst kategori etiketlerinin düzenini temsil eder. Yalnızca Treemap grafikleri için geçerlidir. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Üst seri grubunu döndürür. Salt okunur [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğun hangi veri noktalarını içereceğini belirleme yöntemini belirtir. Bu özellik yalnızca bu seriye değil, üst seri grubundaki tüm serilere aittir - ilgili grup özelliğinin bir yansımasıdır. Bu nedenle bu özellik salt okunurdur. Üst seri grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okunur/yazılır özelliğini kullanın. Salt okunur [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Özel bölme bilgisi, özel bölmesi olan bir pie-of-pie veya bar-of-pie grafiği için. İkinci pasta veya çubukta çizilecek veri noktalarını içerir. Salt okunur [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun hangi veri noktalarını içereceğini belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliği ile birlikte kullanılır. Salt okunur Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. Okunur/yazılır Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Çeyrek metodunu temsil eder. Yalnızca BoxAndWhisker grafiklerinde geçerlidir. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Bu seriyle ilişkili lejand girişini temsil eder. Salt okunur [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzdesi olarak belirtir ( %5 ile %200 arasında olabilir). Salt okunur UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Bağlayıcı çizgileri temsil eder. Yalnızca Waterfall grafiklerinde geçerlidir. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa true değerindedir. Yalnızca BoxAndWhisker grafiklerinde geçerlidir. Okunur/yazılır Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa true değerindedir. Yalnızca BoxAndWhisker grafiklerinde geçerlidir. Okunur/yazılır Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama işaretçiler gösteriliyorsa true değerindedir. Yalnızca BoxAndWhisker grafiklerinde geçerlidir. Okunur/yazılır Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Uç değer noktalarını temsil eder. BoxAndWhisker grafiğinde uç değer noktaları gösteriliyorsa true değerindedir. Yalnızca BoxAndWhisker grafiklerinde geçerlidir. Okunur/yazılır Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Eğri yumuşatmayı temsil eder. Çizgi veya dağılım grafiğinde eğri yumuşatma açık ise true değerindedir. Yalnızca çizgi ve çizgilerle bağlanan dağılım grafiklerinde geçerlidir. Okunur/yazılır Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Seri trend çizgileri koleksiyonunu döndürür. Salt okunur [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Bu serinin tipini döndürür. Okunur/yazılır [`ChartType`](../charttype). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Seri indeksine ve grafik stiline göre serinin otomatik bir rengini döndürür. FillType NotDefined ise bu renk varsayılan olarak kullanılır. |

### Ayrıca Bakınız

* arayüz [IChartComponent](../ichartcomponent)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->