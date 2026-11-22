---
title: refresh_data method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
دیتاهای نمودار را با بارگذاری مجدد از کتاب‌کار منبع تازه می‌کند.


```python
def refresh_data(self):
    ...
```


### توضیحات

اگر نمودار از یک کتاب‌کار خارجی استفاده کند، کتاب‌کار باید در زمان فراخوانی در دسترس باشد.

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | زمانی که قالب کتاب‌کار پشتیبانی نمی‌شود یا زمانی که [`IChartData.data_source_type`](/slides/python-net/fa/aspose.slides.charts/ichartdata/data_source_type) باشد<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/fa/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) و کتاب‌کار خارجی نمی‌تواند دسترسی پیدا کند یا بارگذاری شود. |



### موارد مرتبط
* کلاس [`IChartData`](/slides/python-net/fa/aspose.slides.charts/ichartdata)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)