---
title: check_write_protection method
second_title: مرجع Aspose.Slides للـ Python عبر .NET API
description: 
type: docs
url: /ar/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
يتحقق مما إذا كانت كلمة المرور لتعديل العرض التقديمي محمية للكتابة صحيحة.

### Returns
القيمة المرجعة

True إذا كان العرض التقديمي محميًا للكتابة وكانت كلمة المرور صحيحة. False خلاف ذلك.

```python
def check_write_protection(self, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| password | **str** | كلمة المرور للتحقق منها. |

### Remarks
ملاحظات

1. يجب عليك التحقق من خاصية [`IPresentationInfo.is_write_protected`](/slides/python-net/ar/aspose.slides/ipresentationinfo/is_write_protected) قبل استدعاء هذه الطريقة.
2. عندما تكون كلمة المرور None أو فارغة، تُعيد هذه الطريقة false.

### Exceptions
الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |

### See Also
انظر أيضًا
* الفئة [`IPresentationInfo`](/slides/python-net/ar/aspose.slides/ipresentationinfo)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)