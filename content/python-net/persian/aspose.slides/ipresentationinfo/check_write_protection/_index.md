---
title: check_write_protection method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
بررسی می‌کند که آیا رمز عبور برای ویرایش برای ارائه‌ای که محافظت نوشتاری دارد، صحیح است یا خیر.

### Returns
True اگر ارائه محافظت نوشتاری باشد و رمز عبور صحیح باشد. False در غیر این صورت.



```python
def check_write_protection(self, password):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| password | **str** | رمز عبوری که باید بررسی شود. |

### Remarks
1. باید قبل از فراخوانی این متد، ویژگی [`IPresentationInfo.is_write_protected`](/slides/python-net/fa/aspose.slides/ipresentationinfo/is_write_protected) را بررسی کنید.
2. زمانی که password مقدار None یا خالی باشد، این متد false برمی‌گرداند.

### Exceptions
| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### See Also
* کلاس [`IPresentationInfo`](/slides/python-net/fa/aspose.slides/ipresentationinfo)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)