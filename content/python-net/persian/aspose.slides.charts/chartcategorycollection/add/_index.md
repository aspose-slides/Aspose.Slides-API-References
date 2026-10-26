---
title: add method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
اگر دسته در مجموعه وجود داشته باشد، آن را برگردانید. در غیر این صورت دسته جدید نمودار را از [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell) ایجاد کرده و به مجموعه اضافه می‌کند.

### بازگشت

دسته افزوده‌شده یا موجود.

```python
def add(self, chart_data_cell):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell) | سلولی که برای ایجاد دسته نمودار استفاده می‌شود. |

## add(self, value) {#any}
از مقدار یک [`ChartCategory`](/slides/python-net/fa/aspose.slides.charts/chartcategory) جدید ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

### بازگشت

افزوده شد [`IChartCategory`](/slides/python-net/fa/aspose.slides.charts/ichartcategory).

```python
def add(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | **any** | مقدار. |

### توضیحات

این متد یک برگه کاری با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن قرار می‌دهد. اگر از [`ChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/chartdataworkbook) برای افزودن یا ویرایش مقادیر سلول استفاده می‌کنید، مطمئن شوید که از این برگه کاری استفاده نمی‌کنید
حداکثر تعداد مقادیری که با استفاده از این متد اضافه می‌شوند نباید بیش از 16711680 باشد

### استثنائات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | اگر محدودیت تجاوز شود |

### موارد مرتبط
* کلاس [`ChartCategory`](/slides/python-net/fa/aspose.slides.charts/chartcategory)
* کلاس [`ChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/chartcategorycollection)
* کلاس [`ChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/chartdataworkbook)
* کلاس [`IChartCategory`](/slides/python-net/fa/aspose.slides.charts/ichartcategory)
* کلاس [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)