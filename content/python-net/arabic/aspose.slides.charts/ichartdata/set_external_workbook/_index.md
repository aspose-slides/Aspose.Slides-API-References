---
title: set_external_workbook method
second_title: مرجع API لـ Aspose.Slides للغة Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
يحدد دفتر عمل خارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من دفتر العمل المستهدف.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| workbook_path | **str** | المسار إلى دفتر العمل الهدف |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | دفتر العمل الخارجي غير متوفر أو لا يمكن تحميله. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
يحدد دفتر عمل خارجي كمصدر بيانات للمخطط.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| workbook_path | **str** | المسار إلى دفتر العمل الهدف |
| update_chart_data | **bool** | إذا كانت القيمة false فإن مسار دفتر العمل فقط سيُحدّث. <br/><br/>             لن يتم تحميل بيانات المخطط وتحديثها من دفتر العمل المستهدف. يمكن استخدامها عندما لا يكون دفتر العمل المستهدف موجودًا أو غير متاح.<br/><br/>             إذا كانت القيمة true فإن بيانات المخطط سيتم تحديثها من دفتر العمل المستهدف. |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | دفتر العمل الخارجي غير متوفر أو لا يمكن تحميله. |



### انظر أيضًا
* الصنف [`IChartData`](/slides/python-net/ar/aspose.slides.charts/ichartdata)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)