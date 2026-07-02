---
title: IChartSeriesGroup
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایشگر گروهی از سِری‌ها.
type: docs
weight: 1950
url: /fa/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup رابط

نمایشگر گروهی از سِری‌ها.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | اجازه می‌دهد رابط IChartComponent پایه را دریافت کند. فقط خواندنی [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | مشخص می‌کند مقادیر اندازهٔ حباب‌ها در نمودار حبابی چگونه نمایش داده شوند. قابل خواندن/نوشتن [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین ۰ تا ۳۰۰ درصد اندازهٔ پیش‌فرض باشد). قابل خواندن/نوشتن Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | اندازهٔ حفره در نمودار دونات را مشخص می‌کند (می‌تواند بین ۱۰ تا ۹۰ درصد اندازهٔ ناحیهٔ طرح باشد). قابل خواندن/نوشتن Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | زاویهٔ اولین بخش نمودار دایره‌ای یا دونات را به درجه دریافت یا تنظیم می‌کند (ساعت‌گرد از بالا، از ۰ تا ۳۶۰ درجه). قابل خواندن/نوشتن UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | فاصله، به عنوان درصدی از عرض علامت‌گر، بین سِری‌های داده در یک نمودار سه‌بعدی را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | فضای بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون مشخص می‌کند. قابل خواندن/نوشتن UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | در صورتی‌که نمودار خطوط سِری داشته باشد، مقدار True است. برای نمودارهای میله‌ای انباشته و OfPie اعمال می‌شود. قابل خواندن/نوشتن Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | قالب HiLowLines را مشخص می‌کند. HiLowLines با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | مشخص می‌کند که هر علامت‌گر داده در سِری رنگ متفاوتی دارد. قابل خواندن/نوشتن Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | عنصری را که در ایندکس محدد است، دریافت می‌کند. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | مشخص می‌کند میله‌ها و ستون‌ها در نمودارهای دو-بعدی تا چه حد بر هم هم‌پوشانی داشته باشند، به‌صورت درصد (از -۱۰۰٪ تا ۱۰۰٪). - -۱۰۰٪: بیشترین فاصله (میله‌ها کاملاً جدا هستند). - ۰٪: میله‌ها به صورت کنار هم بدون هم‌پوشانی یا فاصله قرار می‌گیرند. - ۱۰۰٪: بیشترین هم‌پوشانی (میله‌ها کاملاً یک‌دیگر را می‌پوشانند). این ویژگی قابل خواندن/نوشتن SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | نحوهٔ تعیین نقاط داده‌ای که در دایرهٔ دوم یا میلهٔ دوم نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند را مشخص می‌کند. قابل خواندن/نوشتن [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | اطلاعات تقسیم سفارشی برای یک نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در دایرهٔ دوم یا میلهٔ دوم نمودار رسم شوند. فقط خواندنی [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | مقداری را که برای تعیین نقاط داده‌ای که در دایرهٔ دوم یا میلهٔ دوم نمودار pie-of-pie یا bar-of-pie قرار می‌گیرند، استفاده می‌شود، مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. قابل خواندن/نوشتن Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | نشان می‌دهد آیا سِری‌های این گروه بر روی محور ثانویه رسم می‌شوند یا خیر. فقط خواندنی Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | اندازهٔ دایرهٔ دوم یا میلهٔ دوم یک نمودار pie-of-pie یا bar-of-pie را به صورت درصدی از اندازهٔ دایرهٔ اول مشخص می‌کند (می‌تواند بین ۵ تا ۲۰۰ درصد باشد). قابل خواندن/نوشتن UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | یک مجموعهٔ فقط خواندنی از سِری‌های نمودار را برمی‌گرداند. فقط خواندنی [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | یک نوع از این گروه سِری را برمی‌گرداند. فقط خواندنی [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | دسترسی به میله‌های بالا/پایین نمودار خط یا سهام را فراهم می‌کند. فقط خواندنی [`IUpDownBarsManager`](../iupdownbarsmanager). |

### ملاحظات

1) خلاصه و ملاحظات کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup را ببینید.  
2) گروهی از سِری‌ها شامل برخی ویژگی‌های سِری است که برای هر سِری در گروه مشترک است («ویژگی‌های گروه سِری»). ویژگی‌های گروه سِری در کلاس ChartSeriesGroup قابل خواندن/نوشتن هستند. هر یک از «ویژگی‌های گروه سِری» می‌تواند یک تصویر فقط خواندنی در کلاس ChartSeries داشته باشد.

### همچنین ببینید

* رابط [IChartComponent](../ichartcomponent)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->