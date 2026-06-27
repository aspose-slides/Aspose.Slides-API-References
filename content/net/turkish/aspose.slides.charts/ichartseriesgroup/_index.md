---
title: IChartSeriesGroup
second_title: Aspose.Sildes for .NET API Referansı
description: Seri grubunu temsil eder.
type: docs
weight: 1930
url: /tr/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup arabirimi

Serilerin grubunu temsil eder.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Temel IChartComponent arabirimine erişim sağlar. Salt-okunur [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Balon grafik üzerindeki balon boyutu değerlerinin nasıl temsil edileceğini belirtir. Okunur/yazılabilir [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Balon grafik için ölçek faktörünü belirtir (varsayılan boyutun %0-%300 arasında). Okunur/yazılabilir Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Donut grafiğindeki deliğin boyutunu belirtir (grafik alanının %10-%90 arasında). Okunur/yazılabilir Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | İlk pasta ya da donut diliminin açısını derece cinsinden belirler (yukarıdan saat yönünde, 0-360 derece). Okunur/yazılabilir UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | 3B grafikte veri serileri arasındaki mesafeyi işaretçi genişliğinin yüzdesi olarak ayarlar veya döndürür. Okunur/yazılabilir UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Çubuk ya da sütun kümeleri arasındaki boşluğu çubuk ya da sütun genişliğinin yüzdesi olarak belirtir. Okunur/yazılabilir UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Grafik seri çizgilerine sahipse doğru döndürür. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunur/yazılabilir Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | HiLowLines biçimini belirtir. HiLowLines HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik türleriyle birlikte uygulanır. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Serideki her veri işaretçisinin farklı bir renge sahip olduğunu belirtir. Okunur/yazılabilir Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Belirtilen dizindeki öğeyi alır. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Çubuk ve sütunların 2-D grafiklerde %- olarak birbirleriyle ne kadar üst üste geleceğini belirtir (-%100-%100). -%100: En fazla boşluk (çubuklar tamamen ayrık). 0%: Çubuklar yan yana, üst üste binmez veya boşluk olmaz. %100: En fazla üst üste binme (çubuklar tamamen üst üste gelir). Bu özellik Okunur/yazılabilir SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Pie-of-pie veya Bar-of-pie grafiğinde ikinci pasta ya da çubukta hangi veri noktalarının bulunacağını belirleme yöntemini belirtir. Okunur/yazılabilir [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Özel bölme bilgisi, özel bölme içeren bir pie-of-pie veya bar-of-pie grafiği için ikinci pasta ya da çubukta çizilecek veri noktalarını içerir. Salt-okunur [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubukta hangi veri noktalarının bulunacağını belirlemek için kullanılacak değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okunur/yazılabilir Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Bu grubun serisinin ikinci eksende çizilip çizilmediğini gösterir. Salt-okunur Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Pie-of-pie grafiğinin ikinci pasta ya da çubuğunun boyutunu, ilk pastanın boyutuna göre yüzde olarak belirtir ( %5-%200 arasında). Okunur/yazılabilir UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Grafik serilerinin salt-okunur bir koleksiyonunu döndürür. Salt-okunur [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Bu seri grubunun türünü döndürür. Salt-okunur [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Çizgi ya da hisse senedi grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Salt-okunur [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum'ı için özet ve açıklamalara bakın. 2) Seri grubu, gruptaki her seri için ortak olan bazı seri özelliklerini (\"seri grup özellikleri\") içerir. ChartSeriesGroup sınıfındaki \"seri grup özellikleri\" okunur/yazılabilir. Her bir \"seri grup özelliği\" ChartSeries sınıfında salt-okunur bir yansıma alabilir.

### Ayrıca Bakınız

* arabirim [IChartComponent](../ichartcomponent)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->