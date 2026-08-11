---
title: FileWebRequest
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "توفر تنفيذًا للفئة المجردة WebRequest للعمل مع نظام الملفات. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التأكيد. قم دائمًا بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 144
url: /ar/system.net/filewebrequest/
---
## FileWebRequest فئة

توفر تنفيذًا للفئة المجردة [WebRequest](../webrequest/) للعمل مع نظام الملفات. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التأكيد. قم دائمًا بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class FileWebRequest : public System::Net::WebRequest
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [Abort](./abort/)() override | يلغي الطلب الحالي. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يبدأ عملية غير متزامنة للحصول على دفق لكتابة البيانات إلى المورد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يبدأ طلبًا غير متزامنًا للمورد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | ينشئ مثلاً جديدًا من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ مثلاً جديدًا من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ نسخة من [WebRequest](../webrequest/) لمخطط URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | ينشئ مثلاً جديدًا من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ مثلاً جديدًا من الفئة [WebRequest](../webrequest/) باستخدام الـ URI المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | ينتظر حتى تكتمل العملية غير المتزامنة المحددة للحصول على الدفق. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | ينتظر حتى يكتمل الطلب غير المتزامن المحدد للمورد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام صيغ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaN مزدوجة متساوية رغم أن IEC 60559:1989 تنص على أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث تُعتبر NaN مزدوجة متساوية رغم أن IEC 60559:1989 تنص على أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
|  [FileWebRequest](./filewebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ينشئ مثلاً جديدًا. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | يحصل على سياسة التخزين المؤقت. |
| virtual [System::String](../../system/string/) [get_ConnectionGroupName](../webrequest/get_connectiongroupname/)() | يحصل على اسم مجموعة الاتصال. |
| virtual **int64_t** [get_ContentLength](../webrequest/get_contentlength/)() | يحصل على عدد البايتات لبيانات الطلب التي سيتم إرسالها. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | يحصل على نوع MIME للطلب. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](../webrequest/get_credentials/)() | يحصل على معلومات المصادقة المرتبطة بالطلب الحالي. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | يحصل على وكيل HTTP العالمي. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | يحصل على مجموعة رؤوس HTTP. |
| [String](../../system/string/) [get_Method](./get_method/)() override | يحصل على طريقة HTTP. |
| virtual **bool** [get_PreAuthenticate](../webrequest/get_preauthenticate/)() | يحصل على قيمة تشير إلى ما إذا كان يجب مصادقة الطلب مسبقًا. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | يحصل على قائمة البادئات. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](../webrequest/get_proxy/)() | يحصل على وكيل HTTP. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | يعيد URI الطلب. |
| virtual **int32_t** [get_Timeout](../webrequest/get_timeout/)() | يحصل على مقدار الوقت بالمللي ثانية الذي بعده سينتهي مهلة الطلب. |
| virtual **bool** [get_UseDefaultCredentials](../webrequest/get_usedefaultcredentials/)() | يحصل على قيمة تشير إلى ما إذا كانت خاصية 'Credential' مساوية لخاصية 'DefaultCredentials'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تمثيل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](../webrequest/getrequeststream/)() | يعيد الدفق لكتابة البيانات إلى المورد. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | يعيد استجابة الويب المرتبطة بطلب الويب الحالي. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تمثيل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. تمثيل للمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تمثيل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويتيح بناء نسخ الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويتيح بناء نسخ الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | يسجل النسخة [WebRequest](../webrequest/) للـ URI المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | يضبط سياسة التخزين المؤقت. |
| virtual void [set_ConnectionGroupName](../webrequest/set_connectiongroupname/)([System::String](../../system/string/)) | يضبط اسم مجموعة الاتصال. |
| virtual void [set_ContentLength](../webrequest/set_contentlength/)(**int64_t**) | يضبط عدد البايتات لبيانات الطلب التي سيتم إرسالها. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | يضبط نوع MIME للطلب. |
| virtual void [set_Credentials](../webrequest/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | يضبط معلومات المصادقة المرتبطة بالطلب الحالي. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | يضبط وكيل HTTP العالمي. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | يضبط مجموعة رؤوس HTTP. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | يضبط طريقة HTTP. |
| virtual void [set_PreAuthenticate](../webrequest/set_preauthenticate/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب مصادقة الطلب مسبقًا. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | يضبط قائمة البادئات. |
| virtual void [set_Proxy](../webrequest/set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | يضبط وكيل HTTP. |
| void [set_Timeout](./set_timeout/)(int) override | يضبط مقدار الوقت بالمللي ثانية بعده ينتهي مهلة الطلب. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | يضبط مقدار الوقت بالمللي ثانية بعده ينتهي مهلة الطلب. |
| virtual void [set_UseDefaultCredentials](../webrequest/set_usedefaultcredentials/)(**bool**) | يضبط قيمة تشير إلى ما إذا كانت خاصية 'Credential' مساوية لخاصية 'DefaultCredentials'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. يجب عدم استدعائه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدد المراجع المشتركة. يجب عدم استدعائه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تمثيل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. يجب عدم استدعائه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. يجب عدم استدعائه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [WebRequest](../webrequest/)
* النطاق [System::Net](../)
* المكتبة [Aspose.Slides](../../)