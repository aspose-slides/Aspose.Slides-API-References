---
title: Details_InvalidCastException
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يتم إلقاء استثناء InvalidCastException عندما يتم محاولة عملية تحويل غير صالحة أو تحويل صريح غير صحيح. لا تقم بإنشاء مثيلات لهذه الفئة يدويًا. استخدم فئة InvalidCastException بدلاً من ذلك. لا تقم أبدًا بلف مثيلات فئة InvalidCastException داخل System::SmartPtr."
type: docs
weight: 495
url: /ar/system/details_invalidcastexception/
---
## Details_InvalidCastException فئة


يتم إلقاء استثناء InvalidCastException عند محاولة عملية تحويل غير صالحة أو تحويل صريح غير صحيح. لا تقم بإنشاء مثيلات لهذه الفئة يدويًا. استخدم فئة InvalidCastException بدلاً من ذلك. لا تُغلف مثيلات فئة InvalidCastException داخل [System::SmartPtr](../smartptr/).

```cpp
class Details_InvalidCastException : public System::Details_SystemException
```

## طرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار قيمتي NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار قيمتي NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | يُعيد قاموسًا يحتوي على بيانات استثناء مخصصة. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | يُعيد قيمة عدد صحيح 32-بت وهي رمز HRESULT المرتبط بالاستثناء المُمَثَّل بالكائن الحالي. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | يُعيد إشارة إلى الكائن الذي يمثل الاستثناء الداخلي. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | يُعيد السلسلة النصية التي تحتوي على وصف الخطأ. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | يُعيد السلسلة النصية التي تحتوي على أثر المكدس. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | يُعيد نسخة من كائن Exception الذي يمثل الاستثناء الأكثر داخلاً. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية عداد المراجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ينفذ قفل أمر C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات عن طريق المرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات عن طريق المرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المراجع المشتركة بالقيمة المحددة. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | يعين HRESULT، وهو قيمة عددية مشفرة تُخصص لاستثناء معين. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n كإشارة ضعيفة (بدلاً من مشتركة). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | يُعيد تمثيل السلسلة النصية للكائن الحالي. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ينفذ إلغاء قفل أمر C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | ينفذ طريقة [what()](../details_exception/what/) التي يتم استدعاؤها بواسطة فئة [ExceptionWrapper](../exceptionwrapper/). على الرغم من أن هذه الفئة ليست موروثة من std::exception، يمكن للفئات المشتقة استخدام الأعضاء المحمية/الخاصة لتنفيذ منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../exceptionwrapper/) قد يُكسر ذلك المنطق. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
## انظر أيضًا

* فئة [Details_SystemException](../details_systemexception/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)