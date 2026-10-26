---
title: set_license method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
مجوزدهی به مؤلفه.


```python
def set_license(self, license_name):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| license_name | **str** | می‌تواند نام فایل کامل یا کوتاه یا نام منبع تعبیه‌شده باشد.<br/><br/>برای تغییر به حالت ارزیابی یک رشتهٔ خالی را استفاده کنید. |

### توضیحات

سعی می‌کند مجوز را در مکان‌های زیر پیدا کند:


1. مسیر صریح.

2. پوشهٔ اسمبلی مؤلفه.

3. پوشهٔ اسمبلی فراخوانی‌کنندهٔ مشتری.

4. پوشهٔ اسمبلی ورودی.

5. منبع تعبیه‌شده در اسمبلی فراخوانی‌کنندهٔ مشتری.

**توجه:** در .NET Compact Framework، سعی می‌کند مجوز را فقط در این مکان‌ها پیدا کند:


1. مسیر صریح.

2. منبع تعبیه‌شده در اسمبلی فراخوانی‌کنندهٔ مشتری.


## set_license(self, stream) {#iorawiobase}
مجوزدهی به مؤلفه.


```python
def set_license(self, stream):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| stream | **io.RawIOBase** | جریانی که شامل مجوز است. |

### توضیحات

از این روش برای بارگذاری مجوز از یک جریان استفاده کنید.



### موارد مرتبط
* کلاس [`ILicense`](/slides/python-net/fa/aspose.slides/ilicense)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)