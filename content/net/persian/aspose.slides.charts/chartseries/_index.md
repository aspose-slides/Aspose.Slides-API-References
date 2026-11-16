---
title: ChartSeries
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر یک سری نمودار.
type: docs
weight: 1450
url: /fa/aspose.slides.charts/chartseries/
---
## ChartSeries کلاس

نمایش یک سری نمودار.

```csharp
public class ChartSeries : IChartSeries
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | مشخص می‌کند شکل یک سری نمودار میله‌ای سه‌بعدی را. تغییر مقدار این ویژگی می‌تواند باعث تغییر خودکار نوع سری شود. خواندنی/قابل نوشتن [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | مشخص می‌کند مقادیر اندازه حباب‌ها چگونه در نمودار حبابی نمایش داده شوند. این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.BubbleSizeRepresentation خواندنی/قابل نوشتن استفاده کنید. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | مشخص می‌کند مقیاس اندازه حباب‌ها در نمودار حبابی (می‌تواند بین ۰ تا ۳۰۰ درصد از اندازه پیش‌فرض باشد). این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.BubbleSizeScale خواندنی/قابل نوشتن استفاده کنید. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | نمودار والد را برمی‌گرداند. فقط خواندنی [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | مجموعه‌ای از نقاط داده این سری را برمی‌گرداند. فقط خواندنی [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | اندازهٔ سوراخ در یک نمودار دونات را مشخص می‌کند (می‌تواند بین ۱۰ تا ۹۰ درصد از اندازه ناحیهٔ نمودار باشد). این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.DoughnutHoleSize خواندنی/قابل نوشتن استفاده کنید. فقط خواندنی Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | نمودار خطاهای یک سری با جهت X را نشان می‌دهد. خطاهای با جهت X برای سری‌های نوع area، bar، scatter و bubble در دسترس هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (شامل نمودارهای ۳بعدی). در صورت استفاده از مقادیر سفارشی از مجموعه DataPoints برای مشخص کردن مقدار (با ویژگی [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)) استفاده کنید. فقط خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | نمودار خطاهای یک سری با جهت Y را نشان می‌دهد. خطاهای با جهت Y برای سری‌های نوع area، bar، line، scatter و bubble در دسترس هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (شامل نمودارهای ۳بعدی). در صورت استفاده از مقادیر سفارشی از مجموعه DataPoints برای مشخص کردن مقدار (با ویژگی [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)) استفاده کنید. فقط خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | فاصلهٔ یک برش دایره‌ای باز از مرکز نمودار دایره به صورت درصدی از قطر دایره بیان می‌شود. خواندنی/قابل نوشتن Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | زاویهٔ اولین برش نمودار دایره یا دونات را بر حسب درجه مشخص می‌کند (ساعت‌گرد از بالا، از ۰ تا ۳۶۰ درجه). این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.FirstSliceAngle خواندنی/قابل نوشتن استفاده کنید. فقط خواندنی UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | قالب یک سری را برمی‌گرداند. فقط خواندنی [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | فاصلهٔ بین سری‌های داده در یک نمودار ۳بعدی را به صورت درصدی از عرض نشانگر برمی‌گرداند یا تنظیم می‌کند. این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.GapDepth خواندنی/قابل نوشتن استفاده کنید. فقط خواندنی Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | فاصلهٔ بین خوشه‌های میله یا ستون را به صورت درصدی از عرض میله یا ستون مشخص می‌کند. این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.GapWidth خواندنی/قابل نوشتن استفاده کنید. فقط خواندنی Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | تعیین می‌کند آیا خطوط سری برای این سری و سری‌های مرتبط وجود دارند یا خیر. این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.HasSeriesLines خواندنی/قابل نوشتن استفاده کنید. برای قالب‌بندی خطوط سری از ویژگی ParentSeriesGroup.SeriesLinesFormat استفاده کنید. فقط خواندنی Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | تعیین می‌کند آیا نمودار خط یا سهام دارای میله‌های بالا/پایین است یا خیر. این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.UpDownBars.HasUpDownBars خواندنی/قابل نوشتن استفاده کنید. برای قالب‌بندی میله‌های بالا/پایین از ویژگی ParentSeriesGroup.UpDownBars استفاده کنید. فقط خواندنی Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | رنگ جامد معکوس برای سری را مشخص می‌کند. برای اعمال تنظیم رنگ، نوع پر کردن قالب سری را به FillType.Solid تنظیم کنید. خواندنی/قابل نوشتن [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | مشخص می‌کند میله، ستون یا سری حبابی رنگ‌های خود را در صورت منفی بودن مقدار معکوس کند. خواندنی/قابل نوشتن Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | مشخص می‌کند هر نشانگر داده در سری رنگ متفاوتی داشته باشد. این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.IsColorVaried خواندنی/قابل نوشتن استفاده کنید. فقط خواندنی Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | برچسب‌های یک سری را برمی‌گرداند. فقط خواندنی [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | نشانگر. فقط خواندنی [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | نام سری را برمی‌گرداند. فقط خواندنی [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. خواندنی/قابل نوشتن String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. خواندنی/قابل نوشتن String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. خواندنی/قابل نوشتن String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. خواندنی/قابل نوشتن String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | ترتیب یک سری را برمی‌گرداند. خواندنی/قابل نوشتن Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | مشخص می‌کند میله‌ها و ستون‌ها تا چه اندازه در نمودارهای دو‌بعدی همپوشانی داشته باشند، به صورت درصد (از -100٪ تا 100٪). این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است. برای تغییر مقدار، از ویژگی !:ParentSeriesGroup.Overlap خواندنی/قابل نوشتن استفاده کنید. فقط خواندنی SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | طرح‌بندی برچسب‌های دسته‌بندی والد را نشان می‌دهد. فقط برای نمودارهای Treemap اعمال می‌شود. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. فقط خواندنی [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | مشخص می‌کند چگونه تعیین شود کدام نقاط داده در دایره یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار گیرند. این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.PieSplitBy خواندنی/قابل نوشتن استفاده کنید. فقط خواندنی [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای یک نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی را شامل می‌شود. نقاط داده‌ای که باید در دایره یا میله دوم رسم شوند را در بر دارد. این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. فقط خواندنی [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | مقداری را که برای تعیین اینکه کدام نقاط داده در دایره یا میله دوم قرار گیرند استفاده می‌شود، مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.PieSplitPosition خواندنی/قابل نوشتن استفاده کنید. فقط خواندنی Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | نشان می‌دهد آیا این سری روی محور ثانویه رسم می‌شود یا خیر. خواندنی/قابل نوشتن Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | روش چارک نمایی را نشان می‌دهد. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | ورودی افسانه مربوط به این سری را نشان می‌دهد. فقط خواندنی [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | اندازهٔ دایره یا میلهٔ دوم در یک نمودار pie-of-pie یا bar-of-pie را به صورت درصدی از اندازهٔ دایره یا میلهٔ اول مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). این ویژگی نه فقط برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.SecondPieSize خواندنی/قابل نوشتن استفاده کنید. فقط خواندنی UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | خطوط اتصال را نشان می‌دهد. فقط برای نمودارهای Waterfall اعمال می‌شود. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | نقاط داخلی را نشان می‌دهد. اگر نقاط داخلی در نمودار BoxAndWhisker نشان داده شوند، مقدار True است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/قابل نوشتن Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | خط میانگین را نشان می‌دهد. اگر خط میانگین در نمودار BoxAndWhisker نشان داده شود، مقدار True است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/قابل نوشتن Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | نشانگرهای میانگین را نشان می‌دهد. اگر نشانگرهای میانگین در نمودار BoxAndWhisker نشان داده شوند، مقدار True است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/قابل نوشتن Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | نقاط دورافتاده را نشان می‌دهد. اگر نقاط دورافتاده در نمودار BoxAndWhisker نشان داده شوند، مقدار True است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/قابل نوشتن Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | هموارسازی منحنی را نشان می‌دهد. اگر هموارسازی منحنی برای نمودار خطی یا نقطه‌ای فعال باشد، مقدار True است. فقط برای نمودارهای خطی و نقطه‌ای متصل به خطوط اعمال می‌شود. خواندنی/قابل نوشتن Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | مجموعه‌ای از خطوط روند سری‌ها. فقط خواندنی [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | نوع این سری را برمی‌گرداند. خواندنی/قابل نوشتن [`ChartType`](../charttype). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | یک رنگ خودکار برای سری بر اساس اندیس سری و سبک نمودار برمی‌گرداند. این رنگ به‌صورت پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد. |

### مراجعه کنید

* رابط [IChartSeries](../ichartseries)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->