---
title: IChartSeriesGroup
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایندهٔ گروهی از سری‌ها.
type: docs
weight: 1950
url: /fa/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup رابط

نمایندهٔ گروهی از سری‌ها.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## خواص

| نام | توضیح |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | امکان دریافت رابط پایه IChartComponent را فراهم می‌کند. فقط-خواندنی [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | نحوهٔ نمایش مقادیر اندازهٔ حباب‌ها در نمودار حبابی را تعیین می‌کند. قابل‌خواندن و نوشتن [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | نسبت مقیاس برای نمودار حبابی را تعیین می‌کند (می‌تواند بین 0 تا 300 درصد اندازه پیش‌فرض باشد). قابل‌خواندن و نوشتن Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | اندازهٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد اندازهٔ ناحیهٔ رسم باشد). قابل‌خواندن و نوشتن Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | زاویهٔ اولین برش پای أو دونات را بر حسب درجه (ساعتگرد از بالا، از 0 تا 360 درجه) تعیین می‌کند. قابل‌خواندن و نوشتن UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | فاصلهٔ درصدی عرض نشانگر بین سلسله‌های داده در نمودار سه‌بعدی را بر می‌گرداند یا تنظیم می‌کند. قابل‌خواندن و نوشتن UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | فاصلهٔ بین خوشه‌های میله یا ستون را به‌عنوان درصدی از عرض میله یا ستون مشخص می‌کند. قابل‌خواندن و نوشتن UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | اگر نمودار خطوط سری داشته باشد، مقدار True است. برای نمودارهای stacked bar و OfPie اعمال می‌شود. قابل‌خواندن و نوشتن Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | قالب HiLowLines را مشخص می‌کند. HiLowLines در ترکیب با انواع نمودار HiLowClose, OpenHiLowClose, VolumeHiLowClose و VolumeOpenHiLowClose به‌کار می‌رود. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی داشته باشد. قابل‌خواندن و نوشتن Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | عنصر موجود در اندیس مشخص‌شده را برمی‌گرداند. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | مقدار همپوشانی میله‌ها و ستون‌ها در نمودارهای 2-بعدی را به‌صورت درصدی (از -100% تا 100%) تعیین می‌کند. -100%: حداکثر فاصله (میله‌ها کاملاً جدا هستند). 0%: میله‌ها بدون همپوشانی یا فاصله کنار هم قرار می‌گیرند. 100%: حداکثر همپوشانی (میله‌ها کاملاً یکدیگر را پوشانده‌اند). این ویژگی قابل‌خواندن و نوشتن SByte است. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | تعیین می‌کند که چه داده‌هایی در پای دوم یا میلهٔ دوم در نمودار pie-of-pie یا bar-of-pie قرار گیرند. قابل‌خواندن و نوشتن [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی را شامل می‌شود. شامل نقاط داده‌ای است که باید در پای دوم یا میلهٔ دوم رسم شوند. فقط-خواندنی [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | مقداری که برای تعیین نقاط داده‌ای که در پای دوم یا میلهٔ دوم قرار می‌گیرند، استفاده می‌شود. همراه با ویژگی PieSplitBy به کار می‌رود. قابل‌خواندن و نوشتن Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | نشان می‌دهد آیا سری‌های این گروه بر محور ثانویه رسم می‌شوند یا نه. فقط-خواندنی Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | اندازهٔ پای یا میلهٔ دوم در نمودار pie-of-pie یا bar-of-pie را به‌صورت درصدی از اندازهٔ پای اول تعیین می‌کند (می‌تواند بین 5 تا 200 درصد باشد). قابل‌خواندن و نوشتن UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | مجموعهٔ فقط-خواندنی‌ ای از سری‌های نمودار را برمی‌گرداند. فقط-خواندنی [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | نوع این گروه سری را برمی‌گرداند. فقط-خواندنی [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | دسترسی به میله‌های بالا/پایین نمودار خط یا سهام را فراهم می‌کند. فقط-خواندنی [`IUpDownBarsManager`](../iupdownbarsmanager). |

### توضیحات

1) به خلاصه و توضیحات برای کلاس ChartSeriesGroupCollection و عدد شمارشی CombinableSeriesTypesGroup مراجعه کنید. 2) گروهی از سری‌ها شامل برخی از ویژگی‌های سری است که برای هر سری در گروه مشترک است ("series group properties"). "Series group properties" در کلاس ChartSeriesGroup قابل‌خواندن و نوشتن است. هر یک از "series group properties" می‌تواند یک بازنمایی فقط-خواندنی در کلاس ChartSeries داشته باشد.

### موارد مرتبط

* رابط [IChartComponent](../ichartcomponent)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->