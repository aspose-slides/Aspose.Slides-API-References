---
title: WebClientProtocol
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يُستخدم هذا الصنف الأساسي في جميع وكلاء عميل خدمة ويب XML الذين تم إنشاؤهم باستخدام ASP.NET. يجب تخصيص كائنات هذا الصنف باستخدام دالة System::MakeObject() فقط. لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، حيث سيتسبب ذلك في أخطاء وقت تشغيل و/أو أخطاء تأكيد. احرص دائماً على تغليف هذا الصنف في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 144
url: /ar/system.web.services.protocols/webclientprotocol/
---
## فئة WebClientProtocol

هذه الفئة الأساسية تُستخدم في جميع وكلاء عميل خدمة XML [Web](../../system.web/) الذين تم إنشاؤهم باستخدام ASP.NET. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء تشغيلية و/أو أخطاء تأكيد. احرص دائماً على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class WebClientProtocol : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [Abort](./abort/)() | يلغى الطلب. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام صفة [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر NaNان متساويتين على الرغم من أن المعيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة نقطية عائمة بأسلوب C# حيث تُعتبر NaNان متساويتين على الرغم من أن المعيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() | يحصل على اسم مجموعة الاتصال. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](./get_credentials/)() | يحصل على معلومات المصادقة. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() | يحصل على قيمة تُظهر ما إذا كان التوثيق المسبق مفعلاً. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](./get_requestencoding/)() | يحصل على الترميز المستخدم في طلبات العميل. |
| **int32_t** [get_Timeout](./get_timeout/)() | يحصل على فترة الانتظار قبل انتهاء مهلة الطلب. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](./get_uri/)() | يحصل على عنوان URI لخدمة XML [Web](../../system.web/). |
| [String](../../system/string/) [get_Url](./get_url/)() | يحصل على عنوان URL لخدمة XML [Web](../../system.web/). |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | يحصل على قيمة تُظهر ما إذا كانت الخاصية 'Credential' مساوية للخاصية 'DefaultCredentials'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة [Object.GetHashCode()](../../system/object/gethashcode/) في C#. يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير لاستدعاء [System.Object.GetType()](../../system/object/gettype/) في C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير للمشغل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفّذ عملية القفل في عبارة lock() في C#. يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة [Object.MemberwiseClone()](../../system/object/memberwiseclone/) في C#. يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يقوم بإنشاء كائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([String](../../system/string/)) | يضبط اسم مجموعة الاتصال. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | يضبط معلومات المصادقة. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) | يضبط قيمة تُظهر ما إذا كان التوثيق المسبق مفعلاً. |
| void [set_RequestEncoding](./set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | يضبط الترميز المستخدم في طلبات العميل. |
| void [set_Timeout](./set_timeout/)(**int32_t**) | يضبط فترة الانتظار قبل انتهاء مهلة الطلب. |
| void [set_Uri](./set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يضبط URI لخدمة XML [Web](../../system.web/). |
| void [set_Url](./set_url/)([String](../../system/string/)) | يضبط URL لخدمة XML [Web](../../system.web/). |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | يضبط قيمة تُظهر ما إذا كانت الخاصية 'Credential' مساوية للخاصية 'DefaultCredentials'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n كمرجع ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلّ ويُعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة [Object.ToString()](../../system/object/tostring/) في C#. يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية typeof([System.Object](../../system/object/)) في C#. |
| void [Unlock](../../system/object/unlock/)() | ينفّذ عملية إلغاء القفل في عبارة lock() في C#. يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلّ عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Web::Services::Protocols](../)
* المكتبة [Aspose.Slides](../../)