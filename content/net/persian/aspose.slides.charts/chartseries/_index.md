---
title: ChartSeries
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک سری نمودار است.
type: docs
weight: 1440
url: /fa/aspose.slides.charts/chartseries/
---
## ChartSeries کلاس

نمایانگر یک سری نمودار است.

```csharp
public class ChartSeries : IChartSeries
```

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | شکل یک سری نمودار میله‌ای ۳-بعدی را تعیین می‌کند. تغییر مقدار این خصوصیت می‌تواند منجر به تغییر خودکار نوع سری شود. خواندن/نوشتن [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | نحوه نمایش مقادیر اندازه حباب‌ها در نمودار حبابی را تعیین می‌کند. این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.BubbleSizeRepresentation خواندن/نوشتن استفاده کنید. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | فاکتور مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد اندازه پیش‌فرض باشد). این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.BubbleSizeScale خواندن/نوشتن استفاده کنید. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | نمودار والد را برمی‌گرداند. فقط-خواندنی [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | مجموعه نقاط داده این سری را برمی‌گرداند. فقط-خواندنی [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | اندازه سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین ۱۰ تا ۹۰ درصد اندازه ناحیه رسم باشد). این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.DoughnutHoleSize خواندن/نوشتن استفاده کنید. فقط-خواندنی Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | نمایش ErrorBars سری با جهت X. ErrorBars با جهت X برای سری‌های نوع area، bar، scatter و bubble در دسترس هستند. برای سایر انواع نمودار این خصوصیت null برمی‌گرداند (از جمله نمودارهای 3D). در صورت استفاده از مقادیر سفارشی، از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با خصوصیت [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). فقط-خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | نمایش ErrorBars سری با جهت Y. ErrorBars با جهت Y برای سری‌های نوع area، bar، line، scatter و bubble در دسترس هستند. برای سایر انواع نمودار این خصوصیت null برمی‌گرداند (از جمله نمودارهای 3D). در صورت استفاده از مقادیر سفارشی، از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با خصوصیت [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). فقط-خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | فاصله یک برش پیت باز از مرکز نمودار پیت به صورت درصدی از قطر پیت بیان می‌شود. خواندن/نوشتن Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | زاویه اولین برش پیت یا دونات را بر حسب درجه (ساعتگرد از بالا، از ۰ تا ۳۶۰ درجه) تعیین می‌کند. این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.FirstSliceAngle خواندن/نوشتن استفاده کنید. فقط-خواندنی UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | قالب یک سری را برمی‌گرداند. فقط-خواندنی [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | فاصله را به عنوان درصدی از عرض نشانگر بین سری‌های داده در یک نمودار 3D برمی‌گرداند یا تنظیم می‌کند. این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.GapDepth خواندن/نوشتن استفاده کنید. فقط-خواندنی Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | فضای بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون مشخص می‌کند. این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.GapWidth خواندن/نوشتن استفاده کنید. فقط-خواندنی Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | تعیین می‌کند آیا خطوط سری برای این سری و سری‌های مرتبط وجود دارد یا خیر. این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.HasSeriesLines خواندن/نوشتن استفاده کنید. برای قالب‌بندی خطوط سری از خصوصیت ParentSeriesGroup.SeriesLinesFormat استفاده کنید. فقط-خواندنی Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | تعیین می‌کند آیا نمودار خطی یا سهام دارای نوارهای بالا/پایین است یا خیر. این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.UpDownBars.HasUpDownBars خواندن/نوشتن استفاده کنید. برای قالب‌بندی نوارهای بالا/پایین از خصوصیت ParentSeriesGroup.UpDownBars استفاده کنید. فقط-خواندنی Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | رنگ ثابت معکوس برای سری را تعیین می‌کند. برای اعمال تنظیم رنگ، نوع پر کردن سری را به FillType.Solid تنظیم کنید. خواندن/نوشتن [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | مشخص می‌کند که اگر مقدار منفی باشد، سری میله، ستون یا حباب رنگ‌های خود را معکوس کند. خواندن/نوشتن Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | تعیین می‌کند که هر نشانگر داده در سری رنگ متفاوتی داشته باشد. این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.IsColorVaried خواندن/نوشتن استفاده کنید. فقط-خواندنی Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | برچسب‌های یک سری را برمی‌گرداند. فقط-خواندنی [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | نشانگر. فقط-خواندنی [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | نام سری را برمی‌گرداند. فقط-خواندنی [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. خواندن/نوشتن String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. خواندن/نوشتن String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. خواندن/نوشتن String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. خواندن/نوشتن String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | ترتیب یک سری را برمی‌گرداند. خواندن/نوشتن Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | تعیین می‌کند که میله‌ها و ستون‌ها در نمودارهای ۲-بعدی چقدر روی هم پوشانده شوند، به عنوان درصد (از -۱۰۰٪ تا ۱۰۰٪). این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است. بنابراین این خصوصیت فقط-خواندنی است. برای تغییر مقدار از خصوصیت ParentSeriesGroup.Overlap خواندن/نوشتن استفاده کنید. فقط-خواندنی SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | نمایی از برچسب‌های دسته والد را نشان می‌دهد. فقط برای نمودارهای Treemap کاربرد دارد. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. فقط-خواندنی [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | تعیین می‌کند چگونه نقاط داده‌ای که در دایره یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، انتخاب شوند. این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.PieSplitBy خواندن/نوشتن استفاده کنید. فقط-خواندنی [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی را شامل می‌شود. شامل نقاط داده‌ای است که باید در دایره یا میله دوم رسم شوند. این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه است. فقط-خواندنی [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | مقدار مورد استفاده برای تعیین نقاط داده‌ای که در دایره یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند را مشخص می‌کند. همراه با خصوصیت PieSplitBy استفاده می‌شود. این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.PieSplitPosition خواندن/نوشتن استفاده کنید. فقط-خواندنی Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | نشان می‌دهد آیا این سری بر محور ثانویه رسم می‌شود یا خیر. خواندن/نوشتن Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | نمایانگر روش چارک‌کویی است. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | ورودی افسانه مرتبط با این سری را نشان می‌دهد. فقط-خواندنی [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | اندازه دایره یا میله دوم در نمودار pie-of-pie یا bar-of-pie را به عنوان درصدی از اندازه اولین دایره تعیین می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). این خصوصیت نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروژکشن از خصوصیت مناسب گروه می‌باشد. بنابراین این خصوصیت فقط-خواندنی است. برای دسترسی به گروه سری والد از خصوصیت ParentSeriesGroup استفاده کنید. برای تغییر مقدار از خصوصیت ParentSeriesGroup.SecondPieSize خواندن/نوشتن استفاده کنید. فقط-خواندنی UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | نمایانگر خطوط اتصال است. فقط برای نمودارهای Waterfall کاربرد دارد. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | نمایانگر نقاط داخلی است. اگر نقاط داخلی در نمودار BoxAndWhisker نشان داده شوند، مقدار True است. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. خواندن/نوشتن Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | نمایانگر خط میانگین است. اگر خط میانگین در نمودار BoxAndWhisker نشان داده شود، مقدار True است. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. خواندن/نوشتن Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | نمایانگر نشانگرهای میانگین است. اگر نشانگرهای میانگین در نمودار BoxAndWhisker نشان داده شوند، مقدار True است. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. خواندن/نوشتن Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | نمایانگر نقاط دورافتاده است. اگر نقاط دورافتاده در نمودار BoxAndWhisker نشان داده شوند، مقدار True است. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. خواندن/نوشتن Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | نمایانگر صاف‌سازی منحنی است. اگر صاف‌سازی منحنی برای نمودار خطی یا پراکندگی فعال باشد، مقدار True است. فقط برای نمودارهای خطی و پراکندگی متصل به خطوط کاربرد دارد. خواندن/نوشتن Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | مجموعه خطوط روند سری‌ها. فقط-خواندنی [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | نوع این سری را برمی‌گرداند. خواندن/نوشتن [`ChartType`](../charttype). |

## متدها

| Name | Description |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | یک رنگ خودکار برای سری بر اساس اندیس سری و سبک نمودار برمی‌گرداند. این رنگ به‌طور پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد. |

### مراجع

* رابط [IChartSeries](../ichartseries)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->