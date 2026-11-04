---
title: ChartSeriesGroup
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایشگر گروهی از سری‌ها.
type: docs
weight: 1470
url: /fa/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup کلاس

نمایشگر گروهی از سری‌ها.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | مشخص می‌کند که مقادیر اندازه حباب‌ها چگونه در نمودار حبابی نمایش داده می‌شوند. قابل خواندن/قابل نوشتن [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | مشخص می‌کند که ضریب مقیاس برای نمودار حبابی چیست (می‌تواند بین ۰ تا ۳۰۰ درصد اندازه پیش‌فرض باشد). قابل خواندن/قابل نوشتن Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | نمودار والد را بر می‌گرداند. فقط‌خواندنی [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | مشخص می‌کند که اندازه سوراخ در نمودار دونات (می‌تواند بین ۰ تا ۹۰ درصد اندازه ناحیه طرح باشد). قابل خواندن/قابل نوشتن Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | زاویه اولین برش نمودار پای یا دونات را به درجه می‌دهد (ساعتگرد از بالا، از ۰ تا ۳۶۰ درجه). قابل خواندن/قابل نوشتن UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | فاصله بین سری‌های داده در یک نمودار سه‌بعدی را به عنوان درصد عرض نشانگر تنظیم می‌کند. مقدار باید بین ۰ تا ۵۰۰ باشد. قابل خواندن/قابل نوشتن UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | فاصله بین خوشه‌های نوار یا ستون را به عنوان درصد عرض نوار یا ستون تنظیم می‌کند. مقدار باید بین ۰ تا ۵۰۰ باشد. قابل خواندن/قابل نوشتن UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | اگر نمودار خطوط سری دارد، صحیح است. برای نمودارهای ستونی انباشته و OfPie اعمال می‌شود. قابل خواندن/قابل نوشتن Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | فرمت HiLowLines را مشخص می‌کند. HiLowLines با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی داشته باشد. قابل خواندن/قابل نوشتن Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | عنصر در شاخص مشخص شده را بر می‌گرداند. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | مشخص می‌کند که نوارها و ستون‌ها در نمودارهای دو-بعدی چقدر باید هم‌پوشانی داشته باشند، به درصد (از -100٪ تا 100٪). -100٪: بیشینه فاصله (نوارها کاملاً جدا هستند). -0٪: نوارها بدون هم‌پوشانی یا فاصله کنار هم قرار می‌گیرند. 100٪: بیشینه هم‌پوشانی (نوارها کاملاً بر هم‌اند). این ویژگی قابل خواندن/قابل نوشتن SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | مشخص می‌کند که چگونه تعیین شود کدام نقاط داده در دومین پای یا نوار در یک نمودار pie-of-pie یا bar-of-pie قرار بگیرند. قابل خواندن/قابل نوشتن [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای یک نمودار pie-of-pie یا بار-of-pie با تقسیم سفارشی را شامل می‌شود. شامل نقاط داده‌ای است که باید در دومین پای یا نوار در این نمودار رسم شوند. فقط‌خواندنی [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | مقداری که برای تعیین کدام نقاط داده در دومین پای یا نوار در نمودار pie-of-pie یا bar-of-pie استفاده می‌شود را مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. قابل خواندن/قابل نوشتن Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | نشان می‌دهد آیا سری‌های این گروه روی محور ثانویه رسم می‌شوند. فقط‌خواندنی Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | اندازه دومین پای یا نوار یک نمودار pie-of-pie یا bar-of-pie را به درصد اندازه اولین پای مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). قابل خواندن/قابل نوشتن UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | مجموعه‌ای از سری‌ها را بر می‌گرداند. فقط‌خواندنی [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | نوع این گروه سری را بر می‌گرداند. فقط‌خواندنی [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | دسترسی به نوارهای بالا/پایین نمودار خط یا سهام را فراهم می‌کند. فقط‌خواندنی [`IUpDownBarsManager`](../iupdownbarsmanager). |

### توضیحات

1) به خلاصه و توضیحات برای کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup مراجعه کنید. 2) گروه سری شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است («ویژگی‌های گروه سری»). «ویژگی‌های گروه سری» در کلاس ChartSeriesGroup قابل خواندن/قابل نوشتن است. هر یک از «ویژگی‌های گروه سری» می‌تواند یک نمایش فقط‌خواندنی در کلاس ChartSeries داشته باشد.

### موارد مرتبط

* رابط [IChartSeriesGroup](../ichartseriesgroup)
* فضای نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبل [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->