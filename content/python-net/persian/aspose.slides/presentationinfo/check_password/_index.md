---
title: check_password method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
بررسی می‌کند که آیا رمز عبور برای یک ارائه که با رمز باز محافظت شده است، صحیح است یا خیر.

### بازگشت

True اگر ارائه با رمز باز محافظت شده باشد و رمز عبور صحیح باشد و در غیر این صورت false است.



```python
def check_password(self, password):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| password | **str** | رمزی که باید بررسی شود. |

### یادداشت‌ها

وقتی رمز عبور None یا خالی باشد، این متد false را برمی‌گرداند.

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### موارد مرتبط
* کلاس [`PresentationInfo`](/slides/python-net/fa/aspose.slides/presentationinfo)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)