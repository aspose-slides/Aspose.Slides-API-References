---
title: Console
second_title: Aspose.Slides برای C++ مرجع API
description: متدهایی را برای خروجی کردن داده‌ها به جریان خروجی استاندارد فراهم می‌کند. این یک نوع ایستایی است که سرویس‌های نمونه‌ای ندارد. شما هرگز نباید به هیچ صورت نمونه‌ای از آن ایجاد کنید.
type: docs
weight: 196
url: /fa/system/console/
---
## Console کلاس

Provides methods for outputting data to the standard output stream. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Console
```

## متدها

| متد | توضیح |
| --- | --- |
| static void [Beep](./beep/)() | پیاده‌سازی نشده. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | باز می‌گرداند shared pointerی که به شیئی اشاره می‌کند که جریان خطای استاندارد را نشان می‌دهد. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | باز می‌گرداند shared pointerی که به شیئی اشاره می‌کند که جریان ورودی استاندارد را نشان می‌دهد. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | باز می‌گرداند shared pointerی که به شیئی اشاره می‌کند که جریان خروجی استاندارد را نشان می‌دهد. |
| static void [Mute](./mute/)(**bool**) | صدای جریان خروجی استاندارد را خاموش یا روشن می‌کند. |
| static void [ReadKey](./readkey/)() | پیاده‌سازی نشده. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | عنوان پنجرهٔ کنسول را تنظیم می‌کند. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | شیء مشخص‌شده را به ویژگی Error کلاس اختصاص می‌دهد. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | ویژگی In را به شیء TextReader مشخص‌شده تنظیم می‌کند. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | شیء مشخص‌شده را به ویژگی Out کلاس اختصاص می‌دهد. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | نمایش رشته‌ای شیء مشخص‌شده را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(**bool**) | نمایش رشته‌ای مقدار بولی را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(char_t) | مقدار کاراکتر مشخص‌شده را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | نمایش رشته‌ای آرایهٔ کاراکترهای مشخص‌شده را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | نمایش رشته‌ای مقدار [Decimal](../decimal/) را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(**double**) | نمایش رشته‌ای مقدار عدد ممیز شناور دوچندریزه را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(**float**) | نمایش رشته‌ای مقدار عدد ممیز شناور تک‌دقت را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(**int32_t**) | نمایش رشته‌ای مقدار عدد صحیح ۳۲ بیتی را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(**int64_t**) | نمایش رشته‌ای مقدار عدد صحیح ۶۴ بیتی را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(const [String](../string/)\&) | شیء رشتهٔ مشخص‌شده را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(const char_t *) | رشتهٔ C مشخص‌شده را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | نمایش رشته‌ای مقدار [TypeInfo](../typeinfo/) را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(**uint32_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۳۲ بیتی را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(**uint64_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۶۴ بیتی را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | نمایش رشته‌ای بازهٔ مشخص‌شده از آرایهٔ کاراکترهای مشخص‌شده را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | نمایش رشته‌ای آرگومان‌های مشخص‌شده که با قالب مشخص‌ شده فرمت شده‌اند را به جریان خروجی استاندارد می‌فرستد. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | پایان‌خط فعلی را به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | نمایش رشته‌ای شیء مشخص‌شده را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(**bool**) | نمایش رشته‌ای مقدار بولی را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(char_t) | مقدار کاراکتر مشخص‌شده را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | نمایش رشته‌ای آرایهٔ کاراکترهای مشخص‌شده را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | نمایش رشته‌ای مقدار [Decimal](../decimal/) را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(**double**) | نمایش رشته‌ای مقدار عدد ممیز شناور دوچندریزه را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(**float**) | نمایش رشته‌ای مقدار عدد ممیز شناور تک‌دقت را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(**int32_t**) | نمایش رشته‌ای مقدار عدد صحیح ۳۲ بیتی را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(**int64_t**) | نمایش رشته‌ای مقدار عدد صحیح ۶۴ بیتی را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | شیء رشتهٔ مشخص‌شده را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(const char_t *) | رشتهٔ C مشخص‌شده را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | نمایش رشته‌ای مقدار [TypeInfo](../typeinfo/) را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(**uint32_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۳۲ بیتی را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(**uint64_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۶۴ بیتی را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | نمایش رشته‌ای بازهٔ مشخص‌شده از آرایهٔ کاراکترهای مشخص‌شده را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | نمایش رشته‌ای شیء Exception مشخص‌شده را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | نمایش رشته‌ای آرگومان‌های مشخص‌شده که با قالب مشخص‌ شده فرمت شده‌اند را به‌همراه پایان‌خط فعلی به جریان خروجی استاندارد می‌فرستد. |
| static void [WriteLine](./writeline/)(const char *) |  |

## ملاحظات

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // پیام خوش‌آمد را چاپ می‌کند.
  Console::WriteLine(u"Hello, world!");

  // یک نمونه از کلاس 'std::array' ایجاد می‌کند.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // عناصر آرایه را چاپ می‌کند.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
Hello, world!
1 2 3 4 5
*/
```

## همچنین ببینید

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)