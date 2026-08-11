---
title: Details_ExternalException
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "نوع الاستثناء الأساسي لجميع استثناءات تفاعل COM واستثناءات معالجة الاستثناءات المهيكلة (SEH). لا تقم بإنشاء مثيلات من هذه الفئة يدويًا. استخدم فئة ExternalException بدلاً منها. لا تقم بتغليف مثيلات فئة ExternalException في System::SmartPtr."
type: docs
weight: 1
url: /ar/system.runtime.interopservices/details_externalexception/
---
## Details_ExternalException فئة

النوع الأساسي للاستثناءات لجميع استثناءات تفاعل COM واستثناءات معالجة الاستثناءات المهيكلة (SEH). لا تقم بإنشاء مثيلات من هذه الفئة يدويًا. استخدم فئة ExternalException بدلاً منها. لا تقم بتغليف مثيلات فئة ExternalException في [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_ExternalException : public System::Details_ExceptionWithErrorCode<Details_SystemException>
```

## الطرق

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يُحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN لا تكون مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يُحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر قيمتا NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 فإن NaN لا تكون مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | يرجع قاموسًا يحتوي على بيانات استثناء مخصصة. |
| virtual **int32_t** [get_ErrorCode](../../system/details_exceptionwitherrorcode/get_errorcode/)() const | يحصل على قيمة HRESULT للخطأ. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | يرجع قيمة صحيحة 32-بت تمثل رمز HRESULT المرتبط بالاستثناء الممثل بواسطة الكائن الحالي. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | يرجع إشارة إلى الكائن الذي يمثل الاستثناء الداخلي. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwitherrorcode/get_message/)() const override |  |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | يرجع السلسلة التي تحتوي على أثر المكدس. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | يرجع نسخة من كائن Exception الذي يمثل الاستثناء الداخلي الأكثر تعمقًا. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يُمكّن من تجزئة الكائنات المخصصة. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | ينفذ عملية القفل في عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يُمكّن من استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن بناء النسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن بناء النسخ من الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | يضبط HRESULT، وهو قيمة عددية مشفرة تُعيّن لاستثناء معين. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n مؤشرًا ضعيفًا (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | يرجع تمثيل السلسلة للكائن الحالي. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | ينفذ عملية إلغاء القفل في عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الweak. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الweak. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | ينفذ طريقة [what()](../../system/details_exception/what/) التي تُستدعى من فئة [ExceptionWrapper](../../system/exceptionwrapper/). على الرغم من أن هذه الفئة لا تُورّث من std::exception، يمكن للفئات المشتقة استخدام الأعضاء المحمية/الخاصة لتنفيذ منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../../system/exceptionwrapper/) قد يُكسر ذلك المنطق. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [Details_ExceptionWithErrorCode](../../system/details_exceptionwitherrorcode/)
* نطاق [System::Runtime::InteropServices](../)
* مكتبة [Aspose.Slides](../../)