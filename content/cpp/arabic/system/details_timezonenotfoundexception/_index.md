---
title: Details_TimeZoneNotFoundException
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "TimeZoneNotFoundException يُرمى عندما لا يتم العثور على معلومات المنطقة الزمنية. لا تقم بإنشاء مثيلات من هذه الفئة يدويًا. استخدم فئة TimeZoneNotFoundException بدلاً من ذلك. لا تقم أبداً بلف مثيلات فئة TimeZoneNotFoundException داخل System::SmartPtr."
type: docs
weight: 729
url: /ar/system/details_timezonenotfoundexception/
---
## Details_TimeZoneNotFoundException فئة

TimeZoneNotFoundException يُرْمى عندما لا يتم العثور على معلومات المنطقة الزمنية. لا تقم بإنشاء كائنات لهذه فئة يدويًا. استخدم فئة TimeZoneNotFoundException بدلاً من ذلك. لا تقم أبدًا بلف كائنات فئة TimeZoneNotFoundException داخل [System::SmartPtr](../smartptr/).

```cpp
class Details_TimeZoneNotFoundException : public System::Details_Exception
```

## الأساليب

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان مساويين رغم أن IEC 60559:1989 تنص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان مساويين رغم أن IEC 60559:1989 تنص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | يُرجّع القاموس الذي يحتوي على بيانات استثناء مخصّصة. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | يُرجّع قيمة عددية من 32 بت تمثل رمز HRESULT المرتبط بالاستثناء الممثّل بواسطة الكائن الحالي. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | يُرجّع إشارة إلى الكائن الذي يمثل الاستثناء الداخلي. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | يُرجّع السلسلة التي تحتوي على وصف الخطأ. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | يُرجّع السلسلة التي تحتوي على تتبع المكدس. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | يُرجّع نسخة من كائن Exception الذي يمثل الاستثناء الداخلي الأكثر. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | نسخة مماثلة لطريقة C# [Object.GetHashCode()](../object/gethashcode/). تمكّن تجزئة الكائنات المخصّصة. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | نسخة مماثلة لطريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). تمكّن استنساخ الأنواع المخصّصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | يضبط HRESULT، وهو قيمة رقمية مشفرة تُعيّن إلى استثناء معين. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشّر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | يُرجّع تمثيل السلسلة للكائن الحالي. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استعمل المؤشرات الذكية أو ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | ينفّذ طريقة [what()](../details_exception/what/) التي تستدعيها فئة [ExceptionWrapper](../exceptionwrapper/). بالرغم من أن هذه الفئة لا تُورّث من std::exception، إلا أن الفئات المشتقة يمكنها استخدام الأعضاء المحمية/الخاصة لتنفيذ منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../exceptionwrapper/) قد يكسّر ذلك المنطق. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Details_Exception](../details_exception/)
* مساحة الاسم [System](../)
* المكتبة [Aspose.Slides](../../)