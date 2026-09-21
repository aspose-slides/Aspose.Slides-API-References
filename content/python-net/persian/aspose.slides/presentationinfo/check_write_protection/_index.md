---
title: check_write_protection method
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
بررسی می‌کند که آیا رمز عبور برای ویرایش برای ارائه‌ای که محافظت‌نویسی دارد صحیح است یا خیر.

### بازگشت

True اگر ارائه محافظت‌نویسی باشد و رمز عبور صحیح باشد. False در غیر این صورت.



```python
def check_write_protection(self, password):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| password | **str** | رمز عبوری که باید بررسی شود. |

### نکات

1. باید پیش از فراخوانی این متد، ویژگی [`PresentationInfo.is_write_protected`](/slides/python-net/fa/aspose.slides/presentationinfo/is_write_protected) را بررسی کنید.
2. وقتی password برابر None یا تهی باشد، این متد false را برمی‌گرداند.

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### موارد مرتبط
* کلاس [`PresentationInfo`](/slides/python-net/fa/aspose.slides/presentationinfo)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)