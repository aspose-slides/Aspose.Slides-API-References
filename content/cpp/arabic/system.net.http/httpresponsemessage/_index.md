---
title: HttpResponseMessage
second_title: Aspose.Slides لـ C++ مرجع API
description: "يمثل رسالة استجابة HTTP. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيتسبب في أخطاء وقت التشغيل أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 118
url: /ar/system.net.http/httpresponsemessage/
---
## HttpResponseMessage فئة

يمثل رسالة استجابة HTTP. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغّل new، لأن ذلك سيؤدي إلى أخطاء في وقت التشغيل أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class HttpResponseMessage : public System::IDisposable
```

## الطرق

| Method | Description |
| --- | --- |
| void [Dispose](./dispose/)() override | يفرغ الكائن الحالي. كما يقوم هذا الأسلوب أيضًا بإفراغ محتوى استجابة HTTP. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpResponseMessage](./)\> [EnsureSuccessStatusCode](./ensuresuccessstatuscode/)() | يفحص رمز الحالة. سيتم إلقاء استثناء HttpRequestException عندما لا ينتمي رمز الحالة إلى 2xx. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقاط عائمة بأسلوب C# حيث تُ considered NaNانين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقاط عائمة بأسلوب C# حيث تُ considered NaNانين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\> [get_Content](./get_content/)() const | يحصل على محتوى استجابة HTTP. |
| [System::SharedPtr](../../system/sharedptr/)\<[Headers::HttpResponseHeaders](../../system.net.http.headers/httpresponseheaders/)\> [get_Headers](./get_headers/)() const | يعيد رؤوس محتوى HTTP. |
| **bool** [get_IsSuccessStatusCode](./get_issuccessstatuscode/)() const | يتحقق مما إذا كان رمز الحالة يشير إلى أن الطلب الذي قدمه العميل قد استُقبل وفُهم وقُبل. |
| [String](../../system/string/) [get_ReasonPhrase](./get_reasonphrase/)() const | يحصل على عبارة السبب (Reason-Phrase) التي يرسلها الخادم مع رمز الحالة. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\> [get_RequestMessage](./get_requestmessage/)() const | يحصل على رسالة طلب HTTP. |
| [HttpStatusCode](../../system.net/httpstatuscode/) [get_StatusCode](./get_statuscode/)() const | يحصل على رمز حالة HTTP. |
| [System::Version](../../system/version/) [get_Version](./get_version/)() const | يحصل على نسخة HTTP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعية المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مقابل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مكافئ لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpResponseMessage](./httpresponsemessage/)() | ينشئ نسخةً جديدةً. |
|  [HttpResponseMessage](./httpresponsemessage/)([HttpStatusCode](../../system.net/httpstatuscode/)) | ينشئ نسخةً جديدةً. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموضّح بـ targetType. مكافئ لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل بيان C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مقابل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Content](./set_content/)([System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\>) | يضبط محتوى استجابة HTTP. |
| void [set_ReasonPhrase](./set_reasonphrase/)([String](../../system/string/)) | يضبط عبارة السبب (Reason-Phrase) التي يرسلها الخادم مع رمز الحالة. |
| void [set_RequestMessage](./set_requestmessage/)([System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\>) | يضبط رسالة طلب HTTP. |
| void [set_StatusCode](./set_statuscode/)([HttpStatusCode](../../system.net/httpstatuscode/)) | يضبط رمز حالة HTTP. |
| void [set_Version](./set_version/)([System::Version](../../system/version/)) | يضبط نسخة HTTP. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط وسيطة القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | [System::Object::ToString](../../system/object/tostring/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل بيان C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحذف جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [IDisposable](../../system/idisposable/)
* نطاق [System::Net::Http](../)
* مكتبة [Aspose.Slides](../../)