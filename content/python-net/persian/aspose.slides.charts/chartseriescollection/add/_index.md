---
title: add method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
یک سری نمودار جدید ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

### بازمی‌گردد

سری نمودار جدید.



```python
def add(self, type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype) | نوع سری |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
یک سری نمودار جدید از [`ChartDataCell`](/slides/python-net/fa/aspose.slides.charts/chartdatacell) ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

### بازمی‌گردد

سری نمودار اضافه‌شده یا سری که پیشاپیش در مجموعه موجود است.



```python
def add(self, cell_with_series_name, type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell) | سلولی که نام سری را شامل می‌شود. |
| type | [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype) | نوع مشخص‌کننده نوع سری |

### یادداشت‌ها

اگر سری نمودار از همان سلول که پیشاپیش در مجموعه وجود دارد ایجاد شود، روش هیچ‌چیزی اضافه نمی‌کند و اندیس آن را بازمی‌گرداند.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
یک سری نمودار جدید از [`ChartCellCollection`](/slides/python-net/fa/aspose.slides.charts/chartcellcollection) ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

### بازمی‌گردد

سری نمودار اضافه‌شده یا سری که پیشاپیش در مجموعه موجود است.



```python
def add(self, cells_with_series_name, type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcellcollection) | سلول‌هایی که نام سری را شامل می‌شوند. |
| type | [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype) | نوع مشخص‌کننده نوع سری |

### یادداشت‌ها

اگر سری نمودار از همان سلول که پیشاپیش در مجموعه وجود دارد ایجاد شود، روش هیچ‌چیزی اضافه نمی‌کند و اندیس آن را بازمی‌گرداند.


## add(self, name, type) {#str-charttype}
یک سری نمودار جدید از مقدار ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

### بازمی‌گردد

سری نمودار اضافه‌شده.



```python
def add(self, name, type):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| name | **str** | نام سری. |
| type | [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype) | نوع مشخص‌کننده نوع سری |



### مراجع
* کلاس [`ChartCellCollection`](/slides/python-net/fa/aspose.slides.charts/chartcellcollection)
* کلاس [`ChartDataCell`](/slides/python-net/fa/aspose.slides.charts/chartdatacell)
* کلاس [`ChartSeriesCollection`](/slides/python-net/fa/aspose.slides.charts/chartseriescollection)
* شمارش [`ChartType`](/slides/python-net/fa/aspose.slides.charts/charttype)
* کلاس [`IChartCellCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcellcollection)
* کلاس [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell)
* کلاس [`IChartSeries`](/slides/python-net/fa/aspose.slides.charts/ichartseries)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)