---
title: ChartSeriesGroup
second_title: Aspose.Sildes .NET API Referansı
description: Seri grubunu temsil eder.
type: docs
weight: 1470
url: /tr/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup sınıf

Represents group of series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Özellikler

| Name | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Baloncuk grafikinde baloncuk boyutu değerlerinin nasıl temsil edildiğini belirtir. Okunur/Yazılır [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Baloncuk grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Okunur/Yazılır Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Üst grafiği döndürür. Salt okunur [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Halka grafikindeki deliğin boyutunu belirtir (grafik alanının boyutunun %0 ile %90 arasında olabilir). Okunur/Yazılır Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | İlk dilim ya da halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0 ile 360 derece arasında). Okunur/Yazılır UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | 3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak alır veya ayarlar. Değer 0 ile 500 arasında olmalıdır. Okunur/Yazılır UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzdesi olarak alır veya ayarlar. Değer 0 ile 500 arasında olmalıdır. Okunur/Yazılır UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Grafik seriler çizgileri varsa doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunur/Yazılır Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | HiLowLines biçimini belirtir. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tipleriyle uygulanır. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. Okunur/Yazılır Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Belirtilen indeksteki öğeyi alır. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Bar ve sütunların 2D grafiklerde ne kadar çakışacağını yüzde olarak belirtir (-100% ile %100 arasında). - -100%: Azami boşluk (çubuklar tamamen ayrıdır). - 0%: Çubuklar yan yana, çakışma ve boşluk olmadan yerleştirilir. - 100%: Azami çakışma (çubuklar birbirinin üzerine tamamen gelir). Bu özellik Okunur/Yazılır SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci dilim veya çubuğa hangi veri noktalarının dahil edileceğini nasıl belirleyeceğini belirtir. Okunur/Yazılır [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Özel bölünme içeren bir pie-of-pie veya bar-of-pie grafiği için özel bölme bilgisidir. Pie-of-pie veya bar-of-pie grafiğinde ikinci dilim veya çubukta çizilecek veri noktalarını içerir. Salt okunur [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci dilim veya çubuğa hangi veri noktalarının dahil edileceğini belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okunur/Yazılır Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Salt okunur Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Pie-of-pie ya da bar-of-pie grafiğinin ikinci dilim veya çubuğunun, ilk dilimin boyutuna göre yüzde olarak boyutunu belirtir ( %5 ile %200 arasında olabilir). Okunur/Yazılır UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Serilerin bir koleksiyonunu döndürür. Salt okunur [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Bu seri grubunun tipini döndürür. Salt okunur [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Line- veya Stock-grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Salt okunur [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enumu için özet ve açıklamalara bakın. 2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerini içerir ("seri grup özellikleri"). ChartSeriesGroup sınıfındaki "seri grup özellikleri" okunur/yazılır. "Seri grup özellikleri"nin her biri ChartSeries sınıfında salt okunur bir yansımaya sahip olabilir.

### İlgili

* arayüz [IChartSeriesGroup](../ichartseriesgroup)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->