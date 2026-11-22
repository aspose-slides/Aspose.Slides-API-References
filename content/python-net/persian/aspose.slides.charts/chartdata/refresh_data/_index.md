---
title: refresh_data method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
دیتای نمودار را با بارگذاری مجدد از دفتر کار منبع تازه می‌کند.

```python
def refresh_data(self):
    ...
```

### توضیحات

اگر نمودار از یک دفتر کار خارجی استفاده کند، دفتر کار باید در زمان فراخوانی در دسترس باشد.

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | در زمانی که قالب دفتر کار پشتیبانی نمی‌شود، یا زمانی که [`ChartData.data_source_type`](/slides/python-net/fa/aspose.slides.charts/chartdata/data_source_type) است<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/fa/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) و دفتر کار خارجی قابل دسترسی یا بارگذاری نیست. |

### مراجع
* کلاس [`ChartData`](/slides/python-net/fa/aspose.slides.charts/chartdata)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)