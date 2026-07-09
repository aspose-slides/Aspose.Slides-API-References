---
title: DataLabelFormat
second_title: مرجع API Aspose.Sildes برای .NET
description: گزینه‌های قالب‌بندی برای DataLabel را نشان می‌دهد.
type: docs
weight: 1570
url: /fa/aspose.slides.charts/datalabelformat/
---
## کلاس DataLabelFormat

گزینه‌های قالب‌بندی برای DataLabel را نشان می‌دهد.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | اجازه می‌دهد تا رابط پایه IPresentationComponent را دریافت کند. فقط برای خواندن [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | نمودار را برمی‌گرداند. فقط برای خواندن [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | فرمت برچسب داده را نشان می‌دهد. فقط برای خواندن [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Boolean خواندن/نوشتن. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | رشته فرمت برای شیء DataLabels را نشان می‌دهد. خواندن/نوشتن String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | موقعیت برچسب داده را نشان می‌دهد. خواندن/نوشتن [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | یک Variant که جداساز استفاده‌شده برای برچسب‌های داده در یک نمودار را نشان می‌دهد، تنظیم یا برمی‌گرداند. خواندن/نوشتن String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | رفتار نمایش مقدار اندازه حباب برچسب داده یک نمودار مشخص را نشان می‌دهد. True مقدار اندازه حباب را نمایش می‌دهد. False برای مخفی‌کردن. خواندن/نوشتن Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | رفتار نمایش نام دسته‌بندی برچسب داده یک نمودار مشخص را نشان می‌دهد. True برای نمایش نام دسته‌بندی برچسب‌های داده در یک نمودار. False برای مخفی‌کردن. خواندن/نوشتن Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | تعیین می‌کند که برچسب داده یک نمودار مشخص به عنوان فراخوانی داده یا به عنوان برچسب داده نمایش داده شود. اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی ShowLabelAsDataCallout را برای برچسب‌های داده جدید در مجموعه DataLabelCollection به‌دست می‌آورد یا تنظیم می‌کند. تنظیم این ویژگی با مقدار، همچنین این مقدار را برای ویژگی ShowLabelAsDataCallout تمام برچسب‌های داده در مجموعه DataLabelCollection تنظیم می‌کند (به عنوان مثال "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" باعث می‌شود همه DataLabels[i].ShowLabelAsDataCallout برابر با val باشد). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | رفتار نمایش مقدار سلول برچسب داده یک نمودار مشخص را نشان می‌دهد. True مقدار سلول را نمایش می‌دهد. False برای مخفی‌کردن. خواندن/نوشتن Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | رفتار نمایش خطوط راهنمای برچسب داده یک نمودار مشخص را نشان می‌دهد. True خطوط راهنما را نمایش می‌دهد. False برای مخفی‌کردن. خواندن/نوشتن Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | رفتار نمایش کلید افسانه برچسب داده یک نمودار مشخص را نشان می‌دهد. True اگر کلید افسانه برچسب داده قابل مشاهده باشد. خواندن/نوشتن Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص را نشان می‌دهد. True مقدار درصد را نمایش می‌دهد. False برای مخفی‌کردن. خواندن/نوشتن Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | یک Boolean را برمی‌گرداند یا تنظیم می‌کند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. True برای نمایش نام سری. False برای مخفی‌کردن. خواندن/نوشتن Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص را نشان می‌دهد. True مقدار درصد را نمایش می‌دهد. False برای مخفی‌کردن. خواندن/نوشتن Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | قالب متن نمودار را برمی‌گرداند. فقط برای خواندن [`IChartTextFormat`](../icharttextformat). |

## متدها

| نام | توضیح |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | با شیء مشخص مقایسه می‌کند. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را برمی‌گرداند. |

### موارد مرتبط

* کلاس [PVIObject](../../aspose.slides/pviobject)
* رابط [IDataLabelFormat](../idatalabelformat)
* فضای نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->