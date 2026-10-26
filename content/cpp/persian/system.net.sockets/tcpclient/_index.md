---
title: TcpClient
second_title: مرجع API Aspose.Slides برای C++
description: "نماینده‌ای برای سرویس‌های شبکه TCP است. اشیاء این کلاس باید تنها با استفاده از تابع System::MakeObject() ایجاد شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 66
url: /fa/system.net.sockets/tcpclient/
---
## TcpClient کلاس


نماینده‌ای برای سرویس‌های شبکه TCP است. اشیاء این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) ایجاد شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class TcpClient : public System::IDisposable
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | یک عملیات اتصال ناهمزمان را آغاز می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | یک عملیات اتصال ناهمزمان را آغاز می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | یک عملیات اتصال ناهمزمان را آغاز می‌کند. |
| void [Close](./close/)() | اتصال را می‌بندد و نمونهٔ فعلی را از بین می‌برد. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | یک اتصال به میزبان راه‌دور مشخص‌شده برقرار می‌کند. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | یک اتصال به میزبان راه‌دور مشخص‌شده برقرار می‌کند. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | یک اتصال به میزبان راه‌دور مشخص‌شده برقرار می‌کند. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | یک اتصال به میزبان راه‌دور مشخص‌شده برقرار می‌کند. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | هیچ کاری انجام نمی‌دهد. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | تا پایان عملیات اتصال ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه عددی مشابه C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه عددی مشابه C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| **int32_t** [get_Available](./get_available/)() | تعداد بایت‌های دریافت‌شده که آمادهٔ خواندن هستند را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | سوکت را دریافت می‌کند. |
| **bool** [get_Connected](./get_connected/)() | مقداری که نشان می‌دهد سوکت به میزبان راه‌دور متصل است را برمی‌گرداند. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | مقداری که نشان می‌دهد نمونهٔ فعلی فقط اجازهٔ یک مشتری برای استفاده از یک پورت را می‌دهد را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | مقداری که نشان می‌دهد سوکت برای ارسال تمام داده‌های معلق، بسته شدن را به تعویق می‌اندازد را برمی‌گرداند. |
| **bool** [get_NoDelay](./get_nodelay/)() | مقداری که نشان می‌دهد نمونهٔ فعلی از الگوریتم Nagle استفاده می‌کند را برمی‌گرداند. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | اندازهٔ بافر مورد استفاده برای دریافت داده‌ها را برمی‌گرداند. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | مقداری که نشان می‌دهد پس از چه مدت زمانی دریافت داده‌ها منقضی می‌شود را برمی‌گرداند. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | اندازهٔ بافر مورد استفاده برای ارسال داده‌ها را برمی‌گرداند. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | مقداری که نشان می‌دهد پس از چه مدت زمانی ارسال داده‌ها منقضی می‌شود را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با آبجکت را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | جریان استفاده‌شده برای ارسال و دریافت داده‌ها را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمادی از یک نمونهٔ از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌ (lock) در C#. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع برای شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | سوکت را تنظیم می‌کند. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | مقداری که نشان می‌دهد نمونهٔ فعلی فقط اجازهٔ یک مشتری برای استفاده از یک پورت را می‌دهد را تنظیم می‌کند. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | مقداری که نشان می‌دهد سوکت برای ارسال تمام داده‌های معلق، بسته شدن را به تعویق می‌اندازد را تنظیم می‌کند. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | مقداری که نشان می‌دهد نمونهٔ فعلی از الگوریتم Nagle استفاده می‌کند را تنظیم می‌کند. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | اندازهٔ بافر مورد استفاده برای دریافت داده‌ها را تنظیم می‌کند. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | مقداری که نشان می‌دهد پس از چه مدت زمانی دریافت داده‌ها منقضی می‌شود را تنظیم می‌کند. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | اندازهٔ بافر مورد استفاده برای ارسال داده‌ها را تنظیم می‌کند. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | مقداری که نشان می‌دهد پس از چه مدت زمانی ارسال داده‌ها منقضی می‌شود را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف تنظیم می‌کند (به جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | یک نمونهٔ جدید ایجاد می‌کند. |
|  [TcpClient](./tcpclient/)() | یک نمونهٔ جدید ایجاد می‌کند. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | یک نمونهٔ جدید ایجاد می‌کند. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | یک نمونهٔ جدید ایجاد می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار [System.Object](../../system/object/) در C# (typeof). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی حذف قفل (unlock) در C#. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
| virtual  [~TcpClient](./~tcpclient/)() | نمونهٔ فعلی را از بین می‌برد. |
## مراجع

* کلاس [IDisposable](../../system/idisposable/)
* فضای‌نام [System::Net::Sockets](../)
* کتابخانه [Aspose.Slides](../../)