---
title: set_range method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
تعيين نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على النطاق الجديد للبيانات.
            إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط فإن السلاسل الإضافية من نفس النوع
            كآخر سلسلة في المجموعة الحالية ستُضاف إلى نهاية المجموعة.

```python
def set_range(self, formula):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| formula | **str** | صيغة نطاق بيانات الخلايا. على سبيل المثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### استثناءات

| استثناء | وصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | الصيغة هي None. |
| **RuntimeError(Proxy error(ArgumentException))** | الصيغة ذات تنسيق غير صحيح. |

### انظر أيضًا
* فئة [`IChartData`](/slides/python-net/ar/aspose.slides.charts/ichartdata)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)