---
title: IChartDataPoint
second_title: Aspose.Sildes için .NET API Referansı
description: Seri veri noktasını temsil eder.
type: docs
weight: 1840
url: /tr/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint arayüz

Seri veri noktasını temsil eder.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Özellikler

| Name | Description |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | IActualLayout arayüzünü döndürür. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Bir grafik veri noktasının baloncuk boyutunu alır. Sadece okuma [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Bir grafik veri noktasının önbelleğe alınmış baloncuk boyutunu alır. Sadece okuma [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Bir grafik veri noktasının önbelleğe alınmış değerini alır. Sadece okuma [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Bir grafik veri noktasının önbelleğe alınmış X değerini alır. Sadece okuma [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Bir grafik veri noktasının önbelleğe alınmış Y değerini alır. Sadece okuma [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Bir grafik veri noktasının renk değerini alır. Harita grafiklerinde kullanılır. Sadece okuma [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Veri noktası seviyelerinin konteynerini döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyesi indekslemesi sıfır tabanlıdır. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Özel değer türü durumunda seri hata çubukları değerlerini temsil eder. Sadece okuma [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Veri noktasının pasta merkezinden ne kadar taşınacağını belirtir. Okunur/yazılabilir Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Biçimlendirme özelliklerini temsil eder. Okunur/yazılabilir [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Bu veri noktasının ebeveynin çocuk koleksiyonundan hangisine uygulandığını belirler. Okunur UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. Okunur/yazılabilir Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Baloncukların 3-B etkisine sahip olacağını belirtir. Okunur/yazılabilir Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Bir grafik veri noktasının etiketini temsil eder. Sadece okuma [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Bir veri işaretçisini belirtir. Sadece okuma [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Bu listedeki grafik türlerinden biri olduğunda ilgili lejand girişinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Sadece okuma [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall seri türü için uygulanır. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Bir grafik veri noktasının boyut değerini alır. Treemap ve Sunburst grafiklerinde kullanılır. Sadece okuma [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Bir grafik veri noktasının değerini alır. Sadece okuma [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Bir grafik veri noktasının x değerini alır. Sadece okuma [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Bir grafik veri noktasının y değerini alır. Sadece okuma [`IDoubleChartValue`](../idoublechartvalue). |

## Metotlar

| Name | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Seri indeksine, veri noktası indeksine, ParentSeriesGroup.IsColorVaried özelliğine ve grafik stiline göre veri noktasının otomatik rengini döndürür. Bu renk, FillType NotDefined olduğunda varsayılan olarak kullanılır. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Veri noktasını grafik serisinden kaldırır. |

### Ayrıca Bakınız

* arayüz [IActualLayout](../iactuallayout)
* ad alanı [Aspose.Slides.Charts](../../aspose.slides.charts)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->