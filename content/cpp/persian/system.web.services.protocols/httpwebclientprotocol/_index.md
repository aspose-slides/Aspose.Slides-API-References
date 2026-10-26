---
title: HttpWebClientProtocol
second_title: Aspose.Slides برای C++ مرجع API
description: "این کلاس پایه در تمام پروکسی‌های کلاینت سرویس وب XML که از HTTP استفاده می‌کنند به کار گرفته می‌شود. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از operator new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بسته‌بندی کنید و از این اشاره‌گر برای انتقال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 14
url: /fa/system.web.services.protocols/httpwebclientprotocol/
---
## HttpWebClientProtocol کلاس

این کلاس پایه در تمام پروکسی‌های کلاینت سرویس XML [Web](../../system.web/) که از HTTP استفاده می‌کنند به کار می‌رود. اشیاء این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های صحت‌سنجی می‌شود. همیشه این کلاس را در یک نشانگر [System::SmartPtr](../../system/smartptr/) بسته‌بندی کنید و از این نشانگر برای انتقال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class HttpWebClientProtocol : public System::Web::Services::Protocols::WebClientProtocol
```

## متدها

| Method | Description |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | درخواست را لغو می‌کند. |
| virtual void [CheckForCookies](./checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | کوکی‌های درخواست مشخص‌شده را به مخزن داخلی کوکی‌ها اضافه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا کلاینت ریدایرکت‌های سرور را دنبال می‌کند یا نه. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | مجموعه‌ گواهینامه‌های کلاینت را برمی‌گرداند. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | نام گروه اتصال را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | مخزنی را برمی‌گرداند که برای ذخیره کوکی‌ها استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | اطلاعات احراز هویت را برمی‌گرداند. |
| **bool** [get_EnableDecompression](./get_enabledecompression/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا فشرده‌سازی معکوس فعال است یا نه. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا پیش‌احراز هویت فعال است یا نه. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](./get_proxy/)() | اطلاعات پروکسی را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | کدگذاری‌ای را که برای ارسال درخواست‌های کلاینت استفاده می‌شود برمی‌گرداند. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | مدت زمان انتظار قبل از پایان زمان انتظار درخواست را برمی‌گرداند. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](./get_unsafeauthenticatedconnectionsharing/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا به‌اشتراک‌گذاری اتصال هنگام استفاده کلاینت از احراز هویت NTLM فعال است یا نه. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | URI سرویس XML [Web](../../system.web/) را برمی‌گرداند. |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | آدرس URL سرویس XML [Web](../../system.web/) را برمی‌گرداند. |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا ویژگی 'Credential' برابر با ویژگی 'DefaultCredentials' است یا نه. |
| [String](../../system/string/) [get_UserAgent](./get_useragent/)() | مقدار هدر 'User-Agent' را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده نمایید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقداری را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مراجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا کلاینت ریدایرکت‌های سرور را دنبال می‌کند یا نه. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | نام گروه اتصال را تنظیم می‌کند. |
| void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | مخزنی را تنظیم می‌کند که برای ذخیره کوکی‌ها استفاده می‌شود. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | اطلاعات احراز هویت را تنظیم می‌کند. |
| void [set_EnableDecompression](./set_enabledecompression/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا فشرده‌سازی معکوس فعال است یا نه. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا پیش‌احراز هویت فعال است یا نه. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | اطلاعات پروکسی را تنظیم می‌کند. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | کدگذاری‌ای را تنظیم می‌کند که برای ارسال درخواست‌های کلاینت استفاده می‌شود. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | مدت زمان انتظار قبل از پایان زمان انتظار درخواست را تنظیم می‌کند. |
| void [set_UnsafeAuthenticatedConnectionSharing](./set_unsafeauthenticatedconnectionsharing/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا به‌اشتراک‌گذاری اتصال هنگام استفاده کلاینت از احراز هویت NTLM فعال است یا نه. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | URI سرویس XML [Web](../../system.web/) را تنظیم می‌کند. |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | آدرس URL سرویس XML [Web](../../system.web/) را تنظیم می‌کند. |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا ویژگی 'Credential' برابر با ویژگی 'DefaultCredentials' است یا نه. |
| void [set_UserAgent](./set_useragent/)([String](../../system/string/)) | مقدار هدر 'User-Agent' را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراک‌گذاری) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده نمایید. |
| void [UnregisterMapping](./unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [WebClientProtocol](../webclientprotocol/)
* فضای نام [System::Web::Services::Protocols](../)
* کتابخانه [Aspose.Slides](../../)