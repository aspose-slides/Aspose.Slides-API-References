---
title: IChartSeries
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر یک سری نمودار است.
type: docs
weight: 1930
url: /fa/aspose.slides.charts/ichartseries/
---
## IChartSeries رابط

نمایانگر یک سری نمودار است.

```csharp
public interface IChartSeries : IChartComponent
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | اجازه می‌دهد رابط IChartComponent پایه را دریافت کند. فقط‌خواندنی [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | شکل یک سری از نمودار میله‌ای سه‌بعدی را مشخص می‌کند. تغییر مقدار این ویژگی می‌تواند باعث تغییر خودکار نوع سری شود. خواندنی/نوشتنی [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | مشخص می‌کند مقادیر اندازه حباب‌ها چگونه در نمودار حبابی نشان داده می‌شوند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.BubbleSizeRepresentation خواندنی/نوشتنی استفاده کنید. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | فاکتور مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد اندازه پیش‌فرض باشد). این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.BubbleSizeScale خواندنی/نوشتنی استفاده کنید. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | مجموعه‌ای از نقاط داده این سری را برمی‌گرداند. فقط‌خواندنی [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازه ناحیهٔ رسم باشد). این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.DoughnutHoleSize خواندنی/نوشتنی استفاده کنید. فقط‌خواندنی Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | ErrorBars سری با جهت X را نشان می‌دهد. ErrorBars با جهت X برای سری‌های نوع area، bar، scatter و bubble در دسترس است. برای سایر نوع نمودارها این ویژگی مقدار null را برمی‌گرداند (شامل نمودارهای 3D). در صورت استفاده از مقادیر سفارشی، از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با ویژگی [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). فقط‌خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | ErrorBars سری با جهت Y را نشان می‌دهد. ErrorBars با جهت Y برای سری‌های نوع area، bar، line، scatter و bubble در دسترس است. برای سایر نوع نمودارها این ویژگی مقدار null را برمی‌گرداند (شامل نمودارهای 3D). در صورت استفاده از مقادیر سفارشی، از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با ویژگی [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). فقط‌خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | فاصله یک برش پیت باز از مرکز نمودار پیت به صورت درصدی از قطر پیت بیان می‌شود. خواندنی/نوشتنی Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | زاویه اولین برش پیت یا دونات را به درجه (از بالا به جهت ساعتگرد، از 0 تا 360 درجه) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.FirstSliceAngle خواندنی/نوشتنی استفاده کنید. فقط‌خواندنی UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | فرمت یک سری را برمی‌گرداند. فقط‌خواندنی [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | فاصله، به‌عنوان درصدی از عرض نشانگر، بین سری‌های داده در یک نمودار 3D را برمی‌گرداند یا تنظیم می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.GapDepth خواندنی/نوشتنی استفاده کنید. فقط‌خواندنی Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | فاصله بین خوشه‌های میله یا ستون را به‌عنوان درصدی از عرض میله یا ستون مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.GapWidth خواندنی/نوشتنی استفاده کنید. فقط‌خواندنی Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | تعیین می‌کند آیا خطوط سری برای این سری و سری‌های مرتبط وجود دارد یا خیر. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.HasSeriesLines خواندنی/نوشتنی استفاده کنید. برای فرمت خطوط سری از ویژگی ParentSeriesGroup.SeriesLinesFormat استفاده کنید. فقط‌خواندنی Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | تعیین می‌کند آیا نمودار خط یا سهام دارای میله‌های بالا/پایین است یا خیر. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.UpDownBars.HasUpDownBars خواندنی/نوشتنی استفاده کنید. برای فرمت میله‌های بالا/پایین از ویژگی ParentSeriesGroup.UpDownBars استفاده کنید. فقط‌خواندنی Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | رنگ جامد معکوس برای سری را مشخص می‌کند. برای اعمال تنظیم رنگ، نوع پر کردن سری را بر روی FillType.Solid تنظیم کنید. خواندنی/نوشتنی [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | مشخص می‌کند آیا سری میله، ستون یا حباب رنگ‌های خود را در صورت منفی بودن مقدار معکوس کند. خواندنی/نوشتنی Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | مشخص می‌کند هر نشانگر داده در سری دارای رنگ متفاوت باشد. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.IsColorVaried خواندنی/نوشتنی استفاده کنید. فقط‌خواندنی Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | برچسب‌های یک سری را برمی‌گرداند. فقط‌خواندنی [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | نشانگر سری را برمی‌گرداند. فقط‌خواندنی [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | نام سری را برمی‌گرداند. فقط‌خواندنی [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | فرمت عددی برای اندازه‌های حباب‌های سری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | فرمت عددی برای مقادیر سری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | فرمت عددی برای مقادیر x سری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | فرمت عددی برای مقادیر y سری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | ترتیب یک سری را برمی‌گرداند. خواندنی/نوشتنی Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | میزان همپوشانی میله‌ها و ستون‌ها در نمودارهای 2-بعدی را به‌صورت درصد (از -100% تا 100%) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای تغییر مقدار، از ویژگی ParentSeriesGroup.Overlap خواندنی/نوشتنی استفاده کنید. فقط‌خواندنی SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | نمای کلی برچسب‌های دسته والد را نشان می‌دهد. فقط برای نمودارهای Treemap اعمال می‌شود. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | گروه سری والد را برمی‌گرداند. فقط‌خواندنی [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | تعیین می‌کند چه نقاط داده‌ای در دومین پیت یا میله در نمودارهای pie-of-pie یا bar-of-pie قرار می‌گیرند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.PieSplitBy خواندنی/نوشتنی استفاده کنید. فقط‌خواندنی [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | اطلاعات تقسیم‌سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در دومین پیت یا میله رسم شوند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. فقط‌خواندنی [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | مقداری که برای تعیین نقاط داده در دومین پیت یا میله در نمودارهای pie-of-pie یا bar-of-pie استفاده می‌شود را مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.PieSplitPosition خواندنی/نوشتنی استفاده کنید. فقط‌خواندنی Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | نشان می‌دهد آیا این سری بر روی محور مقدار دوم رسم می‌شود. خواندنی/نوشتنی Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | روش چارک‌تل را نشان می‌دهد. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | ورودی افسانه مرتبط با این سری را نشان می‌دهد. فقط‌خواندنی [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | اندازه دومین پیت یا میله در نمودار pie-of-pie یا bar-of-pie را به‌عنوان درصدی از اندازه اولین پیت مشخص می‌کند (می‌تواند بین 5 تا 200 درصد باشد). این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب گروه است. بنابراین این ویژگی فقط‌خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار، از ویژگی ParentSeriesGroup.SecondPieSize خواندنی/نوشتنی استفاده کنید. فقط‌خواندنی UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | خطوط اتصال را نشان می‌دهد. فقط برای نمودارهای Waterfall اعمال می‌شود. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | نقاط داخلی را نشان می‌دهد. اگر نقاط داخلی در نمودار BoxAndWhisker نشان داده شوند مقدار true است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/نوشتنی Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | نشانگرهای میانگین را نشان می‌دهد. اگر خط میانگین در نمودار BoxAndWhisker نشان داده شود مقدار true است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/نوشتنی Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | نشانگرهای میانگین را نشان می‌دهد. اگر نشانگرهای میانگین در نمودار BoxAndWhisker نشان داده شوند مقدار true است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/نوشتنی Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | نقاط دورریز را نشان می‌دهد. اگر نقاط دورریز در نمودار BoxAndWhisker نشان داده شوند مقدار true است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/نوشتنی Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | صاف‌سازی منحنی را نشان می‌دهد. اگر صاف‌سازی منحنی برای نمودار خطی یا نقطه‌ای فعال باشد مقدار true است. فقط برای نمودارهای خطی و نقطه‌ای که توسط خطوط به هم متصل هستند اعمال می‌شود. خواندنی/نوشتنی Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | مجموعهٔ خطوط روند سری‌ها. فقط‌خواندنی [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | نوع این سری را برمی‌گرداند. خواندنی/نوشتنی [`ChartType`](../charttype). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | رنگ خودکار یک سری را بر اساس شاخص سری و سبک نمودار برمی‌گرداند. این رنگ به‌صورت پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد. |

### موارد مرتبط

* رابط [IChartComponent](../ichartcomponent)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->