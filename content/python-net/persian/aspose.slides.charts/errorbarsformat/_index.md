---
title: ErrorBarsFormat class
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/errorbarsformat/
---
## کلاس ErrorBarsFormat

نوارهای خطای مجموعه نمودار را نشان می‌دهد. مقادیر سفارشی ErrorBars در IChartDataPointCollection (در ویژگی [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)) قرار دارند.

نوع ErrorBarsFormat اعضای زیر را در اختیار دارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`type`](/slides/python-net/fa/aspose.slides.charts/errorbarsformat/type/) | دریافت یا تنظیم نوع نوارهای خطا. <br/>            خواندن/نوشتن [`ErrorBarType`](/slides/python-net/fa/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/fa/aspose.slides.charts/errorbarsformat/value_type/) | نمایش روش‌های ممکن برای تعیین طول نوارهای خطا. <br/>            در صورت استفاده از نوع مقدار سفارشی برای مشخص کردن مقدار، از ویژگی [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/fa/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) نقطه داده خاص در مجموعه DataPoints سری استفاده کنید.<br/>            در صورت استفاده از نوع مقدار Fixed، Percentage یا StandardDeviation، از ویژگی Value برای مشخص کردن مقدار استفاده کنید.  <br/>            خواندن/نوشتن [`ErrorBarValueType`](/slides/python-net/fa/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/fa/aspose.slides.charts/errorbarsformat/has_end_cap/) | مشخص می‌کند که سرپای انتهایی روی نوارهای خطا رسم نمی‌شود.<br/>            خواندن/نوشتن **bool**. |
| [`value`](/slides/python-net/fa/aspose.slides.charts/errorbarsformat/value/) | دریافت یا تنظیم مقدار که با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. <br/>            در سایر موارد NaN برگردانده می‌شود.<br/>            خواندن/نوشتن **float**. |
| [`format`](/slides/python-net/fa/aspose.slides.charts/errorbarsformat/format/) | نمایش قالب نوارهای خطا.<br/>            خواندن/نوشتن [`IFormat`](/slides/python-net/fa/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/errorbarsformat/chart/) | برگشتن نمودار والد.<br/>            فقط-خواندنی [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/fa/aspose.slides.charts/errorbarsformat/is_visible/) | دریافت یا تنظیم قابلیت مشاهده نوارهای خطا.<br/>            خواندن/نوشتن **bool**. |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/errorbarsformat/presentation/) |  |

### موارد مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)