---
title: ChartSeriesGroup
second_title: Aspose.Sildes for .NET API Referansı
description: Seri grubunu temsil eder.
type: docs
weight: 1460
url: /tr/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup sınıfı

Seri grubunu temsil eder.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Balon grafiğinde balon boyutu değerlerinin nasıl temsil edildiğini belirtir. Okuma/Yazma [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Balon grafiği için ölçek faktörünü belirtir (varsayılan boyutun %0 ile %300 arasında olabilir). Okuma/Yazma Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Üst grafiği döndürür. Salt Okunur [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Halka grafiğindeki deliğin boyutunu belirtir (çizim alanının %0 ile %90 arasında olabilir). Okuma/Yazma Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | İlk pasta veya halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0 ile 360 derece arasında). Okuma/Yazma UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | 3D grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzde olarak döndürür veya ayarlar. Okuma/Yazma UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk veya sütun genişliğinin yüzde olarak belirtir. Okuma/Yazma UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Grafiğin seri çizgileri varsa doğru döner. Yığınlı çubuk ve OfPie grafiklerine uygulanır. Okuma/Yazma Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | HiLowLines biçimini belirtir. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik türleriyle uygulanır. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Serideki her veri işaretleyicisinin farklı bir renge sahip olmasını belirtir. Okuma/Yazma Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Belirtilen indeksdeki öğeyi alır. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | 2D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-%100 ile %100 arasında). - -%100: En fazla boşluk (çubuklar tamamen ayrılmıştır). - %0: Çubuklar yan yana, üst üste gelmeden yer alır. - %100: En fazla üst üste binme (çubuklar tamamen üst üste gelir). Bu özellik Okuma/Yazma SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun hangi veri noktalarından oluşacağını belirleme şeklini belirtir. Okuma/Yazma [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Özel bölme bilgisi, özelleştirilmiş bölmesi olan bir pie-of-pie veya bar-of-pie grafiği için. Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubukta çizilecek veri noktalarını içerir. Salt Okunur [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta veya çubuğun hangi veri noktalarından oluşacağını belirlemek için kullanılacak bir değeri belirtir. PieSplitBy özelliğiyle birlikte kullanılır. Okuma/Yazma Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Salt Okunur Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinin ikinci pasta veya çubuğunun boyutunu, ilk pastanın boyutunun yüzde olarak belirtir (%5 ile %200 arasında olabilir). Okuma/Yazma UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Seri koleksiyonunu döndürür. Salt Okunur [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Bu seri grubunun tipini döndürür. Salt Okunur [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Çizgi veya Stok grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Salt Okunur [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum'ı için özet ve açıklamalara bakınız. 2) Seri grubu, grup içindeki her seri için ortak olan bazı seri özelliklerini içerir ("seri grup özellikleri"). ChartSeriesGroup sınıfındaki "seri grup özellikleri" Okuma/Yazma'dır. "Seri grup özellikleri"nin her biri ChartSeries sınıfında salt okunur bir yansıtma olabilir.

### İlgili

* arayüz [IChartSeriesGroup](../ichartseriesgroup)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->