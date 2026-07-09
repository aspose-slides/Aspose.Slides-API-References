---
title: Axis
second_title: Aspose.Sildes برای .NET مرجع API
description: شیئی که محور نمودار را نشان می‌دهد را در بر می‌گیرد.
type: docs
weight: 1180
url: /fa/aspose.slides.charts/axis/
---
## Axis کلاس

شیئی که نمایانگر محور نمودار است را در بر می‌گیرد.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## خواص

| نام | توضیح |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | حداکثر مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | مقیاس واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | حداقل مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را صدا بزنید. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | نوع تجمیع محور دسته (باینینگ) را نشان می‌دهد. برای دسته‌بندی اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته را قطع می‌کند یا خیر. این ویژگی فقط برای محورهاهای دسته‌ای اعمال می‌شود و در نمودارهای سه‌بعدی کاربرد ندارد. خواندنی/نوشتنی Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | کوچک‌ترین واحد زمان که بر روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | عرض باین را زمانی که مقدار ویژگی AggregationType روی AxisAggregationType.ByBinWidth تنظیم شده است، مشخص می‌کند. برای محورهاهای دسته‌ای اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | نوع محور دسته را مشخص می‌کند. خواندنی/نوشتنی [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | نمودار والد را برمی‌گرداند. فقط-خواندنی [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | نقطه‌ای روی محور را که محور عمود بر آن تقاطع می‌کند نشان می‌دهد. خواندنی/نوشتنی Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | نوع CrossType را بر روی محوری که محور دیگر آن را قطع می‌کند، نشان می‌دهد. خواندنی/نوشتنی [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | مقدار مقیاس‌بندی واحدهای نمایش برای محور مقدار را مشخص می‌کند. خواندنی/نوشتنی [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | قالب محور را نشان می‌دهد. فقط-خواندنی [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | تعیین می‌کند آیا محور دارای عنوان قابل مشاهده است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | نشان می‌دهد آیا واحد اصلی محور به‌طور خودکار اختصاص داده می‌شود یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | نشان می‌دهد آیا مقدار حداکثر به‌طور خودکار اختصاص داده می‌شود یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | نشان می‌دهد آیا واحد فرعی محور به‌طور خودکار اختصاص داده می‌شود یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | نشان می‌دهد آیا مقدار حداقل به‌طور خودکار اختصاص داده می‌شود یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | مقدار خودکار باین سرریز را مشخص می‌کند. اگر False باشد: از ویژگی OverflowBin استفاده کنید. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | مقدار خودکار فاصله برچسب تیک را مشخص می‌کند. اگر False باشد: از ویژگی TickLabelSpacing استفاده کنید. خواندنی/نوشتنی Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | مقدار خودکار فاصله علامت‌های تیک را مشخص می‌کند. اگر False باشد: از ویژگی TickMarksSpacing استفاده کنید. خواندنی/نوشتنی Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | مقدار خودکار باین زیرسرریز را مشخص می‌کند. اگر False باشد: از ویژگی UnderflowBin استفاده کنید. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | نشان می‌دهد آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | نشان می‌دهد آیا قالب به داده منبع لینک شده است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | مشخص می‌کند آیا باین سرریز اعمال شده است یا خیر. برای تنظیم مقدار باین سرریز از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | نشان می‌دهد آیا PowerPoint مایکروسافت داده‌ها را از آخر به ابتدا رسم می‌کند یا خیر. خواندنی/نوشتنی Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | مشخص می‌کند آیا باین زیرسرریز اعمال شده است یا خیر. برای تنظیم مقدار باین زیرسرریز از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | نشان می‌دهد آیا محور قابل مشاهده است یا خیر. خواندنی/نوشتنی Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | فاصله برچسب‌ها از محور را مشخص می‌کند. برای محورهای دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. خواندنی/نوشتنی UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | پایه لگاریتمی را نشان می‌دهد. مقدار پیش‌فرض 10 است. خواندنی/نوشتنی Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | قالب خطوط توری اصلی را بر روی محور نمودار نشان می‌دهد. فقط-خواندنی [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | نوع علامت تیک اصلی برای محور مشخص شده را نشان می‌دهد. خواندنی/نوشتنی [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | حداکثر مقدار روی محور مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | قالب خطوط توری فرعی را بر روی محور نمودار نشان می‌دهد. فقط-خواندنی [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | نوع علامت تیک فرعی برای محور مشخص شده را نشان می‌دهد. خواندنی/نوشتنی [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | حداقل مقدار روی محور مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | رشته قالب برای برچسب‌های محور را نشان می‌دهد. خواندنی/نوشتنی String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | تعداد باین‌ها را زمانی که مقدار ویژگی AggregationType روی AxisAggregationType.ByNumberOfBins تنظیم شده باشد، مشخص می‌کند. برای محورهاهای دسته‌ای اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | مقدار سفارشی باین سرریز را مشخص می‌کند. وقتی ویژگی IsAutomaticOverflowBin روی false تنظیم شده و ویژگی IsOverflowBin برابر true باشد، اعمال می‌شود. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | موقعیت محور را نشان می‌دهد. خواندنی/نوشتنی [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | برای مخفی کردن خطوط توری اصلی، MajorGridLinesFormat.Line.FillFormat.FillType را روی FillType.NoFill تنظیم کنید. فقط-خواندنی Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | برای مخفی کردن خطوط توری فرعی، MinorGridLinesFormat.Line.FillFormat.FillType را روی FillType.NoFill تنظیم کنید. فقط-خواندنی Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | قالب متن را نشان می‌دهد. فقط-خواندنی [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | موقعیت برچسب‌های علامت تیک روی محور مشخص شده را نشان می‌دهد. خواندنی/نوشتنی [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | زاویه چرخش برچسب‌های تیک را نشان می‌دهد. خواندنی/نوشتنی Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | تعداد برچسب‌های تیکی که باید بین برچسب‌های رسم‌شده کنار گذاشته شوند را مشخص می‌کند. برای محورهای دسته یا سری اعمال می‌شود. خواندنی/نوشتنی UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | تعداد علامت‌های تیکی که باید قبل از نماد بعدی رد شوند را مشخص می‌کند. برای محورهای دسته یا سری اعمال می‌شود. خواندنی/نوشتنی UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | عنوان محور را دریافت می‌کند. فقط-خواندنی [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | مقدار سفارشی باین زیرسرریز را مشخص می‌کند. وقتی ویژگی IsAutomaticUnderflowBin روی false تنظیم شده و ویژگی IsUnderflowBin برابر true باشد، اعمال می‌شود. |

## متدها

| نام | توضیح |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | IAxis.CategoryAxisType property را با مقداری که به‌صورت خودکار بر اساس داده‌های محور تعیین می‌شود تنظیم می‌کند. |

### موارد مرتبط

* کلاس [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* کلاس [AxesManager](../axesmanager)
* رابط [IAxis](../iaxis)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->