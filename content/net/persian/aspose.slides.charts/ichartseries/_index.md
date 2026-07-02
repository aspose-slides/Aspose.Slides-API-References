---
title: IChartSeries
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایش‌دهنده یک سری نمودار.
type: docs
weight: 1930
url: /fa/aspose.slides.charts/ichartseries/
---
## IChartSeries رابط

نمایش‌دهنده یک سری نمودار.

```csharp
public interface IChartSeries : IChartComponent
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | امکان دریافت رابط پایه IChartComponent را می‌دهد. فقط-خواندنی [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | شکل یک سری نمودار میله‌ای سه‌بعدی را مشخص می‌کند. تغییر مقدار این ویژگی می‌تواند باعث تغییر خودکار Type سری شود. خواندنی/نوشتنی [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | نحوه نمایش مقادیر اندازه حباب‌ها در نمودار حبابی را مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeRepresentation خواندنی/نوشتنی استفاده کنید. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | مقیاس‌ساز برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد اندازه پیش‌فرض باشد). این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeScale خواندنی/نوشتنی استفاده کنید. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | مجموعه‌ای از نقاط داده این سری را برمی‌گرداند. فقط-خواندنی [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | اندازه‌ٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد اندازهٔ ناحیه نمودار باشد). این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.DoughnutHoleSize خواندنی/نوشتنی استفاده کنید. فقط-خواندنی Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | نشانگر ErrorBars سری با جهت X را نشان می‌دهد. ErrorBars با جهت X برای سری‌های نوع area, bar, scatter و bubble قابل استفاده است. برای دیگر انواع نمودار این ویژگی مقدار null برمی‌گرداند (از جمله نمودارهای 3D). برای مقادیر سفارشی از مجموعه DataPoints با ویژگی [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) استفاده کنید. فقط-خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | نشانگر ErrorBars سری با جهت Y را نشان می‌دهد. ErrorBars با جهت Y برای سری‌های نوع area, bar, line, scatter و bubble قابل استفاده است. برای دیگر انواع نمودار این ویژگی مقدار null برمی‌گرداند (از جمله نمودارهای 3D). برای مقادیر سفارشی از مجموعه DataPoints با ویژگی [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) استفاده کنید. فقط-خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | فاصلهٔ یک برش باز پیت از مرکز نمودار پیت به صورت درصدی از قطر پیت بیان می‌شود. خواندنی/نوشتنی Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | زاویهٔ اولین برش پیت یا دونات را بر حسب درجه (به جهت ساعتگرد از بالا، از 0 تا 360 درجه) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.FirstSliceAngle خواندنی/نوشتنی استفاده کنید. فقط-خواندنی UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | قالب یک سری را برمی‌گرداند. فقط-خواندنی [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | فاصلهٔ بین سری‌های داده در نمودار سه‌بعدی را به عنوان درصدی از عرض مارکر مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapDepth خواندنی/نوشتنی استفاده کنید. فقط-خواندنی Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | فاصلهٔ بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapWidth خواندنی/نوشتنی استفاده کنید. فقط-خواندنی Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | تعیین می‌کند آیا خطوط سری برای این سری و سری‌های مرتبط وجود دارد یا نه. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.HasSeriesLines خواندنی/نوشتنی استفاده کنید. برای قالب‌بندی خطوط سری از ویژگی ParentSeriesGroup.SeriesLinesFormat استفاده کنید. فقط-خواندنی Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | تعیین می‌کند آیا نمودار خطی یا سهام‌بری دارای نوارهای صعودی/نزولی است یا نه. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.UpDownBars.HasUpDownBars خواندنی/نوشتنی استفاده کنید. برای قالب‌بندی نوارهای صعودی/نزولی از ویژگی ParentSeriesGroup.UpDownBars استفاده کنید. فقط-خواندنی Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | رنگ جامد معکوس برای سری را مشخص می‌کند. برای اعمال تنظیم رنگ، FillType قالب سری را روی FillType.Solid تنظیم کنید. خواندنی/نوشتنی [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | تعیین می‌کند که میله، ستون یا سری حبابی رنگ‌های خود را در صورت منفی بودن مقدار معکوس کند. خواندنی/نوشتنی Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | تعیین می‌کند که هر مارکر داده‌ای در سری رنگ متفاوتی داشته باشد. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.IsColorVaried خواندنی/نوشتنی استفاده کنید. فقط-خواندنی Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | برچسب‌های یک سری را برمی‌گرداند. فقط-خواندنی [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | مارکر سری را برمی‌گرداند. فقط-خواندنی [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | نام سری را برمی‌گرداند. فقط-خواندنی [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | قالب عددی برای اندازه‌های حباب‌های سری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | قالب عددی برای مقادیر سری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | قالب عددی برای مقادیر x سری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | قالب عددی برای مقادیر y سری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | ترتیب یک سری را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | میزان هم‌پوشانی میله‌ها و ستون‌ها در نمودارهای دو-بعدی را به صورت درصد (از -100٪ تا 100٪) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.Overlap خواندنی/نوشتنی استفاده کنید. فقط-خواندنی SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | نمایان‌سازی چیدمان برچسب‌های دسته‌بندی والد را نشان می‌دهد. فقط برای نمودارهای Treemap اعمال می‌شود. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | گروه سری والد را برمی‌گرداند. فقط-خواندنی [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | تعیین می‌کند که چه نقاط داده‌ای در دومین پیت یا میله در نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitBy خواندنی/نوشتنی استفاده کنید. فقط-خواندنی [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی را شامل می‌شود. حاوی نقاط داده‌ای است که باید در دومین پیت یا میله رسم شوند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. فقط-خواندنی [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | مقداری را مشخص می‌کند که برای تعیین نقاط داده‌ای که در دومین پیت یا میله قرار می‌گیرند استفاده می‌شود. همراه با ویژگی PieSplitBy به‌کار می‌رود. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitPosition خواندنی/نوشتنی استفاده کنید. فقط-خواندنی Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | نشان می‌دهد که این سری بر روی محور مقدار دوم رسم می‌شود یا نه. خواندنی/نوشتنی Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | روش چارک را نشان می‌دهد. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | ورودی افسانه مرتبط با این سری را برمی‌گرداند. فقط-خواندنی [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | اندازهٔ دومین پیت یا میله در نمودار pie-of-pie یا bar-of-pie را به عنوان درصدی از اندازه پیت اول (می‌تواند بین 5 تا 200 درصد باشد) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است – این یک بازتاب از ویژگی گروه مربوطه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.SecondPieSize خواندنی/نوشتنی استفاده کنید. فقط-خواندنی UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | خطوط اتصال را نشان می‌دهد. فقط برای نمودارهای Waterfall اعمال می‌شود. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | نقاط داخلی را نشان می‌دهد. اگر true باشد، نقاط داخلی در نمودار BoxAndWhisker نشان داده می‌شوند. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/نوشتنی Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | نشانگرهای میانگین را نشان می‌دهد. اگر true باشد، خط میانگین در نمودار BoxAndWhisker نشان داده می‌شود. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/نوشتنی Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | نشانگرهای میانگین را نشان می‌دهد. اگر true باشد، نشانگرهای میانگین در نمودار BoxAndWhisker نشان داده می‌شوند. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/نوشتنی Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | نقاط پرت را نشان می‌دهد. اگر true باشد، نقاط پرت در نمودار BoxAndWhisker نشان داده می‌شوند. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. خواندنی/نوشتنی Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | صاف‌سازی منحنی را نشان می‌دهد. اگر true باشد، صاف‌سازی منحنی برای نمودار خطی یا نقطه‌ای فعال می‌شود. فقط برای نمودارهای خطی و نقطه‌ای که به‌وسیله خطوط به هم متصل هستند اعمال می‌شود. خواندنی/نوشتنی Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | مجموعه‌ای از خطوط روند سری را برمی‌گرداند. فقط-خواندنی [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | نوع این سری را برمی‌گرداند. خواندنی/نوشتنی [`ChartType`](../charttype). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | یک رنگ خودکار برای سری بر پایهٔ اندیس سری و سبک نمودار برمی‌گرداند. این رنگ به‌طور پیش‌فرض زمانی استفاده می‌شود که FillType برابر NotDefined باشد. |

### موارد مرتبط

* رابط [IChartComponent](../ichartcomponent)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->