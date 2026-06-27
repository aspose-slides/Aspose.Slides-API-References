---
title: ChartDataPoint
second_title: Aspose.Sildes for .NET API Referansı
description: Seri veri noktasını temsil eder.
type: docs
weight: 1310
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
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Gerçek grafiğin öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın. Okunur Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Gerçek grafiğin öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın. Okunur Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın. Okunur Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() yöntemini çağırın. Okunur Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Yalnızca okunur [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Veri noktasının renk değerini döndürür. Harita grafiklerinde kullanılır. Yalnızca okunur [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Veri noktası seviyelerinin kapsayıcısını döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyeleri sıfır tabanlı indekslenir. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Özel değer türü durumunda serinin hata çubukları değerlerini temsil eder. Yalnızca okunur [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Veri noktasının pasta merkezinden ne kadar taşınacağını belirtir. Okunur/yazılabilir Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Biçimlendirme özelliklerini temsil eder. Okunur/yazılabilir [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Değer negatif ise veri noktasının renklerini tersine çevireceğini belirtir. Okunur/yazılabilir Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Balonların 3B etkisine sahip olacağını belirtir. Okunur/yazılabilir Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Yalnızca okunur [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Veri işaretçisini belirtir. Yalnızca okunur [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Bu listedeki grafik türleri için ilgili gösterge girişinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Yalnızca okunur [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall serisi tipi için uygulanır. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Grafik veri noktasının boyut değerini döndürür. Treemap ve Sunburst grafiklerinde kullanılır. Yalnızca okunur [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Yalnızca okunur [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Yalnızca okunur [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Yalnızca okunur [`IDoubleChartValue`](../idoublechartvalue). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Veri noktasının seri indeksine, veri noktası indeksine, ParentSeriesGroup.IsColorVaried özelliğine ve grafik stiline bağlı otomatik bir rengi döndürür. FillType NotDefined ise bu renk varsayılan olarak kullanılır. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Veri noktasını grafik serisinden kaldırır. |

### İlgili

* arayüz [IChartDataPoint](../ichartdatapoint)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->