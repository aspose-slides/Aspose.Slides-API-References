---
title: set_external_workbook method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
يحدد المصنف الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من المصنف المستهدف.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | مسار المصنف المستهدف |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | مصنف خارجي غير متاح أو لا يمكن تحميله. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
يحدد المصنف الخارجي كمصدر بيانات للمخطط.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | مسار المصنف المستهدف |
| update_chart_data | **bool** | إذا كانت القيمة false فسيتم تحديث مسار المصنف فقط. <br/><br/>             لا يتم تحميل بيانات المخطط وتحديثها من المصنف المستهدف. يمكن استخدامها عندما لا يكون المصنف المستهدف موجودًا أو غير متاح.<br/><br/>             إذا كانت القيمة true فسيتم تحديث بيانات المخطط من المصنف المستهدف. |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | مصنف خارجي غير متاح أو لا يمكن تحميله. |



### انظر أيضًا
* الفئة [`ChartData`](/slides/python-net/ar/aspose.slides.charts/chartdata)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)