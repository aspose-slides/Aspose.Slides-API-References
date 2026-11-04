---
title: IChartSeriesGroup
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایانگر گروهی از سری‌ها.
type: docs
weight: 1970
url: /fa/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup رابط

نمایانگر گروهی از سری‌ها.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | اجازه می‌دهد رابط پایه IChartComponent را دریافت کند. فقط-خواندنی [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | مشخص می‌کند مقادیر اندازه حباب چگونه در نمودار حباب نمایش داده شوند. قابل خواندن/نوشتن [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | فاکتور مقیاس نمودار حباب را مشخص می‌کند (می‌تواند بین 0 و 300 درصد اندازه پیش‌فرض باشد). قابل خواندن/نوشتن Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | اندازهٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 و 90 درصد اندازهٔ ناحیهٔ نمودار باشد). قابل خواندن/نوشتن Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | زاویهٔ اولین برش پای یا دونات را بر حسب درجه (ساعتگرد از بالا، از 0 تا 360 درجه) دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | فاصله بین سری‌های داده در نمودار 3D را به عنوان درصدی از عرض علامت دریافت یا تنظیم می‌کند. مقدار باید بین 0 و 500 باشد. قابل خواندن/نوشتن UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | فاصله بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون دریافت یا تنظیم می‌کند. مقدار باید بین 0 و 500 باشد. قابل خواندن/نوشتن UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | درست اگر نمودار خطوط سری داشته باشد. برای میله‌های پشته‌ای و نمودارهای OfPie اعمال می‌شود. قابل خواندن/نوشتن Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | قالب HiLowLines را مشخص می‌کند. HiLowLines با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | مشخص می‌کند که هر علامت داده در سری رنگ متفاوتی داشته باشد. قابل خواندن/نوشتن Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | عنصری را که در اندیس مشخص شده است دریافت می‌کند. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | مشخص می‌کند میله‌ها و ستون‌ها در نمودارهای دو-بعدی تا چه حد هم‌پوشانی داشته باشند، به عنوان درصد (از -100% تا 100%). - -100%: بیشترین فاصله (میله‌ها کاملاً جدا هستند). - 0%: میله‌ها به‌صورت کنار هم بدون هم‌پوشانی یا فاصله قرار می‌گیرند. - 100%: بیشترین هم‌پوشانی (میله‌ها کاملاً بر روی یکدیگر می‌باشند). این ویژگی قابل خواندن/نوشتن SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | نحوه تعیین نقاط داده‌ای که در پای دوم یا میلهٔ دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند را مشخص می‌کند. قابل خواندن/نوشتن [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی را فراهم می‌کند. شامل نقاط داده‌ای است که باید در پای دوم یا میلهٔ دوم در یک نمودار pie-of-pie یا bar-of-pie کشیده شوند. فقط-خواندنی [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | مقداری را مشخص می‌کند که برای تعیین نقاط داده‌ای که در پای دوم یا میلهٔ دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند، استفاده می‌شود. همراه با ویژگی PieSplitBy به کار می‌رود. قابل خواندن/نوشتن Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | نشان می‌دهد آیا سری‌های این گروه روی محور ثانویه رسم می‌شوند. فقط-خواندنی Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | اندازهٔ پای دوم یا میلهٔ دوم در نمودار pie-of-pie یا bar-of-pie را به عنوان درصدی از اندازهٔ اولین پای مشخص می‌کند (می‌تواند بین 5 و 200 درصد باشد). قابل خواندن/نوشتن UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | مجموعه‌ای فقط-خواندنی از سری‌های نمودار را برمی‌گرداند. فقط-خواندنی [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | یک نوع از این گروه سری را برمی‌گرداند. فقط-خواندنی [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | دسترسی به میله‌های بالا/پایین در نمودار خط یا سهام را فراهم می‌کند. فقط-خواندنی [`IUpDownBarsManager`](../iupdownbarsmanager). |

### توضیحات

1) خلاصه و توضیحات مربوط به کلاس ChartSeriesGroupCollection و شمارش CombinableSeriesTypesGroup را ببینید. 2) گروهی از سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("series group properties"). "Series group properties" در کلاس ChartSeriesGroup قابل خواندن/نوشتن است. هر یک از "series group properties" می‌توانند یک تصویر فقط-خواندنی در کلاس ChartSeries داشته باشند.

### موارد مرتبط

* رابط [IChartComponent](../ichartcomponent)
* فضا‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->