---
title: add method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
ينشئ سلسلة مخطط جديدة ويضيفها إلى المجموعة.

### Returns
سلسلة مخطط جديدة.



```python
def add(self, type):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع السلسلة |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
ينشئ سلسلة مخطط جديدة من [`ChartDataCell`](/slides/python-net/ar/aspose.slides.charts/chartdatacell) ويضيفها إلى المجموعة.

### Returns
سلسلة المخطط المضافة أو السلسلة الموجودة بالفعل في المجموعة.



```python
def add(self, cell_with_series_name, type):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell) | الخلية التي تحتوي على اسم السلسلة. |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع مجموعة نوع السلسلة |

### Remarks
إذا كانت سلسلة المخطط المنشأة من نفس الخلية موجودة بالفعل في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد مؤشرها.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
ينشئ سلسلة مخطط جديدة من [`ChartCellCollection`](/slides/python-net/ar/aspose.slides.charts/chartcellcollection) ويضيفها إلى المجموعة.

### Returns
سلسلة المخطط المضافة أو السلسلة الموجودة بالفعل في المجموعة.



```python
def add(self, cells_with_series_name, type):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcellcollection) | الخلايا التي تحتوي على اسم السلسلة. |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع مجموعة نوع السلسلة |

### Remarks
إذا كانت سلسلة المخطط المنشأة من نفس الخلية موجودة بالفعل في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد مؤشرها.


## add(self, name, type) {#str-charttype}
ينشئ سلسلة مخطط جديدة من القيمة ويضيفها إلى المجموعة.

### Returns
سلسلة المخطط المضافة.



```python
def add(self, name, type):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| name | **str** | اسم السلسلة. |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع مجموعة نوع السلسلة |



### انظر أيضًا
* class [`ChartCellCollection`](/slides/python-net/ar/aspose.slides.charts/chartcellcollection)
* class [`ChartDataCell`](/slides/python-net/ar/aspose.slides.charts/chartdatacell)
* class [`ChartSeriesCollection`](/slides/python-net/ar/aspose.slides.charts/chartseriescollection)
* enumeration [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype)
* class [`IChartCellCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcellcollection)
* class [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell)
* class [`IChartSeries`](/slides/python-net/ar/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)