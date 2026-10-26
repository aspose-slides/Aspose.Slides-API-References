---
title: IAxis
second_title: Aspose.Sildes برای .NET - مرجع API
description: شیئی را که نمایانگر محور نمودار است محصور می‌کند.
type: docs
weight: 1710
url: /fa/aspose.slides.charts/iaxis/
---
## IAxis رابط

شیئی را که محور نمودار را نشان می‌دهد، می‌پوشاند.

```csharp
public interface IAxis : IFormattedTextContainer
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | حداکثر مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | مقیاس واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | حداقل مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | نوع تجمیع محور دسته (باینینگ) را نشان می‌دهد. برای دسته اعمال می‌شود. فقط با سری‌های هیستوگرام یا هیستوگرام‌پارتو استفاده می‌شود. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | به‌دست آوردن رابط پایه IFormattedTextContainer را امکان‌پذیر می‌سازد. فقط‌خواندنی [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | نمایانگر این است که آیا محور مقدار بین دسته‌ها محور دسته را قطع می‌کند یا خیر. این ویژگی فقط برای محورهاى دسته اعمال می‌شود و برای نمودارهای سه‌بعدی کاربرد ندارد. خواندنی/نوشتنی Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | کوچک‌ترین واحد زمان نمایانده شده در محور تاریخ را مشخص می‌کند. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | عرض بینه را وقتی مقدار ویژگی AggregationType برابر AxisAggregationType.ByBinWidth باشد، مشخص می‌کند. برای محورهاى دسته اعمال می‌شود. فقط با سری‌های هیستوگرام یا هیستوگرام‌پارتو استفاده می‌شود. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | نوع محور دسته را مشخص می‌کند. خواندنی/نوشتنی [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | نقطه‌ای روی محور را نشان می‌دهد که در آن محور عمود به آن می‌رسد. خواندنی/نوشتنی Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | نوع CrossType را در محور مشخص شده که محور دیگر آن را قطع می‌کند، نشان می‌دهد. خواندنی/نوشتنی [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. خواندنی/نوشتنی [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | قالب محور را نشان می‌دهد. فقط‌خواندنی [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | تعیین می‌کند آیا محور دارای عنوان قابل مشاهده است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | نشان می‌دهد آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | نشان می‌دهد آیا حداکثر مقدار به‌صورت خودکار اختصاص داده می‌شود یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | نشان می‌دهد آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | نشان می‌دهد آیا حداقل مقدار به‌صورت خودکار اختصاص داده می‌شود یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | مقدار بینهٔ سرریز خودکار را مشخص می‌کند. اگر false باشد: از ویژگی OverflowBin استفاده کنید. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | مقدار فاصلهٔ خودکار برچسب تیک را مشخص می‌کند. اگر false باشد: از ویژگی TickLabelSpacing استفاده کنید. خواندنی/نوشتنی Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | مقدار فاصلهٔ خودکار علامت‌های تیک را مشخص می‌کند. اگر false باشد: از ویژگی TickMarksSpacing استفاده کنید. خواندنی/نوشتنی Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | مقدار بینهٔ زیرریزی خودکار را مشخص می‌کند. اگر false باشد: از ویژگی UnderflowBin استفاده کنید. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | نشان می‌دهد آیا نوع مقیاس محور مقدار لگاریتمی است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | نشان می‌دهد آیا قالب به داده منبع لینک شده است یا خیر. خواندنی/نوشتنی Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | مشخص می‌کند آیا بینهٔ سرریز اعمال شده است. برای تنظیم مقدار بینهٔ سرریز از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | نشان می‌دهد آیا PowerPoint داده‌ها را از آخر به اول ترسیم می‌کند یا خیر. خواندنی/نوشتنی Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | مشخص می‌کند آیا بینهٔ زیرریزی اعمال شده است. برای تنظیم مقدار بینهٔ زیرریزی از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | نشان می‌دهد آیا محور قابل مشاهده است یا خیر. خواندنی/نوشتنی Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | فاصلهٔ برچسب‌ها از محور را مشخص می‌کند. برای محور دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. خواندنی/نوشتنی UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | پایهٔ لگاریتمی را نشان می‌دهد. مقدار پیش‌فرض 10 است. خواندنی/نوشتنی Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | قالب خطوط شبکهٔ اصلی بر روی محور نمودار را نشان می‌دهد. فقط‌خواندنی [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | نوع علامت تیک اصلی برای محور مشخص شده را نشان می‌دهد. خواندنی/نوشتنی [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | بیشترین مقدار بر روی محور مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | قالب خطوط شبکهٔ فرعی بر روی محور نمودار را نشان می‌دهد. فقط‌خواندنی [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | نوع علامت تیک فرعی برای محور مشخص شده را نشان می‌دهد. خواندنی/نوشتنی [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | حداقل مقدار بر روی محور مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | رشتهٔ قالب برای برچسب‌های محور را نشان می‌دهد. خواندنی/نوشتنی String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | تعداد بینه‌ها را وقتی مقدار ویژگی AggregationType برابر AxisAggregationType.ByNumberOfBins باشد، مشخص می‌کند. برای محورهاى دسته اعمال می‌شود. فقط با سری‌های هیستوگرام یا هیستوگرام‌پارتو استفاده می‌شود. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | مقدار سفارشی بینهٔ سرریز را مشخص می‌کند. وقتی ویژگی IsAutomaticOverflowBin برابر false بوده و ویژگی IsOverflowBin برابر true باشد، اعمال می‌شود. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | موقعیت محور را نشان می‌دهد. خواندنی/نوشتنی [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | نشان می‌دهد آیا خطوط شبکهٔ اصلی نمایش داده می‌شوند یا خیر. فقط‌خواندنی Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | نشان می‌دهد آیا خطوط شبکهٔ فرعی نمایش داده می‌شوند یا خیر. فقط‌خواندنی Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | موقعیت برچسب‌های علامت تیک بر روی محور مشخص شده را نشان می‌دهد. خواندنی/نوشتنی [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | زاویهٔ چرخش برچسب‌های تیک را نشان می‌دهد. خواندنی/نوشتنی Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | تعداد برچسب‌های تیک که باید بین دو برچسب کشیده شده از قلم بیفتد را مشخص می‌کند. خواندنی/نوشتنی UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | تعداد علامت‌های تیک که قبل از کشیدن علامت بعدی باید حذف شوند را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود. خواندنی/نوشتنی UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | عنوان محور را دریافت می‌کند. فقط‌خواندنی [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | مقدار سفارشی بینهٔ زیرریزی را مشخص می‌کند. وقتی ویژگی IsAutomaticUnderflowBin برابر false باشد و ویژگی IsUnderflowBin برابر true باشد، اعمال می‌شود. |

## متدها

| نام | توضیح |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | ویژگی IAxis.CategoryAxisType را با مقداری که به‌صورت خودکار بر اساس داده‌های محور تعیین می‌شود تنظیم می‌کند. |

### مراجع

* رابط [IFormattedTextContainer](../iformattedtextcontainer)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبل [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->