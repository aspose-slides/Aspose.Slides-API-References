---
title: Socket
second_title: مرجع API Aspose.Slides برای C++
description: کلاس Socket رابط سوکت‌های برکلی را پیاده‌سازی می‌کند.
type: docs
weight: 53
url: /fa/system.net.sockets/socket/
---
## کلاس Socket

کلاس [Socket](./) رابط Berkeley sockets را پیاده‌سازی می‌کند.
```cpp
class Socket : public System::IDisposable
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | یک سوکت جدید برای اتصال تازه‌ ایجاد شده ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | یک عملیات اتصال ناهمزمان را آغاز می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | یک عملیات اتصال ناهمزمان را آغاز می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | یک عملیات اتصال ناهمزمان را آغاز می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | یک عملیات اتصال ناهمزمان را آغاز می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | یک عملیات ارسال ناهمزمان را آغاز می‌کند. |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | سوکت را به نقطهٔ انتهایی محلی مشخص بایند می‌کند. |
| void [Close](./close/)() | اتصال سوکت را می‌بندد. |
| void [Close](./close/)(int) | اتصال سوکت را با زمان‌سنجی مشخص می‌بندد تا داده‌های صف‌گذاری‌شده ارسال شوند. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | اتصال به نقطهٔ انتهایی ریموت مشخص برقرار می‌کند. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | اتصال به نقطهٔ انتهایی ریموت مشخص برقرار می‌کند. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | اتصال به نقطهٔ انتهایی ریموت مشخص برقرار می‌کند. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | اتصال به نقطهٔ انتهایی ریموت مشخص برقرار می‌کند. |
| void [Dispose](./dispose/)() override | کاری انجام نمی‌دهد. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | تا زمانی که عملیات اتصال ناهمزمان مشخص تکمیل شود، صبر می‌کند. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | تا زمانی که عملیات دریافت ناهمزمان مشخص تکمیل شود، صبر می‌کند. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | تا زمانی که عملیات دریافت ناهمزمان مشخص تکمیل شود، صبر می‌کند. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | تا زمانی که عملیات ارسال ناهمزمان مشخص تکمیل شود، صبر می‌کند. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | تا زمانی که عملیات ارسال ناهمزمان مشخص تکمیل شود، صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیء‌ها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی استفاده می‌شود. |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | خانوادهٔ آدرس را برمی‌گرداند. |
| **int32_t** [get_Available](./get_available/)() | تعداد بایت‌های دریافت‌شده از شبکه و در دسترس برای خواندن را دریافت می‌کند. |
| **bool** [get_Blocking](./get_blocking/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا سوکت در حالت مسدود است یا نه. |
| **bool** [get_Connected](./get_connected/)() | مقداری را برمی‌گرداند که نشان می‌دهد سوکت به میزبان ریموت متصل است یا نه. |
| **bool** [get_DontFragment](./get_dontfragment/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا سوکت اجازهٔ تکه‌تکه شدن دیتاگرام‌های IP را می‌دهد یا نه. |
| **bool** [get_DualMode](./get_dualmode/)() | مقداری را برمی‌گرداند که نشان می‌دهد سوکت در حالت دوگانه است یا نه. |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا سوکت بسته‌های پخش را مجاز می‌داند یا نه. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | مقداری را برمی‌گرداند که نشان می‌دهد تنها یک فرآیند می‌تواند سوکت را به یک پورت بایند کند یا نه. |
| **bool** [get_IsBound](./get_isbound/)() | مقداری را برمی‌گرداند که نشان می‌دهد سوکت به پورت محلی خاصی بایند شده است یا نه. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | مقداری را برمی‌گرداند که نشان می‌دهد سوکت برای ارسال تمام داده‌های معلق، بسته شدن را تأخیر می‌دهد یا نه. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | نقطهٔ انتهایی محلی را برمی‌گرداند. |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | مقداری را برمی‌گرداند که نشان می‌دهد سوکت بسته‌های چندپخشی خروجی را دریافت می‌کند یا نه. |
| **bool** [get_NoDelay](./get_nodelay/)() | مقداری را برمی‌گرداند که نشان می‌دهد سوکت از الگوریتم نِیگل استفاده می‌کند یا نه. |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا سیستم‌عامل و آداپتورهای شبکه IPv4 را پشتیبانی می‌کنند یا نه. |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا سیستم‌عامل و آداپتورهای شبکه IPv6 را پشتیبانی می‌کنند یا نه. |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | نوع پروتکل را برمی‌گرداند. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | اندازهٔ بافر دریافت را برمی‌گرداند. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | دوره‌ای را برمی‌گرداند که پس از آن فراخوانی 'Receive' به پایان زمان می‌رسد. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | نقطهٔ انتهایی ریموت را برمی‌گرداند. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | اندازهٔ بافر ارسال را برمی‌گرداند. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | دوره‌ای را برمی‌گرداند که پس از آن فراخوانی 'Send' به پایان زمان می‌رسد. |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | نوع سوکت را برمی‌گرداند. |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا میزبان فعلی IPv4 را پشتیبانی می‌کند یا نه. |
| **int16_t** [get_Ttl](./get_ttl/)() | مقدار TTL را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مربوط به شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/) است. امکان هش‌گذاری شیء‌های سفارشی را فراهم می‌کند. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | یک اشاره‌گر به پیاده‌سازی را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | مقداری را که به نام گزینهٔ مشخص شده مربوط می‌شود، برمی‌گرداند. |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | مقداری را که به نام گزینهٔ مشخص شده مربوط می‌شود، دریافت می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | مقداری را که به نام گزینهٔ مشخص شده مربوط می‌شود، برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/) است. |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | حالت‌های عملیاتی سطح پایین برای سوکت را تنظیم می‌کند. |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | حالت‌های عملیاتی سطح پایین برای سوکت را تنظیم می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایندهٔ نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is' است. |
| void [Listen](./listen/)(**int32_t**) | وضعیت سوکت را به 'listen' تغییر می‌دهد. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) است. امکان کپی‌برداری از انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | وضعیت سوکت را بر اساس حالت پولینگ مشخص‌شده برمی‌گرداند. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | داده‌ها را از سوکت دریافت می‌کند و در آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | داده‌ها را از سوکت دریافت می‌کند و در آرایه‌های بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | داده‌ها را از سوکت دریافت می‌کند و در آرایه‌های بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | داده‌ها را از سوکت دریافت می‌کند و در آرایه‌های بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطهٔ انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطهٔ انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطهٔ انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطهٔ انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطهٔ انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | داده‌ها را از نقطه انتهایی مشخص دریافت می‌کند و در آرایه بایتی مشخص می‌نویسد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار شیء نوع مقدار را با nullptr مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مشترک ارجاع را به مقدار مشخص کم می‌کند. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | داده‌های مشخص را به سوکت ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | داده‌ها را به نقطه انتهایی مشخص ارسال می‌کند. |
| void [set_Blocking](./set_blocking/)(**bool**) | مقداری تنظیم می‌کند که نشان‌دهنده این است که سوکت در حالت مسدود است. |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | مهلت زمان اتصال را تنظیم می‌کند. |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | مقداری تنظیم می‌کند که نشان‌دهنده امکان تقسیم بسته‌های IP توسط سوکت است. |
| void [set_DualMode](./set_dualmode/)(**bool**) | مقداری تنظیم می‌کند که نشان‌دهنده این است که سوکت در حالت دوگانه است. |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | مقداری تنظیم می‌کند که نشان‌دهنده این است که سوکت بسته‌های پخش را مجاز می‌کند. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | مقداری تنظیم می‌کند که نشان‌دهنده این است که فقط یک فرآیند می‌تواند سوکت را به یک پورت متصل کند. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | مقداری تنظیم می‌کند که نشان‌دهنده این است که سوکت قبل از بستن برای ارسال تمام داده‌های انتظار دار شده تاخیر می‌کند. |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | مقداری تنظیم می‌کند که نشان‌دهنده این است که سوکت بسته‌های چندپخشی خروجی را دریافت می‌کند. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | مقداری تنظیم می‌کند که نشان‌دهنده این است که سوکت از الگوریتم نایگل استفاده می‌کند. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | اندازه‌ی بافر دریافت را تنظیم می‌کند. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | دوره‌ای را تنظیم می‌کند که پس از آن فراخوانی 'Receive' زمان‌سنجی می‌شود. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | اندازه‌ی بافر ارسال را تنظیم می‌کند. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | دوره‌ای را تنظیم می‌کند که پس از آن فراخوانی 'Send' زمان‌سنجی می‌شود. |
| void [set_Ttl](./set_ttl/)(**int16_t**) | مقدار TTL را تنظیم می‌کند. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | گزینه سوکت مشخص را به مقدار مشخص تنظیم می‌کند. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | گزینه سوکت مشخص را به مقدار مشخص تنظیم می‌کند. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | گزینه سوکت مشخص را به مقدار مشخص تنظیم می‌کند. |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | گزینه سوکت مشخص را به مقدار مشخص تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده ارجاع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | عملیات ارسال و دریافت سوکت را غیرفعال می‌کند. |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | یک نمونه جدید می‌سازد. |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | یک نمونه جدید می‌سازد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
| virtual  [~Socket](./~socket/)() | نمونه فعلی را تخریب می‌کند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [ImplPtr](./implptr/) | پیاده‌سازی سوکت. |

## مراجع دیگر

* کلاس [IDisposable](../../system/idisposable/)
* فضای‌نام [System::Net::Sockets](../)
* کتابخانه [Aspose.Slides](../../)