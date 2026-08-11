---
title: Details_TimeoutException
second_title: Aspose.Slides لـ C++ مرجع API
description: "TimeoutException يشير إلى ما إذا كان الوقت المخصص للعملية أو العملية قد انتهى. لا تقم بإنشاء مثيلات هذه الفئة يدويًا. استخدم فئة TimeoutException بدلاً من ذلك. لا تقم أبدًا بلف مثيلات فئة TimeoutException داخل System::SmartPtr."
type: docs
weight: 716
url: /ar/system/details_timeoutexception/
---
## Details_TimeoutException فئة

TimeoutException يشير إلى ما إذا كان الوقت المخصص لعملية أو عملية ما قد انتهى. لا تقم بإنشاء مثيلات هذه الفئة يدوياً. استخدم فئة TimeoutException بدلاً من ذلك. لا تقم أبدًا بلف مثيلات فئة TimeoutException داخل [System::SmartPtr](../smartptr/).

```cpp
class Details_TimeoutException : public System::Details_SystemException
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقاط العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقاط العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | يرجع القاموس مع بيانات الاستثناء المخصصة. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | يرجع قيمة عدد صحيح 32-bit وهو رمز HRESULT المرتبط بالاستثناء الممثل بواسطة الكائن الحالي. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | يرجع مرجعًا إلى الكائن الذي يمثل الاستثناء الداخلي. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | يرجع السلسلة التي تحتوي على وصف الخطأ. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | يرجع السلسلة التي تحتوي على تتبع المكدس. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | يرجع نسخة من كائن Exception الذي يمثل الاستثناء الأكثر داخلية. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../object/gethashcode/). يمكّن تجزئة الكائنات المخصَّصة. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ينفّذ قفل جملة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يمكّن استنساخ الأنواع المخصَّصة. |
| [Object](../object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../object/object/)([Object](../object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن إنشاء نسخ من الفئات الفرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | يضبط HRESULT، وهو قيمة رقمية مُرمَّزة تُعيَّن إلى استثناء معين. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط المتغيّر النمطي الـ n كإشارة ضعيفة (بدلاً من shared). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | يرجع تمثيل السلسلة للكائن الحالي. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ينفّذ إلغاء قفل جملة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | ينفّذ طريقة [what()](../details_exception/what/) التي تستدعيها فئة [ExceptionWrapper](../exceptionwrapper/). على الرغم من أن هذه الفئة لا تُورّث من std::exception، يمكن للفئات المشتقة استخدامها الأعضاء المحمية/الخاصة لتطبيق منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../exceptionwrapper/) قد يكسّر ذلك المنطق. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [Details_SystemException](../details_systemexception/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)