---
title: add method
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
cell جدید را به مجموعه اضافه می‌کند.

```python
def add(self, cell):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell) | cell جدید برای افزودن. |

## add(self, value) {#any}
[`ChartDataCell`](/slides/python-net/fa/aspose.slides.charts/chartdatacell) را از value مشخص شده ایجاد می‌کند و آن را به مجموعه اضافه می‌کند.

```python
def add(self, value):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| value | **any** | مقدار. |

### توضیحات
این متد worksheet با نام AUTO_DATA را اضافه می‌کند و تمام مقادیر را در آن می‌افزاید.  اگر از [`ChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/chartdataworkbook) برای اضافه یا ویرایش Cell مقادیر استفاده می‌کنید، مطمئن شوید که از این worksheet استفاده نمی‌کنید
            حداکثر تعداد مقادیر اضافه شده با این متد نباید از 16711680 تجاوز کند

### استثنائات
| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | اگر حد تجاوز شود |

### مراجع
* کلاس [`ChartCellCollection`](/slides/python-net/fa/aspose.slides.charts/chartcellcollection)
* کلاس [`ChartDataCell`](/slides/python-net/fa/aspose.slides.charts/chartdatacell)
* کلاس [`ChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/chartdataworkbook)
* کلاس [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)