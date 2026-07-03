---
title: IAxis
second_title: Aspose.Sildes برای .NET مرجع API
description: شیئی که محورهای نمودار را نمایندگی می‌کند را در بر می‌گیرد.
type: docs
weight: 1710
url: /fa/aspose.slides.charts/iaxis/
---
## IAxis رابط

Encapsulates the object that represents a chart's axis.

```csharp
public interface IAxis : IFormattedTextContainer
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | واحد اصلی واقعی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی به دست آید. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی به دست آید. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | حداکثر مقدار واقعی روی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی به دست آید. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | واحد فرعی واقعی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی به دست آید. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | مقیاس واحد فرعی واقعی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی به دست آید. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | حداقل مقدار واقعی روی محور را مشخص می‌کند. پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید تا مقدار واقعی به دست آید. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | نوع تجمیع محور دسته‌ای (بینی) را نمایش می‌دهد. برای دسته اعمال می‌شود. فقط همراه با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | دسترسی به رابط پایه IFormattedTextContainer را فراهم می‌کند. فقط خواندنی [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | نمایش می‌دهد که آیا محور مقدار، محور دسته‌ای را بین دسته‌ها قطع می‌کند یا خیر. این ویژگی فقط برای محورهای دسته‌ای اعمال می‌شود و برای نمودارهای سه‌بعدی اعمال نمی‌شود. خواندنی/نوشتنی Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | کوچک‌ترین واحد زمان نمایان شده در محور تاریخ را مشخص می‌کند. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | عرض بین‌بینی را زمانی که مقدار ویژگی AggregationType بر AxisAggregationType.ByBinWidth تنظیم شده باشد، مشخص می‌کند. برای محورهای دسته‌ای اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | نوع محور دسته‌ای را مشخص می‌کند. خواندنی/نوشتنی [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | نقطه‌ای روی محور که محور عمودی آن را قطع می‌کند را نمایش می‌دهد. خواندنی/نوشتنی Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | نوع CrossType روی محور مشخص شده که محور دیگر آن را قطع می‌کند را نمایش می‌دهد. خواندنی/نوشتنی [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. خواندنی/نوشتنی [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | قالب محور را نمایش می‌دهد. فقط خواندنی [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | مشخص می‌کند که آیا محور دارای عنوان قابل مشاهده است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | نشان می‌دهد که آیا واحد اصلی محور به‌صورت خودکار اختصاص داده شده است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | نشان می‌دهد که آیا حداکثر مقدار به‌صورت خودکار اختصاص داده شده است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | نشان می‌دهد که آیا واحد فرعی محور به‌صورت خودکار اختصاص داده شده است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | نشان می‌دهد که آیا حداقل مقدار به‌صورت خودکار اختصاص داده شده است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | مقدار بین‌بینی اضافه خودکار را مشخص می‌کند. اگر false: use OverflowBin property. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | مقدار فاصله خودکار برچسب‌های تیک را مشخص می‌کند. اگر false: use TickLabelSpacing property. خواندنی/نوشتنی Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | مقدار فاصله خودکار علامت‌های تیک را مشخص می‌کند. اگر false: use TickMarksSpacing property. خواندنی/نوشتنی Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | مقدار بین‌بینی زیرپوششی خودکار را مشخص می‌کند. اگر false: use UnderflowBin property. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | نمایش می‌دهد که آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | نشان می‌دهد که آیا قالب به داده منبع لینک شده است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | مشخص می‌کند که آیا بین‌بینی اضافه اعمال شده است یا خیر. برای تنظیم مقدار بین‌بینی اضافه از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | نمایش می‌دهد که آیا PowerPoint داده‌ها را از آخر به ابتدا نمودار می‌کند یا خیر. خواندنی/نوشتنی Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | مشخص می‌کند که آیا بین‌بینی زیرپوششی اعمال شده است یا خیر. برای تنظیم مقدار بین‌بینی زیرپوششی از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | نمایش می‌دهد که آیا محور قابل مشاهده است یا خیر. خواندنی/نوشتنی Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | فاصله برچسب‌ها از محور را مشخص می‌کند. برای محورهای دسته‌ای یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. خواندنی/نوشتنی UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | پایه لگاریتم را نمایش می‌دهد. مقدار پیش‌فرض 10 است. خواندنی/نوشتنی Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | قالب خطوط مشبک اصلی روی محور نمودار را نمایش می‌دهد. فقط خواندنی [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | نوع علامت تیک اصلی برای محور مشخص شده را نمایش می‌دهد. خواندنی/نوشتنی [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | واحدهای اصلی برای محور تاریخ یا مقدار را نمایش می‌دهد. خواندنی/نوشتنی Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | مقیاس واحد اصلی برای محور تاریخ را نمایش می‌دهد. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | حداکثر مقدار روی محور مقدار را نمایش می‌دهد. خواندنی/نوشتنی Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | قالب خطوط مشبک فرعی روی محور نمودار را نمایش می‌دهد. فقط خواندنی [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | نوع علامت تیک فرعی برای محور مشخص شده را نمایش می‌دهد. خواندنی/نوشتنی [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | واحدهای فرعی برای محور تاریخ یا مقدار را نمایش می‌دهد. خواندنی/نوشتنی Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | مقیاس واحد اصلی برای محور تاریخ را نمایش می‌دهد. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | حداقل مقدار روی محور مقدار را نمایش می‌دهد. خواندنی/نوشتنی Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | رشته قالب برای برچسب‌های محور را نمایش می‌دهد. خواندنی/نوشتنی String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | تعداد بین‌ها را زمانی که مقدار ویژگی AggregationType بر AxisAggregationType.ByNumberOfBins تنظیم شده باشد، مشخص می‌کند. برای محورهای دسته‌ای اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | مقدار سفارشی بین‌بینی اضافه را مشخص می‌کند. وقتی ویژگی IsAutomaticOverflowBin برابر false و ویژگی IsOverflowBin برابر true باشد، اعمال می‌شود. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | موقعیت محور را نمایش می‌دهد. خواندنی/نوشتنی [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | نشان می‌دهد که خطوط مشبک اصلی نمایش داده شده‌اند یا خیر. فقط خواندنی Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | نشان می‌دهد که خطوط مشبک فرعی نمایش داده شده‌اند یا خیر. فقط خواندنی Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | موقعیت برچسب‌های علامت‌های تیک روی محور مشخص شده را نمایش می‌دهد. خواندنی/نوشتنی [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | زاویه چرخش برچسب‌های تیک را نمایش می‌دهد. خواندنی/نوشتنی Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | تعداد برچسب‌های تیکی که باید بین برچسب‌های کشیده شده حذف شوند را مشخص می‌کند. خواندنی/نوشتنی UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | تعداد علامت‌های تیکی که باید قبل از رسم علامت بعدی حذف شوند را مشخص می‌کند. برای محورهای دسته‌ای یا سری اعمال می‌شود. خواندنی/نوشتنی UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | عنوان محور را برمی‌گرداند. فقط خواندنی [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | مقدار سفارشی بین‌بینی زیرپوششی را مشخص می‌کند. وقتی ویژگی IsAutomaticUnderflowBin برابر false و ویژگی IsUnderflowBin برابر true باشد، اعمال می‌شود. |

## متدها

| نام | توضیح |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | ویژگی IAxis.CategoryAxisType را با مقدار تعیین‌شده خودکار بر اساس داده‌های محور تنظیم می‌کند. |

### موارد مرتبط

* رابط [IFormattedTextContainer](../iformattedtextcontainer)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->