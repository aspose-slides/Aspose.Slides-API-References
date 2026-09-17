---
title: add method
second_title: مرجع API لـ Aspose.Slides for Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
إذا كان الفئة موجودة في المجموعة، تُرجعها. وإلا تُنشئ فئة مخطط جديدة من [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell) وتضيفها إلى المجموعة.

### القيمة المرجعة

الفئة المُضافة أو الموجودة.



```python
def add(self, chart_data_cell):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell) | الخلية المستخدمة لإنشاء فئة المخطط. |


## add(self, value) {#any}
يُنشئ [`ChartCategory`](/slides/python-net/ar/aspose.slides.charts/chartcategory) جديدًا من القيمة ويضيفه إلى المجموعة.

### القيمة المرجعة

تمت إضافة [`IChartCategory`](/slides/python-net/ar/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| value | **any** | القيمة. |

### ملاحظات

تضيف هذه الطريقة ورقة عمل باسم AUTO_DATA وتضيف جميع القيم هناك. إذا استخدمت [`ChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/chartdataworkbook) لإضافة أو تعديل قيم الخلايا، تأكد من عدم استخدام هذه ورقة العمل. الحد الأقصى لعدد القيم المضافة باستخدام هذه الطريقة لا يجب أن يتجاوز 16711680.

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | في حال تجاوز الحد |



### أنظر أيضًا
* الفئة [`ChartCategory`](/slides/python-net/ar/aspose.slides.charts/chartcategory)
* الفئة [`ChartCategoryCollection`](/slides/python-net/ar/aspose.slides.charts/chartcategorycollection)
* الفئة [`ChartDataWorkbook`](/slides/python-net/ar/aspose.slides.charts/chartdataworkbook)
* الفئة [`IChartCategory`](/slides/python-net/ar/aspose.slides.charts/ichartcategory)
* الفئة [`IChartDataCell`](/slides/python-net/ar/aspose.slides.charts/ichartdatacell)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)