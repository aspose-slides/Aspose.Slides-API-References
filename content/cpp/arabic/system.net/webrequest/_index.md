---
title: WebRequest
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل طلب ويب. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() . لا تُنشئ مثلاً من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال تأكيدية. دائمًا ضع هذه الفئة داخل مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط."
type: docs
weight: 508
url: /ar/system.net/webrequest/
---
## فئة WebRequest

يمثل طلب ويب. يجب تخصيص كائنات هذه الفئة فقط باستخدام دالة [System::MakeObject()](../../system/makeobject/). لا تُنشئ مثلاً من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال تأكيدية. ضع دائمًا هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class WebRequest : public virtual System::Object
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual void [Abort](./abort/)() | يلغي الطلب الحالي. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبدأ عملية غير متزامنة للحصول على تدفق لكتابة البيانات إلى المورد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يبدأ طلباً غير متزامن للمورد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](./)\> [Create](./create/)([String](../../system/string/)) | ينشئ مثلاً جديداً من فئة [WebRequest](./) باستخدام العنوان المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](./)\> [Create](./create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ مثلاً جديداً من فئة [WebRequest](./) باستخدام العنوان المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](./)\> [CreateDefault](./createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ نسخة من [WebRequest](./) للمخطط (scheme) المحدد للعنوان. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](./createhttp/)([String](../../system/string/)) | ينشئ مثلاً جديداً من فئة [WebRequest](./) باستخدام العنوان المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](./createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ مثلاً جديداً من فئة [WebRequest](./) باستخدام العنوان المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل العملية غير المتزامنة المحددة للحصول على تدفق. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى يكتمل الطلب غير المتزامن المحدد للمورد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقاط العائمة بأسلوب C# حيث تُعتبر قيمة NaNين متساويتين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقاط العائمة بأسلوب C# حيث تُعتبر قيمة NaNين متساويتين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](./get_cachepolicy/)() | يحصل على سياسة التخزين المؤقت. |
| virtual [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() | يحصل على اسم مجموعة الاتصال. |
| virtual **int64_t** [get_ContentLength](./get_contentlength/)() | يحصل على عدد البايتات من بيانات الطلب التي سيتم إرسالها. |
| virtual [String](../../system/string/) [get_ContentType](./get_contenttype/)() | يحصل على نوع MIME للطلب. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() | يحصل على معلومات المصادقة المرتبطة بالطلب الحالي. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](./get_defaultwebproxy/)() | يحصل على وكيل HTTP العام. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() | يحصل على مجموعة رؤوس HTTP. |
| virtual [String](../../system/string/) [get_Method](./get_method/)() | يحصل على طريقة HTTP. |
| virtual **bool** [get_PreAuthenticate](./get_preauthenticate/)() | يحصل على قيمة تشير إلى ما إذا كان يجب المصادقة المسبقة على الطلب. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](./get_prefixlist/)() | يحصل على قائمة البادئات. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() | يحصل على وكيل HTTP. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() | يعيد عنوان (URI) الطلب. |
| virtual **int32_t** [get_Timeout](./get_timeout/)() | يحصل على مقدار الوقت بالميليثانية الذي سينتهي عنده صلاحية الطلب. |
| virtual **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | يحصل على قيمة تشير إلى ما إذا كانت خاصية 'Credential' مساوية لخاصية 'DefaultCredentials'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مماثلة لطريقة [Object.GetHashCode()](../../system/object/gethashcode/) في C#. تمكّن من تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() | يعيد التدفق لكتابة البيانات إلى المورد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() | يعيد استجابة الويب المرتبطة بطلب الويب الحالي. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة مماثلة لاستدعاء [System.Object.GetType()](../../system/object/gettype/) في C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثلاً للنوع الموصوف بـ targetType. نسخة مماثلة للمشغل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة lock() في C#. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مماثلة لطريقة [Object.MemberwiseClone()](../../system/object/memberwiseclone/) في C#. تمكّن من استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكن من إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكن من إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| static **bool** [RegisterPrefix](./registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | يسجل النسخة [WebRequest](./) للعنوان المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_CachePolicy](./set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | يضبط سياسة التخزين المؤقت. |
| virtual void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) | يضبط اسم مجموعة الاتصال. |
| virtual void [set_ContentLength](./set_contentlength/)(**int64_t**) | يضبط عدد البايتات من بيانات الطلب التي سيتم إرسالها. |
| virtual void [set_ContentType](./set_contenttype/)([String](../../system/string/)) | يضبط نوع MIME للطلب. |
| virtual void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | يضبط معلومات المصادقة المرتبطة بالطلب الحالي. |
| static void [set_DefaultWebProxy](./set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | يضبط وكيل HTTP العام. |
| virtual void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) | يضبط مجموعة رؤوس HTTP. |
| virtual void [set_Method](./set_method/)([String](../../system/string/)) | يضبط طريقة HTTP. |
| virtual void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب المصادقة المسبقة على الطلب. |
| static void [set_PrefixList](./set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | يضبط قائمة البادئات. |
| virtual void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | يضبط وكيل HTTP. |
| virtual void [set_Timeout](./set_timeout/)(**int32_t**) | يضبط مقدار الوقت بالميليثانية الذي سينتهي عنده صلاحية الطلب. |
| virtual void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | يضبط قيمة تشير إلى ما إذا كانت خاصية 'Credential' مساوية لخاصية 'DefaultCredentials'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n ليكون مؤشرًا ضعيفًا (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مماثلة لطريقة [Object.ToString()](../../system/object/tostring/) في C#. تمكّن من تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية typeof([System.Object](../../system/object/)) في C#. |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل عبارة lock() في C#. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الاسم [System::Net](../)
* مكتبة [Aspose.Slides](../../)