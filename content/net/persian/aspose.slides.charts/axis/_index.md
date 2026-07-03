---
title: Axis
second_title: Aspose.Sildes برای .NET مرجع API
description: شیئی را که نمایانگر محورهای نمودار است دربر می‌گیرد.
type: docs
weight: 1180
url: /fa/aspose.slides.charts/axis/
---
## Axis کلاس

شیئی را که نمایانگر محور نمودار است دربر می‌گیرد.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | حداکثر مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | مقیاس واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | حداقل مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد IChart.ValidateChartLayout() را فراخوانی کنید. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | نوع تجمیع محور دسته (باینینگ) را نشان می‌دهد. برای دسته‌بندی اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | مشخص می‌کند که آیا محور مقدار، محور دسته را بین دسته‌ها می‌گذرد یا نه. این ویژگی فقط برای محورهاى دسته‌بندی اعمال می‌شود و برای نمودارهای سه‌بعدی اعمال نمی‌شود. قابل خواندن/نوشتن Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | کوچک‌ترین واحد زمانی که بر روی محور تاریخ نمایان می‌شود را مشخص می‌کند. قابل خواندن/نوشتن [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | عرض باین را وقتی مقدار ویژگی AggregationType بر AxisAggregationType.ByBinWidth تنظیم شده باشد، مشخص می‌کند. برای محورهاى دسته‌بندی اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | نوع محور دسته را مشخص می‌کند. قابل خواندن/نوشتن [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | نمودار والد را برمی‌گرداند. فقط خواندنی [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | نقطه‌ای روی محور که محور عمود بر آن عبور می‌کند را نشان می‌دهد. قابل خواندن/نوشتن Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | نوع CrossType روی محور مشخص شده که محور دیگر از آن عبور می‌کند را نشان می‌دهد. قابل خواندن/نوشتن [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. قابل خواندن/نوشتن [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | قالب محور را نشان می‌دهد. فقط خواندنی [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | تعیین می‌کند که آیا محور عنوان قابل مشاهده دارد یا نه. قابل خواندن/نوشتن Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | نشانه می‌دهد که آیا واحد اصلی محور به‌صورت خودکار اختصاص یافته است یا نه. قابل خواندن/نوشتن Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | نشانه می‌دهد که آیا حداکثر مقدار به‌صورت خودکار اختصاص یافته است یا نه. قابل خواندن/نوشتن Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | نشانه می‌دهد که آیا واحد فرعی محور به‌صورت خودکار اختصاص یافته است یا نه. قابل خواندن/نوشتن Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | نشانه می‌دهد که آیا حداقل مقدار به‌صورت خودکار اختصاص یافته است یا نه. قابل خواندن/نوشتن Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | مقدار باین سرریز خودکار را مشخص می‌کند. اگر false باشد: از ویژگی OverflowBin استفاده کنید. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | مقدار فاصله خودکار برچسب تیک را مشخص می‌کند. اگر false باشد: از ویژگی TickLabelSpacing استفاده کنید. قابل خواندن/نوشتن Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | مقدار فاصله خودکار علامت‌های تیک را مشخص می‌کند. اگر false باشد: از ویژگی TickMarksSpacing استفاده کنید. قابل خواندن/نوشتن Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | مقدار باین زیرریزش خودکار را مشخص می‌کند. اگر false باشد: از ویژگی UnderflowBin استفاده کنید. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | نشان می‌دهد که آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. قابل خواندن/نوشتن Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | نشانه می‌دهد که آیا قالب به داده منبع پیوند خورده است یا نه. قابل خواندن/نوشتن Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | مشخص می‌کند که آیا باین سرریز اعمال شده است یا نه. برای تنظیم مقدار باین سرریز از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | نشان می‌دهد که آیا PowerPoint داده‌ها را از آخر به اول رسم می‌کند یا نه. قابل خواندن/نوشتن Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | مشخص می‌کند که آیا باین زیرریزش اعمال شده است یا نه. برای تنظیم مقدار باین زیرریزش از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | نشان می‌دهد که آیا محور قابل مشاهده است یا نه. قابل خواندن/نوشتن Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | فاصله برچسب‌ها از محور را مشخص می‌کند. برای محورهای دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. قابل خواندن/نوشتن UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | پایه لگاریتمی را نشان می‌دهد. مقدار پیش‌فرض 10 است. قابل خواندن/نوشتن Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | قالب خطوط شبکه اصلی روی محور نمودار را نشان می‌دهد. فقط خواندنی [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | نوع علامت تیک اصلی برای محور مشخص شده را نشان می‌دهد. قابل خواندن/نوشتن [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. قابل خواندن/نوشتن Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. قابل خواندن/نوشتن [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | حداکثر مقدار روی محور مقدار را نشان می‌دهد. قابل خواندن/نوشتن Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | قالب خطوط شبکه فرعی روی محور نمودار را نشان می‌دهد. فقط خواندنی [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | نوع علامت تیک فرعی برای محور مشخص شده را نشان می‌دهد. قابل خواندن/نوشتن [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. قابل خواندن/نوشتن Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. قابل خواندن/نوشتن [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | حداقل مقدار روی محور مقدار را نشان می‌دهد. قابل خواندن/نوشتن Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | رشته قالب برای برچسب‌های محور را نشان می‌دهد. قابل خواندن/نوشتن String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | تعداد باین‌ها را وقتی مقدار ویژگی AggregationType بر AxisAggregationType.ByNumberOfBins تنظیم شده باشد، مشخص می‌کند. برای محورهاى دسته‌بندی اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | مقدار سفارشی باین سرریز را مشخص می‌کند. وقتی ویژگی IsAutomaticOverflowBin بر false تنظیم شده و ویژگی IsOverflowBin برابر true باشد، اعمال می‌شود. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | موقعیت محور را نشان می‌دهد. قابل خواندن/نوشتن [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | برای مخفی کردن خطوط شبکه اصلی، MajorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید. فقط خواندنی Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | برای مخفی کردن خطوط شبکه فرعی، MinorGridLinesFormat.Line.FillFormat.FillType را به FillType.NoFill تنظیم کنید. فقط خواندنی Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | قالب متن را نشان می‌دهد. فقط خواندنی [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | موقعیت برچسب‌های علامت تیک روی محور مشخص شده را نشان می‌دهد. قابل خواندن/نوشتن [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | زاویه چرخش برچسب‌های تیک را نشان می‌دهد. قابل خواندن/نوشتن Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | تعداد برچسب‌های تیک که باید بین برچسب‌های رسم‌شده نادیده گرفته شود را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود. قابل خواندن/نوشتن UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | تعداد علامت‌های تیک که قبل از رسم علامت بعدی باید نادیده گرفته شوند را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود. قابل خواندن/نوشتن UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | عنوان محور را دریافت می‌کند. فقط خواندنی [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | مقدار سفارشی باین زیرریزش را مشخص می‌کند. وقتی ویژگی IsAutomaticUnderflowBin بر false تنظیم شده و ویژگی IsUnderflowBin برابر true باشد، اعمال می‌شود. |

## متدها

| نام | توضیح |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | ویژگی IAxis.CategoryAxisType را با مقداری که به‌صورت خودکار بر پایه داده‌های محور تعیین می‌شود تنظیم می‌کند. |

### موارد مرتبط

* کلاس [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* کلاس [AxesManager](../axesmanager)
* اینترفیس [IAxis](../iaxis)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->