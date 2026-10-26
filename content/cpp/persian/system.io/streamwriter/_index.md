---
title: StreamWriter
second_title: Aspose.Slides برای C++ مرجع API
description: "نویسنده‌ای که کاراکترها را به یک جریان بایت می‌نویسد را نمایندگی می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 391
url: /fa/system.io/streamwriter/
---
## کلاس StreamWriter

نویسنده‌ای را که کاراکترها را به یک جریان بایت می‌نویسد، نمایندگی می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعا خواهد شد. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## متدها

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | جریان را می‌بندد و منابع به‌دست‌آمده را آزاد می‌کند. |
| void [Dispose](./dispose/)() override | تمام منابع استفاده‌شده توسط شیء جاری را آزاد می‌کند و جریان زیرین را می‌بندد. |
| virtual void [Dispose](./dispose/)(**bool**) | تمام منابع استفاده‌شده توسط شیء جاری را آزاد می‌کند و جریان زیرین را می‌بندد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌عهی به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌عهی به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی استفاده می‌شود. |
| void [Flush](./flush/)() override | محتویات بافر را به جریان زیرین روان می‌کند و سپس جریان زیرین را روان می‌کند. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | مقداری برمی‌گرداند که نشان می‌دهد آیا [StreamWriter](./) داده‌ها را به جریان زیرین هر بار که متد [StreamWriter::Write](./write/) فراخوانی می‌شود، روان می‌کند یا نه. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | یک اشاره‌گر مشترک به شیئی که جریان زیرین را نشان می‌دهد، برمی‌گرداند. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | رمزگذاری جاری استفاده‌شده را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | شیء [IFormatProvider](../../system/iformatprovider/) جاری استفاده‌شده را برمی‌گرداند. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | شیء [IFormatProvider](../../system/iformatprovider/) جاری استفاده‌شده را برمی‌گرداند. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | یک رشتهٔ پایانهٔ خط را برمی‌گرداند. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | یک رشتهٔ پایانهٔ خط را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توضیح داده شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت lock() در C# را پیاده‌سازی می‌کند. به‌طور مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور تخصیص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | مقداری برمی‌گرداند که تعیین می‌کند آیا [StreamWriter](./) باید داده‌ها را به جریان زیرین هر بار که متد [StreamWriter::Write](./write/) فراخوانی می‌شود، روان کند یا نه. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | یک رشتهٔ پایانهٔ خط را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | نمونه‌ای از شیء [StreamWriter](./) را می‌سازد که کاراکترها را با رمزگذاری UTF-8 و بافر پیش‌فرض ۱۰۲۴ بایت به جریان زیرین مشخص‌شده می‌نویسد. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | نمونه‌ای از شیء [StreamWriter](./) را می‌سازد که کاراکترها را با رمزگذاری مشخص‌شده و بافر پیش‌فرض ۱۰۲۴ بایت به جریان زیرین می‌نویسد. |
| [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | نمونه‌ای از شیء [StreamWriter](./) را می‌سازد که کاراکترها را با رمزگذاری مشخص‌شده و بافر با اندازه‌ی مشخص به جریان زیرین می‌نویسد. یک پارامتر تعیین می‌کند آیا هنگام از بین رفتن شیء [StreamWriter](./)، جریان زیرین بسته شود یا نه. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | نمونه‌ای از شیء [StreamWriter](./) را می‌سازد که کاراکترها را با رمزگذاری UTF-8 و بافر پیش‌فرض ۱۰۲۴ بایت به فایل مشخص‌شده می‌نویسد. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | نمونه‌ای از شیء [StreamWriter](./) را می‌سازد که کاراکترها را با رمزگذاری مشخص‌شده و بافر پیش‌فرض ۱۰۲۴ بایت به فایل می‌نویسد. یک پارامتر تعیین می‌کند آیا داده باید به فایل افزوده شود یا فایل بازنویسی شود. |
| [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | نمونه‌ای از شیء [StreamWriter](./) را می‌سازد که کاراکترها را با رمزگذاری مشخص‌شده و با اندازهٔ بافر به فایل می‌نویسد. یک پارامتر تعیین می‌کند آیا داده باید به فایل افزوده شود یا فایل بازنویسی شود. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(char_t) override | کاراکتر مشخص‌شده را به جریان می‌نویسد. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | رشتهٔ مشخص‌شده را به جریان می‌نویسد. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | نمایش رشته‌ای از شیء مشخص‌شده را به جریان می‌نویسد. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | تمام کاراکترهای آرایهٔ مشخص‌شده را به جریان می‌نویسد. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | بخش مشخص‌شده‌ای از کاراکترهای UTF-16 را از آرایهٔ کاراکتر مشخص‌شده به جریان می‌نویسد. |
| void [Write](./write/)(const char_t *) override | رشتهٔ C مشخص‌شده را به جریان می‌نویسد. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | نمایش رشته‌ای از شیء مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**bool**) | نمایش رشته‌ای از مقدار بولی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | نمایش رشته‌ای از شیء [Decimal](../../system/decimal/) مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**double**) | نمایش رشته‌ای از مقدار نقطه‌عهی با دابل پرسیژن مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(int) | نمایش رشته‌ای از مقدار عدد صحیح ۳۲ بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | نمایش رشته‌ای از مقدار عدد صحیح ۶۴ بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**float**) | نمایش رشته‌ای از مقدار نقطه‌عهی تک‌دقتی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | نمایش رشته‌ای از مقدار عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | نمایش رشته‌ای از مقدار عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | نمایش رشته‌ای از شیء [TypeInfo](../../system/typeinfo/) مشخص‌شده را به جریان می‌نویسد. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | مقادیر مشخص‌شده را بر اساس قالب مشخص‌شده به جریان می‌نویسد. |
| void [WriteLine](./writeline/)() override | کاراکترهای پایانهٔ خط را به جریان می‌نویسد. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | رشتهٔ مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | نمایش رشته‌ای از شیء مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | تمام کاراکترهای آرایهٔ مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | بخش مشخص‌شده‌ای از کاراکترهای UTF-16 را از آرایهٔ کاراکتر مشخص‌شده به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| void [WriteLine](./writeline/)(const char_t *) override | رشتهٔ C مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | نمایش رشته‌ای از شیء مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | نمایش رشته‌ای از مقدار بولی مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | کاراکتر مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | نمایش رشته‌ای از شیء [Decimal](../../system/decimal/) مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | نمایش رشته‌ای از مقدار نقطه‌عهی دابل پرسیژن مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | نمایش رشته‌ای از مقدار عدد صحیح ۳۲ بیتی مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | نمایش رشته‌ای از مقدار عدد صحیح ۶۴ بیتی مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | نمایش رشته‌ای از مقدار نقطه‌عهی تک‌دقتی مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | نمایش رشته‌ای از مقدار عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | نمایش رشته‌ای از مقدار عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | نمایش رشته‌ای از شیء [TypeInfo](../../system/typeinfo/) مشخص‌شده را به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | مقادیر مشخص‌شده را بر اساس قالب مشخص‌شده به همراه کاراکترهای پایانهٔ خط به جریان می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |
| [~StreamWriter](./~streamwriter/)() | سازنده مخرب. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | سازنده مخرب. |

## موارد مرتبط

* کلاس [TextWriter](../textwriter/)
* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)