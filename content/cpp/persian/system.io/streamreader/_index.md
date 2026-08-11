---
title: StreamReader
second_title: Aspose.Slides برای مرجع API C++
description: "نمایش‌دهندهٔ خواننده‌ای که کاراکترها را از یک جریان بایتی می‌خواند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() ساخته شوند. هرگز نمونهٔ این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچانید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 378
url: /fa/system.io/streamreader/
---
## StreamReader کلاس

یک خواننده که کاراکترها را از یک جریان بایتی می‌خواند. شیءهای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) ساخته شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همواره این کلاس را در یک نشانگر [System::SmartPtr](../../system/smartptr/) بپیچانید و از این نشانگر برای ارسال آن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class StreamReader : public System::IO::TextReader
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Close](./close/)() override | جریان جاری و زیرین را می‌بندد. |
| virtual void [Dispose](./dispose/)(**bool**) | تمام منابع استفاده شده توسط شیء جاری را آزاد می‌کند و جریان زیرین را می‌بندد. |
| void [Dispose](./dispose/)() override | تمام منابع استفاده شده توسط شیء جاری را آزاد می‌کند و جریان زیرین را می‌بندد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | یک اشاره‌گر اشتراکی به شیئی که نمایانگر جریان زیرین است را برمی‌گرداند. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | کدگذاری فعلی مورد استفاده را برمی‌گرداند. |
| **bool** [get_EndOfStream](./get_endofstream/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا انتهای جریان رسیده است یا خیر. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌ کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| int [Peek](./peek/)() override | یک کاراکتر واحد را از جریان می‌خواند بدون تغییر مکان‌نمای خواندن جریان. |
| int [Read](./read/)() override | یک کاراکتر واحد را از جریان می‌خواند. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | تعداد مشخصی کاراکتر را از جریان می‌خواند، آنها را به کدگذاری UTF-16 تبدیل می‌کند و کاراکترهای حاصل UTF-16 را در آرایهٔ کاراکتر مشخص‌شده از موقعیت تعیین‌شده می‌نویسد. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | حداکثر تعداد مشخص‌شده کاراکترها را از خوانندهٔ متن فعلی می‌خواند و داده‌ها را در بافر می‌نویسد، شروع از اندیس مشخص‌شده. |
| [String](../../system/string/) [ReadLine](./readline/)() override | کاراکترها را از جریان تا انتهای خط جاری می‌خواند. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | کاراکترها را از جریان تا انتهای جریان می‌خواند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام تمپلیت را به یک اشاره‌گر ضعیف (به جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | نمونه‌ای از شیء [StreamReader](./) را می‌سازد که کاراکترها را از جریان زیربنایی تعیین‌شده با استفاده از کدگذاری UTF-8 و بافر با اندازهٔ پیش‌فرض ۱۰۲۴ بایت می‌خواند. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | نمونه‌ای از شیء [StreamReader](./) را می‌سازد که کاراکترها را از جریان زیربنایی تعیین‌شده با استفاده از کدگذاری UTF-8 و بافر با اندازهٔ پیش‌فرض ۱۰۲۴ بایت می‌خواند. یک پارامتر مشخص می‌کند آیا تشخیص علامت ترتیب بایت فعال باشد یا نه. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | نمونه‌ای از شیء [StreamReader](./) را می‌سازد که کاراکترها را از جریان زیربنایی تعیین‌شده با استفاده از کدگذاری مشخص و بافر با اندازهٔ پیش‌فرض ۱۰۲۴ بایت می‌خواند. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | نمونه‌ای از شیء [StreamReader](./) را می‌سازد که کاراکترها را از جریان زیربنایی تعیین‌شده با استفاده از کدگذاری مشخص و بافر با اندازهٔ پیش‌فرض ۱۰۲۴ بایت می‌خواند. یک پارامتر مشخص می‌کند آیا تشخیص علامت ترتیب بایت فعال باشد یا نه. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | نمونه‌ای از شیء [StreamReader](./) را می‌سازد که کاراکترها را از جریان زیربنایی تعیین‌شده با استفاده از کدگذاری مشخص و بافر با اندازهٔ مشخص می‌خواند. یک پارامتر مشخص می‌کند آیا تشخیص علامت ترتیب بایت فعال باشد یا نه. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | نمونه‌ای از شیء [StreamReader](./) را می‌سازد که کاراکترها را از فایل مشخص‌شده با استفاده از کدگذاری UTF-8 و بافر با اندازهٔ پیش‌فرض ۴۰۹۶ بایت می‌خواند. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | نمونه‌ای از شیء [StreamReader](./) را می‌سازد که کاراکترها را از فایل مشخص‌شده با استفاده از کدگذاری UTF-8 و بافر با اندازهٔ پیش‌فرض ۴۰۹۶ بایت می‌خواند. یک پارامتر مشخص می‌کند آیا تشخیص علامت ترتیب بایت فعال باشد یا نه. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | نمونه‌ای از شیء [StreamReader](./) را می‌سازد که کاراکترها را از فایل مشخص‌شده با استفاده از کدگذاری مشخص و بافر با اندازهٔ پیش‌فرض ۴۰۹۶ بایت می‌خواند. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | نمونه‌ای از شیء [StreamReader](./) را می‌سازد که کاراکترها را از جریان زیربنایی مشخص‌شده با استفاده از کدگذاری مشخص و بافر با اندازهٔ پیش‌فرض ۴۰۹۶ بایت می‌خواند. یک پارامتر مشخص می‌کند آیا تشخیص علامت ترتیب بایت فعال باشد یا نه. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | نمونه‌ای از شیء [StreamReader](./) را می‌سازد که کاراکترها را از فایل مشخص‌شده با استفاده از کدگذاری مشخص و بافر با اندازهٔ مشخص می‌خواند. یک پارامتر مشخص می‌کند آیا تشخیص علامت ترتیب بایت فعال باشد یا نه. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
|  [~StreamReader](./~streamreader/)() | دست‌ساز. |
## موارد مرتبط

* کلاس [TextReader](../textreader/)
* فضای نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)