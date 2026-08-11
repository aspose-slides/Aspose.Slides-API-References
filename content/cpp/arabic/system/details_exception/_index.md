---
title: Details_Exception
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل استثناءً. لا تقم بإنشاء مثيلات من هذه الفئة يدويًا. استخدم فئة Exception بدلاً من ذلك. لا تقم أبدًا بلف مثيلات فئة Exception داخل System::SmartPtr."
type: docs
weight: 417
url: /ar/system/details_exception/
---
## Details_Exception الفئة


يمثل استثناءً. لا تقم بإنشاء مثيلات من هذه الفئة يدويًا. استخدم فئة Exception بدلًا من ذلك. لا تقم أبدًا بلف مثيلات فئة Exception داخل [System::SmartPtr](../smartptr/).

```cpp
class Details_Exception : public System::Object
```

## الطرق

| Method | Description |
| --- | --- |
| virtual void [DoThrow](./dothrow/)(const [ExceptionPtr](../exceptionptr/)\&) const | يرمي نسخة استثناء مغلفة بواسطة غلاف الاستثناء. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](./get_data/)() | يرجع القاموس مع بيانات الاستثناء المخصص. |
| **int32_t** [get_HResult](./get_hresult/)() const | يرجع قيمة عدد صحيح 32-بت وهي رمز HRESULT المرتبط بالاستثناء الممثل بواسطة الكائن الحالي. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [get_InnerException](./get_innerexception/)() const | يرجع مرجعًا إلى الكائن الذي يمثل الاستثناء الداخلي. |
| virtual [String](../string/) [get_Message](./get_message/)() const | يرجع السلسلة التي تحتوي على وصف الخطأ. |
| virtual [String](../string/) [get_StackTrace](./get_stacktrace/)() const | يرجع السلسلة التي تحتوي على تتبع المكدس. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [GetBaseException](./getbaseexception/)() const | يرجع نسخة من كائن Exception الذي يمثل الاستثناء الأكثر داخلية. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر معامل C# 'is'. |
| void [Lock](../object/lock/)() | ينفذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المتفرعة. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المتفرعة. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](./set_hresult/)(**int32_t**) | يضبط HRESULT، قيمة رقمية مشفرة تُعطى لاستثناء محدد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النوني للقالب كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع الضعيفة. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | يرجع تمثيل السلسلة للكائن الحالي. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ينفذ تركيب C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual const char * [what](./what/)() const | ينفذ طريقة [what()](./what/) التي تستدعيها الفئة [ExceptionWrapper](../exceptionwrapper/). على الرغم من أن هذه الفئة ليست موروثة من std::exception، يمكن للفئات المشتقة استخدامها أعضاء محمية/خاصة لتطبيق منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../exceptionwrapper/) قد يخل بهذا المنطق. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |
## انظر أيضًا

* الفئة [Object](../object/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)