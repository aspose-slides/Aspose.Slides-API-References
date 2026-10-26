---
title: check_write_protection method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
يحدد ما إذا كان العرض التقديمي محميًا بكلمة مرور للتعديل.

### القيمة المرجعة
True إذا كانت كلمة المرور صالحة؛ وإلا false.



```python
def check_write_protection(self, password):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| password | **str** | كلمة المرور للتحقق. |

### ملاحظات
1. يجب عليك فحص الخاصية [`IProtectionManager.is_write_protected`](/slides/python-net/ar/aspose.slides/iprotectionmanager/is_write_protected) قبل استدعاء هذه الطريقة.
2. عندما تكون كلمة المرور None أو فارغة، تُعيد هذه الطريقة false.



### انظر أيضًا
* الفئة [`IProtectionManager`](/slides/python-net/ar/aspose.slides/iprotectionmanager)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)