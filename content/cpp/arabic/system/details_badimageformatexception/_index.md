---
title: Details_BadImageFormatException
second_title: مرجع Aspose.Slides للغة C++
description: "الاستثناء الذي يُرمى عندما تكون صورة ملف مكتبة ربط ديناميكي (DLL) أو برنامج قابل للتنفيذ غير صالحة. لا تقم أبداً بإنشاء مثيلات من هذه الفئة يدوياً. استخدم فئة BadImageFormatException بدلاً من ذلك. لا تقم أبداً بلف مثيلات فئة BadImageFormatException داخل System::SmartPtr."
type: docs
weight: 378
url: /ar/system/details_badimageformatexception/
---
## Details_BadImageFormatException فئة

الاستثناء الذي يُطرح عندما تكون صورة الملف لمكتبة الربط الديناميكي (DLL) أو برنامج قابل للتنفيذ غير صالحة. لا تقم أبداً بإنشاء مثيلات من هذه الفئة يدويًا. استخدم فئة BadImageFormatException بدلاً من ذلك. لا تقم أبداً بلف كائنات فئة BadImageFormatException داخل [System::SmartPtr](../smartptr/).

```cpp
class Details_BadImageFormatException : public System::Details_ExceptionWithFilename<Details_SystemException>
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتي NaN متساويتين رغم أن وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتي NaN متساويتين رغم أن وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | غرض داخلي فقط. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | يرجع قاموسًا ببيانات استثناء مخصصة. |
| virtual [String](../string/) [get_FileName](../details_exceptionwithfilename/get_filename/)() const | يحصل على اسم الملف الذي يسبب هذا الاستثناء. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | يرجع قيمة صحيحة 32-بت تمثل رمز HRESULT المرتبط بالاستثناء الممثل بالكائن الحالي. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | يرجع إشارة إلى الكائن الذي يمثل الاستثناء الداخلي. |
| [String](../string/) [get_Message](../details_exceptionwithfilename/get_message/)() const override |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | يرجع السلسلة التي تحتوي على تتبع المكدس. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | يرجع نسخة من كائن Exception الممثل للاستثناء الأكثر داخلًا. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية عداد المراجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](../details_systemexception/gettype/)() const override | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](../details_systemexception/is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | تنفذ قفل عبارة C# lock(). استدعي مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | مكافئ لطريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ نسخة. لا ينسخ شيئًا، بل يهيئ كائنًا جديدًا ويتيح نسخ البنية للأنواع المشتقة. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا، بل يهيئ كائنًا جديدًا ويتيح نسخ البنية للأنواع المشتقة. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | يضبط HRESULT، قيمة عددية مشفرة تُعين إلى استثناء محدد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../string/) [ToString](../details_exceptionwithfilename/tostring/)() const override |  |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../details_systemexception/type/)() |  |
| void [Unlock](../object/unlock/)() | تنفذ إلغاء قفل عبارة C# lock(). استدعي مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | تنفذ طريقة [what()](../details_exception/what/) التي يتم استدعاؤها بواسطة الفئة [ExceptionWrapper](../exceptionwrapper/). بالرغم من أن هذه الفئة لا تُورث من std::exception، يمكن للفئات المشتقة استخدامها للوصول إلى الأعضاء المحمية/الخاصة لتطبيق منطقها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../exceptionwrapper/) قد يخرق ذلك المنطق. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [Details_ExceptionWithFilename](../details_exceptionwithfilename/)
* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)