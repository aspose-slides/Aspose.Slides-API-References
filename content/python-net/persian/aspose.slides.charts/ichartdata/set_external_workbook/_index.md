---
title: set_external_workbook method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
یک کتاب‌کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کتاب‌کار هدف به‌روزرسانی می‌شوند.

```python
def set_external_workbook(self, workbook_path):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| workbook_path | **str** | مسیر به کتاب‌کار هدف |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | کتاب‌کار خارجی در دسترس نیست یا نمی‌توان آن را بارگیری کرد. |

## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
یک کتاب‌کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند.

```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| workbook_path | **str** | مسیر به کتاب‌کار هدف |
| update_chart_data | **bool** | اگر مقدار false باشد فقط مسیر کتاب‌کار به‌روزرسانی می‌شود. <br/><br/>             داده‌های نمودار از کتاب‌کار هدف بارگیری و به‌روزرسانی نمی‌شوند. می‌توان از آن زمانی استفاده کرد که کتاب‌کار هدف وجود ندارد یا در دسترس نیست.<br/><br/>             اگر مقدار true باشد داده‌های نمودار از کتاب‌کار هدف به‌روزرسانی می‌شوند. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | کتاب‌کار خارجی در دسترس نیست یا نمی‌توان آن را بارگیری کرد. |

### موارد مرتبط
* کلاس [`IChartData`](/slides/python-net/fa/aspose.slides.charts/ichartdata)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)