---
title: Details_ReflectionTypeLoadException
second_title: مرجع API Aspose.Slides للغة C++
description: "يتم إطلاق استثناء ReflectionTypeLoadException من قبل طريقة Module.GetTypes إذا فشل تحميل أي من الفئات في وحدة. لا تقم بإنشاء نسخ من هذه الفئة يدويًا. استخدم فئة ReflectionTypeLoadException بدلاً من ذلك. لا تقم أبدًا بلف نسخ فئة ReflectionTypeLoadException داخل System::SmartPtr."
type: docs
weight: 66
url: /ar/system.reflection/details_reflectiontypeloadexception/
---
## Details_ReflectionTypeLoadException فئة

ReflectionTypeLoadException يتم إطلاقه من قبل طريقة Module.GetTypes إذا فشل تحميل أي من الفئات في وحدة. لا تقم بإنشاء نسخ من هذه الفئة يدويًا. استخدم فئة ReflectionTypeLoadException بدلاً من ذلك. لا تقم أبدًا بلف نسخ فئة ReflectionTypeLoadException داخل [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_ReflectionTypeLoadException : public System::Details_Exception
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة بنقطة عائمة بأسلوب C# حيث تُعتبر NaNان اثنان متساويتين على الرغم من أن معيار IEC 60559:1989 يُشير إلى أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة بنقطة عائمة بأسلوب C# حيث تُعتبر NaNان اثنان متساويتين على الرغم من أن معيار IEC 60559:1989 يُشير إلى أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | يرجع قاموسًا يحتوي على بيانات استثناء مخصصة. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | يرجع قيمة عدد صحيح 32-بت تمثل رمز HRESULT المرتبط بالاستثناء الذي يمثله الكائن الحالي. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | يرجع مرجعًا إلى الكائن الذي يمثل الاستثناء الداخلي. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::Exception](../../system/exception/)\> [get_LoaderExceptions](./get_loaderexceptions/)() const | يرجع الاستثناءات التي تسببت في هذا الاستثناء. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | يرجع السلسلة التي تحتوي على وصف الخطأ. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | يرجع السلسلة التي تحتوي على تتبع المكدس. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::TypeInfo](../../system/typeinfo/)\> [get_Types](./get_types/)() const | يرجع معلومات النوع لأسباب الاستثناء. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | يرجع نسخة من كائن Exception الذي يمثل الاستثناء الداخلي الأكثر عمقًا. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | يضبط HRESULT، وهو قيمة رقمية مُرمّزة تُعيّن لاستثناء معين. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | يرجع تمثيل السلسلة للكائن الحالي. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل جملة C# lock(). استدعِه مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | ينفذ طريقة [what()](../../system/details_exception/what/) التي تُستدعى من قبل الفئة [ExceptionWrapper](../../system/exceptionwrapper/). على الرغم من أن هذه الفئة لا ترث من std::exception، يمكن للفئات المشتقة استخدام الأعضاء المحمية/الخاصة لتنفيذ منطقتها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../../system/exceptionwrapper/) قد يُكسر هذه المنطق. |
| virtual [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [Details_Exception](../../system/details_exception/)
* مساحة الاسم [System::Reflection](../)
* مكتبة [Aspose.Slides](../../)