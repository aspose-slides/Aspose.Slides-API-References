---
title: set_license method
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
مجوزدهی به مؤلفه.


```python
def set_license(self, license_name):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| license_name | **str** | می‌تواند یک نام فایل کامل یا کوتاه یا نام یک منبع جاسازی شده باشد.<br/><br/>            برای سوئیچ به حالت ارزیابی از رشته خالی استفاده کنید. |

### توضیحات

سعی می‌کند لایسنس را در مکان‌های زیر پیدا کند:

1. مسیر صریح.
2. پوشه‌ی اسمبلی مؤلفه.
3. پوشه‌ی اسمبلی فراخوانی‌کنندهٔ مشتری.
4. پوشه‌ی اسمبلی ورودی.
5. یک منبع جاسازی شده در اسمبلی فراخوانی‌کنندهٔ مشتری.

**توجه:** در .NET Compact Framework، سعی می‌کند لایسنس را فقط در این مکان‌ها پیدا کند:

1. مسیر صریح.
2. یک منبع جاسازی شده در اسمبلی فراخوانی‌کنندهٔ مشتری.


## set_license(self, stream) {#iorawiobase}
مجوزدهی به مؤلفه.


```python
def set_license(self, stream):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریانی که لایسنس را شامل می‌شود. |

### توضیحات

از این متد برای بارگذاری لایسنس از یک جریان استفاده کنید.



### موارد مرتبط
* کلاس [`License`](/slides/python-net/fa/aspose.slides/license)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)