---
title: add method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
اگر دسته‌بندی در مجموعه وجود داشته باشد، آن را برمی‌گرداند. در غیر اینصورت، دسته‌بندی نمودار جدیدی از [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌گردد.

### بازگشت

دسته‌بندی اضافه‌شده یا موجود.



```python
def add(self, chart_data_cell):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell) | Cell استفاده شده برای ایجاد دسته‌بندی نمودار. |


## add(self, value) {#any}
یک [`IChartCategory`](/slides/python-net/fa/aspose.slides.charts/ichartcategory) جدید از مقدار ایجاد می‌کند و به مجموعه اضافه می‌گردد.

### بازگشت

[`IChartCategory`](/slides/python-net/fa/aspose.slides.charts/ichartcategory) اضافه شد.



```python
def add(self, value):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| value | **any** | مقدار. |

### توضیحات

این روش worksheet با نام AUTO_DATA را اضافه می‌کند و همه مقادیر را در آن می‌گذارد. اگر از [`IChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/ichartdataworkbook) برای افزودن یا ویرایش مقادیر سلول استفاده کنید، مطمئن شوید که از این worksheet استفاده نمی‌کنید
            حداکثر تعداد مقادیری که با این روش اضافه می‌شود نباید از 16711680 بیشتر باشد

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | اگر محدودیت تجاوز شود |



### موارد مرتبط
* کلاس [`IChartCategory`](/slides/python-net/fa/aspose.slides.charts/ichartcategory)
* کلاس [`IChartCategoryCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcategorycollection)
* کلاس [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell)
* کلاس [`IChartDataWorkbook`](/slides/python-net/fa/aspose.slides.charts/ichartdataworkbook)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)