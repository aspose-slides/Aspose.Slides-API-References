---
title: TextWriter
second_title: Aspose.Slides برای C++ مرجع API
description: "کلاس پایه‌ای برای کلاس‌هایی که نويسندگانی را نمایند که توالی‌های کاراکتر را به مقاصد مختلف می‌نویسند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assert می‌شود. همواره این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 443
url: /fa/system.io/textwriter/
---
## کلاس TextWriter


یک کلاس پایه برای کلاس‌هایی که نويسندگانی را نشان می‌دهند که توالی‌های کاراکتر را به مقاصد مختلف می‌نویسند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class TextWriter : public System::IDisposable
```

## متدها

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | جریان را می‌بندد و منابع به‌دست آمده را آزاد می‌کند. |
| void [Dispose](./dispose/)() override | تمام منابع مورد استفاده توسط شیء جاری را آزاد می‌کند و جریان زیرین را می‌بندد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، حتی خود NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، حتی خود NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی استفاده می‌شود. |
| virtual void [Flush](./flush/)() | محتویات بافر را به جریان زیرین تخلیه می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | رمزگذاری فعلی مورد استفاده را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | شیء [IFormatProvider](../../system/iformatprovider/) فعلی مورد استفاده را برمی‌گرداند. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | شیء [IFormatProvider](../../system/iformatprovider/) فعلی مورد استفاده را برمی‌گرداند. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | یک رشته پایان خط را برمی‌گرداند. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | یک رشته پایان خط را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گیرد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل اپراتور 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌طور مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مرجع-مقایسه شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | یک رشته پایان خط را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در سازنده‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از هوشمند‌پوینترها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از هوشمند‌پوینترها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری معکوس عبارت lock() در C# را پیاده‌سازی می‌کند. به‌طور مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از هوشمند‌پوینترها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از هوشمند‌پوینترها یا ThisProtector استفاده کنید. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | نمایش رشته‌ای شیء مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(**bool**) | نمایش رشته‌ای مقدار بولی مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(char_t) | کاراکتر مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | نمایش رشته‌ای شیء [Decimal](../../system/decimal/) مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(**double**) | نمایش رشته‌ای مقدار عدد اعشاری دوگانه مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(int) | نمایش رشته‌ای مقدار عدد صحیح ۳۲ بیتی مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(**int64_t**) | نمایش رشته‌ای مقدار عدد صحیح ۶۴ بیتی مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(**float**) | نمایش رشته‌ای مقدار عدد اعشاری تک‌دقت مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | رشته مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(**uint32_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(**uint64_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | تمام کاراکترهای آرایه مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از کاراکترهای UTF-16 از آرایه کاراکتر مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(const char_t *) | رشته C مشخص‌شده را در جریان می‌نویسد. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | نمایش رشته‌ای شیء [TypeInfo](../../system/typeinfo/) مشخص‌شده را در جریان می‌نویسد. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | مقدارهای مشخص‌شده را بر اساس قالب مشخص‌شده فرمت‌بندی کرده و در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)() | کاراکترهای پایان خط را در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | نمایش رشته‌ای شیء مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(**bool**) | نمایش رشته‌ای مقدار بولی مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(char_t) | کاراکتر مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | نمایش رشته‌ای شیء [Decimal](../../system/decimal/) مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(**double**) | نمایش رشته‌ای مقدار عدد اعشاری دوبل مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(int) | نمایش رشته‌ای مقدار عدد صحیح ۳۲ بیتی مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | نمایش رشته‌ای مقدار عدد صحیح ۶۴ بیتی مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(**float**) | نمایش رشته‌ای مقدار عدد اعشاری تک‌دقت مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | رشته مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | تمام کاراکترهای آرایه مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از کاراکترهای UTF-16 از آرایه کاراکتر مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(const char_t *) | رشته C مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | نمایش رشته‌ای شیء [TypeInfo](../../system/typeinfo/) مشخص‌شده را به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | مقدارهای مشخص‌شده را بر اساس قالب مشخص‌شده فرمت‌بندی کرده و به‌همراه کاراکترهای پایان خط در جریان می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
| virtual  [~TextWriter](./~textwriter/)() | تخریب‌کننده. |

## تعاریف نوع

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای یک shared pointer به این کلاس. |

## مراجع

* کلاس [IDisposable](../../system/idisposable/)
* فضای نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)