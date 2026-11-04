---
title: DataLabelFormat
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایش گزینه‌های قالب‌بندی برای DataLabel.
type: docs
weight: 1580
url: /fa/aspose.slides.charts/datalabelformat/
---
## کلاس DataLabelFormat

نمایش گزینه‌های قالب‌بندی برای DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | امکان دسترسی به رابط پایه IPresentationComponent را فراهم می‌کند. فقط خواندنی [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | نمودار را برمی‌گرداند. فقط خواندنی [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | قالب برچسب داده را نشان می‌دهد. فقط خواندنی [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Boolean قابل خواندن/نوشتن. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | رشته قالب برای شیء DataLabels را نشان می‌دهد. قابل خواندن/نوشتن String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | موقعیت برچسب داده را نشان می‌دهد. قابل خواندن/نوشتن [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | یک Variant که جداساز استفاده‌شده برای برچسب‌های داده در یک نمودار را نشان می‌دهد، تنظیم یا برمی‌گرداند. قابل خواندن/نوشتن String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | رفتار نمایش مقدار اندازه حباب برچسب داده یک نمودار مشخص را نشان می‌دهد. True مقدار اندازه حباب را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | رفتار نمایش نام دسته‌بندی برچسب داده یک نمودار مشخص را نشان می‌دهد. True برای نمایش نام دسته برای برچسب‌های داده در یک نمودار. False برای مخفی کردن. قابل خواندن/نوشتن Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | تعیین می‌کند که برچسب داده یک نمودار مشخص به‌صورت فراخوانی داده یا به‌صورت برچسب داده نمایش داده شود. اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ShowLabelAsDataCallout را برای برچسب‌های جدید در مجموعه DataLabelCollection دریافت یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همین مقدار را برای ویژگی ShowLabelAsDataCallout تمام برچسب‌های داده در مجموعه DataLabelCollection نیز تنظیم می‌کند (مثلاً "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" باعث می‌شود تمام DataLabels[i].ShowLabelAsDataCallout برابر با val باشد). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | رفتار نمایش مقدار سلول برچسب داده یک نمودار مشخص را نشان می‌دهد. True مقدار سلول را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | رفتار نمایش خطوط رهبری برچسب داده یک نمودار مشخص را نشان می‌دهد. True خطوط رهبری را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | رفتار نمایش کلید افسانه برچسب داده یک نمودار مشخص را نشان می‌دهد. True اگر کلید افسانه برچسب داده قابل مشاهده باشد. قابل خواندن/نوشتن Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص را نشان می‌دهد. True مقدار درصد را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | یک Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. True برای نمایش نام سری. False برای مخفی کردن. قابل خواندن/نوشتن Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص را نشان می‌دهد. True مقدار درصد را نمایش می‌دهد. False برای مخفی کردن. قابل خواندن/نوشتن Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | قالب متن نمودار را برمی‌گرداند. فقط خواندنی [`IChartTextFormat`](../icharttextformat). |

## متدها

| نام | توضیح |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | مقایسه با شیء مشخص‌شده. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را برمی‌گرداند. |

### موارد مرتبط

* کلاس [PVIObject](../../aspose.slides/pviobject)
* رابط [IDataLabelFormat](../idatalabelformat)
* فضای نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->