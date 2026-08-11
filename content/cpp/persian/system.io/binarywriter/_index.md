---
title: BinaryWriter
second_title: مرجع API Aspose.Slides برای C++
description: "یک نویسنده را نشان می‌دهد که مقادیر انواع اولیه را به یک جریان بایتی می‌نویسد. اشیاء این کلاس باید تنها با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را در پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و یا شکست‌های اطمینان می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 105
url: /fa/system.io/binarywriter/
---
## BinaryWriter کلاس

نمایانگر یک نویسنده است که مقدارهای انواع اولیه را به یک جریان بایتی می‌نویسد. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را در استک یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکال تایید می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class BinaryWriter : public System::IDisposable
```

## متدها

| Method | توضیح |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | یک نمونه از کلاس [BinaryWriter](./) را می‌سازد که داده‌ها را به جریان مشخص‌شده با استفاده از رمزگذاری تعیین‌شده می‌نویسد. |
| void [Close](./close/)() | شیء [BinaryWriter](./) جاری و جریان خروجی زیرین را می‌بندد. |
| void [Dispose](./dispose/)() override | تمام منابع استفاده‌شده توسط شیء جاری را آزاد می‌کند و جریان زیرین را می‌بندد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنی‌گذاری [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [Flush](./flush/)() | جریان خروجی را تخلیه می‌کند. |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | جریان خروجی را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌گذاری اشیاء دلخواه را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C# است. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان تکثیر انواع دلخواه را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخه کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخه کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع اشتراکی را بر اساس مقدار مشخص‌شده کاهش می‌دهد. |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | موقعیت جریان نمایان شده توسط شیء جاری را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در سازنده‌ها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش می‌دهد و بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء دلخواه به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [Write](./write/)(**uint8_t**) | مقدار عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص‌شده به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | بخش مشخص‌شده‌ای از کاراکترهای UTF-16 را از آرایه کاراکتر مشخص‌شده به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(**bool**) | یک بایت تک با مقدار ۰ اگر **value** 'true' باشد و ۱ اگر **value** 'false' باشد، به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(char16_t) | مقدار کاراکتر ۱۶ بیتی مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(**int16_t**) | مقدار عدد صحیح ۱۶ بیتی مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(int) | مقدار عدد صحیح ۳۲ بیتی مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(**int64_t**) | مقدار عدد صحیح ۶۴ بیتی مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(**uint16_t**) | مقدار عدد صحیح بدون علامت ۱۶ بیتی مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(**uint32_t**) | مقدار عدد صحیح بدون علامت ۳۲ بیتی مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(**uint64_t**) | مقدار عدد صحیح بدون علامت ۶۴ بیتی مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(**float**) | مقدار نقطه شناور تک‌دقت مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(**double**) | مقدار نقطه شناور دوبل‌دقت مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | نمای بایتی مقدار [Decimal](../../system/decimal/) مشخص‌شده را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | یک رشته با پیشوند طول در رمزگذاری فعلی را به جریان خروجی می‌نویسد. |
| virtual void [Write](./write/)(const char_t *) | یک رشته با پیشوند طول در رمزگذاری فعلی را به جریان خروجی می‌نویسد. |
|  [~BinaryWriter](./~binarywriter/)() | دستگاه تخریب. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## همچنین ببینید

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)