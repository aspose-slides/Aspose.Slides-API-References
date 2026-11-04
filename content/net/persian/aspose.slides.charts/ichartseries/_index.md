---
title: IChartSeries
second_title: Aspose.Sildes برای .NET مرجع API
description: یک سری نمودار را نمایش می‌دهد.
type: docs
weight: 1950
url: /fa/aspose.slides.charts/ichartseries/
---
## IChartSeries رابط

یک سری نمودار را نمایش می‌دهد.

```csharp
public interface IChartSeries : IChartComponent
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | اجازه می‌دهد رابط پایه IChartComponent را دریافت کند. فقط خواندنی [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | مشخص می‌کند شکل یک سری در نمودار میله‌ای ۳-بعدی. تغییر مقدار این ویژگی می‌تواند باعث تغییر خودکار نوع سری شود. قابل خواندن/نوشتن [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | مشخص می‌کند مقادیر اندازه حباب‌ها در نمودار حبابی چگونه نمایش داده شوند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مربوطه در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeRepresentation که قابل خواندن/نوشتن است، استفاده کنید. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | ضریب مقیاس نمودار حبابی را مشخص می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد اندازه پیش‌فرض باشد). این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.BubbleSizeScale که قابل خواندن/نوشتن است، استفاده کنید. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | مجموعه‌ای از نقاط داده این سری را باز می‌گرداند. فقط خواندنی [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | اندازه حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین ۱۰ تا ۹۰ درصد از اندازه ناحیه نمودار باشد). این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.DoughnutHoleSize که قابل خواندن/نوشتن است، استفاده کنید. فقط خواندنی Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | نمایانگر نوارهای خطا برای سری با جهت X است. نوارهای خطا با جهت X برای سری‌های نوع area, bar, scatter و bubble در دسترس هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (شامل نمودارهای ۳-بعدی). در صورت استفاده از مقادیر سفارشی، از مجموعه DataPoints برای تعیین مقدار (با ویژگی [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)) استفاده کنید. فقط خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | نمایانگر نوارهای خطا برای سری با جهت Y است. نوارهای خطا با جهت Y برای سری‌های نوع area, bar, line, scatter و bubble در دسترس هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (شامل نمودارهای ۳-بعدی). در صورت استفاده از مقادیر سفارشی، از مجموعه DataPoints برای تعیین مقدار (با ویژگی [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)) استفاده کنید. فقط خواندنی [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | فاصله یک قطعهٔ پی باز از مرکز نمودار پی به صورت درصدی از قطر پی بیان می‌شود. قابل خواندن/نوشتن Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | زاویهٔ اولین قطعهٔ نمودار پی یا دونات را بر حسب درجه (ساعت‌گرد از بالا، از ۰ تا ۳۶۰ درجه) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.FirstSliceAngle که قابل خواندن/نوشتن است، استفاده کنید. فقط خواندنی UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | قالب یک سری را باز می‌گرداند. فقط خواندنی [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | فاصله را به عنوان درصدی از عرض نشانگر بین سری‌های داده در یک نمودار ۳-بعدی باز می‌گرداند یا تنظیم می‌کند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapDepth که قابل خواندن/نوشتن است، استفاده کنید. فقط خواندنی Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | فضای بین خوشه‌های میله یا ستون را به صورت درصدی از عرض میله یا ستون مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.GapWidth که قابل خواندن/نوشتن است، استفاده کنید. فقط خواندنی Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | تعیین می‌کند آیا خطوط سری برای این سری و سری‌های مرتبط وجود دارد یا نه. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.HasSeriesLines که قابل خواندن/نوشتن است، استفاده کنید. برای قالب‌بندی خطوط سری از ویژگی ParentSeriesGroup.SeriesLinesFormat استفاده کنید. فقط خواندنی Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | تعیین می‌کند آیا نمودار خطی یا سهام دارای میله‌های بالا/پایین است یا نه. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.UpDownBars.HasUpDownBars که قابل خواندن/نوشتن است، استفاده کنید. برای قالب‌بندی میله‌های بالا/پایین از ویژگی ParentSeriesGroup.UpDownBars استفاده کنید. فقط خواندنی Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | رنگ ثابت معکوس برای سری را مشخص می‌کند. برای اعمال تنظیم رنگ، نوع پر کردن قالب سری را به FillType.Solid تنظیم کنید. قابل خواندن/نوشتن [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | مشخص می‌کند که اگر مقدار منفی باشد، میله، ستون یا سری حبابی رنگ‌های خود را معکوس می‌کند. قابل خواندن/نوشتن Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | مشخص می‌کند هر نشانگر داده در سری رنگ متفاوتی داشته باشد. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.IsColorVaried که قابل خواندن/نوشتن است، استفاده کنید. فقط خواندنی Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | برچسب‌های یک سری را باز می‌گرداند. فقط خواندنی [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | نشانگر سری را باز می‌گرداند. فقط خواندنی [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | نام سری را باز می‌گرداند. فقط خواندنی [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | قالب عددی برای اندازه‌های حباب‌های سری را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | قالب عددی برای مقادیر سری را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | قالب عددی برای مقادیر x سری را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | قالب عددی برای مقادیر y سری را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | ترتیب یک سری را باز می‌گرداند. قابل خواندن/نوشتن Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | مشخص می‌کند که میله‌ها و ستون‌ها در نمودارهای دو-بعدی چقدر روی هم می‌افتند، به صورت درصد (از -100٪ تا 100٪). این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای تغییر مقدار از ویژگی ParentSeriesGroup.Overlap که قابل خواندن/نوشتن است، استفاده کنید. فقط خواندنی SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | نمایش چیدمان برچسب‌های دسته‌بندی والد را نشان می‌دهد. فقط برای نمودارهای Treemap اعمال می‌شود. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | گروه سری والد را باز می‌گرداند. فقط خواندنی [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | مشخص می‌کند چگونه تعیین شود کدام نقاط داده در پی یا میلهٔ دوم در نمودار پی-در-پی یا میله-در-پی قرار می‌گیرند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitBy که قابل خواندن/نوشتن است، استفاده کنید. فقط خواندنی [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای پی-در-پی یا میله-در-پی با تقسیم سفارشی را شامل می‌شود. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. فقط خواندنی [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | مقداری را که برای تعیین اینکه کدام نقاط داده در پی یا میلهٔ دوم در نمودار پی-در-پی یا میله-در-پی استفاده می‌شود، مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.PieSplitPosition که قابل خواندن/نوشتن است، استفاده کنید. فقط خواندنی Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | مشخص می‌کند آیا این سری روی محور مقدار دوم ترسیم می‌شود یا نه. قابل خواندن/نوشتن Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | روش چارک‌ها را نمایش می‌دهد. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | ورودی افسانه مربوط به این سری را نمایش می‌دهد. فقط خواندنی [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | اندازهٔ پی یا میلهٔ دوم در نمودار پی-در-پی یا میله-در-پی را به عنوان درصدی از اندازهٔ پی اول (می‌تواند بین ۵ تا ۲۰۰ درصد باشد) مشخص می‌کند. این ویژگی نه تنها برای این سری بلکه برای همه سری‌های گروه سری والد است - این یک پروجکشن از ویژگی مناسب در گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی ParentSeriesGroup.SecondPieSize که قابل خواندن/نوشتن است، استفاده کنید. فقط خواندنی UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | خطوط اتصال را نمایش می‌دهد. فقط برای نمودارهای Waterfall اعمال می‌شود. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | نقاط داخلی را نمایش می‌دهد. اگر نقاط داخلی در نمودار BoxAndWhisker نشان داده شوند مقدار True است. فقط برای نمودارهای BoxAndWhisker اعمال می‌شود. قابل خواندن/نوشتن Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | نشانگرهای میانگین را نمایش می‌دهد. اگر خط میانگین در نمودار BoxAndWhisker نشان داده شود مقدار True است. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | نشانگرهای میانگین را نمایش می‌دهد. اگر نشانگرهای میانگین در نمودار BoxAndWhisker نشان داده شوند مقدار True است. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | نقاط دور را نمایش می‌دهد. اگر نقاط دور در نمودار BoxAndWhisker نشان داده شوند مقدار True است. فقط برای نمودارهای BoxAndWhisker کاربرد دارد. قابل خواندن/نوشتن Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | هموارسازی منحنی را نمایش می‌دهد. اگر هموارسازی منحنی برای نمودار خطی یا پراکنده فعال باشد مقدار True است. فقط برای نمودارهای خطی و پراکنده‌ای که به وسیله خطوط به هم متصل هستند، اعمال می‌شود. قابل خواندن/نوشتن Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | مجموعه‌ای از خطوط روند سری‌ها را باز می‌گرداند. فقط خواندنی [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | نوع این سری را باز می‌گرداند. قابل خواندن/نوشتن [`ChartType`](../charttype). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | یک رنگ خودکار برای سری بر مبنای اندیس سری و سبک نمودار برمی‌گرداند. این رنگ به طور پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد. |

### مراجع

* رابط [IChartComponent](../ichartcomponent)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->