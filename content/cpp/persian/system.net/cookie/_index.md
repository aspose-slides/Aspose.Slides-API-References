---
title: Cookie
second_title: مرجع API Aspose.Slides برای C++
description: "نمایشگر یک کوکی HTTP. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و برای عبور به توابع به‌عنوان آرگومان از این اشاره‌گر استفاده کنید."
type: docs
weight: 1
url: /fa/system.net/cookie/
---
## Cookie class


یک کوکی HTTP را نشان می‌دهد. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و برای عبور به توابع به‌عنوان آرگومان از این اشاره‌گر استفاده کنید.

```cpp
class Cookie : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | یک کپی از نمونهٔ فعلی ایجاد می‌کند. |
| [Cookie](./cookie/)() | یک نمونهٔ جدید می‌سازد. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | یک نمونهٔ جدید می‌سازد. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | یک نمونهٔ جدید می‌سازد. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | یک نمونهٔ جدید می‌سازد. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند به‌طوری که دو NaN برابر درنظر گرفته شوند حتی با توجه به IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند به‌طوری که دو NaN برابر درنظر گرفته شوند حتی با توجه به IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده‌های داخلی. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | مقدار ویژگی 'Comment' را دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | مقدار ویژگی 'CommentURL' را دریافت می‌کند. |
| **bool** [get_Discard](./get_discard/)() const | مقدار ویژگی 'Discard' را دریافت می‌کند. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | مقدار ویژگی 'Domain' را دریافت می‌کند. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا دامنه به‌صورت ضمنی است. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | کلید دامنه را برمی‌گرداند. |
| **bool** [get_Expired](./get_expired/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا کوکی منقضی شده است. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | مقدار ویژگی 'Expires' را دریافت می‌کند. |
| **bool** [get_HttpOnly](./get_httponly/)() const | مقدار ویژگی 'HttpOnly' را دریافت می‌کند. |
| [String](../../system/string/) [get_Name](./get_name/)() const | نام کوکی را دریافت می‌کند. |
| [String](../../system/string/) [get_Path](./get_path/)() const | مقدار ویژگی 'Path' را دریافت می‌کند. |
| **bool** [get_Plain](./get_plain/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا مشخصات کوکی 'Plain' است. |
| [String](../../system/string/) [get_Port](./get_port/)() const | مقدار ویژگی 'Port' را دریافت می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | مجموعهٔ مقادیر ویژگی 'Port' را برمی‌گرداند. |
| **bool** [get_Secure](./get_secure/)() const | مقدار ویژگی 'Secure' را دریافت می‌کند. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | زمانی که کوکی ساخته شده است را برمی‌گرداند. |
| [String](../../system/string/) [get_Value](./get_value/)() const | مقدار کوکی را دریافت می‌کند. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | مشخصات کوکی را دریافت می‌کند. |
| **int32_t** [get_Version](./get_version/)() const | مقدار ویژگی '[Version](../../system/version/)' را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | این متد توسط متدهای دیگر برای تنظیم نام متد فراخوانی می‌شود. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از کلاس‌های مشتق را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از کلاس‌های مشتق را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر مبنای مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر مبنای مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | مقدار ویژگی 'Comment' را تنظیم می‌کند. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | مقدار ویژگی 'CommentURL' را تنظیم می‌کند. |
| void [set_Discard](./set_discard/)(**bool**) | مقدار ویژگی 'Discard' را تنظیم می‌کند. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | مقدار ویژگی 'Domain' را تنظیم می‌کند. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا دامنه به‌صورت ضمنی است. |
| void [set_Expired](./set_expired/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا کوکی منقضی شده است. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | مقدار ویژگی 'Expires' را تنظیم می‌کند. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | مقدار ویژگی 'HttpOnly' را تنظیم می‌کند. |
| void [set_Name](./set_name/)([String](../../system/string/)) | نام کوکی را تنظیم می‌کند. |
| void [set_Path](./set_path/)([String](../../system/string/)) | مقدار ویژگی 'Path' را تنظیم می‌کند. |
| void [set_Port](./set_port/)([String](../../system/string/)) | مقدار ویژگی 'Port' را تنظیم می‌کند. |
| void [set_Secure](./set_secure/)(**bool**) | مقدار ویژگی 'Secure' را تنظیم می‌کند. |
| void [set_Value](./set_value/)([String](../../system/string/)) | مقدار کوکی را تنظیم می‌کند. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | مشخصات کوکی را تنظیم می‌کند. |
| void [set_Version](./set_version/)(**int32_t**) | مقدار ویژگی '[Version](../../system/version/)' را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و بر می‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | نمونهٔ جاری را به نمایش رشته‌ای سریالی می‌کند. |
| [String](../../system/string/) [ToString](./tostring/)() const override | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازگشت قفل‌گذاری lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | مقدارهای پیش‌فرض ویژگی‌ها را تأیید و تنظیم می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## Fields

| Field | Description |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | نام ویژگی 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | نام ویژگی 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | نام ویژگی 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | نام ویژگی 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | جداساز استفاده‌شده برای جدا کردن نام و مقدار یک ویژگی. |
| static [ExpiresAttributeName](./expiresattributename/) | نام ویژگی 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | نام ویژگی 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | نام ویژگی 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | حداکثر نسخهٔ پشتیبانی‌شده. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | نمایش رشته‌ای حداکثر نسخهٔ پشتیبانی‌شده. |
| static [PathAttributeName](./pathattributename/) | نام ویژگی 'Path'. |
| static [PortAttributeName](./portattributename/) | نام ویژگی 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | آرایه‌ای که جداکننده‌های مقادیر ویژگی 'Port' را شامل می‌شود. |
| static [QuotesLiteral](./quotesliteral/) | نماد استفاده‌شده برای بسته‌بندی قسمت‌های ویژگی. |
| static [ReservedToName](./reservedtoname/) | مقداری که برای نام کوکی محفوظ است. |
| static [ReservedToValue](./reservedtovalue/) | مقداری که برای مقدار کوکی محفوظ است. |
| static [SecureAttributeName](./secureattributename/) | نام ویژگی 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | جداکنندهٔ ویژگی. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | پیشوند نام‌های ویژگی‌های ویژه. |
| static [VersionAttributeName](./versionattributename/) | نام ویژگی '[Version](../../system/version/)'. |

## See Also

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Net](../)
* کتابخانه [Aspose.Slides](../../)