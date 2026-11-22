---
title: refresh_data method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/refresh_data/
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

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | يتم إلقاؤه عندما لا يكون تنسيق دفتر العمل مدعومًا، أو عندما [`ChartData.data_source_type`](/slides/python-net/ar/aspose.slides.charts/chartdata/data_source_type) هو<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ar/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) ولا يمكن الوصول إلى دفتر العمل الخارجي أو تحميله. |



### انظر أيضاً
* فئة [`ChartData`](/slides/python-net/ar/aspose.slides.charts/chartdata)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)