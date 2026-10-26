---
title: IChartSeries
second_title: Aspose.Sildes .NET API Referansı
description: Bir grafik serisini temsil eder.
type: docs
weight: 1930
url: /tr/aspose.slides.charts/ichartseries/
---
## IChartSeries arayüzü

Bir grafik serisini temsil eder.

```csharp
public interface IChartSeries : IChartComponent
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Temel IChartComponent arayüzünü elde etmeyi sağlar. Salt okunur [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 3B çubuk grafiğinin bir serisinin şeklini belirler. Bu özelliğin değerinin değiştirilmesi, serinin Tipinin otomatik olarak değişmesine neden olabilir. Okunur/yazılabilir [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeRepresentation okunur/yazılabilir özelliğini kullanın. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Baloncuk grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeScale okunur/yazılabilir özelliğini kullanın. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Bu serinin veri noktaları koleksiyonunu döndürür. Salt okunur [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Doughnut grafiğinde deliğin boyutunu belirtir (grafik alanının %10 ile %90 arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.DoughnutHoleSize okunur/yazılabilir özelliğini kullanın. Salt okunur Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Serinin X yönündeki ErrorBars öğesini temsil eder. X yönündeki ErrorBars, area, bar, scatter ve bubble tipindeki seriler için kullanılabilir. Diğer grafik tiplerinde bu özellik null döndürür (3D grafikler dahil). Özel değerlerde değeri belirlemek için DataPoints koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliğiyle kullanın. Salt okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Serinin Y yönündeki ErrorBars öğesini temsil eder. Y yönündeki ErrorBars, area, bar, line, scatter ve bubble tipindeki seriler için kullanılabilir. Diğer grafik tiplerinde bu özellik null döndürür (3D grafikler dahil). Özel değerlerde değeri belirlemek için DataPoints koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliğiyle kullanın. Salt okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Açık bir dilim ile pasta grafiğinin merkezi arasındaki mesafe, pasta çapının yüzdesi olarak ifade edilir. Okunur/yazılabilir Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | İlk pasta veya doughnut diliminin açısını derece cinsinden (yukarıdan saat yönünde, 0'dan 360 dereceye) belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.FirstSliceAngle okunur/yazılabilir özelliğini kullanın. Salt okunur UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Bir serinin biçimini döndürür. Salt okunur [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 3D grafikte veri serileri arasındaki boşluğu, işaretleyici genişliğinin yüzde olarak döndürür veya ayarlar. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapDepth okunur/yazılabilir özelliğini kullanın. Salt okunur Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Bar veya sütun kümeleri arasındaki boşluğu, bar veya sütun genişliğinin yüzde olarak belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.GapWidth okunur/yazılabilir özelliğini kullanın. Salt okunur Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Serinin ve ilişkili serilerin seri çizgilerine sahip olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.HasSeriesLines okunur/yazılabilir özelliğini kullanın. Seri çizgilerini biçimlendirmek için ParentSeriesGroup.SeriesLinesFormat özelliğini kullanın. Salt okunur Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Line- veya Stock-grafiğinin yukarı/aşağı çubukları olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.UpDownBars.HasUpDownBars okunur/yazılabilir özelliğini kullanın. Yukarı/aşağı çubukları biçimlendirmek için ParentSeriesGroup.UpDownBars özelliğini kullanın. Salt okunur Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Serinin ters katı rengini belirtir. Renk ayarını uygulamak için seri biçimi FillType'ı FillType.Solid olarak ayarlayın. Okunur/yazılabilir [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Değer negatifse bar, sütun veya baloncuk serisinin renklerini tersine çevirir. Okunur/yazılabilir Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Serideki her veri işaretleyicisinin farklı bir renk almasını belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.IsColorVaried okunur/yazılabilir özelliğini kullanın. Salt okunur Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Bir serinin Etiketlerini döndürür. Salt okunur [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Seri işaretleyicisini döndürür. Salt okunur [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Seri adını döndürür. Salt okunur [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Seri baloncuk boyutları için sayı biçimini döndürür veya ayarlar. Okunur/yazılabilir String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Seri değerleri için sayı biçimini döndürür veya ayarlar. Okunur/yazılabilir String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Seri x değerleri için sayı biçimini döndürür veya ayarlar. Okunur/yazılabilir String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Seri y değerleri için sayı biçimini döndürür veya ayarlar. Okunur/yazılabilir String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Serinin sırasını döndürür. Okunur/yazılabilir Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 2D grafiklerde çubuk ve sütunların birbirine ne kadar üst üste bindiğini yüzde olarak belirtir (-100% ile 100% arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Değeri değiştirmek için ParentSeriesGroup.Overlap okunur/yazılabilir özelliğini kullanın. Salt okunur SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Üst kategori etiketlerinin düzenini temsil eder. Yalnızca Treemap grafiklerine uygulanır. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Üst seri grubunu döndürür. Salt okunur [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubukta hangi veri noktalarının bulunacağını belirlemek için kullanılan yöntemi belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Üst seriler grubuna erişmek için ParentSeriesGroup özelliğini kullanın. Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okunur/yazılabilir özelliğini kullanın. Salt okunur [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Özel bölme bilgisi, pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubukta çizilecek veri noktalarını içerir. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir. Salt okunur [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | İkinci pasta ya da çubukta hangi veri noktalarının bulunacağını belirlemek için kullanılacak değeri belirtir. PieSplitBy özelliği ile birlikte kullanılır. Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Değeri değiştirmek için ParentSeriesGroup.PieSplitPosition okunur/yazılabilir özelliğini kullanın. Salt okunur Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. Okunur/yazılabilir Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Çeyrek metodunu temsil eder. Yalnızca BoxAndWhisker grafiklerine uygulanır. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Bu seriyle ilişkili lejand girişini temsil eder. Salt okunur [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğun boyutunu, ilk pastanın boyutuna yüzde olarak belirtir (5% ile 200% arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubunun tüm serilerine ait bir yansıma özelliğidir – bu yüzden salt okunurdur. Değeri değiştirmek için ParentSeriesGroup.SecondPieSize okunur/yazılabilir özelliğini kullanın. Salt okunur UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Bağlantı çizgilerini temsil eder. Yalnızca Waterfall grafiklerine uygulanır. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa true olur. Yalnızca BoxAndWhisker grafiklerine uygulanır. Okunur/yazılabilir Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa true olur. Yalnızca BoxAndWhisker grafiklerine uygulanır. Okunur/yazılabilir Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama işaretçiler gösteriliyorsa true olur. Yalnızca BoxAndWhisker grafiklerine uygulanır. Okunur/yazılabilir Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Aykırı nokta işaretçilerini temsil eder. BoxAndWhisker grafiğinde aykırı noktalar gösteriliyorsa true olur. Yalnızca BoxAndWhisker grafiklerine uygulanır. Okunur/yazılabilir Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Eğri yumuşatmayı temsil eder. Çizgi veya dağılım grafiklerinde eğri yumuşatma açıksa true olur. Yalnızca çizgi ve dağılım (bağlantılı) grafiklerine uygulanır. Okunur/yazılabilir Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Seri trend çizgileri koleksiyonu. Salt okunur [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Bu serinin türünü döndürür. Okunur/yazılabilir [`ChartType`](../charttype). |

## Metotlar

| Ad | Açıklama |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Seri indeksi ve grafik tarzına göre otomatik bir renk döndürür. FillType NotDefined olduğunda bu renk varsayılan olarak kullanılır. |

### Ayrıca Bakınız

* arayüz [IChartComponent](../ichartcomponent)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->