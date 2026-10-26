---
title: set_range method
second_title: Aspose.Slides للبايثون عبر .NET – مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
تعيين نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على النطاق الجديد للبيانات.
    إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط، فستتم إضافة سلاسل إضافية من نفس النوع كسلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة.


```python
def set_range(self, formula):
    ...
```


| معلمة | نوع | الوصف |
| :- | :- | :- |
| formula | **str** | صيغة نطاق بيانات الخلايا. مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula هو None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | نوع المخطط غير مدعوم |
| **RuntimeError(Proxy error(ArgumentException))** | الصيغة غير صحيحة. |



### انظر أيضا
* فئة [`ChartData`](/slides/python-net/ar/aspose.slides.charts/chartdata)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)