---
title: FieldAttributes
second_title: Aspose.Slides برای مرجع API C++
description: ویژگی‌های فیلد بازتاب‌ یافته.
type: docs
weight: 170
url: /fa/system.reflection/fieldattributes/
---
## FieldAttributes شمارش

ویژگی‌های فیلد بازتاب‌ یافته.

```cpp
enum class FieldAttributes
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| FieldAccessMask | 7 | ماسک دسترسی عضو. از این ماسک برای بازیابی اطلاعات دسترسی استفاده کنید. |
| PrivateScope | 0 | اعضای غیر قابل ارجاع. |
| Private | 1 | اعضای خصوصی. |
| FamANDAssem | 2 | اعضای خصوصی و محدوده‌ای اسمبلی. |
| Assembly | 3 | اعضای محدوده‌ای اسمبلی. |
| Family | 4 | اعضای قابل دسترسی توسط نوع و زیرنوع‌ها. |
| FamORAssem | 5 | اعضای قابل دسترسی توسط نوع، زیرنوع‌ها و اسمبلی. |
| Public | 6 | اعضای قابل دسترسی برای همه. |
| Static | 16 | اعضای ایستا در مقابل اعضای نمونه. |
| InitOnly | 32 | اعضای ثابت که فقط می‌توانند مقداردهی اولیه شوند ولی تغییر نمی‌کنند. |
| Literal | 64 | اعضای ثابت زمان کامپایل. |
| NotSerialized | 128 | اعضای غیر سریال‌شده. |
| SpecialName | 512 | فیلد ویژه با یکی از نام‌های زیر. |
| PinvokeImpl | 8192 | پیاده‌سازی ارجاع شده برای اینترآپ. |
| ReservedMask | 38144 | پرچم‌های رزرو شده فقط برای استفاده در زمان اجرا. |
| RTSpecialName | 1024 | زمان اجرا باید رمزگذاری نام را بررسی کند. |
| HasFieldMarshal | 4096 | اطلاعات مارشالینگ موجود است. |
| HasDefault | 32768 | مقدار پیش‌فرض موجود است. |
| HasFieldRVA | 256 | RVA موجود است. |

## مراجعه

* فضای‌نام [System::Reflection](../)
* کتابخانه [Aspose.Slides](../../)