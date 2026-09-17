---
title: add method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
ينشئ سلسلة مخطط جديدة ويضيفها إلى المجموعة.

### الإرجاع
سلسلة مخطط جديدة.



```python
def add(self, type):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع السلسلة |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
ينشئ سلسلة مخطط جديدة من [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell) ويضيفها إلى المجموعة.

### الإرجاع
سلسلة مخطط مضافة أو سلسلة موجودة بالفعل في المجموعة.



```python
def add(self, cell_with_series_name, type):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell) | خلية تحتوي على اسم السلسلة. |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع يحدد نوع السلسلة |

### ملاحظات
إذا تم إنشاء سلسلة مخطط من نفس الخلية الموجودة بالفعل في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد فهرسها.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
ينشئ سلسلة مخطط جديدة من [`IChartCellCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcellcollection) ويضيفها إلى المجموعة.

### الإرجاع
سلسلة مخطط مضافة أو سلسلة موجودة بالفعل في المجموعة.



```python
def add(self, cells_with_series_name, type):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcellcollection) | الخلايا التي تحتوي على اسم السلسلة. |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع يحدد نوع السلسلة |

### ملاحظات
إذا تم إنشاء سلسلة مخطط من نفس الخلية الموجودة بالفعل في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد فهرسها.


## add(self, name, type) {#str-charttype}
ينشئ سلسلة مخطط جديدة من القيمة ويضيفها إلى المجموعة.

### الإرجاع
سلسلة مخطط مضافة.



```python
def add(self, name, type):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| name | **str** | اسم السلسلة. |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع يحدد نوع السلسلة |



### انظر أيضًا
* تعداد [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype)
* فئة [`IChartCellCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcellcollection)
* فئة [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell)
* فئة [`IChartSeries`](/slides/python-net/ar/aspose.slides.charts/ichartseries)
* فئة [`IChartSeriesCollection`](/slides/python-net/ar/aspose.slides.charts/ichartseriescollection)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)