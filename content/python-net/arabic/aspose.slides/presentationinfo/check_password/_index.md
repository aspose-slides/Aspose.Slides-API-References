---
title: check_password method
second_title: مرجع API Aspose.Slides للغة بايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
يتحقق مما إذا كانت كلمة المرور صحيحة لعروض تقديمية محمية بكلمة مرور مفتوحة.

### الإرجاع

True إذا كان العرض التقديمي محميًا بكلمة مرور مفتوحة وكانت كلمة المرور صحيحة، وإلا false.



```python
def check_password(self, password):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| password | **str** | كلمة المرور للتحقق منها. |

### ملاحظات

عندما تكون كلمة المرور None أو فارغة، تُعيد هذه الطريقة false.

### الاستثناءات

| استثناء | وصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### انظر أيضًا
* فئة [`PresentationInfo`](/slides/python-net/ar/aspose.slides/presentationinfo)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)