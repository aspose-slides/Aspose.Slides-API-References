---
title: set_external_workbook method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
یک کاربرگ خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کاربرگ هدف به‌روز می‌شوند.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| workbook_path | **str** | مسیر به کاربرگ هدف |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | کاربرگ خارجی در دسترس نیست یا نمی‌تواند بارگذاری شود. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
یک کاربرگ خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| workbook_path | **str** | مسیر به کاربرگ هدف |
| update_chart_data | **bool** | اگر مقدار false باشد فقط مسیر کاربرگ به‌روزرسانی می‌شود. <br/><br/>             داده‌های نمودار بارگذاری و به‌روز نمی‌شوند از کاربرگ هدف. می‌توان از آن زمانی استفاده کرد که کاربرگ هدف وجود نداشته باشد یا در دسترس نباشد.<br/><br/>             اگر مقدار true باشد داده‌های نمودار از کاربرگ هدف به‌روز می‌شوند. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | کاربرگ خارجی در دسترس نیست یا نمی‌تواند بارگذاری شود. |



### موارد مرتبط
* کلاس [`IChartData`](/slides/python-net/fa/aspose.slides.charts/ichartdata)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)