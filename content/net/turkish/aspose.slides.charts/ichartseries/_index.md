---
title: IChartSeries
second_title: Aspose.Sildes için .NET API Referansı
description: Bir grafik serisini temsil eder.
type: docs
weight: 1950
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
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Temel IChartComponent arayüzünü almaya izin verir. Salt okunur [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Bir serinin 3-B çubuk grafiği şeklini belirler. Bu özelliğin değerinin değiştirilmesi serinin Tipinin otomatik olarak değişmesine neden olabilir. Okuma/yazma [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Baloncuk grafiğinde balon boyutu değerlerinin nasıl temsil edileceğini belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. ParentSeriesGroup özelliğini kullanarak üst seri grubuna erişin. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeRepresentation okuma/yazma özelliğini kullanın. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Baloncuk grafiği için ölçek katsayısını belirler (varsayılan boyutun %0-%300 arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. ParentSeriesGroup özelliğini kullanarak üst seri grubuna erişin. Değeri değiştirmek için ParentSeriesGroup.BubbleSizeScale okuma/yazma özelliğini kullanın. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Bu serinin veri noktaları koleksiyonunu döndürür. Salt okunur [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Halka grafiğinde boşluğun boyutunu belirler (grafik alanının %10-%90 arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. ParentSeriesGroup özelliğini kullanarak üst seri grubuna erişin. Değeri değiştirmek için ParentSeriesGroup.DoughnutHoleSize okuma/yazma özelliğini kullanın. Salt okunur Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | X yönündeki seri için ErrorBars'ı temsil eder. X yönündeki ErrorBars yalnızca area, bar, scatter ve bubble tipindeki seriler için mevcuttur. Diğer grafik tipleri için bu özellik null döndürür (3D grafikler dahil). Özel değerlerde değerleri belirtmek için DataPoints koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliğiyle kullanın. Salt okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Y yönündeki seri için ErrorBars'ı temsil eder. Y yönündeki ErrorBars yalnızca area, bar, line, scatter ve bubble tipindeki seriler için mevcuttur. Diğer grafik tipleri için bu özellik null döndürür (3D grafikler dahil). Özel değerlerde değerleri belirtmek için DataPoints koleksiyonunu [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) özelliğiyle kullanın. Salt okunur [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Açık bir pasta diliminin pasta grafiğinin merkezinden olan mesafesi, pasta çapının yüzde olarak ifade edilir. Okuma/yazma Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | İlk pasta veya halka grafiği diliminin açısını derece cinsinden (yukarıdan saat yönünde, 0-360 derece) belirtir. Salt okunur UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Bir serinin biçimini döndürür. Salt okunur [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak döndürür veya ayarlar. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. ParentSeriesGroup özelliğini kullanarak üst seri grubuna erişin. Değeri değiştirmek için ParentSeriesGroup.GapDepth okuma/yazma özelliğini kullanın. Salt okunur Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. ParentSeriesGroup özelliğini kullanarak üst seri grubuna erişin. Değeri değiştirmek için ParentSeriesGroup.GapWidth okuma/yazma özelliğini kullanın. Salt okunur Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Bu seri ve ilişkili seriler için seri hatlarının olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. ParentSeriesGroup özelliğini kullanarak üst seri grubuna erişin. Değeri değiştirmek için ParentSeriesGroup.HasSeriesLines okuma/yazma özelliğini kullanın. Seri hatlarının biçimi için ParentSeriesGroup.SeriesLinesFormat özelliğini kullanın. Salt okunur Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Çizgi- veya hisse senedi grafiğinin yukarı/aşağı çubukları olup olmadığını belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. ParentSeriesGroup özelliğini kullanarak üst seri grubuna erişin. Değeri değiştirmek için ParentSeriesGroup.UpDownBars.HasUpDownBars okuma/yazma özelliğini kullanın. Up/down çubukları biçimlendirmek için ParentSeriesGroup.UpDownBars özelliğini kullanın. Salt okunur Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Seri için ters katı rengi belirler. Renk ayarını uygulamak için serinin Formatının FillType özelliğini FillType.Solid olarak ayarlayın. Okuma/yazma [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Çubuk, sütun veya baloncuk serisinin değeri negatif ise renklerini tersine çevireceğini belirler. Okuma/yazma Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Serideki her veri işaretçisinin farklı bir renge sahip olacağını belirler. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. ParentSeriesGroup özelliğini kullanarak üst seri grubuna erişin. Değeri değiştirmek için ParentSeriesGroup.IsColorVaried okuma/yazma özelliğini kullanın. Salt okunur Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Bir serinin Etiketlerini döndürür. Salt okunur [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Seri işaretçisini döndürür. Salt okunur [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Seri adını döndürür. Salt okunur [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Seri baloncuk boyutları için sayı biçimini döndürür veya ayarlar. Okuma/yazma String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Seri değerleri için sayı biçimini döndürür veya ayarlar. Okuma/yazma String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Seri x değerleri için sayı biçimini döndürür veya ayarlar. Okuma/yazma String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Seri y değerleri için sayı biçimini döndürür veya ayarlar. Okuma/yazma String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Bir serinin sırasını döndürür. Okuma/yazma Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 2B grafiklerde çubuk ve sütunların ne kadar çakıştığını yüzde olarak (-100%-%100) belirtir. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. Değeri değiştirmek için ParentSeriesGroup.Overlap okuma/yazma özelliğini kullanın. Salt okunur SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Üst kategori etiketlerinin düzlemini temsil eder. Yalnızca Treemap grafiklerinde uygulanır. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Üst seri grubunu döndürür. Salt okunur [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun hangi veri noktalarını içereceğini belirleme yöntemini tanımlar. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. Değeri değiştirmek için ParentSeriesGroup.PieSplitBy okuma/yazma özelliğini kullanın. Salt okunur [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Özel bölme bilgilerini içerir; pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta çizilecek veri noktalarını tanımlar. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Salt okunur [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | İkinci pasta veya çubukta hangi veri noktalarının bulunacağını belirlemek için kullanılacak değeri tanımlar. PieSplitBy özelliğiyle birlikte kullanılır. Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. Değeri değiştirmek için ParentSeriesGroup.PieSplitPosition okuma/yazma özelliğini kullanın. Salt okunur Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Bu serinin ikinci değer ekseninde çizilip çizilmediğini gösterir. Okuma/yazma Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Çeyrek yöntemini temsil eder. Yalnızca BoxAndWhisker grafiklerinde uygulanır. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Bu seriyle ilgili lejand girişini temsil eder. Salt okunur [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak belirler ( %5-%200 arasında). Bu özellik yalnızca bu seriye değil, üst seriler grubundaki tüm serilere ait bir projeksiyondur. Bu nedenle özellik sadece okunabilir. Değeri değiştirmek için ParentSeriesGroup.SecondPieSize okuma/yazma özelliğini kullanın. Salt okunur UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Bağlantı çizgilerini temsil eder. Yalnızca Waterfall grafiklerinde uygulanır. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | İç noktaları temsil eder. BoxAndWhisker grafiğinde iç noktalar gösteriliyorsa true değerindedir. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama çizgi gösteriliyorsa true değerindedir. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Ortalama işaretçilerini temsil eder. BoxAndWhisker grafiğinde ortalama işaretçileri gösteriliyorsa true değerindedir. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Aykırı noktaları temsil eder. BoxAndWhisker grafiğinde aykırı noktalar gösteriliyorsa true değerindedir. Yalnızca BoxAndWhisker grafiklerinde uygulanır. Okuma/yazma Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Eğri pürüzsüzleştirmeyi temsil eder. Çizgi grafiği veya dağılım grafiği için eğri pürüzsüzleştirme açıksa true değerindedir. Yalnızca çizgi ve bağlantılı dağılım grafikleri için uygulanır. Okuma/yazma Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Seri trend çizgileri koleksiyonu. Salt okunur [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Bu serinin tipini döndürür. Okuma/yazma [`ChartType`](../charttype). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Seri dizini ve grafik stiline göre otomatik bir seri rengi döndürür. FillType NotDefined olduğunda bu renk varsayılan olarak kullanılır. |

### Ayrıca Bakınız

* arayüz [IChartComponent](../ichartcomponent)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->