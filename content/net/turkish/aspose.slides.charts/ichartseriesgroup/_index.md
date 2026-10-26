---
title: IChartSeriesGroup
second_title: Aspose.Sildes for .NET API Referansı
description: Seri grubunu temsil eder.
type: docs
weight: 1950
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
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Temel IChartComponent arabirimini almaya izin verir. Yalnızca okuma [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Baloncuk grafiğinde baloncuk boyutu değerlerinin nasıl temsil edileceğini belirler. Okuma/yazma [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Baloncuk grafiği için ölçek faktörünü belirler (varsayılan boyutun %0 ile %300 arasında olabilir). Okuma/yazma Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Halka grafiğindeki boşluğun boyutunu belirler (çizim alanının boyutunun %10 ile %90 arasında olabilir). Okuma/yazma Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | İlk pasta ya da halka grafiği diliminin açısını derece cinsinden alır veya ayarlar (yukarıdan saat yönünde, 0 ile 360 derece arasında). Okuma/yazma UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | 3B grafikte veri serileri arasındaki mesafeyi, işaretçi genişliğinin yüzdesi olarak alır veya ayarlar. Okuma/yazma UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Çubuk veya sütun kümeleri arasındaki boşluğu, çubuk ya da sütun genişliğinin yüzdesi olarak belirler. Okuma/yazma UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Grafik serileri çizgileri varsa doğru. Yığılmış çubuk ve OfPie grafiklerine uygulanır. Okuma/yazma Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | HiLowLines biçimini belirler. HiLowLines, HiLowClose, OpenHiLowClose, VolumeHiLowClose ve VolumeOpenHiLowClose grafik tipleriyle uygulanır. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Serideki her veri işaretçisinin farklı bir renkte olmasını belirler. Okuma/yazma Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Belirtilen indeksteki öğeyi alır. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | 2B grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirler (-100% ile %100 arasında). --100%: Azami boşluk (çubuklar tamamen ayrıdır). -0%: Çubuklar yan yana, üst üste gelmeden veya boşluk olmadan yer alır. -100%: Azami üst üste gelme (çubuklar tamamen birbirinin üzerine biner). Bu özellik okuma/yazma SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubukta hangi veri noktalarının bulunacağını belirleme şeklini tanımlar. Okuma/yazma [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Özel bölünmeye sahip bir pie-of-pie veya bar-of-pie grafiği için özel bölünme bilgisi. İkinci pasta veya çubukta çizilecek veri noktalarını içerir. Yalnızca okuma [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubukta hangi veri noktalarının bulunacağını belirlemek için kullanılacak değeri tanımlar. PieSplitBy özelliği ile birlikte kullanılır. Okuma/yazma Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Bu grubun serilerinin ikincil eksende çizilip çizilmediğini gösterir. Yalnızca okuma Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Pie-of-pie veya bar-of-pie grafiğinde ikinci pasta ya da çubuğun boyutunu, birinci pastanın boyutunun yüzdesi olarak belirler ( %5 ile %200 arasında olabilir). Okuma/yazma UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Grafik serilerinin sadece okuma koleksiyonunu döndürür. Yalnızca okuma [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Bu seri grubunun türünü döndürür. Yalnızca okuma [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Line veya Stock grafiğinin yukarı/aşağı çubuklarına erişim sağlar. Yalnızca okuma [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Açıklamalar

1) ChartSeriesGroupCollection sınıfı ve CombinableSeriesTypesGroup enum'ı için özet ve açıklamaya bakınız.  
2) Seri grubu, grup içindeki her seriye ortak olan bazı seri özelliklerini içerir ("seri grup özellikleri"). ChartSeriesGroup sınıfındaki "seri grup özellikleri" okuma/yazma özelliğindedir. "seri grup özellikleri" nin her biri ChartSeries sınıfında yalnızca okuma projeksiyonuna sahip olabilir.

### Diğer Bağlantılar

* arabirimi [IChartComponent](../ichartcomponent)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->