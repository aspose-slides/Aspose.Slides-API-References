---
title: Details_AggregateException
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل استثناءً يحتوي على استثناءات داخلية متعددة.
type: docs
weight: 300
url: /ar/system/details_aggregateexception/
---
## Details_AggregateException فئة

Represents an exception that contains multiple inner exceptions.

```cpp
class Details_AggregateException : public System::Details_Exception
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaN متساويتين رغم أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [AggregateException](../aggregateexception/) [Flatten](./flatten/)() | يفكك الاستثناء المجمع عن طريق فك جميع AggregateExceptions المتداخلة إلى قائمة ذات مستوى واحد. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | يرجع القاموس مع بيانات الاستثناء المخصصة. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | يرجع قيمة عدد صحيح 32 بت وهي رمز HRESULT المرتبط بالاستثناء الممثل بواسطة الكائن الحالي. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | يرجع مرجعًا إلى الكائن الذي يمثل الاستثناء الداخلي. |
| **int32_t** [get_InnerExceptionCount](./get_innerexceptioncount/)() | يحصل على عدد الاستثناءات الداخلية الموجودة في هذا الاستثناء المجمع. |
| [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[Exception](../exception/)\>\> [get_InnerExceptions](./get_innerexceptions/)() | يحصل على مجموعة قراءة فقط من الاستثناءات الداخلية. |
| const [ArrayPtr](../arrayptr/)\<[Exception](../exception/)\>\& [get_InternalInnerExceptions](./get_internalinnerexceptions/)() | يرجع المصفوفة الداخلية للاستثناءات الداخلية. |
| [String](../string/) [get_Message](./get_message/)() const override | يتجاوز الرسالة الأساسية لتضمين معلومات مجمعة من جميع الاستثناءات الداخلية. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | يرجع السلسلة التي تحتوي على تتبع المكدس. |
| [Exception](../exception/) [GetBaseException](./getbaseexception/)() const override | يرجع استثناء السبب الجذري عن طريق فك الاستثناءات الداخلية بشكل متكرر. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../object/gettype/). |
| void [Handle](./handle/)(const [Func](../func/)\<[Exception](../exception/), **bool**\>\&) | ينفذ دالة معالج على كل استثناء داخلي ويعيد رمي أي استثناءات غير معالجة. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثيلًا من النوع الموصف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يتهيء جميع هياكل البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ النسخ. لا ينسخ شيئًا، في الواقع، فقط يتهيء كائنًا جديدًا ويتيح نسخ البنى الفرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا، في الواقع، فقط يتهيء كائنًا جديدًا ويتيح نسخ البنى الفرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | يضبط HRESULT، قيمة رقمية مشفرة تُعيّن إلى استثناء معين. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط وسيط القالب الـ n'th كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعدد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | يرجع تمثيل السلسلة للستثناء، بما في ذلك جميع الاستثناءات الداخلية. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ينفذ بناء C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | ينفذ طريقة [what()](../details_exception/what/) التي يتم استدعاؤها من قبل الفئة [ExceptionWrapper](../exceptionwrapper/). على الرغم من أن هذه الفئة ليست موروثة من std::exception، يمكن للفئات المشتقة استخدام الأعضاء المحمية/الخاصة لتنفيذ منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../exceptionwrapper/) قد يكسر هذا المنطق. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## ملاحظات

هذه الفئة تُستخدم عادةً لتجميع عدة استثناءات تحدث متزامنًا، مثلًا في معالجة متوازية أو سيناريوهات تنفيذ مهام غير متزامنة. يسمح للمستخدمين بفحص، أو فك، أو التعامل انتقائيًا مع الاستثناءات المحتواة.

## انظر أيضًا

* فئة [Details_Exception](../details_exception/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)