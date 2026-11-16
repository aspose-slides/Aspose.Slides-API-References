---
title: ChartDataPoint
second_title: Aspose.Sildes برای مرجع API .NET
description: نقطه دادهٔ سری را نشان می‌دهد.
type: docs
weight: 1340
url: /fa/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint کلاس

Represents series data point.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از این، متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقادیر واقعی را دریافت کنید. قابل‌خواندن Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از این، متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقادیر واقعی را دریافت کنید. قابل‌خواندن Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | موقعیت x واقعی (چپ) عنصر نمودار نسبت به گوشهٔ بالا-چپ نمودار را مشخص می‌کند. قبل از این، متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقادیر واقعی را دریافت کنید. قابل‌خواندن Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | موقعیت بالایی واقعی عنصر نمودار نسبت به گوشهٔ بالا-چپ نمودار را مشخص می‌کند. قبل از این، متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقادیر واقعی را دریافت کنید. قابل‌خواندن Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. فقط‌خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | اندازهٔ حباب ذخیره‌شدهٔ یک نقطه دادهٔ نمودار را برمی‌گرداند. فقط‌خواندنی [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | مقدار ذخیره‌شدهٔ یک نقطه دادهٔ نمودار را برمی‌گرداند. فقط‌خواندنی [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | مقدار X ذخیره‌شدهٔ یک نقطه دادهٔ نمودار را برمی‌گرداند. فقط‌خواندنی [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | مقدار Y ذخیره‌شدهٔ یک نقطه دادهٔ نمودار را برمی‌گرداند. فقط‌خواندنی [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | مقدار رنگ نقطه دادهٔ نمودار را برمی‌گرداند. برای نمودارهای نقشه استفاده می‌شود. فقط‌خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | محفظهٔ سطوح نقطه داده را برمی‌گرداند. برای سری‌های Treeamp و Sunburst اعمال می‌شود. ایندکس‌گذاری سطوح نقطه داده صفر مبنا است. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | مقادیر نوارهای خطای سری را در حالت نوع مقدار Custom نشان می‌دهد. فقط‌خواندنی [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | مقداری که نقطه داده باید از مرکز دایره‌پای حرکت کند، مشخص می‌کند. خواندن/نوشتن Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | خواص قالب‌بندی را نشان می‌دهد. خواندن/نوشتن [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | مشخص می‌کند که نقطه داده در صورت منفی بودن مقدار، رنگ‌های خود را معکوس کند. خواندن/نوشتن Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. خواندن/نوشتن Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | برچسب. فقط‌خواندنی [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | یک نشانگر داده را مشخص می‌کند. فقط‌خواندنی [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | خواص ورودی مربوط به لیژند در صورت نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. فقط‌خواندنی [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | نقطه داده را به عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | مقدار اندازهٔ نقطه دادهٔ نمودار را برمی‌گرداند. برای نمودارهای Treemap و Sunburst استفاده می‌شود. فقط‌خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | مقدار. فقط‌خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. فقط‌خواندنی [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. فقط‌خواندنی [`IDoubleChartValue`](../idoublechartvalue). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | یک رنگ خودکار برای نقطه داده بر اساس ایندکس سری، ایندکس نقطه داده، خاصیت ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. این رنگ به‌طور پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | DataPoint را از سری نمودار حذف می‌کند. |

### موارد مرتبط

* رابط [IChartDataPoint](../ichartdatapoint)
* فضای نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->