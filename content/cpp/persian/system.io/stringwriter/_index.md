---
title: StringWriter
second_title: Aspose.Slides برای مرجع API C++
description: "یک TextWriter را پیاده‌سازی می‌کند که اطلاعات را به یک رشته می‌نویسد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 417
url: /fa/system.io/stringwriter/
---
## کلاس StringWriter

یک [TextWriter](../textwriter/) را پیاده‌سازی می‌کند که اطلاعات را به یک رشته می‌نویسد. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در داخل نشانگر [System::SmartPtr](../../system/smartptr/) بپیچید و از این نشانگر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class StringWriter : public System::IO::TextWriter
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | جریان را می‌بندد و منابع به‌دست آمده را آزاد می‌کند. |
| void [Dispose](../textwriter/dispose/)() override | تمام منابع مورد استفاده توسط شیء فعلی را آزاد می‌کند و جریان زیرین را می‌بندد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از منطق [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی با این که طبق IEC 60559:1989 NaN با هیچ مقدار، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی با این که طبق IEC 60559:1989 NaN با هیچ مقدار، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual void [Flush](../textwriter/flush/)() | محتویات بافر را به جریان زیرین تخلیه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | کدگذاری فعلی مورد استفاده را بر می‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | شیء [IFormatProvider](../../system/iformatprovider/) فعلی مورد استفاده را بر می‌گرداند. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | شیء [IFormatProvider](../../system/iformatprovider/) فعلی مورد استفاده را بر می‌گرداند. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | یک رشته خاتمه خط را بر می‌گرداند. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | یک رشته خاتمه خط را بر می‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارنده‌ی مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌سازی اشیاء سفارشی را فعال می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | StringBuilder فعلی مورد استفاده را بر می‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان شبیه‌سازی (clone) انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت اشیاء فرعی با کپی را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت اشیاء فرعی با کپی را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | یک رشته خاتمه خط را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را بر می‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | یک نمونهٔ جدید از [StringWriter](./) را با استفاده از StringBuilder و [IFormatProvider](../../system/iformatprovider/) مشخص‌شده می‌سازد. |
| [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | یک نمونهٔ جدید از [StringWriter](./) را با استفاده از StringBuilder مشخص‌شده و [IFormatProvider](../../system/iformatprovider/) از فرهنگ فعلی می‌سازد. |
| [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | یک نمونهٔ جدید از [StringWriter](./) را با استفاده از [IFormatProvider](../../system/iformatprovider/) مشخص‌شده می‌سازد. |
| [StringWriter](./stringwriter/)() | یک نمونهٔ جدید از [StringWriter](./) را با استفاده از [IFormatProvider](../../system/iformatprovider/) از فرهنگ فعلی می‌سازد. |
| [String](../../system/string/) [ToString](./tostring/)() const override | رشتهٔ زیرین را بر می‌گرداند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازندهٔ typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداشتی بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(char_t) override | کاراکتر مشخص‌شده را به جریان می‌نویسد. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | بخش تعیین‌شده‌ای از کاراکترها را از آرایه کاراکتر مشخص‌شده به جریان می‌نویسد. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | رشتهٔ مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | نمایش رشته‌ای شیء مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**bool**) | نمایش رشته‌ای مقدار بولی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | نمایش رشته‌ای شیء [Decimal](../../system/decimal/) مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**double**) | نمایش رشته‌ای مقدار نقطه شناور دوچند‌دقهٔ double مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(int) | نمایش رشته‌ای مقدار عدد صحیح 32-بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | نمایش رشته‌ای مقدار عدد صحیح 64-بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**float**) | نمایش رشته‌ای مقدار نقطه شناور تک‌دقهٔ float مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت 32-بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت 64-بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | تمام کاراکترهای آرایهٔ مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(const char_t *) | رشتهٔ C‌ مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | نمایش رشته‌ای شیء [TypeInfo](../../system/typeinfo/) مشخص‌شده را به جریان می‌نویسد. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | مقدارهای مشخص‌شده را بر اساس قالب‌بندی تعیین‌شده به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)() | کاراکترهای خاتمه خط را به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | نمایش رشته‌ای شیء مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | نمایش رشته‌ای مقدار بولی مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | کاراکتر مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | نمایش رشته‌ای شیء [Decimal](../../system/decimal/) مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | نمایش رشته‌ای مقدار double دقیق می‌نویسد و به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | نمایش رشته‌ای مقدار عدد صحیح 32-بیتی مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | نمایش رشته‌ای مقدار عدد صحیح 64-بیتی مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | نمایش رشته‌ای مقدار نقطه شناور تک‌دقهٔ float مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | رشتهٔ مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت 32-بیتی مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | نمایش رشته‌ای مقدار عدد صحیح بدون علامت 64-بیتی مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | تمام کاراکترهای آرایهٔ مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | بخش تعیین‌شده‌ای از کاراکترهای UTF-16 را از آرایهٔ کاراکتر مشخص‌شده به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | رشتهٔ C‌ مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | نمایش رشته‌ای شیء [TypeInfo](../../system/typeinfo/) مشخص‌شده را به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | مقدارهای مشخص‌شده را بر اساس قالب‌بندی تعیین‌شده به‌همراه کاراکترهای خاتمه خط به جریان می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | دست‌سازنده. |

## موارد مرتبط

* کلاس [TextWriter](../textwriter/)
* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)