---
title: ColorTranslator
second_title: مرجع برنامه‌نویسی Aspose.Slides برای C++
description: "عملیات ترجمه رنگ را انجام می‌دهد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خرابی‌های assertion می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 66
url: /fa/system.drawing/colortranslator/
---
## ColorTranslator کلاس

Performs color translations. Objects of this کلاس should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this کلاس into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ColorTranslator
```

## متدها

| متد | توضیح |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | نمایش رنگ HTML مشخص‌شده را به شیء [Color](../color/) معادل تبدیل می‌کند. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | رنگ [Windows](../../system.windows/) مشخص‌شده را به شیء [Color](../color/) معادل تبدیل می‌کند. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | شیء [Color](../color/) مشخص‌شده را به نمایش رشته‌ای رنگ HTML معادل تبدیل می‌کند. |

## مراجع

* فضای‌نام [System::Drawing](../)
* کتابخانه [Aspose.Slides](../../)