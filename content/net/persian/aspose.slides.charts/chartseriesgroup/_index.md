---
title: ChartSeriesGroup
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر گروهی از سری‌ها.
type: docs
weight: 1460
url: /fa/aspose.slides.charts/chartseriesgroup/
---
## کلاس ChartSeriesGroup

نمایانگر گروهی از سری‌ها.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | مشخص می‌کند مقادیر اندازهٔ حباب‌ها چگونه در نمودار حبابی نمایش داده شوند. قابل خواندن/نوشتن [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | مقیاس‌عامل نمودار حبابی را تعیین می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد از اندازهٔ پیش‌فرض باشد). قابل خواندن/نوشتن Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | نمودار والد را برمی‌گرداند. فقط-خواندنی [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین ۰ تا ۹۰ درصد از اندازهٔ ناحیهٔ نمودار باشد). قابل خواندن/نوشتن Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | زاویهٔ اولین برش نمودار دایره‌ای یا دونات را بر حسب درجه دریافت یا تنظیم می‌کند (ساعتگرد از بالا، از ۰ تا ۳۶۰ درجه). قابل خواندن/نوشتن UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | فاصله را به‌عنوان درصدی از عرض نشانگر بین سری‌های داده‌ای در نمودار ۳‌بعدی برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | فاصله بین خوشه‌های نوار یا ستون را به‌عنوان درصدی از عرض نوار یا ستون مشخص می‌کند. قابل خواندن/نوشتن UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | اگر نمودار خطوط سری داشته باشد، مقدار True است. برای نمودارهای نوار انباشته و OfPie اعمال می‌شود. قابل خواندن/نوشتن Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | قالب HiLowLines را مشخص می‌کند. HiLowLines همراه با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | مشخص می‌کند هر نشانگر داده در سری رنگ متفاوتی داشته باشد. قابل خواندن/نوشتن Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | عنصری که در اندیس مشخص شده قرار دارد را دریافت می‌کند. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | مشخص می‌کند نوارها و ستون‌ها در نمودارهای دو-بعدی چقدر باید همپوشانی داشته باشند، به‌صورت درصد (از -۱۰۰٪ تا ۱۰۰٪). - -۱۰۰٪: بیشترین فاصله (نوارها کاملاً جدا هستند). - ۰٪: نوارها بدون همپوشانی یا فاصله کنار هم قرار می‌گیرند. - ۱۰۰٪: بیشترین همپوشانی (نوارها کاملاً بر یکدیگر همپوشانی می‌شوند). این ویژگی قابل خواندن/نوشتن SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | نحوه تعیین اینکه کدام نقاط داده در دایرهٔ دوم یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار گیرند را مشخص می‌کند. قابل خواندن/نوشتن [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای یک نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در دایرهٔ دوم یا نوار دوم در یک نمودار pie-of-pie یا bar-of-pie رسم شوند. فقط-خواندنی [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | مقدارِی را مشخص می‌کند که برای تعیین اینکه کدام نقاط داده در دایرهٔ دوم یا نوار دوم در یک نمودار pie-of-pie یا bar-of-pie قرار گیرند استفاده می‌شود. همراه با ویژگی PieSplitBy استفاده می‌شود. قابل خواندن/نوشتن Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | نشان می‌دهد آیا سری‌های این گروه بر روی محور ثانویه رسم می‌شوند یا خیر. فقط-خواندنی Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | اندازهٔ دایرهٔ دوم یا نوار دوم در یک نمودار pie-of-pie یا bar-of-pie را به‌عنوان درصدی از اندازهٔ اولین دایره مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). قابل خواندن/نوشتن UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | مجموعه‌ای از سری‌ها را برمی‌گرداند. فقط-خواندنی [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | نوع این گروه سری را برمی‌گرداند. فقط-خواندنی [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | دسترسی به نوارهای بالا/پایین نمودار خط یا سهام را فراهم می‌کند. فقط-خواندنی [`IUpDownBarsManager`](../iupdownbarsmanager). |

### یادداشت‌ها

1) خلاصه و یادداشت‌های مربوط به کلاس ChartSeriesGroupCollection و شمارش CombinableSeriesTypesGroup را ببینید. 2) گروهی از سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("ویژگی‌های گروه سری"). «ویژگی‌های گروه سری» در کلاس ChartSeriesGroup قابل خواندن/نوشتن است. هر یک از «ویژگی‌های گروه سری» می‌تواند یک نمای فقط-خواندنی در کلاس ChartSeries داشته باشد.

### مطالب مرتبط

* رابط [IChartSeriesGroup](../ichartseriesgroup)
* فضای‌نامی [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->