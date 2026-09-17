---
title: check_write_protection method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
يحدد ما إذا كان عرض تقديمي محميًا بكلمة مرور للتعديل.

### القيمة المرجعة
True إذا كان كلمة المرور صالحة؛ وإلا false.



```python
def check_write_protection(self, password):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| password | **str** | كلمة المرور للتحقق. |

### ملاحظات
1. يجب عليك التحقق من الخاصية [`ProtectionManager.is_write_protected`](/slides/python-net/ar/aspose.slides/protectionmanager/is_write_protected) قبل استدعاء هذه الطريقة.
2. عند كون كلمة المرور None أو فارغة، تعيد هذه الطريقة false.



### انظر أيضًا
* فئة [`ProtectionManager`](/slides/python-net/ar/aspose.slides/protectionmanager)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)