---
title: HttpWebRequest
second_title: مرجع API Aspose.Slides برای C++
description: "نمایش درخواست وب HTTP. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکال‌های assert می‌شود. همیشه این کلاس را در اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 274
url: /fa/system.net/httpwebrequest/
---
## HttpWebRequest کلاس

نمایش درخواست وب HTTP. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکال‌های assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Abort](./abort/)() override | درخواست فعلی را لغو می‌کند. |
| virtual void [AddRange](./addrange/)(**int32_t**) | هدر '[Range](../../system/range/)' را به درخواست فعلی اضافه می‌کند. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | هدر '[Range](../../system/range/)' را به درخواست فعلی اضافه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | یک عملیات ناهمگام برای دریافت یک جریان به منظور نوشتن داده‌ها به منبع آغاز می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | یک درخواست ناهمگام برای منبع آغاز می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | یک نمونه جدید از کلاس [WebRequest](../webrequest/) را با استفاده از URI مشخص‌شده ایجاد می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | یک نمونه جدید از کلاس [WebRequest](../webrequest/) را با استفاده از URI مشخص‌شده ایجاد می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | یک فرزند [WebRequest](../webrequest/) برای طرح URI مشخص‌شده ایجاد می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | یک نمونه جدید از کلاس [WebRequest](../webrequest/) را با استفاده از URI مشخص‌شده ایجاد می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | یک نمونه جدید از کلاس [WebRequest](../webrequest/) را با استفاده از URI مشخص‌شده ایجاد می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | تا تکمیل عملیات ناهمگام مشخص‌شده برای دریافت یک جریان صبر می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | تا تکمیل درخواست ناهمگام مشخص‌شده برای منبع صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارزش را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | مقدار هدر 'Accept' HTTP را دریافت می‌کند. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | مقداری را دریافت می‌کند که نشان می‌دهد آیا درخواست باید ریدایرکت‌ها را دنبال کند یا نه. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | مقداری را دریافت می‌کند که نشان می‌دهد آیا داده‌های دریافت‌شده از منبع باید بافر شوند یا نه. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | مقداری را دریافت می‌کند که نشان می‌دهد آیا بافر برای ارسال داده فعال است یا نه. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | سیاست کش را دریافت می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | مجموعه گواهینامه‌های مرتبط با درخواست فعلی را دریافت می‌کند. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | نام گروه اتصال را دریافت می‌کند. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | تعداد بایت‌های داده درخواست برای ارسال را دریافت می‌کند. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | نوع MIME درخواست را دریافت می‌کند. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | زمان انتظار (timeout) برای دریافت کد وضعیت 100-Continue را دریافت می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | یک مخزن کوکی مرتبط با درخواست وب فعلی را دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | اطلاعات احراز هویت مرتبط با درخواست فعلی را دریافت می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | پروکسی HTTP سراسری را دریافت می‌کند. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | مقدار را برمی‌گرداند که نشان می‌دهد آیا پاسخی دریافت شده است یا نه. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | مجموعه هدرهای HTTP را دریافت می‌کند. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | مقداری را دریافت می‌کند که نشان می‌دهد آیا درخواست فعلی باید هدر 'Keep-Alive' را داشته باشد یا نه. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | حداکثر تعداد ریدایرکت‌های مجاز را دریافت می‌کند. |
| [String](../../system/string/) [get_Method](./get_method/)() override | متد HTTP را دریافت می‌کند. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | مقداری را دریافت می‌کند که نشان می‌دهد آیا درخواست باید پیش‌احراز هویت شود یا نه. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | فهرست پیشوندها را دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | پروکسی HTTP را دریافت می‌کند. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | مقدار هدر 'Referer' را دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | URI درخواست را برمی‌گرداند. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | مقداری را دریافت می‌کند که نشان می‌دهد آیا داده باید به صورت بخش‌ها ارسال شود یا نه. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | یک نقطه سرویس را برمی‌گرداند که نمایانگر اتصال شبکه به منبع است. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا درخواست فعلی می‌تواند از مخزن کوکی استفاده کند یا نه. |
| **int32_t** [get_Timeout](./get_timeout/)() override | مقدار زمان (به میلی‌ثانیه) پس از آن که درخواست منقضی می‌شود را دریافت می‌کند. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | مقداری را دریافت می‌کند که نشان می‌دهد آیا ویژگی 'Credential' برابر با ویژگی 'DefaultCredentials' است یا نه. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | مقدار هدر 'User-Agent' را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | یک معادل برای متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | جریان برای نوشتن داده‌ها به منبع را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | پاسخ وب مرتبط با درخواست وب فعلی را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | یک نمونه جدید می‌سازد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع ارزشی را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | فرزند [WebRequest](../webrequest/) را برای URI مشخص‌شده ثبت می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | مقدار هدر HTTP 'Accept' را تنظیم می‌کند. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا درخواست باید ریدایرکت‌ها را دنبال کند یا نه. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا داده‌های دریافت‌شده از منبع باید بافر شوند یا نه. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا بافر برای ارسال داده فعال است یا نه. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | سیاست کش را تنظیم می‌کند. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | مجموعه گواهینامه‌های مرتبط با درخواست فعلی را تنظیم می‌کند. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | نام گروه اتصال را تنظیم می‌کند. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | تعداد بایت‌های داده درخواست برای ارسال را تنظیم می‌کند. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | نوع MIME درخواست را تنظیم می‌کند. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | زمان انتظار (timeout) تا دریافت کد وضعیت 100-Continue را تنظیم می‌کند. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | مخزن کوکی مرتبط با درخواست وب فعلی را تنظیم می‌کند. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | اطلاعات احراز هویت مرتبط با درخواست فعلی را تنظیم می‌کند. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | پروکسی HTTP سراسری را تنظیم می‌کند. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | مجموعه هدرهای HTTP را تنظیم می‌کند. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا درخواست فعلی باید هدر 'Keep-Alive' را داشته باشد یا نه. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | حداکثر تعداد ریدایرکت‌های مجاز را تنظیم می‌کند. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | متد HTTP را تنظیم می‌کند. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | مقداری را تنظیم می‌کند که نشان می‌دهد آیا درخواست باید پیش‌احراز هویت شود یا نه. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | فهرست پیشوندها را تنظیم می‌کند. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | نسخه HTTP را تنظیم می‌کند. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | پروکسی HTTP را تنظیم می‌کند. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | مقدار هدر 'Referer' را تنظیم می‌کند. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا داده باید به صورت بخش‌ها ارسال شود یا نه. |
| void [set_Timeout](./set_timeout/)(int) override | مقدار زمان (به میلی‌ثانیه) پس از آن که درخواست منقضی می‌شود را تنظیم می‌کند. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | مقدار زمان (به میلی‌ثانیه) پس از آن که درخواست منقضی می‌شود را تنظیم می‌کند. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | مقداری را تنظیم می‌کند که نشان می‌دهد آیا ویژگی 'Credential' برابر با ویژگی 'DefaultCredentials' است یا نه. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | مقدار هدر 'User-Agent' را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [WebRequest](../webrequest/)
* فضای‌نام [System::Net](../)
* کتابخانه [Aspose.Slides](../../)