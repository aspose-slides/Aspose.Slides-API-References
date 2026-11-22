---
title: set_external_workbook method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
يحدد دفتر عمل خارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من دفتر العمل المستهدف.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| معلمة | نوع | وصف |
| :- | :- | :- |
| workbook_path | **str** | المسار إلى دفتر العمل المستهدف |

### الاستثناءات

| استثناء | وصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | دفتر العمل الخارجي غير متاح أو لا يمكن تحميله. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
يحدد دفتر عمل خارجي كمصدر بيانات للمخطط.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| معلمة | نوع | وصف |
| :- | :- | :- |
| workbook_path | **str** | المسار إلى دفتر العمل المستهدف |
| update_chart_data | **bool** | إذا كانت القيمة false سيتم تحديث مسار دفتر العمل فقط. <br/><br/>             لن يتم تحميل بيانات المخطط وتحديثها من دفتر العمل المستهدف. يمكن استخدام ذلك عندما لا يكون دفتر العمل المستهدف موجودًا أو غير متاح.<br/><br/>             إذا كانت القيمة true سيتم تحديث بيانات المخطط من دفتر العمل المستهدف. |

### الاستثناءات

| استثناء | وصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | دفتر العمل الخارجي غير متاح أو لا يمكن تحميله. |



### انظر أيضًا
* فئة [`ChartData`](/slides/python-net/ar/aspose.slides.charts/chartdata)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)