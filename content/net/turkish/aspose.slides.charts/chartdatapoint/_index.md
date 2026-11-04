---
title: ChartDataPoint
second_title: Aspose.Sildes için .NET API Referansı
description: Seri veri noktasını temsil eder.
type: docs
weight: 1340
url: /tr/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint sınıfı

Seri veri noktasını temsil eder.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunur Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunur Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunur Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunur Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Yalnızca okuma [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Bir grafik veri noktasının önbelleğe alınmış balon boyutunu alır. Yalnızca okuma [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Bir grafik veri noktasının önbelleğe alınmış değerini alır. Yalnızca okuma [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Bir grafik veri noktasının önbelleğe alınmış X değerini alır. Yalnızca okuma [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Bir grafik veri noktasının önbelleğe alınmış Y değerini alır. Yalnızca okuma [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Grafik veri noktasının renk değerini döndürür. Harita grafiklerinde kullanılır. Yalnızca okuma [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Veri noktası seviyelerinin konteynerini döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyeleri indeksi sıfır temellidir. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Özel değer türü durumunda seri hata çubukları değerlerini temsil eder. Yalnızca okuma [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Veri noktasının pasta merkezinden ne kadar kaydırılacağını belirtir. Okunur/yazılabilir Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Biçimlendirme özelliklerini temsil eder. Okunur/yazılabilir [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Değer negatif ise veri noktasının renklerini tersine çevirmesini belirtir. Okunur/yazılabilir Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Balonların 3B efektine sahip olduğunu belirtir. Okunur/yazılabilir Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Etiket. Yalnızca okuma [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Bir veri işaretçisi belirtir. Yalnızca okuma [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Bu listedeki grafik türlerinden biri olduğunda ilgili lejand girdisinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Yalnızca okuma [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall seri tipi için uygulanır. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Grafik veri noktasının boyut değerini döndürür. Treemap ve Sunburst grafiklerinde kullanılır. Yalnızca okuma [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Değer. Yalnızca okuma [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Yalnızca okuma [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Yalnızca okuma [`IDoubleChartValue`](../idoublechartvalue). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Seri indeksi, veri noktası indeksi, ParentSeriesGroup.IsColorVaried özelliği ve grafik stiline göre veri noktasının otomatik bir rengini döndürür. FillType NotDefined ise bu renk varsayılan olarak kullanılır. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Veri noktasını grafik serisinden kaldırır. |

### Ayrıca Bakınız

* arayüz [IChartDataPoint](../ichartdatapoint)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->