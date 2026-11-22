---
title: refresh_data method
second_title: مرجع API Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
يقوم بتحديث بيانات المخطط عن طريق إعادة تحميلها من دفتر العمل المصدر.

```python
def refresh_data(self):
    ...
```

### ملاحظات
إذا كان المخطط يستخدم دفتر عمل خارجي، يجب أن يكون دفتر العمل متاحًا في وقت الاستدعاء.

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | يتم رمي الاستثناء عندما لا يكون تنسيق دفتر العمل مدعومًا، أو عندما يكون [`IChartData.data_source_type`](/slides/python-net/ar/aspose.slides.charts/ichartdata/data_source_type)<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ar/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) ولا يمكن الوصول إلى دفتر العمل الخارجي أو تحميله. |

### انظر أيضًا
* الفئة [`IChartData`](/slides/python-net/ar/aspose.slides.charts/ichartdata)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)