---
title: IChartSeriesGroup
second_title: Aspose.Sildes için .NET API Referansı
description: Seri grubunu temsil eder.
type: docs
weight: 1970
url: /tr/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup arabirimi

Seri grubunu temsil eder.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Temel IChartComponent arabirimini almaya izin verir. Salt okunur [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Okunur/yazılır [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Balon grafiği için ölçek çarpanını belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Okunur/yazılır Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Halka grafiğindeki boşluğun boyutunu belirtir (çizim alanının boyutunun %10 ile %90 arasında olabilir). Okunur/yazılır Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0 ile 360 derece arasında). Okunur/yazılır UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | 3B grafikte veri serileri arasındaki mesafeyi işaretçi genişliğinin yüzdesi olarak alır veya ayarlar. Değer 0 ile 500 arasında olmalıdır. Okunur/yazılır UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Sütun veya çubuk kümeleri arasındaki boşluğu çubuk veya sütun genişliğinin yüzdesi olarak alır veya ayarlar. Değer 0 ile 500 arasında olmalıdır. Okunur/yazılır UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Grafik seri çizgileri varsa doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okunur/yazılır Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | HiLowLines biçimini belirtir. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tiplerinde uygulanır. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Serideki her veri işaretçisinin farklı bir renge sahip olmasını belirtir. Okunur/yazılır Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Belirtilen indeksteki elemanı alır. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | 2B grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100 ile %100 arasında). - -100%: Azami boşluk (çubuklar tamamen ayrılmıştır). - 0%: Çubuklar yan yana, üst üste gelmeden ya da boşluk olmadan yerleştirilir. - 100%: Azami örtüşme (çubuklar birbirinin üzerine tamamen gelir). Bu özellik okunur/yazılır SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Pie-of-pie veya bar-of-pie grafiklerinde ikinci pasta veya çubukta hangi veri noktalarının bulunacağını belirleme şeklini belirtir. Okunur/yazılır [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Özel bölme ile pie-of-pie veya bar-of-pie grafiği için özel bölme bilgisini içerir. Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta çizilecek veri noktalarını içerir. Salt okunur [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta hangi veri noktalarının bulunacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okunur/yazılır Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Salt okunur Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun boyutunu, ilk pastanın boyutunun yüzdesi olarak belirtir ( %5 ile %200 arasında olabilir). Okunur/yazılır UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Grafik serilerinin salt okunur bir koleksiyonunu döndürür. Salt okunur [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Bu seri grubunun tipini döndürür. Salt okunur [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Çizgi veya Hisse senedi grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Salt okunur [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enumu için özet ve açıklamalara bakın. 2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerine sahiptir (seri grup özellikleri). ChartSeriesGroup sınıfındaki seri grup özellikleri okunur/yazılırdır. Seri grup özelliklerinin her biri ChartSeries sınıfında salt okunur bir projeksiyona sahip olabilir.

### Bakınız

* arayüz [IChartComponent](../ichartcomponent)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->