---
title: ChartDataPoint
second_title: Aspose.Sildes برای .NET مرجع API
description: نقطه دادهٔ سری را نمایان می‌کند.
type: docs
weight: 1330
url: /fa/aspose.slides.charts/chartdatapoint/
---
## کلاس ChartDataPoint

نقطه دادهٔ سری را نمایان می‌سازد.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط خواندنی Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط خواندنی Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | موقعیت افقی واقعی (چپ) عنصر نمودار نسبت به گوشهٔ بالای سمت چپ نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط خواندنی Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | موقعیت عمودی واقعی عنصر نمودار نسبت به گوشهٔ بالای سمت چپ نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. فقط خواندنی Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. فقط خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | مقدار رنگ نقطه دادهٔ نمودار را برمی‌گرداند. برای نمودارهای نقشه استفاده می‌شود. فقط خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | مخزن سطوح نقطه داده را برمی‌گرداند. برای سری‌های Treeamp و Sunburst اعمال می‌شود. ایندکس‌گذاری سطوح نقطه داده صفر-مبنایی است. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | مقادیر نوارهای خطای سری را در حالت نوع مقدار سفارشی باز می‌گرداند. فقط خواندنی [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | مقدار جابجایی نقطه داده از مرکز پای چارت را مشخص می‌کند. قابل خواندن/نوشتن Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | ویژگی‌های قالب‌بندی را نشان می‌دهد. قابل خواندن/نوشتن [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | در صورتی که مقدار منفی باشد، نقطه داده رنگ‌های خود را معکوس می‌کند. قابل خواندن/نوشتن Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | مشخص می‌کند که حباب‌ها اثر سه-بعدی داشته باشند. قابل خواندن/نوشتن Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | برچسب. فقط خواندنی [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | یک نشانگر داده را مشخص می‌کند. فقط خواندنی [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | ویژگی‌های ورودی مربوط به ورودی افسانه‌ای در صورت استفاده از نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. فقط خواندنی [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | نقطه داده را به‌عنوان مجموع تعیین می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | مقدار اندازهٔ نقطه دادهٔ نمودار را برمی‌گرداند. برای نمودارهای Treemap و Sunburst استفاده می‌شود. فقط خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | مقدار. فقط خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. فقط خواندنی [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. فقط خواندنی [`IDoubleChartValue`](../idoublechartvalue). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | یک رنگ خودکار برای نقطه داده بر اساس ایندکس سری، ایندکس نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار بر می‌گرداند. این رنگ به‌صورت پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | DataPoint را از سری نمودار حذف می‌کند. |

### مراجع

* رابط [IChartDataPoint](../ichartdatapoint)
* فضای نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->