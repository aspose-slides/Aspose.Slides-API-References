---
title: ChartDataPoint
second_title: Aspose.Sildes için .NET API Referansı
description: Seri veri noktasını temsil eder.
type: docs
weight: 1330
url: /tr/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint sınıfı

Represents series data point.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın. Okunur Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın. Okunur Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Grafiğin sol üst köşesine göre grafik öğesinin gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın. Okunur Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Grafiğin sol üst köşesine göre grafik öğesinin gerçek üst konumunu belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın. Okunur Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Yalnızca okunabilir [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Grafik veri noktasının renk değerini döndürür. Harita grafiklerinde kullanılır. Yalnızca okunabilir [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Veri noktası seviyelerinin kapsayıcısını döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyesi indekslemesi sıfır temellidir. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Özel değer türü durumunda seri hata çubukları değerlerini temsil eder. Yalnızca okunabilir [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Veri noktasının pasta merkezinden ne kadar taşınacağını belirtir. Okunabilir/Yazılabilir Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Biçimlendirme özelliklerini temsil eder. Okunabilir/Yazılabilir [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Değer negatif ise veri noktasının renklerini tersine çevireceğini belirtir. Okunabilir/Yazılabilir Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Baloncukların 3-D etkisine sahip olduğunu belirtir. Okunabilir/Yazılabilir Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Etiket. Yalnızca okunabilir [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Veri işaretçisi belirler. Yalnızca okunabilir [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Bu listedeki grafik türlerinden biri durumunda ilgili lejand girişinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Yalnızca okunabilir [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall seri türü için uygulanır. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Grafik veri noktasının boyut değerini döndürür. Treemap ve Sunburst grafiklerinde kullanılır. Yalnızca okunabilir [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Değer. Yalnızca okunabilir [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Yalnızca okunabilir [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Yalnızca okunabilir [`IDoubleChartValue`](../idoublechartvalue). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Seri indeksine, veri noktası indeksine, ParentSeriesGroup.IsColorVaried özelliğine ve grafik stiline bağlı olarak veri noktasının otomatik bir rengini döndürür. FillType NotDefined olduğunda bu renk varsayılan olarak kullanılır. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Grafik serisinden DataPoint öğesini kaldırır. |

### İlgili

* arayüz [IChartDataPoint](../ichartdatapoint)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->