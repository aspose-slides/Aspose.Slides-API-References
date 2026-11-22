---
title: set_range method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
تعيين نطاق بيانات المخطط. سيُحدَّث السلاسل والفئات بناءً على نطاق البيانات الجديد.
إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط، فستُضاف سلاسل إضافية من نفس النوع
كالسلسلة الأخيرة في المجموعة الحالية، وستُضاف إلى نهاية المجموعة.


```python
def set_range(self, formula):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | **str** | صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | الصيغة هي None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | نوع المخطط غير مدعوم |
| **RuntimeError(Proxy error(ArgumentException))** | الصيغة ذات تنسيق غير صحيح. |



### انظر أيضًا
* الفئة [`ChartData`](/slides/python-net/ar/aspose.slides.charts/chartdata)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)