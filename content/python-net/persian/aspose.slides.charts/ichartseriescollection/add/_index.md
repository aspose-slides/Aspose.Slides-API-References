---
title: add method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
یک سری جدید نمودار ایجاد می‌کند و آن را به مجموعه اضافه می‌کند.

### بازگرداندن

سری جدید نمودار.



```python
def add(self, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype) | نوع سری |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
یک سری جدید نمودار از [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell) ایجاد می‌کند و آن را به مجموعه اضافه می‌کند.

### بازگرداندن

سری نمودار اضافه‌شده یا سری‌ای که قبلاً در مجموعه وجود دارد.



```python
def add(self, cell_with_series_name, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell) | سلولی که حاوی نام سری است. |
| type | [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype) | نوع تعیین شده برای سری |

### توضیحات

اگر سری نمودار از همان سلول که قبلاً در مجموعه وجود دارد ایجاد شده باشد، متد هیچ‌چیز اضافه نمی‌کند و اندیس آن را برمی‌گرداند.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
یک سری جدید نمودار از [`IChartCellCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcellcollection) ایجاد می‌کند و آن را به مجموعه اضافه می‌کند.

### بازگرداندن

سری نمودار اضافه‌شده یا سری‌ای که قبلاً در مجموعه وجود دارد.



```python
def add(self, cells_with_series_name, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcellcollection) | سلول‌هایی که حاوی نام سری هستند. |
| type | [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype) | نوع تعیین شده برای سری |

### توضیحات

اگر سری نمودار از همان سلول که قبلاً در مجموعه وجود دارد ایجاد شده باشد، متد هیچ‌چیز اضافه نمی‌کند و اندیس آن را برمی‌گرداند.


## add(self, name, type) {#str-charttype}
یک سری جدید نمودار از مقدار ایجاد می‌کند و آن را به مجموعه اضافه می‌کند.

### بازگرداندن

سری نمودار اضافه شد.



```python
def add(self, name, type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | **str** | نام سری. |
| type | [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype) | نوع تعیین شده برای سری |



### موارد مرتبط
* شمارشی [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype)
* کلاس [`IChartCellCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcellcollection)
* کلاس [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell)
* کلاس [`IChartSeries`](/slides/python-net/fa/aspose.slides.charts/ichartseries)
* کلاس [`IChartSeriesCollection`](/slides/python-net/fa/aspose.slides.charts/ichartseriescollection)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)