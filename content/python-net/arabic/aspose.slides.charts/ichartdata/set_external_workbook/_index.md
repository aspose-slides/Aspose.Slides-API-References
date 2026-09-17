---
title: set_external_workbook method
second_title: Aspose.Slides للبايثون عبر .NET - مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
يحدد دفتر عمل خارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من دفتر العمل المستهدف.

```python
def set_external_workbook(self, workbook_path):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| workbook_path | **str** | المسار إلى دفتر العمل المستهدف |

### الاستثناءات

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
| workbook_path | **str** | المسار إلى دفتر العمل المستهدف |
| update_chart_data | **bool** | إذا كانت القيمة false سيتم تحديث مسار دفتر العمل فقط. <br/><br/>             لن يتم تحميل بيانات المخطط وتحديثها من دفتر العمل المستهدف. يمكن استخدام هذا عندما يكون دفتر العمل المستهدف غير موجود أو غير متاح.<br/><br/>             إذا كانت القيمة true سيتم تحديث بيانات المخطط من دفتر العمل المستهدف. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | دفتر العمل الخارجي غير متوفر أو لا يمكن تحميله. |

### انظر أيضًا
* الفئة [`IChartData`](/slides/python-net/ar/aspose.slides.charts/ichartdata)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)