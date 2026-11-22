---
title: set_external_workbook method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
کاربرگ خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کاربرگ هدف به‌روزرسانی خواهند شد.

```python
def set_external_workbook(self, workbook_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | مسیر کاربرگ هدف |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | کاربرگ خارجی در دسترس نیست یا نمی‌تواند بارگذاری شود. |

## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
کاربرگ خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند.

```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | مسیر کاربرگ هدف |
| update_chart_data | **bool** | اگر مقدار false باشد، فقط مسیر کاربرگ به‌روزرسانی می‌شود. <br/><br/>             داده‌های نمودار از کاربرگ هدف بارگذاری و به‌روزرسانی نخواهد شد. می‌توان از آن زمانی استفاده کرد که کاربرگ هدف وجود نداشته باشد یا در دسترس نباشد.<br/><br/>             اگر مقدار true باشد، داده‌های نمودار از کاربرگ هدف به‌روزرسانی خواهند شد. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | کاربرگ خارجی در دسترس نیست یا نمی‌تواند بارگذاری شود. |

### موارد مرتبط
* کلاس [`ChartData`](/slides/python-net/fa/aspose.slides.charts/chartdata)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)