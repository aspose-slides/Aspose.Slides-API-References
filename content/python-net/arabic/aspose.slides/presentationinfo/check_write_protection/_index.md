---
title: check_write_protection method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة للعرض المحمي للكتابة.

### القيم المرجعة

True إذا كان العرض محميًا للكتابة وكانت كلمة المرور صحيحة. False غير ذلك.



```python
def check_write_protection(self, password):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| password | **str** | كلمة المرور للتحقق. |

### الملاحظات

1. يجب عليك التحقق من الخاصية [`PresentationInfo.is_write_protected`](/slides/python-net/ar/aspose.slides/presentationinfo/is_write_protected) قبل استدعاء هذه الطريقة.
2. عندما تكون كلمة المرور None أو فارغة، تُعيد هذه الطريقة false.

### الاستثناءات

| استثناء | وصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### انظر أيضًا
* الفئة [`PresentationInfo`](/slides/python-net/ar/aspose.slides/presentationinfo)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)