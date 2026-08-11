---
title: ContentRangeHeaderValue
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر مقداری از هدر 'Content-Range' است. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 40
url: /fa/system.net.http.headers/contentrangeheadervalue/
---
## ContentRangeHeaderValue کلاس

Represents a value of the 'Content-Range' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ContentRangeHeaderValue : public System::ICloneable
```

## متدها

| متد | توضیح |
| --- | --- |
|  [ContentRangeHeaderValue](./contentrangeheadervalue/)(**int64_t**, **int64_t**, **int64_t**) | یک نمونه جدید می‌سازد. |
|  [ContentRangeHeaderValue](./contentrangeheadervalue/)(**int64_t**) | یک نمونه جدید می‌سازد. |
|  [ContentRangeHeaderValue](./contentrangeheadervalue/)(**int64_t**, **int64_t**) | یک نمونه جدید می‌سازد. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | با استفاده از سمانتیک [Object.Equals](../../system/object/equals/) C# اشیاء را مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | با استفاده از سمانتیک [Object.Equals](../../system/object/equals/) C# اشیاء را مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_From](./get_from/)() | موقعیتی را که ارسال داده باید از آن شروع شود برمی‌گرداند. |
| **bool** [get_HasLength](./get_haslength/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا طول برای سرآیند جاری مشخص شده است یا نه. |
| **bool** [get_HasRange](./get_hasrange/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا بازه برای سرآیند جاری مشخص شده است یا نه. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_Length](./get_length/)() | طول بدنه‌ی موجودیت را دریافت می‌کند. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_To](./get_to/)() | موقعیتی را که ارسال داده باید متوقف شود برمی‌گرداند. |
| [String](../../system/string/) [get_Unit](./get_unit/)() | واحدهای استفاده‌شده در بازه را دریافت می‌کند. |
| static **int32_t** [GetContentRangeLength](./getcontentrangelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | رشته پاس داده‌شده را از موقعیت مشخص به یک نمونه از کلاس [ContentRangeHeaderValue](./) تبدیل می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده‌ی ارجاع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. هش‌سازی اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ContentRangeHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | رشته پاس داده‌شده را به یک نمونه از کلاس [ContentRangeHeaderValue](./) تبدیل می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را به صورت مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را به صورت مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارش مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_Unit](./set_unit/)([String](../../system/string/)) | واحدهای استفاده‌شده در بازه را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](./tostring/)() const override | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ContentRangeHeaderValue](./)\>\&) | سعی می‌کند رشته پاس داده‌شده را به یک نمونه از کلاس [ContentRangeHeaderValue](./) تبدیل کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را حذف می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [ICloneable](../../system/icloneable/)
* فضای‌نام [System::Net::Http::Headers](../)
* کتابخانه [Aspose.Slides](../../)