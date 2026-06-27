---
title: ChartSeriesGroup
second_title: Aspose.Sildes için .NET API Referansı
description: Seri grubunu temsil eder.
type: docs
weight: 1440
url: /tr/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup sınıf

Seri grubunu temsil eder.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Balon grafikinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Okunur/yazılabilir [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında). Okunur/yazılabilir Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Üst grafiği döndürür. Yalnızca okunabilir [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Halka grafiğinde deliğin boyutunu belirtir (çizim alanının boyutunun %0 ile %90 arasında). Okunur/yazılabilir Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0 ile 360 derece arasında). Okunur/yazılabilir UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | 3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak, döndürür veya ayarlar. Okunur/yazılabilir UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Bar veya sütun kümeleri arasındaki boşluğu, bar veya sütun genişliğinin yüzde olarak belirtir. Okunur/yazılabilir UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Grafikte seri çizgileri varsa doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunur/yazılabilir Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | HiLowLines biçimini belirtir. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik türleriyle uygulanır. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Okunur/yazılabilir Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Belirtilen indeksteki öğeyi alır. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (%-100 ile %100 arasında). - %-100: Azami boşluk (çubuklar tamamen ayrılmış). - %0: Çubuklar yan yana, üst üste gelmeden veya boşluk olmadan yerleştirilir. - %100: Azami üst üste binme (çubuklar tamamen birbirinin üzerine gelir). Bu özellik okunur/yazılabilir SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubuğun hangi veri noktalarını içereceğini belirleme yöntemini belirtir. Okunur/yazılabilir [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Özel bölme ile bir pie-of-pie veya bar-of-pie grafiği için özel bölme bilgisi. İkinci pasta veya çubukta çizilecek veri noktalarını içerir. Yalnızca okunabilir [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun hangi veri noktalarını içereceğini belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okunur/yazılabilir Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Yalnızca okunabilir Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzde olarak belirtir (%5 ile %200 arasında olabilir). Okunur/yazılabilir UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Serilerin bir koleksiyonunu döndürür. Yalnızca okunabilir [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Bu seri grubunun tipini döndürür. Yalnızca okunabilir [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Çizgi veya Hisse senedi grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Yalnızca okunabilir [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enumu için özet ve açıklamalara bakınız. 2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerine sahiptir ("seri grup özellikleri"). ChartSeriesGroup sınıfındaki "Series group properties" okunur/yazılabilir. "Series group properties" öğelerinin her biri ChartSeries sınıfında yalnızca okunabilir bir projeksiyona sahip olabilir.

### Ayrıca Bakınız

* arayüz [IChartSeriesGroup](../ichartseriesgroup)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->