---
title: FtpWebRequest
second_title: مرجع API لـ Aspose.Slides لـ C++
description: تنفيذ عميل بروتوكول نقل الملفات (FTP). فئة تجريبية تجعل من الممكن ربط الشفرة المترجمة بمراجع FtpWebRequest، لكن دون تنفيذها. لا تحتوي على أي أعضاء تم تنفيذهم بصورة صحيحة.
type: docs
weight: 170
url: /ar/system.net/ftpwebrequest/
---
## FtpWebRequest فئة


Implements a File Transfer Protocol (FTP) client. Dummy class making it possible linking translated code with [FtpWebRequest](./) references, but not executing it. Contains no properly implemented members.

```cpp
class FtpWebRequest : public System::Net::WebRequest
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [Abort](../webrequest/abort/)() | يلغي الطلب الحالي. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](../webrequest/begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبدأ عملية غير متزامنة للحصول على تدفق لكتابة البيانات إلى المورد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](../webrequest/begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبدأ طلبًا غير متزامن للمورد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | ينشئ مثيلًا جديدًا من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ مثيلًا جديدًا من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ نسخةً من [WebRequest](../webrequest/) للمخطط URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | ينشئ مثيلًا جديدًا من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ مثيلًا جديدًا من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](../webrequest/endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى يكتمل العملية غير المتزامنة المحددة للحصول على تدفق. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](../webrequest/endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى يكتمل الطلب غير المتزامن المحدد للمورد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات وفق قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN متساوية مع NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN متساوية مع NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | يحصل على سياسة التخزين المؤقت. |
| virtual [System::String](../../system/string/) [get_ConnectionGroupName](../webrequest/get_connectiongroupname/)() | يحصل على اسم مجموعة الاتصال. |
| virtual **int64_t** [get_ContentLength](../webrequest/get_contentlength/)() | يحصل على عدد البايتات لبيانات الطلب التي سيتم إرسالها. |
| virtual [String](../../system/string/) [get_ContentType](../webrequest/get_contenttype/)() | يحصل على نوع MIME للطلب. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](../webrequest/get_credentials/)() | يحصل على معلومات المصادقة المرتبطة بالطلب الحالي. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | يحصل على بروكسي HTTP العالمي. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](../webrequest/get_headers/)() | يحصل على مجموعة رؤوس HTTP. |
| virtual [String](../../system/string/) [get_Method](../webrequest/get_method/)() | يحصل على طريقة HTTP. |
| virtual **bool** [get_PreAuthenticate](../webrequest/get_preauthenticate/)() | يحصل على قيمة تشير إلى ما إذا كان يجب المصادقة المسبقة للطلب. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | يحصل على قائمة البادئات. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](../webrequest/get_proxy/)() | يحصل على بروكسي HTTP. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](../webrequest/get_requesturi/)() | يرجع URI الطلب. |
| virtual **int32_t** [get_Timeout](../webrequest/get_timeout/)() | يحصل على مقدار الوقت بالملي ثانية الذي سينتهي بعده مهلة الطلب. |
| virtual **bool** [get_UseDefaultCredentials](../webrequest/get_usedefaultcredentials/)() | يحصل على قيمة تشير إلى ما إذا كانت الخاصية 'Credential' مساوية للخاصية 'DefaultCredentials'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](../webrequest/getrequeststream/)() | يرجع التدفق لكتابة البيانات إلى المورد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](../webrequest/getresponse/)() | يرجع استجابة الويب المرتبطة بالطلب الحالي. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا من النوع المحدد بـ targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ العبارة C# lock() لقفل الكائن. استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع قيم بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | يسجل النسخة [WebRequest](../webrequest/) للمخطط URI المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | يضبط سياسة التخزين المؤقت. |
| virtual void [set_ConnectionGroupName](../webrequest/set_connectiongroupname/)([System::String](../../system/string/)) | يضبط اسم مجموعة الاتصال. |
| virtual void [set_ContentLength](../webrequest/set_contentlength/)(**int64_t**) | يضبط عدد البايتات لبيانات الطلب التي سيتم إرسالها. |
| virtual void [set_ContentType](../webrequest/set_contenttype/)([String](../../system/string/)) | يضبط نوع MIME للطلب. |
| virtual void [set_Credentials](../webrequest/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | يضبط معلومات المصادقة المرتبطة بالطلب الحالي. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | يضبط بروكسي HTTP العالمي. |
| virtual void [set_Headers](../webrequest/set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) | يضبط مجموعة رؤوس HTTP. |
| virtual void [set_Method](../webrequest/set_method/)([String](../../system/string/)) | يضبط طريقة HTTP. |
| virtual void [set_PreAuthenticate](../webrequest/set_preauthenticate/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب المصادقة المسبقة للطلب. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | يضبط قائمة البادئات. |
| virtual void [set_Proxy](../webrequest/set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | يضبط بروكسي HTTP. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | يضبط مقدار الوقت بالملي ثانية الذي سينتهي بعده مهلة الطلب. |
| virtual void [set_UseDefaultCredentials](../webrequest/set_usedefaultcredentials/)(**bool**) | يضبط قيمة تشير إلى ما إذا كانت الخاصية 'Credential' مساوية للخاصية 'DefaultCredentials'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضع وسيط القالب n كمرجع ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ العبارة C# lock() لإلغاء القفل. استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [WebRequest](../webrequest/)
* النطاق [System::Net](../)
* المكتبة [Aspose.Slides](../../)