---
title: IPAddress
second_title: مرجع API Aspose.Slides برای C++
description: "آدرس IP را نشان می‌دهد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشتباهات اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچانید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 326
url: /fa/system.net/ipaddress/
---
## IPAddress کلاس

آدرس IP را نشان می‌دهد. شیءهای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خرابی‌های اعتبارسنجی می‌شود. همواره این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچانید و از این اشاره‌گر برای گذراندن به توابع به عنوان پارامتر استفاده کنید.

```cpp
class IPAddress : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN مساوی در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN مساوی در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | خانوادهٔ آدرس را برمی‌گرداند. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا آدرس یک آدرس IPv4 است و به آدرس IPv6 نگاشته شده است. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا آدرس یک آدرس IPv6 محلی-پیوند است. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا آدرس یک آدرس چندپخشی جهانی IPv6 است. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا آدرس یک آدرس IPv6 محلی-سایت است. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا آدرس یک آدرس IPv6 Teredo است. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | شناسهٔ محدودهٔ آدرس IPv6 را دریافت می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | یک آرایه بایتی از آدرس IP را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | یک اشاره‌گر به پیاده‌سازی را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | ترتیب بایت میزبان مشخص‌شده را به ترتیب بایت شبکهٔ متناظر تبدیل می‌کند. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | ترتیب بایت میزبان مشخص‌شده را به ترتیب بایت شبکهٔ متناظر تبدیل می‌کند. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | ترتیب بایت میزبان مشخص‌شده را به ترتیب بایت شبکهٔ متناظر تبدیل می‌کند. |
| [IPAddress](./ipaddress/)(**int64_t**) | یک نمونهٔ جدید می‌سازد. |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | یک نمونهٔ جدید می‌سازد. |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | یک نمونهٔ جدید می‌سازد. |
| [IPAddress](./ipaddress/)() | یک نمونهٔ جدید می‌سازد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | مقداری را برمی‌گرداند که نشان می‌دهد آیا آدرس مشخص‌شده یک آدرس loopback است. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | آدرس را به آدرس IPv4 نگاشت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | آدرس را به آدرس IPv6 نگاشت می‌کند. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | ترتیب بایت شبکهٔ مشخص‌شده را به ترتیب بایت میزبان متناظر تبدیل می‌کند. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | ترتیب بایت شبکهٔ مشخص‌شده را به ترتیب بایت میزبان متناظر تبدیل می‌کند. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | ترتیب بایت شبکهٔ مشخص‌شده را به ترتیب بایت میزبان متناظر تبدیل می‌کند. |
| [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | یک رشتهٔ عبوری را به نمونه‌ای از کلاس [IPAddress](./) تبدیل می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء ارزش نوع را با nullptr بر اساس ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به میزان مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | شناسهٔ محدودهٔ آدرس IPv6 را تنظیم می‌کند. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | یک اشاره‌گر به پیاده‌سازی را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تبدیل اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](./tostring/)() const override | معادل روش [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | سعی می‌کند یک رشتهٔ عبوری را به نمونه‌ای از کلاس [IPAddress](./) تبدیل کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Any](./any/) | آدرس IPv4 که نشان می‌دهد آیا سرور باید تمام رابط‌های شبکه را گوش دهد. |
| static [Broadcast](./broadcast/) | آدرس پخش IPv4. |
| static [IPv6Any](./ipv6any/) | آدرس IPv6 که نشان می‌دهد آیا سرور باید تمام رابط‌های شبکه را گوش دهد. |
| static [IPv6Loopback](./ipv6loopback/) | آدرس loopback IPv6. |
| static [IPv6None](./ipv6none/) | آدرس IPv6 که نشان می‌دهد آیا سرور نباید هیچ رابط شبکه‌ای را گوش دهد. |
| static [Loopback](./loopback/) | آدرس loopback IPv4. |
| static [None](./none/) | آدرس IPv4 که نشان می‌دهد آیا سرور نباید هیچ رابط شبکه‌ای را گوش دهد. |

## تعاریف‌نوع

| تعریف‌نوع | توضیح |
| --- | --- |
| [ImplPtr](./implptr/) | یک اشاره‌گر به نوع پیاده‌سازی. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [System::Net](../)
* کتابخانه [Aspose.Slides](../../)