---
title: HttpWebRequest
second_title: مرجع API Aspose.Slides للغة C++
description: "يمثل طلب ويب HTTP. يجب إنشاء كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت تشغيل أو أخطاء تأكيد. دائمًا قم بتغليف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 274
url: /ar/system.net/httpwebrequest/
---
## HttpWebRequest فئة

يمثل طلب ويب HTTP. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبب أخطاء وقت تشغيل أو أخطاء تأكيد. دائمًا قم بتغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## Methods

| Method | Description |
| --- | --- |
| void [Abort](./abort/)() override | يلغي الطلب الحالي. |
| virtual void [AddRange](./addrange/)(**int32_t**) | يضيف رأس '[Range](../../system/range/)' إلى الطلب الحالي. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | يضيف رأس '[Range](../../system/range/)' إلى الطلب الحالي. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يبدأ عملية غير متزامنة للحصول على تدفق لكتابة البيانات إلى المورد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يبدأ طلبًا غير متزامنًا للمورد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | ينشئ نسخة جديدة من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ نسخة جديدة من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ نسخة [WebRequest](../webrequest/) مشتقة لمخطط الـ URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | ينشئ نسخة جديدة من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ نسخة جديدة من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | ينتظر حتى يكتمل العملية غير المتزامنة المحددة للحصول على تدفق. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | ينتظر حتى يكتمل الطلب غير المتزامن المحدد للمورد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي على نمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي على نمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة على نمط C# حيث تُعتبر NaNين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة على نمط C# حيث تُعتبر NaNين متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | يحصل على قيمة رأس HTTP 'Accept'. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | يحصل على قيمة تشير إلى ما إذا كان الطلب يجب أن يتبع عمليات إعادة التوجيه. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | يحصل على قيمة تشير إلى ما إذا كان يجب تخزين البيانات المستلمة من المورد في الذاكرة المؤقتة. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | يحصل على قيمة تشير إلى ما إذا كان التخزين المؤقت مفعلاً لإرسال البيانات. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | يحصل على سياسة التخزين المؤقت. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | يحصل على مجموعة الشهادات المرتبطة بالطلب الحالي. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | يحصل على اسم مجموعة الاتصال. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | يحصل على عدد البايتات من بيانات الطلب لإرسالها. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | يحصل على نوع MIME للطلب. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | يحصل على مهلة الانتظار حتى يتم استلام حالة 100-Continue. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | يحصل على حاوية ملفات تعريف الارتباط المرتبطة بطلب الويب الحالي. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | يحصل على معلومات المصادقة المرتبطة بالطلب الحالي. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | يحصل على وكيل HTTP العام. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | يرجع قيمة تشير إلى ما إذا تم استلام استجابة. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | يحصل على مجموعة رؤوس HTTP. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | يحصل على قيمة تشير إلى ما إذا كان يجب أن يحتوي الطلب الحالي على رأس 'Keep-Alive'. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | يحصل على الحد الأقصى المسموح به لإعادة التوجيه. |
| [String](../../system/string/) [get_Method](./get_method/)() override | يحصل على طريقة HTTP. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | يحصل على قيمة تشير إلى ما إذا كان يجب المصادقة المسبقة للطلب. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | يحصل على قائمة البادئات. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | يحصل على وكيل HTTP. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | يحصل على قيمة رأس 'Referer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | يرجع URI الطلب. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | يحصل على قيمة تشير إلى ما إذا كان يجب إرسال البيانات على أقسام. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | يرجع نقطة الخدمة التي تمثل اتصال الشبكة بالمورد. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | يرجع قيمة تشير إلى ما إذا كان الطلب الحالي يمكنه استخدام حاوية ملفات تعريف الارتباط. |
| **int32_t** [get_Timeout](./get_timeout/)() override | يحصل على مقدار الوقت بالمللي ثانية الذي بعده سينتهي مهلة الطلب. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | يحصل على قيمة تشير إلى ما إذا كانت خاصية 'Credential' مساوية لخاصية 'DefaultCredentials'. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | يحصل على قيمة رأس 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | يرجع التدفق لكتابة البيانات إلى المورد. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | يرجع استجابة الويب المرتبطة بطلب الويب الحالي. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يبني نسخة جديدة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع الهياكل الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعلاً، فقط يهيئ كائنًا جديدًا ويمكّن النسخ الظهري للفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعلاً، فقط يهيئ كائنًا جديدًا ويمكّن النسخ الظهري للفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | يسجّل النسخة [WebRequest](../webrequest/) المشتقة للـ URI المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | يضبط قيمة رأس HTTP 'Accept'. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب أن يتبع الطلب عمليات إعادة التوجيه. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب تخزين البيانات المستلمة من المورد في الذاكرة المؤقتة. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان التخزين المؤقت مفعلاً لإرسال البيانات. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | يضبط سياسة التخزين المؤقت. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | يضبط مجموعة الشهادات المرتبطة بالطلب الحالي. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | يضبط اسم مجموعة الاتصال. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | يضبط عدد البايتات من بيانات الطلب لإرسالها. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | يضبط نوع MIME للطلب. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | يضبط مهلة الانتظار حتى يتم استلام حالة 100-Continue. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | يضبط حاوية ملفات تعريف الارتباط المرتبطة بطلب الويب الحالي. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | يضبط معلومات المصادقة المرتبطة بالطلب الحالي. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | يضبط وكيل HTTP العام. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | يضبط مجموعة رؤوس HTTP. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب أن يحتوي الطلب الحالي على رأس 'Keep-Alive'. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | يضبط الحد الأقصى المسموح به لإعادة التوجيه. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | يضبط طريقة HTTP. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | يضبط قيمة تشير إلى ما إذا كان يجب المصادقة المسبقة للطلب. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | يضبط قائمة البادئات. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | يضبط نسخة HTTP. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | يضبط وكيل HTTP. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | يضبط قيمة رأس 'Referer'. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب إرسال البيانات على أقسام. |
| void [set_Timeout](./set_timeout/)(int) override | يضبط مقدار الوقت بالمللي ثانية الذي بعده سيُنتهي مهلة الطلب. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | يضبط مقدار الوقت بالمللي ثانية الذي بعده سيُنتهي مهلة الطلب. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | يضبط قيمة تشير إلى ما إذا كانت خاصية 'Credential' مساوية لخاصية 'DefaultCredentials'. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | يضبط قيمة رأس 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر لطريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع الهياكل الداخلية. |

## انظر أيضًا

* فئة [WebRequest](../webrequest/)
* مساحة الاسم [System::Net](../)
* مكتبة [Aspose.Slides](../../)