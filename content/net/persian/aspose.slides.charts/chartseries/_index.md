---
title: ChartSeries
second_title: مرجع API Aspose.Sildes برای .NET
description: نشان‌دهنده یک سری نمودار.
type: docs
weight: 1440
url: /fa/aspose.slides.charts/chartseries/
---
## کلاس ChartSeries

نشان‌دهنده یک سری نمودار.

```csharp
public class ChartSeries : IChartSeries
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | شکل یک سری از نمودار میله‌ای ۳-بعدی را مشخص می‌کند. تغییر مقدار این ویژگی می‌تواند باعث تغییر خودکار Type سری شود. Read/write [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | نحوه نمایش مقادیر اندازه حباب در نمودار حباب را مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeRepresentation read/write استفاده کنید. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | ضریب مقیاس برای نمودار حباب را مشخص می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد اندازه پیش‌فرض باشد). این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeScale read/write استفاده کنید. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | نمودار والد را برمی‌گرداند. فقط-خواندنی [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | مجموعه‌ای از نقاط داده این سری را برمی‌گرداند. فقط-خواندنی [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین ۱۰ تا ۹۰ درصد اندازه ناحیهٔ طرح باشد). این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.DoughnutHoleSize read/write استفاده کنید. فقط-خواندنی Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | ErrorBarsهای سری با جهت X را نشان می‌دهد. ErrorBarsهای جهت X برای سری‌های نوع area، bar، scatter و bubble در دسترس هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (شامل نمودارهای ۳-بعدی). در صورت استفاده از مقادیر سفارشی، برای مشخص کردن مقدار از مجموعه DataPoints با ویژگی [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) استفاده کنید. فقط-خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | ErrorBarsهای سری با جهت Y را نشان می‌دهد. ErrorBarsهای جهت Y برای سری‌های نوع area، bar، line، scatter و bubble در دسترس هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (شامل نمودارهای ۳-بعدی). در صورت استفاده از مقادیر سفارشی، برای مشخص کردن مقدار از مجموعه DataPoints با ویژگی [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) استفاده کنید. فقط-خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | فاصله یک قطعهٔ باز پیت از مرکز نمودار پیت به صورت درصدی از قطر پیت بیان می‌شود. Read/write Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | زاویهٔ اولین قطعهٔ پیت یا دونات را به درجه (ساعتگرد از بالا، از ۰ تا ۳۶۰ درجه) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.FirstSliceAngle read/write استفاده کنید. فقط-خواندنی UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | قالب یک سری را برمی‌گرداند. فقط-خواندنی [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | فاصله را به صورت درصدی از عرض نشانگر بین سری‌های داده در یک نمودار ۳-بعدی برمی‌گرداند یا تنظیم می‌کند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapDepth read/write استفاده کنید. فقط-خواندنی Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | فضای بین خوشه‌های میله یا ستون را به درصدی از عرض میله یا ستون مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapWidth read/write استفاده کنید. فقط-خواندنی Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | تعیین می‌کند آیا برای این سری و سری‌های مرتبط خطوط سری وجود دارد یا نه. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.HasSeriesLines read/write استفاده کنید. برای فرمت خطوط سری از ویژگی ParentSeriesGroup.SeriesLinesFormat استفاده کنید. فقط-خواندنی Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | تعیین می‌کند آیا نمودار خطی یا سهام دارای نوارهای بالا/پایین است یا نه. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.UpDownBars.HasUpDownBars read/write استفاده کنید. برای فرمت نوارهای بالا/پایین از ویژگی ParentSeriesGroup.UpDownBars استفاده کنید. فقط-خواندنی Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | رنگ جامد معکوس برای سری را مشخص می‌کند. برای اعمال تنظیم رنگ، FillType قالب سری را روی FillType.Solid تنظیم کنید. Read/write [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | تعیین می‌کند که میله، ستون یا سری حباب در صورت مقدار منفی رنگ‌های خود را معکوس کند. Read/write Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | مشخص می‌کند هر نشانگر داده در سری رنگ متفاوتی داشته باشد. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.IsColorVaried read/write استفاده کنید. فقط-خواندنی Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | برچسب‌های یک سری را برمی‌گرداند. فقط-خواندنی [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | نشانگر. فقط-خواندنی [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | نام سری را برمی‌گرداند. فقط-خواندنی [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Read/write String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Read/write String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Read/write String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Read/write String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | ترتیب یک سری را برمی‌گرداند. Read/write Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | میزان همپوشانی میله‌ها و ستون‌ها در نمودارهای دو-بعدی را به درصد (از -۱۰۰٪ تا ۱۰۰٪) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.Overlap read/write استفاده کنید. فقط-خواندنی SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | نمایان‌ساز چیدمان برچسب‌های دسته‌بندی والد. فقط برای نمودارهای Treemap اعمال می‌شود. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. فقط-خواندنی [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | تعیین نحوهٔ تشخیص اینکه کدام نقاط داده در دومین پیت یا میلهٔ نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitBy read/write استفاده کنید. فقط-خواندنی [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی را شامل می‌شود. شامل نقاط داده‌ای است که باید در دومین پیت یا میله رسم شوند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. فقط-خواندنی [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | مقدار استفاده‌شده برای تعیین اینکه کدام نقاط داده در دومین پیت یا میلهٔ نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند را مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitPosition read/write استفاده کنید. فقط-خواندنی Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | نشان می‌دهد آیا این سری روی محور ثانوی رسم می‌شود یا نه. Read/write Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | روش چارکویل را نشان می‌دهد. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | مدخل لگند مرتبط با این سری را نشان می‌دهد. فقط-خواندنی [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | اندازهٔ دومین پیت یا میلهٔ نمودار pie-of-pie یا bar-of-pie را به درصدی از اندازهٔ اولین پیت مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک بازتاب از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.SecondPieSize read/write استفاده کنید. فقط-خواندنی UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | خطوط اتصال را نشان می‌دهد. فقط برای نمودارهای Waterfall اعمال می‌شود. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | نقاط داخلی را نشان می‌دهد. در نمودار BoxAndWhisker اگر نقاط داخلی نشان داده شوند true است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. Read/write Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | خط میانگین را نشان می‌دهد. در نمودار BoxAndWhisker اگر خط میانگین نشان داده شود true است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. Read/write Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | نشانگرهای میانگین را نشان می‌دهد. در نمودار BoxAndWhisker اگر نشانگرهای میانگین نشان داده شوند true است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. Read/write Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | نقاط خارج از محدوده را نشان می‌دهد. در نمودار BoxAndWhisker اگر نقاط خارج از محدوده نشان داده شوند true است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. Read/write Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | صاف‌سازی منحنی را نشان می‌دهد. اگر صاف‌سازی منحنی برای نمودار خطی یا پراکنده فعال باشد true است. فقط برای نمودارهای خطی و پراکنده متصل به خطوط اعمال می‌شود. Read/write Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | مجموعهٔ خطوط روند سری‌ها. فقط-خواندنی [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | نوع این سری را برمی‌گرداند. Read/write [`ChartType`](../charttype). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | یک رنگ خودکار برای سری بر پایهٔ اندیس سری و سبک نمودار برمی‌گرداند. این رنگ به‌صورت پیش‌فرض زمانی استفاده می‌شود که FillType برابر NotDefined باشد. |

### موارد مرتبط

* رابط [IChartSeries](../ichartseries)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->