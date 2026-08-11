---
title: BindingFlags
second_title: Aspose.Slides برای C++ مرجع API
description: اعضا و حالت‌های جستجوی نوع و بایندینگ‌ها را تعریف می‌کند.
type: docs
weight: 157
url: /fa/system.reflection/bindingflags/
---
## BindingFlags enum

اعضا و حالت‌های جستجوی نوع و بایندینگ‌ها را تعریف می‌کند.

```cpp
enum class BindingFlags
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Default | 0 | بدون گزینهٔ خاص. |
| IgnoreCase | 1 | در هنگام جستجوی مورد، حروف بزرگ و کوچک نام را نادیده می‌گیرد. |
| DeclaredOnly | 2 | فقط اعضایی را که در نوع تعریف شده‌اند جستجو می‌کند و نه در نوع پایه. |
| Instance | 4 | از میان اعضای نمونه مرور می‌کند. |
| Static | 8 | از میان اعضای ایستا مرور می‌کند. |
| Public | 16 | از میان اعضای عمومی مرور می‌کند. |
| NonPublic | 32 | از میان اعضای غیرعمومی مرور می‌کند. |
| FlattenHierarchy | 64 | از میان اعضای ایستای عمومی و حفاظت‌شدهٔ نوع پایه مرور می‌کند. |
| InvokeMethod | 256 | متد را فراخوانی می‌کند. |
| CreateInstance | 512 | یک نمونه از نوع بازتاب‌شده ایجاد می‌کند. |
| GetField | 1024 | مقدار فیلد را دریافت می‌کند. |
| SetField | 2048 | مقدار فیلد را تنظیم می‌کند. |
| GetProperty | 4096 | مقدار ویژگی را دریافت می‌کند. |
| SetProperty | 8192 | مقدار ویژگی را تنظیم می‌کند. |
| PutDispProperty | 16384 | ویژگی COM را تنظیم می‌کند. |
| PutRefDispProperty | 32768 | ویژگی مرجع COM را تنظیم می‌کند. |
| ExactBinding | 65536 | بایندینگ نوع باید دقیق باشد، بدون هیچ تغییری در نوع. |
| SuppressChangeType | 131072 | پشتیبانی نمی‌شود. |
| OptionalParamBinding | 262144 | براساس تعداد آرگومان‌ها، overload را انتخاب می‌کند. |
| IgnoreReturn | 16777216 | مقدار بازگشتی interop COM را نادیده می‌گیرد. |

## موارد مرتبط

* فضای نام [System::Reflection](../)
* کتابخانه [Aspose.Slides](../../)