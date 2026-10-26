---
title: ServicePointManager
second_title: مرجع API Aspose.Slides برای C++
description: "مراحل چرخه حیات (ایجاد، نگهداری و حذف) نمونه‌های کلاس ServicePoint را مدیریت می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 430
url: /fa/system.net/servicepointmanager/
---
## ServicePointManager کلاس

چرخه‌ی حیات (ایجاد، نگهداری و حذف) نمونه‌های کلاس [ServicePoint](../servicepoint/) را مدیریت می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class ServicePointManager : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناهای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN با هیچ مقداری برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN با هیچ مقداری برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | یک سیاست گواهی را دریافت می‌کند. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا گواهی باید در مقابل فهرست بازنشانی گواهی مرجع بررسی شود یا خیر. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | حداکثر تعداد ارتباطات همزمان مجاز توسط نمونه‌های کلاس ServicePoint را دریافت می‌کند. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | زمان-پایان (به میلی‌ثانیه) که در آن یک حل DNS معتبر تلقی می‌شود را دریافت می‌کند. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا حل DNS بین آدرس‌های IP قابل اعمال می‌چرخد یا خیر. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | سیاست رمزنگاری مورد استفاده توسط نمونه‌ی فعلی را برمی‌گرداند. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا نمونه‌های کلاس ServicePoint رفتار 100-Continue را استفاده می‌کنند یا خیر. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | حداکثر زمان بیکاری نمونه‌های کلاس ServicePoint را دریافت می‌کند. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | حداکثر تعداد نمونه‌های کلاس ServicePoint که می‌تواند توسط نمونه‌ی فعلی مدیریت شود را دریافت می‌کند. |
| static **bool** [get_ReusePort](./get_reuseport/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا سوکت‌های خروجی ارتباطات گزینه‌ی 'SO_REUSE_UNICASTPORT' را استفاده می‌کنند یا خیر. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | نوع پروتکل امنیتی استفاده شده توسط نمونه‌های کلاس ServicePoint که توسط نمونه‌ی فعلی مدیریت می‌شود را دریافت می‌کند. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | callback استفاده‌شده برای اعتبارسنجی گواهی سرور را دریافت می‌کند. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا نمونه‌های کلاس ServicePoint از الگوریتم Nagle استفاده می‌کنند یا خیر. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارنده‌ی مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل کردن دستور C# lock(). مستقیماً فراخوانی کنید یا از شیء sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کلاس‌های فرزند به صورت کپی را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کلاس‌های فرزند به صورت کپی را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده‌ی مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | یک سیاست گواهی را تنظیم می‌کند. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا گواهی باید در مقابل فهرست بازنشانی گواهی مرجع بررسی شود یا خیر. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | حداکثر تعداد ارتباطات همزمان مجاز توسط نمونه‌های کلاس ServicePoint را تنظیم می‌کند. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | زمان-پایان (به میلی‌ثانیه) که در آن یک حل DNS معتبر تلقی می‌شود را تنظیم می‌کند. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا حل DNS بین آدرس‌های IP قابل اعمال می‌چرخد یا خیر. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا نمونه‌های کلاس ServicePoint رفتار 100-Continue را استفاده می‌کنند یا خیر. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | حداکثر زمان بیکاری نمونه‌های کلاس ServicePoint را تنظیم می‌کند. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | حداکثر تعداد نمونه‌های کلاس ServicePoint که می‌تواند توسط نمونه‌ی فعلی مدیریت شود را تنظیم می‌کند. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا سوکت‌های خروجی ارتباطات گزینه‌ی 'SO_REUSE_UNICASTPORT' را استفاده می‌کنند یا خیر. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | نوع پروتکل امنیتی استفاده شده توسط نمونه‌های کلاس ServicePoint که توسط نمونه‌ی فعلی مدیریت می‌شود را تنظیم می‌کند. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | callback استفاده‌شده برای اعتبارسنجی گواهی سرور را تنظیم می‌کند. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا نمونه‌های کلاس ServicePoint از الگوریتم Nagle استفاده می‌کنند یا خیر. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | مقدار نشان‌دهنده فعال بودن گزینه‌ی 'Keep-Alive' را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده‌ی مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده‌ی مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده‌ی مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازه‌ی C# typeof([System.Object](../../system/object/)) را انجام می‌دهد. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل دستور C# lock(). مستقیماً فراخوانی کنید یا از شیء sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده‌ی مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده‌ی مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | تعداد پیش‌فرض اتصالات غیرپایدار. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | تعداد پیش‌فرض اتصالات پایدار. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Net](../)
* کتابخانه [Aspose.Slides](../../)