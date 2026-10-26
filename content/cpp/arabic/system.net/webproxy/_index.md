---
title: WebProxy
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل خادم وكيل ويب http. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 495
url: /ar/system.net/webproxy/
---
## فئة WebProxy

يمثل خادم وكيل ويب http. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدالات كمعامل.

```cpp
class WebProxy : public System::Net::IWebProxy
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سياق C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين بالرغم من أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | يحصل على عنوان خادم الوكيل الحالي. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_BypassList](./get_bypasslist/)() | يحصل على قائمة العناوين التي لا تستخدم خادم الوكيل. |
| **bool** [get_BypassProxyOnLocal](./get_bypassproxyonlocal/)() | يحصل على قيمة تشير إلى ما إذا كان يجب استخدام خادم الوكيل للعناوين المحلية. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() | يحصل على بيانات الاعتماد التي تُرسل إلى خادم الوكيل للمصادقة. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | يحصل على قيمة تشير إلى ما إذا كان يجب إرسال بيانات الاعتماد الافتراضية مع الطلبات. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebProxy](./)\> [GetDefaultProxy](./getdefaultproxy/)() | يعيد الوكيل الذي يستخدم إعدادات Internet Explorer غير الديناميكية. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة تماثلية لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن من تجزئة الكائنات المخصَّصة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [GetProxy](./getproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يعيد عنوان URI الموكَّل لطلب ويب. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة تماثلية لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بواسطة targetType. نسخة تماثلية لمعامل C# 'is'. |
| virtual **bool** [IsBypassed](./isbypassed/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يفحص ما إذا لم يُستخدم خادم الوكيل للعنوان URI المحدد. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة تماثلية لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن من استنساخ الأنواع المخصَّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيّئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيّئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمراجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمراجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن القيمة بالمراجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Address](./set_address/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يضبط عنوان خادم الوكيل الحالي. |
| void [set_BypassList](./set_bypasslist/)([System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | يضبط قائمة العناوين التي لا تستخدم خادم الوكيل. |
| void [set_BypassProxyOnLocal](./set_bypassproxyonlocal/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب استخدام خادم الوكيل للعناوين المحلية. |
| virtual void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | يضبط بيانات الاعتماد التي تُرسل إلى خادم الوكيل للمصادقة. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | يضبط قيمة تشير إلى ما إذا كان يجب إرسال بيانات الاعتماد الافتراضية مع الطلبات. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتغيير المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة تماثلية لطريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن من تحويل الكائنات المخصَّصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
|  [WebProxy](./webproxy/)() | إنشاء مثيل جديد. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | إنشاء مثيل جديد. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**) | إنشاء مثيل جديد. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | إنشاء مثيل جديد. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | إنشاء مثيل جديد. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **int32_t**) | إنشاء مثيل جديد. |
|  [WebProxy](./webproxy/)([String](../../system/string/)) | إنشاء مثيل جديد. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**) | إنشاء مثيل جديد. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | إنشاء مثيل جديد. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | إنشاء مثيل جديد. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## أنظر أيضًا

* الفئة [IWebProxy](../iwebproxy/)
* النطاق [System::Net](../)
* المكتبة [Aspose.Slides](../../)