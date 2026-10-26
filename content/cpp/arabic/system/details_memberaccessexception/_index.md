---
title: Details_MemberAccessException
second_title: مرجع API Aspose.Slides للغة C++
description: "يتم إلقاء MemberAccessException عندما يتم محاولة الوصول إلى عضو في فئة غير موجودة أو عندما لا يُسمح بالوصول إلى العضو. لا تقم بإنشاء مثيلات من هذه الفئة يدويًا. استخدم فئة MemberAccessException بدلاً من ذلك. لا تقم أبدًا بلف مثيلات فئة MemberAccessException في System::SmartPtr."
type: docs
weight: 547
url: /ar/system/details_memberaccessexception/
---
## Details_MemberAccessException فئة


يتم إلقاء MemberAccessException عندما يتم محاولة الوصول إلى عضو في فئة غير موجودة أو عندما لا يُسمح بالوصول إلى العضو. لا تقم بإنشاء مثيلات من هذه الفئة يدويًا. استخدم فئة MemberAccessException بدلاً من ذلك. لا تقم أبدًا بلف مثيلات فئة MemberAccessException في [System::SmartPtr](../smartptr/).

```cpp
class Details_MemberAccessException : public System::Details_SystemException
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNانان متساويتين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNانان متساويتين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | إرجاع القاموس مع بيانات الاستثناء المخصصة. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | إرجاع قيمة عدد صحيح 32 بت تمثل رمز HRESULT المرتبط بالاستثناء الممثَّل بواسطة الكائن الحالي. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | إرجاع مرجع إلى الكائن الذي يمثل الاستثناء الداخلي. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | إرجاع السلسلة التي تحتوي على وصف الخطأ. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | إرجاع السلسلة التي تحتوي على تتبع المكدس. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | إرجاع نسخة من كائن Exception الذي يمثل الاستثناء الأكثر داخلية. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | الحصول على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | الحصول على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | تنفيذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | إنشاء كائن. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | يضبط HRESULT، وهو قيمة عددية مشفرة تُعطى لاستثناء معين. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | تعيين المعامل النمطي الـ n't إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضعية الضعيفة. |
| int [SharedCount](../object/sharedcount/)() const | الحصول على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | زيادة عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | خفض وإرجاع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | إرجاع تمثيل السلسلة للكائن الحالي. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | تنفيذ إلغاء قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | زيادة عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | خفض عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | ينفذ طريقة [what()](../details_exception/what/) التي يتم استدعاؤها بواسطة فئة [ExceptionWrapper](../exceptionwrapper/). على الرغم من أن هذه الفئة لا تُورّث من std::exception، يمكن للفئات المشتقة استخدامها للعضوات المحمية/الخاصة لتنفيذ منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../exceptionwrapper/) قد يفسد ذلك المنطق. |
| virtual  [~Object](../object/~object/)() | يدمّر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [Details_SystemException](../details_systemexception/)
* مساحة اسم [System](../)
* مكتبة [Aspose.Slides](../../)