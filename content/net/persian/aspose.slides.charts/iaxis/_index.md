---
title: IAxis
second_title: Aspose.Sildes برای .NET مرجع API
description: شیء‌ای را که نمایانگر محور نمودار است، در بر می‌گیرد.
type: docs
weight: 1720
url: /fa/aspose.slides.charts/iaxis/
---
## IAxis رابط

انرژی‌گر شیئی که محور نمودار را نشان می‌دهد.

```csharp
public interface IAxis : IFormattedTextContainer
```

## خواص

| نام | توضیح |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | حداکثر مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | واحد جزئی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | مقیاس واحد جزئی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | حداقل مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از آن متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | نوع تجمیع محور دسته‌ای (باینینگ) را نشان می‌دهد. برای دسته‌ها به کار می‌رود. فقط در سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | امکان دریافت رابط پایه IFormattedTextContainer را فراهم می‌کند. فقط-خواندنی [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | نشان می‌دهد که محور مقدار، محور دسته‌ای را بین دسته‌ها قطع می‌کند یا خیر. این ویژگی فقط برای محورهاى دسته‌ای اعمال می‌شود و برای نمودارهای سه‌بعدی اعمال نمی‌شود. خواندنی/نوشتنی Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | کوچک‌ترین واحد زمانی که بر محور تاریخ نشان داده می‌شود را مشخص می‌کند. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | عرض باین را زمانی که مقدار ویژگی AggregationType روی AxisAggregationType.ByBinWidth تنظیم شده باشد، مشخص می‌کند. برای محورهاى دسته‌ای به کار می‌رود. فقط در سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | نوع محور دسته‌ای را مشخص می‌کند. خواندنی/نوشتنی [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | نقطه‌ای روی محور که محور عمود بر آن عبور می‌کند را نشان می‌دهد. خواندنی/نوشتنی Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | نوع تقاطع (CrossType) روی محوری که محور دیگر از آن عبور می‌کند را نشان می‌دهد. خواندنی/نوشتنی [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. خواندنی/نوشتنی [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | قالب محور را نشان می‌دهد. فقط-خواندنی [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | تعیین می‌کند که آیا محور عنوان قابل رؤیتی دارد یا خیر. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | نشان می‌دهد که آیا واحد اصلی محور به‌صورت خودکار اختصاص یافته است. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | نشان می‌دهد که آیا حداکثر مقدار به‌صورت خودکار اختصاص یافته است. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | نشان می‌دهد که آیا واحد جزئی محور به‌صورت خودکار اختصاص یافته است. خواندنی/نوشتنی Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | نشان می‌دهد که آیا حداقل مقدار به‌صورت خودکار اختصاص یافته است. خواندنی/نوشتنی Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | مقدار خودکار باین سرریز را مشخص می‌کند. اگر False باشد: از ویژگی OverflowBin استفاده کنید. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | مقدار خودکار فاصله برچسب تیک را مشخص می‌کند. اگر False باشد: از ویژگی TickLabelSpacing استفاده کنید. خواندنی/نوشتنی Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | مقدار خودکار فاصله علامت‌های تیک را مشخص می‌کند. اگر False باشد: از ویژگی TickMarksSpacing استفاده کنید. خواندنی/نوشتنی Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | مقدار خودکار باین زیرسرریز را مشخص می‌کند. اگر False باشد: از ویژگی UnderflowBin استفاده کنید. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | نشان می‌دهد که آیا مقیاس محور مقدار لگاریتمی است یا نه. خواندنی/نوشتنی Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | نشان می‌دهد که آیا قالب به داده منبع پیوند دارد. خواندنی/نوشتنی Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | نشان می‌دهد که آیا باین سرریز اعمال شده است. برای تنظیم مقدار باین سرریز از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | نشان می‌دهد که آیا PowerPoint داده‌ها را از آخر به ابتدا رسم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | نشان می‌دهد که آیا باین زیرسرریز اعمال شده است. برای تنظیم مقدار باین زیرسرریز از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | نشان می‌دهد که آیا محور قابل مشاهده است یا خیر. خواندنی/نوشتنی Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | فاصله برچسب‌ها از محور را مشخص می‌کند. برای محورهای دسته‌ای یا تاریخ به کار می‌رود. مقدار باید بین 0٪ و 1000٪ باشد. خواندنی/نوشتنی UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | پایه لگاریتمی را نشان می‌دهد. مقدار پیش‌فرض 10 است. خواندنی/نوشتنی Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | قالب خطوط شبکه اصلی روی محور نمودار را نشان می‌دهد. فقط-خواندنی [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | نوع علامت تیک اصلی برای محور مشخص‌شده را نشان می‌دهد. خواندنی/نوشتنی [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | حداکثر مقدار روی محور مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | قالب خطوط شبکه جزئی روی یک محور نمودار را نشان می‌دهد. فقط-خواندنی [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | نوع علامت تیک جزئی برای محور مشخص‌شده را نشان می‌دهد. خواندنی/نوشتنی [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | واحدهای جزئی برای محور تاریخ یا مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | مقیاس واحد جزئی برای محور تاریخ را نشان می‌دهد. خواندنی/نوشتنی [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | حداقل مقدار روی محور مقدار را نشان می‌دهد. خواندنی/نوشتنی Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | رشته قالب برای برچسب‌های محور را نشان می‌دهد. خواندنی/نوشتنی String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | تعداد باین‌ها را زمانی که مقدار ویژگی AggregationType روی AxisAggregationType.ByNumberOfBins تنظیم شده باشد، مشخص می‌کند. برای محورهاى دسته‌ای به کار می‌رود. فقط در سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | مقدار سفارشی باین سرریز را مشخص می‌کند. زمانی که IsAutomaticOverflowBin برابر False و IsOverflowBin برابر True باشد، اعمال می‌شود. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | موقعیت محور را نشان می‌دهد. خواندنی/نوشتنی [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | نشان می‌دهد که آیا خطوط شبکه اصلی نمایش داده می‌شوند یا خیر. فقط-خواندنی Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | نشان می‌دهد که آیا خطوط شبکه جزئی نمایش داده می‌شوند یا خیر. فقط-خواندنی Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | موقعیت برچسب‌های علامت تیک روی محور مشخص‌شده را نشان می‌دهد. خواندنی/نوشتنی [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | زاویه چرخش برچسب‌های تیک را نشان می‌دهد. خواندنی/نوشتنی Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | تعداد برچسب‌های تیکی که باید بین دو برچسب رسم‌شده حذف شوند را مشخص می‌کند. خواندنی/نوشتنی UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | تعداد علامت‌های تیکی که باید قبل از علامت بعدی حذف شوند را مشخص می‌کند. برای محورهای دسته‌ای یا سری به کار می‌رود. خواندنی/نوشتنی UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | عنوان محور را باز می‌گرداند. فقط-خواندنی [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | مقدار سفارشی باین زیرسرریز را مشخص می‌کند. زمانی که IsAutomaticUnderflowBin برابر False و IsUnderflowBin برابر True باشد، اعمال می‌شود. |

## متدها

| نام | توضیح |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | ویژگی IAxis.CategoryAxisType را با مقدار تعیین‌شده به‌صورت خودکار بر اساس داده‌های محور تنظیم می‌کند. |

### موارد مرتبط

* رابط [IFormattedTextContainer](../iformattedtextcontainer)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->