---
title: check_write_protection method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
تعیین می‌کند که آیا یک ارائه با گذرواژه برای ویرایش محافظت شده است یا خیر.

### بازگشت

True اگر گذرواژه معتبر باشد؛ در غیر این صورت false.



```python
def check_write_protection(self, password):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| password | **str** | گذرواژه برای بررسی. |

### توضیحات

1. شما باید قبل از فراخوانی این متد، خصوصیت [`IProtectionManager.is_write_protected`](/slides/python-net/fa/aspose.slides/iprotectionmanager/is_write_protected) را بررسی کنید.
2. وقتی گذرواژه None یا خالی باشد، این متد false برمی‌گرداند.



### موارد مرتبط
* کلاس [`IProtectionManager`](/slides/python-net/fa/aspose.slides/iprotectionmanager)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)