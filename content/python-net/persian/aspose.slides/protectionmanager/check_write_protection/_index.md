---
title: check_write_protection method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
تعیین می‌کند آیا ارائه برای ویرایش با رمز عبور محافظت شده است یا خیر.

### مقدار بازگشتی

اگر رمز عبور معتبر باشد، True؛ در غیر این صورت، false.



```python
def check_write_protection(self, password):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| password | **str** | The password for checking. |

### توضیحات

1. قبل از فراخوانی این متد، باید ویژگی [`ProtectionManager.is_write_protected`](/slides/python-net/fa/aspose.slides/protectionmanager/is_write_protected) را بررسی کنید.
2. وقتی رمز عبور None یا خالی باشد، این متد false برمی‌گرداند.



### مراجع
* کلاس [`ProtectionManager`](/slides/python-net/fa/aspose.slides/protectionmanager)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)