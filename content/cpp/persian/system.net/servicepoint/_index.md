---
title: ServicePoint
second_title: مرجع API Aspose.Slides برای C++
description: "مدیریت اتصال HTTP را فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 417
url: /fa/system.net/servicepoint/
---
## کلاس ServicePoint

مدیریت اتصال HTTP را فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class ServicePoint : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | اتصالاتی را که به گروه اتصال مشخص تعلق دارند بسته و حذف می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از مفهوم [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaNs برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaNs برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | URI سرور را که نمونه فعلی به آن متصل می‌شود برمی‌گرداند. |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | دلتگیت مورد استفاده برای ارتباط [IPEndPoint](../ipendpoint/) محلی با نمونه فعلی را دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | گواهی‌ای را که توسط نمونه فعلی استفاده می‌شود برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | آخرین گواهی مشتری را برمی‌گرداند. |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | مدت زمان انتظار بر حسب میلی‌ثانیه را که پس از آن [ServicePoint](./) فعال بسته می‌شود، دریافت می‌کند. |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | حداکثر تعداد اتصالات مجاز برای نمونه فعلی را دریافت می‌کند. |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | نام اتصال را برمی‌گرداند. |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | تعداد اتصالات باز را برمی‌گرداند. |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | مقداری را دریافت می‌کند که نشان می‌دهد آیا رفتار 100-Continue استفاده می‌شود یا نه. |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | تاریخ و زمان آخرین اتصال به یک هاست را برمی‌گرداند. |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | مقدار زمان بر حسب میلی‌ثانیه را که پس از آن یک اتصال بیکار بسته می‌شود، دریافت می‌کند. |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | نسخه HTTP را برمی‌گرداند. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | اندازه بافر دریافت را دریافت می‌کند. |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا نمونه فعلی از اتصالات پایپلاین پشتیبانی می‌کند یا نه. |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | مقداری را دریافت می‌کند که نشان می‌دهد آیا الگوریتم Nagle توسط اتصالات مدیریت‌شده توسط نمونه فعلی استفاده می‌شود یا نه. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیا سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با بیان lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع اشتراکی را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | دلتگیت مورد استفاده برای ارتباط [IPEndPoint](../ipendpoint/) محلی با نمونه فعلی را تنظیم می‌کند. |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | مدت زمان انتظار بر حسب میلی‌ثانیه را که پس از آن [ServicePoint](./) فعال بسته می‌شود، تنظیم می‌کند. |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | حداکثر تعداد اتصالات مجاز برای نمونه فعلی را تنظیم می‌کند. |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا رفتار 100-Continue استفاده می‌شود یا نه. |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | مقدار زمان بر حسب میلی‌ثانیه را که پس از آن یک اتصال بیکار بسته می‌شود، تنظیم می‌کند. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | اندازه بافر دریافت را تنظیم می‌کند. |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا الگوریتم Nagle توسط اتصالات مدیریت‌شده توسط نمونه فعلی استفاده می‌شود یا نه. |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا گزینه 'Keep-Alive' فعال است یا نه. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش می‌دهد و باز می‌گرداند. نباید به طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیا سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری با بیان lock() در C# را رفع می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## مراجع

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Net](../)
* کتابخانه [Aspose.Slides](../../)