---
title: IConvertible
second_title: مرجع API Aspose.Slides برای C++
description: "متدهایی را تعریف می‌کند که مقدار نوع مرجع یا مقدار پیاده‌سازی‌شده را به یک نوع Common Language Runtime که مقدار معادل دارد تبدیل می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr محصور کنید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 937
url: /fa/system/iconvertible/
---
## IConvertible کلاس

متدهایی را تعریف می‌کند که مقدار نوع مرجع یا مقدار پیاده‌سازی‌شده را به یک نوع زمان اجرا (CLR) تبدیل می‌کند که مقدار معادل دارد. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../smartptr/) محصور کنید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class IConvertible : public virtual System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | آبجکت‌ها را با استفاده از [Object.Equals](../object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی استفاده می‌شود. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار داده شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../object/gethashcode/) در C# است. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../object/gettype/) در C# است. |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | کد نوع این نمونه را برمی‌گرداند. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایندهٔ نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../object/lock/)() | قفل‌گذاری بر پایه‌ی دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نظارت [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../object/memberwiseclone/) در C# است. امکان تکثیر (کلون) انواع سفارشی را فراهم می‌کند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و ساخت کپی برای زیرکلاس‌ها را فعال می‌سازد. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | اپراتور انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را بر پایهٔ ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایهٔ ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصصی برای [Object::ReferenceEquals](../object/referenceequals/) در مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصصی برای [Object::ReferenceEquals](../object/referenceequals/) در مورد رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را بر می‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به مقدار معادل [Boolean](../boolean/) تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد 8 بیتی uint32_teger معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به کاراکتر یونیکود معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به [System::DateTime](../datetime/) معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد [System::Decimal](../decimal/) معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد نقطه شناور با دقت دو برابر (double) معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد صحیح 16 بیتی با علامت معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد صحیح 32 بیتی با علامت معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد صحیح 64 بیتی با علامت معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد صحیح 8 بیتی با علامت معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد نقطه شناور تک دقت معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به [System::String](../string/) معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual [String](../string/) [ToString](./tostring/)() const | معادل متد [Object.ToString()](../object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به [System::Object](../object/) از نوع System::Type مشخص‌شده که مقدار معادل دارد تبدیل می‌کند، با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد 16 بیتی uint32_teger معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد 32 بیتی uint32_teger معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | مقدار این نمونه را به عدد 64 بیتی uint32_teger معادل تبدیل می‌کند با استفاده از اطلاعات قالب‌بندی مخصوص فرهنگ مشخص‌شده. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ساختار typeof([System.Object](../object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../object/unlock/)() | قفل‌گذاری معکوس بر پایه‌ی دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نظارت [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../object/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)