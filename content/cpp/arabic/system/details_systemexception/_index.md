---
title: Details_SystemException
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "فئة أساسية للفئات التي تمثل الاستثناءات النظامية (بدلاً من الاستثناءات التطبيقية). لا تنشئ أمثلة من هذه الفئة يدويًا. استخدم فئة SystemException بدلاً من ذلك. لا تقم أبدًا بلف مثيلات فئة SystemException داخل System::SmartPtr."
type: docs
weight: 703
url: /ar/system/details_systemexception/
---
## Details_SystemException فئة


فئة أساسية للفئات التي تمثل الاستثناءات النظامية (وليس التطبيقية). لا تقم بإنشاء أمثلة من هذه الفئة يدويًا. استخدم فئة SystemException بدلاً من ذلك. لا تقم بتغليف مثيلات فئة SystemException داخل [System::SmartPtr](../smartptr/).

```cpp
class Details_SystemException : public System::Details_Exception
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانين متساويين رغم أنه وفقًا لـ IEC 60559:1989 NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانين متساويين رغم أنه وفقًا لـ IEC 60559:1989 NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | إرجاع قاموس ببيانات استثناء مخصصة. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | إرجاع قيمة عدد صحيح 32-bit وهي رمز HRESULT المرتبط بالاستثناء الممثَل بالكيان الحالي. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | إرجاع مرجع إلى الكائن الذي يمثل الاستثناء الداخلي. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | إرجاع السلسلة التي تحتوي على وصف الخطأ. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | إرجاع السلسلة التي تحتوي على تتبع المكدس. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | إرجاع نسخة من كائن Exception الذي يمثل الاستثناء الأكثر داخلًا. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | الحصول على بنية بيانات عدّاد المرجع المرتبط بالكيان. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | مشابه لطريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | الحصول على النوع الفعلي للكيان. مشابه لاستدعاء C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | تنفيذ عبارة القفل C# lock() . استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | مشابه لطريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | إنشاء كائن. يهيء جميع هياكل البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل إسناد. لا ينسخ أي شيء فعليًا، بل يهيء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع قيم بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../object/referenceequals/) في حالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يخفض عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | تعيين HRESULT، قيمة عددية مشفّرة تُعطى لاستثناء معين. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | تعيين الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../object/sharedcount/)() const | الحصول على القيمة الحالية لعدد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | زيادة عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | خفض وإرجاع عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | إرجاع تمثيل السلسلة للكيان الحالي. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | تنفيذ إلغاء قفل عبارة C# lock(). استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | زيادة عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | خفض عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | تنفيذ طريقة [what()](../details_exception/what/) التي يستدعيها الصف [ExceptionWrapper](../exceptionwrapper/). بالرغم من أن هذه الفئة لا تُورّث من std::exception، يمكن للفئات المشتقة استخدامها للوصول إلى الأعضاء المحمية/الخاصة لتنفيذ منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../exceptionwrapper/) قد يفسد ذلك المنطق. |
| virtual  [~Object](../object/~object/)() | تدمير الكائن. تحرير جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [Details_Exception](../details_exception/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)