---
title: register_ink_effect_image method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
یک تصویر را به مجموعه‌ای از تصاویر سفارشی که برای شبیه‌سازی افکت‌های بصری قلم جوهر استفاده می‌شود، ثبت می‌کند.
            این تصاویر هنگام رندرینگ جوهر با مقادیر خاص [`InkEffectType`](/slides/python-net/fa/aspose.slides.ink/inkeffecttype)، مانند Galaxy، Rainbow و غیره استفاده می‌شوند.
            با فراهم کردن تصاویر خودتان، می‌توانید کنترل کنید که هر افکت جوهر چگونه نمایش داده شود.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/fa/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/fa/aspose.slides/iimage) |  |

### یادداشت‌ها

این متد امکان جایگزینی بافت‌های پیش‌فرض افکت جوهر را با بافت‌های تعریف‌شده توسط کاربر فراهم می‌کند، که خصوصاً زمانی مفید است که دارایی‌های پیش‌فرض به‌دلیل محدودیت‌های مجوزی یا عدم دسترسی در زمان اجرا محدود باشند.
            هر جفت مقدار ثبت‌شده باید یک مقدار [`InkEffectType`](/slides/python-net/fa/aspose.slides.ink/inkeffecttype) را با یک شیء [`IImage`](/slides/python-net/fa/aspose.slides/iimage) متناظر (به عنوان مثال، Bitmap یا یک رابط تصویر Aspose) مرتبط کند.



### موارد مرتبط
* class [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* class [`Ink`](/slides/python-net/fa/aspose.slides.ink/ink)
* enumeration [`InkEffectType`](/slides/python-net/fa/aspose.slides.ink/inkeffecttype)
* module [`aspose.slides.ink`](/slides/python-net/fa/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)