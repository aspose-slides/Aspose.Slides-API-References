---
title: set_external_workbook method
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
یک کتابخانه کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کتابخانه هدف به‌روزرسانی خواهد شد.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| workbook_path | **str** | مسیر به کتابخانه کار هدف |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | کتابخانه کار خارجی در دسترس نیست یا قابل بارگذاری نیست. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
یک کتابخانه کار خارجی را به عنوان منبع داده برای نمودار تنظیم می‌کند.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| workbook_path | **str** | مسیر به کتابخانه کار هدف |
| update_chart_data | **bool** | اگر مقدار false باشد فقط مسیر کتابخانه کار به‌روزرسانی می‌شود. <br/><br/>             داده‌های نمودار از کتابخانه هدف بارگذاری یا به‌روزرسانی نخواهد شد. می‌تواند زمانی که کتابخانه هدف وجود ندارد یا در دسترس نیست استفاده شود.<br/><br/>             اگر مقدار true باشد داده‌های نمودار از کتابخانه هدف به‌روزرسانی خواهد شد. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | کتابخانه کار خارجی در دسترس نیست یا قابل بارگذاری نیست. |



### همچنین ببینید
* کلاس [`ChartData`](/slides/python-net/fa/aspose.slides.charts/chartdata)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)