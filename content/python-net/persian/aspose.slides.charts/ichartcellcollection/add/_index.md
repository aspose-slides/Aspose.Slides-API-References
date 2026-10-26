---
title: add method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
یک سلول جدید به مجموعه اضافه می‌کند.

```python
def add(self, chart_data_cell):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell) | سلول جدید برای اضافه کردن. |

## add(self, value) {#any}
از مقدار مشخص شده [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell) را ساخته و به مجموعه اضافه می‌کند.

```python
def add(self, value):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| value | **any** | مقدار. |

### توضیحات
این متد یک کاربرگ با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن درج می‌نماید. اگر از [`IChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/ichartdataworkbook) برای افزودن یا ویرایش مقادیر سلول استفاده می‌کنید، اطمینان حاصل کنید که از این کاربرگ استفاده نکنید.
    حداکثر تعداد مقادیری که با استفاده از این متد اضافه می‌شوند نباید از 16711680 بیشتر باشد

### استثناها
| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | اگر محدودیت تجاوز شد |

### موارد مرتبط
* کلاس [`IChartCellCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcellcollection)
* کلاس [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell)
* کلاس [`IChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/ichartdataworkbook)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)