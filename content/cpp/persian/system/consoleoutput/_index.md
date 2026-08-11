---
title: ConsoleOutput
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر جریان خروجی استاندارد است. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() ایجاد شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اطمینان‌سنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 209
url: /fa/system/consoleoutput/
---
## ConsoleOutput کلاس

نمایانگر جریان خروجی استاندارد است. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../makeobject/) ایجاد شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خرابی‌های اطمینان‌سنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## متدها

| Method | Description |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | جریان را بسته و منابع به‌دست‌آمده را آزاد می‌کند. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | تمام منابع استفاده‌شده توسط شیء فعلی را آزاد می‌کند و جریان زیرین را می‌بندد. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | اشیاء را با استفاده از معناشناسی C# [Object.Equals](../object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | محتویات بافر را به جریان زیرین تخلیه می‌کند. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | همیشه رمزگذاری ASCII را برمی‌گرداند. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | شیء [IFormatProvider](../iformatprovider/) فعلی استفاده‌شده را برمی‌گرداند. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | شیء [IFormatProvider](../iformatprovider/) فعلی استفاده‌شده را برمی‌گرداند. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | یک رشتهٔ پایان خط را برمی‌گرداند. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | یک رشتهٔ پایان خط را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../object/memberwiseclone/). امکان شبیه‌سازی (کلون) انواع سفارشی را فراهم می‌کند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصص [Object::ReferenceEquals](../object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | یک رشتهٔ پایان خط تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | معادل متد C# [Object.ToString()](../object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ساختار typeof([System.Object](../object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../object/unlock/)() | بازکردن قفل بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(**bool**) override | نمایش رشته‌ای مقدار bool مشخص‌شده به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | نمایش رشته‌ای شیء مشخص‌شده به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(char_t) override | نمایش مقدار کاراکتر مشخص‌شده به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)([Decimal](../decimal/)) override | نمایش رشته‌ای مقدار [Decimal](../decimal/) به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(**double**) override | نمایش رشته‌ای مقدار double به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(**int32_t**) override | نمایش رشته‌ای مقدار عدد صحیح ۳۲ بیتی به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(**int64_t**) override | نمایش رشته‌ای مقدار عدد صحیح ۶۴ بیتی به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(**float**) override | نمایش رشته‌ای مقدار float به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(const [String](../string/)\&) override | نمایش شیء رشتهٔ مشخص‌شده به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(**uint32_t**) override | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۳۲ بیتی به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(**uint64_t**) override | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۶۴ بیتی به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | نمایش رشته‌ای آرایهٔ کاراکترهای مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | نمایش رشته‌ای بازه‌ای از مقادیر آرایهٔ کاراکترهای مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(const char_t *) override | نمایش رشتهٔ C-string مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | نمایش رشته‌ای شیء [TypeInfo](../typeinfo/) مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | رشتهٔ نمایشی مقدار عدد صحیح ۳۲ بیتی مشخص‌شده را در جریان می‌نویسد. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | مقادیر مشخص‌شده را مطابق با قالب مشخص‌شده به جریان می‌نویسد. |
| void [WriteLine](./writeline/)() override | نمایش پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | نمایش رشته‌ای شیء مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(**bool**) override | نمایش رشته‌ای مقدار bool مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(char_t) override | نمایش مقدار کاراکتر مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | نمایش رشته‌ای مقدار [Decimal](../decimal/) به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(**double**) override | نمایش رشته‌ای مقدار double به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(int) override | نمایش رشته‌ای مقدار عدد صحیح ۳۲ بیتی به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(**int64_t**) override | نمایش رشته‌ای مقدار عدد صحیح ۶۴ بیتی به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(**float**) override | نمایش رشته‌ای مقدار float به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | نمایش شیء رشتهٔ مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(**uint32_t**) override | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۳۲ بیتی به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(**uint64_t**) override | نمایش رشته‌ای مقدار عدد صحیح بدون علامت ۶۴ بیتی به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | نمایش رشته‌ای آرایهٔ کاراکترهای مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | نمایش رشته‌ای بازه‌ای از مقادیر آرایهٔ کاراکترهای مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(const char_t *) override | نمایش رشتهٔ C-string مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | نمایش رشته‌ای شیء [TypeInfo](../typeinfo/) مشخص‌شده به‌همراه پایان خط جاری به جریان خروجی که توسط شیء جاری نمایان شده است. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | مقادیر مشخص‌شده را مطابق با قالب مشخص‌شده نوشتاری می‌کند و سپس کاراکترهای پایان خط را به جریان اضافه می‌کند. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | تخریب‌کننده. |

## موارد مرتبط

* کلاس [TextWriter](../../system.io/textwriter/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)