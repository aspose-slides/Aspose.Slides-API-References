---
title: IChartDataPoint
second_title: مرجع API Aspose.Sildes برای .NET
description: نماد نقطه دادهٔ سری.
type: docs
weight: 1840
url: /fa/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint رابط

نماد نقطه دادهٔ سری.

```csharp
public interface IChartDataPoint : IActualLayout
```

## خصوصیات

| نام | شرح |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | IActualLayout رابط را برمی‌گرداند. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | اندازه حباب نقطه دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | اندازه حباب کشیده‌شدهٔ نقطه دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | مقدار کشیده‌شدهٔ نقطه دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | مقدار X کشیده‌شدهٔ نقطه دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | مقدار Y کشیده‌شدهٔ نقطه دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | مقدار رنگ نقطه دادهٔ نمودار را دریافت می‌کند. برای نمودارهای نقشه استفاده می‌شود. فقط-خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | مخزن سطوح نقطه داده را برمی‌گرداند. برای سری‌های Treeamp و Sunburst اعمال می‌شود. ایندکس‌گذاری سطوح نقطه داده از صفر شروع می‌شود. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | مقادیر نوارهای خطا سری را در حالت نوع مقدار سفارشی نشان می‌دهد. فقط-خواندنی [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | مقدار جابجایی نقطه داده از مرکز دایرهٔ کیک را مشخص می‌کند. خواند و نوشتن Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | خواص قالب‌بندی را نشان می‌دهد. خواند و نوشتن [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | مشخص می‌کند این نقطه داده به کدام مجموعهٔ فرزندان والد اعمال می‌شود. خواند UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | اگر مقدار منفی باشد، نقطه داده رنگ‌های خود را معکوس می‌کند. خواند و نوشتن Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | مشخص می‌کند حباب‌ها اثر 3-بعدی دارند. خواند و نوشتن Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | برچسب نقطه دادهٔ نمودار را نشان می‌دهد. فقط-خواندنی [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | یک نشانگر داده را مشخص می‌کند. فقط-خواندنی [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | خواص ورودی افسانهٔ متناظر را در صورت نوع نمودار از این فهرست: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie نشان می‌دهد. فقط-خواندنی [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | نقطه داده را به عنوان مجموع تنظیم می‌کند. فقط برای نوع سری Waterfall اعمال می‌شود. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | مقدار اندازهٔ نقطه دادهٔ نمودار را دریافت می‌کند. برای نمودارهای Treemap و Sunburst استفاده می‌شود. فقط-خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | مقدار نقطه دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | مقدار x نقطه دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | مقدار y نقطه دادهٔ نمودار را دریافت می‌کند. فقط-خواندنی [`IDoubleChartValue`](../idoublechartvalue). |

## متدها

| نام | شرح |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | رنگ خودکار نقطه داده را بر اساس شاخص سری، شاخص نقطه داده، ویژگی ParentSeriesGroup.IsColorVaried و سبک نمودار برمی‌گرداند. این رنگ به‌طور پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | DataPoint را از سری نمودار حذف می‌کند. |

### موارد مرتبط

* رابط [IActualLayout](../iactuallayout)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->