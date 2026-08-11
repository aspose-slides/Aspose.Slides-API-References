---
title: CacheControlHeaderValue
second_title: "مرجع API Aspose.Slides برای C++"
description: "نمایانگر مقدار هدر 'Cache-Control' است. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 14
url: /fa/system.net.http.headers/cachecontrolheadervalue/
---
## کلاس CacheControlHeaderValue

نمایانگر مقداری از هدر 'Cache-Control' است. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## متدها

| Method | Description |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | یک نمونه جدید را می‌سازد. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | اشیاء را با استفاده از معنابندی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنابندی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | مجموعه توکن‌های cache-extension را برمی‌گرداند. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | مقدار حداکثر عمر را بر حسب ثانیه دریافت می‌کند که زمان پذیرش پاسخ توسط کلاینت را تعیین می‌کند. |
| **bool** [get_MaxStale](./get_maxstale/)() | مقداری را دریافت می‌کند که تعیین می‌کند آیا کلاینت پاسخ‌های منقضی‌شده را می‌پذیرد یا نه. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | مقدار را بر حسب ثانیه دریافت می‌کند که زمان پذیرش پاسخ‌های منقضی‌شده توسط کلاینت را تعیین می‌کند. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | مقداری را دریافت می‌کند که طول عمر تازگی را تعیین می‌کند. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | مقداری را دریافت می‌کند که تعیین می‌کند آیا سرور نیاز به اعتبارسنجی مجدد ورودی کش دارد زمانی که منسوخ می‌شود. |
| **bool** [get_NoCache](./get_nocache/)() | مقداری را دریافت می‌کند که تعیین می‌کند آیا کلاینت پاسخ کش‌شده را می‌پذیرد. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | مجموعه نام‌های فیلد در دستورالعمل 'no-cache' در هدر 'Cache-Control' را دریافت می‌کند. |
| **bool** [get_NoStore](./get_nostore/)() | مقداری را دریافت می‌کند که تعیین می‌کند آیا کش نباید هیچ بخشی از درخواست یا پاسخ HTTP را ذخیره کند. |
| **bool** [get_NoTransform](./get_notransform/)() | مقداری را دریافت می‌کند که تعیین می‌کند آیا کش یا پراکسی نباید هیچ بخشی از بدنهٔ موجودیت را تغییر دهد. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | مقداری را دریافت می‌کند که تعیین می‌کند آیا کلاینت باید فقط از ورودی‌های کش‌شده استفاده کند. |
| **bool** [get_Private](./get_private/)() | مقداری را دریافت می‌کند که تعیین می‌کند آیا پیام پاسخ HTTP یا بخشی از آن برای یک کاربر واحد است و نباید توسط کش اشتراکی کش شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | مجموعه نام‌های فیلد در دستورالعمل 'private' در هدر 'Cache-Control' را دریافت می‌کند. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | مقداری را دریافت می‌کند که تعیین می‌کند آیا سرور نیاز به اعتبارسنجی مجدد ورودی کش دارد زمانی که برای کش‌های مشترک کاربران منسوخ می‌شود. |
| **bool** [get_Public](./get_public/)() | مقداری را دریافت می‌کند که تعیین می‌کند آیا یک پاسخ HTTP می‌تواند توسط هر کشی کش شود. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | مقدار حداکثر عمر مشترک را بر حسب ثانیه دریافت می‌کند که دستورالعمل 'max-age' در 'Cache-Control' یا هدر 'Expires' را برای کش مشترک بازنویسی می‌کند. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | یک رشتهٔ داده‌شده را از اندیس مشخص‌شده به یک نمونه از کلاس [CacheControlHeaderValue](./) تبدیل می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کپی‌برداری از انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | یک رشتهٔ داده‌شده را به یک نمونه از کلاس [CacheControlHeaderValue](./) تبدیل می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع‌دار شیء مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | مقدار حداکثر عمر را بر حسب ثانیه تنظیم می‌کند که زمان پذیرش پاسخ توسط کلاینت را تعیین می‌کند. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا کلاینت پاسخ‌های منقضی‌شده را می‌پذیرد یا نه. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | مقدار را بر حسب ثانیه تنظیم می‌کند که زمان پذیرش پاسخ‌های منقضی‌شده توسط کلاینت را تعیین می‌کند. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | مقداری را تنظیم می‌کند که طول عمر تازگی را تعیین می‌کند. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا سرور نیاز به اعتبارسنجی مجدد ورودی کش دارد زمانی که منسوخ می‌شود. |
| void [set_NoCache](./set_nocache/)(**bool**) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا کلاینت پاسخ کش‌شده را می‌پذیرد. |
| void [set_NoStore](./set_nostore/)(**bool**) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا کش نباید هیچ بخشی از درخواست یا پاسخ HTTP را ذخیره کند. |
| void [set_NoTransform](./set_notransform/)(**bool**) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا کش یا پراکسی نباید هیچ بخشی از بدنهٔ موجودیت را تغییر دهد. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا کلاینت باید فقط از ورودی‌های کش‌شده استفاده کند. |
| void [set_Private](./set_private/)(**bool**) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا پیام پاسخ HTTP یا بخشی از آن برای یک کاربر واحد است و نباید توسط کش اشتراکی کش شود. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا سرور نیاز به اعتبارسنجی مجدد ورودی کش دارد زمانی که برای کش‌های مشترک کاربران منسوخ می‌شود. |
| void [set_Public](./set_public/)(**bool**) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا یک پاسخ HTTP می‌تواند توسط هر کشی کش شود. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | مقدار حداکثر عمر مشترک را بر حسب ثانیه تنظیم می‌کند که دستورالعمل 'max-age' در 'Cache-Control' یا هدر 'Expires' را برای کش مشترک بازنویسی می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nth قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](./tostring/)() const override | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | سعی می‌کند یک رشتهٔ داده‌شده را به یک نمونه از کلاس [CacheControlHeaderValue](./) تبدیل کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای آزادسازی قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## مراجع دیگر

* کلاس [ICloneable](../../system/icloneable/)
* فضای‌نام [System::Net::Http::Headers](../)
* کتابخانه [Aspose.Slides](../../)