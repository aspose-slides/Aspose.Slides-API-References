---
title: Debug
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه‌ای از متدهای اشکال‌زدایی که امکان ارسال اطلاعات اشکال‌زدایی به شنونده‌های ثبت‌شده را فراهم می‌کند. تمام توابع خروجی فقط در Debug کار می‌کنند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.
type: docs
weight: 105
url: /fa/system.diagnostics/debug/
---
## ساختار Debug


مجموعه‌ای از متدهای اشکال‌زدایی که امکان ارسال اطلاعات اشکال‌زدایی به شنونده‌های ثبت‌شده را فراهم می‌کند. تمام توابع خروجی فقط در [Debug](./) کار می‌کنند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.

```cpp
class Debug
```

## متدها

| متد | توضیح |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | شرط را بررسی کنید و در صورت خطا اطلاعات را ارسال کنید. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | شرط را بررسی کنید و در صورت خطا اطلاعات را ارسال کنید. |
| static void [Assert](./assert/)(**bool**, const char *) | شرط را بررسی کنید و در صورت خطا اطلاعات را ارسال کنید. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | شرط را بررسی کنید و در صورت خطا اطلاعات را ارسال کنید. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | پیام خطا را ارسال کنید. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | به لیست استاتیک شنونده‌ها دسترسی می‌یابد. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | پیام را به رابط اشکال‌زدایی چاپ می‌کند. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | پیام را به رابط اشکال‌زدایی چاپ می‌کند. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | رشته را به رابط اشکال‌زدایی می‌نویسد. |
| static void [Write](./write/)(const char_t *) | رشته را به رابط اشکال‌زدایی می‌نویسد. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | اگر شرطی صحیح باشد، رشته را به رابط اشکال‌زدایی می‌نویسد. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | خط را به رابط اشکال‌زدایی می‌نویسد. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | خط را به رابط اشکال‌زدایی می‌نویسد. |
| static void [WriteLine](./writeline/)(const char_t *) | خط را به رابط اشکال‌زدایی می‌نویسد. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | خط را به رابط اشکال‌زدایی می‌نویسد. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | اگر شرطی صحیح باشد، خط را به رابط اشکال‌زدایی می‌نویسد. |
## موارد مرتبط

* فضای‌نام [System::Diagnostics](../)
* کتابخانه [Aspose.Slides](../../)