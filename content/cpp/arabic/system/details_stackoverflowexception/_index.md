---
title: Details_StackOverflowException
second_title: مرجع API Aspose.Slides للغة C++
description: "يتم إلقاء استثناء StackOverflowException عندما يتجاوز مكدس تنفيذ الخيط سعه. لا تقم بإنشاء كائنات من هذه الفئة يدويًا. استخدم فئة StackOverflowException بدلاً من ذلك. لا تقم أبدًا بلف كائنات فئة StackOverflowException داخل System::SmartPtr."
type: docs
weight: 690
url: /ar/system/details_stackoverflowexception/
---
## فئة Details_StackOverflowException

StackOverflowException تُطرح عندما يتجاوز مكدس تنفيذ الخيط سعة التخزين. لا تقم بإنشاء كائنات من هذه الفئة يدويًا. استخدم فئة StackOverflowException بدلاً من ذلك. لا تُغلف كائنات فئة StackOverflowException داخل [System::SmartPtr](../smartptr/).

```cpp
class Details_StackOverflowException : public System::Details_SystemException
```

## الطرق

| طريقة | وصف |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطة عائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يُعَد NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطة عائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يُعَد NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | يرجع قاموسًا ببيانات استثناء مخصصة. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | يرجع قيمة عددية 32-بت تمثل رمز HRESULT المرتبط بالاستثناء الممثل بواسطة الكائن الحالي. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | يرجع مرجعًا إلى الكائن الذي يمثل الاستثناء الداخلي. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | يرجع السلسلة التي تحتوي على وصف الخطأ. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | يرجع السلسلة التي تحتوي على تتبع المكدس. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | يرجع نسخة من كائن Exception الذي يمثل الاستثناء الأكثر داخلية. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ينفذ قفل تعبير C# lock(). يُستدعى مباشرةً أو يستخدم كائن الحارس [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بواسطة المرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بواسطة المرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | يضبط HRESULT، قيمة عددية مشفرة تُعطى لاستثناء محدد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | يرجع تمثيل السلسلة للكائن الحالي. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ينفذ إلغاء القفل لتعبير C# lock(). يُستدعى مباشرةً أو يستخدم كائن الحارس [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعمل المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual const char * [what](../details_exception/what/)() const | ينفذ الطريقة [what()](../details_exception/what/) التي تستدعيها الفئة [ExceptionWrapper](../exceptionwrapper/). بالرغم من أن هذه الفئة لا تُورّث من std::exception، يمكن للفئات المشتقة استخدامها الأعضاء المحمية/الخاصة لتنفيذ منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../exceptionwrapper/) قد يكسر ذلك المنطق. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Details_SystemException](../details_systemexception/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)