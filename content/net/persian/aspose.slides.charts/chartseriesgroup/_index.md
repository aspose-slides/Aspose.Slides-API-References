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

| نام | توضیح |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | مشخص می‌کند مقادیر اندازهٔ حباب چگونه در نمودار حباب نمایش داده می‌شوند. قابل خواندن/نوشتن [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | مشخص می‌کند ضریب مقیاس برای نمودار حباب (می‌تواند بین 0 و 300 درصد از اندازهٔ پیش‌فرض باشد). قابل خواندن/نوشتن Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | نشان می‌دهد نمودار والد. فقط-خواندنی [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | مشخص می‌کند اندازهٔ حفره در نمودار دونات (می‌تواند بین 0 و 90 درصد از اندازهٔ ناحیهٔ نمودار باشد). قابل خواندن/نوشتن Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | زاویهٔ اولین برش نمودار پای یا دونات را دریافت یا تنظیم می‌کند، به درجه (ساعت‌گرد از بالا، از 0 تا 360 درجه). قابل خواندن/نوشتن UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | فاصله را به‌عنوان درصدی از عرض نشانگر بین سری‌های داده در نمودار 3-بعدی دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | فضای بین خوشه‌های میله یا ستون را به‌عنوان درصدی از عرض میله یا ستون مشخص می‌کند. قابل خواندن/نوشتن UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True اگر نمودار خطوط سری داشته باشد. برای میله‌های انباشته و نمودارهای OfPie اعمال می‌شود. قابل خواندن/نوشتن Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | قالب HiLowLines را مشخص می‌کند. HiLowLines همراه با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | مشخص می‌کند هر نشانگر داده در سری رنگ متفاوتی داشته باشد. قابل خواندن/نوشتن Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | عنصر را در اندیس مشخص دریافت می‌کند. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | مشخص می‌کند میله‌ها و ستون‌ها در نمودارهای دو-بعدی تا چه میزان روی هم قرار بگیرند، به‌صورت درصدی (از -100% تا 100%). - -100%: حداکثر فاصله (میله‌ها کاملاً جدا هستند). - 0%: میله‌ها کنار هم بدون هم‌پوشانی یا فاصله قرار می‌گیرند. - 100%: حداکثر هم‌پوشانی (میله‌ها کاملاً روی هم هستند). این ویژگی قابل خواندن/نوشتن SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | مشخص می‌کند چگونه تعیین شود کدام نقاط داده در پای دوم یا میله دوم در نمودار Pie-of-Pie یا Bar-of-Pie قرار گیرند. قابل خواندن/نوشتن [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای نمودار Pie-of-Pie یا Bar-of-Pie با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در پای یا میلهٔ دوم در نمودار Pie-of-Pie یا Bar-of-Pie رسم شوند. فقط-خواندنی [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | مقداری را مشخص می‌کند که برای تعیین نقاط دادهٔ در پای یا میلهٔ دوم در نمودار Pie-of-Pie یا Bar-of-Pie استفاده می‌شود. همراه با ویژگی PieSplitBy استفاده می‌شود. قابل خواندن/نوشتن Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | نشان می‌دهد آیا سری‌های این گروه بر روی محور ثانویه ترسیم می‌شوند. فقط-خواندنی Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | اندازهٔ پای یا میلهٔ دوم در نمودار Pie-of-Pie یا Bar-of-Pie را به‌عنوان درصدی از اندازهٔ پای اول مشخص می‌کند (می‌تواند بین 5 و 200 درصد باشد). قابل خواندن/نوشتن UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | یک مجموعه از سری‌ها را بازمی‌گرداند. فقط-خواندنی [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | نوع این گروه سری را بازمی‌گرداند. فقط-خواندنی [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | دسترسی به میله‌های بالا/پایین نمودار خط یا سهام را فراهم می‌کند. فقط-خواندنی [`IUpDownBarsManager`](../iupdownbarsmanager). |

### توضیحات

1) خلاصه و یادداشت‌ها را برای کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup ببینید. 2) گروه سری‌ها شامل برخی از ویژگی‌های سری است که برای هر سری در گروه مشترک است ("ویژگی‌های گروه سری"). "ویژگی‌های گروه سری" در کلاس ChartSeriesGroup قابل خواندن/نوشتن است. هر یک از "ویژگی‌های گروه سری" می‌توانند یک پروجکشن فقط-خواندنی در کلاس ChartSeries داشته باشند.

### موارد مرتبط

* رابط [IChartSeriesGroup](../ichartseriesgroup)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->