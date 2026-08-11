---
title: ProcessStartInfo
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: "يصف معلمات بدء العملية. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() . لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغِل new، لأنه سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 40
url: /ar/system.diagnostics/processstartinfo/
---
## ProcessStartInfo فئة

يصف معلمات بدء العملية. يجب أن يتم تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبدًا بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيؤدي إلى أخطاء وقت التشغيل أو أخطاء تأكيد. دائمًا غلف هذه الفئة إلى مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class ProcessStartInfo : public System::Object
```

## الطرق

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة نقطية بنمط C# حيث يُعتبر NaNانان متساويين بالرغم من أنه وفقًا لـ IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة نقطية بنمط C# حيث يُعتبر NaNانان متساويين بالرغم من أنه وفقًا لـ IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [String](../../system/string/) [get_Arguments](./get_arguments/)() const | يسترجع معلمات العملية. |
| **bool** [get_CreateNoWindow](./get_createnowindow/)() const | يسترجع الخاصية NoWindow. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [get_EnvironmentVariables](./get_environmentvariables/)() const | يسترجع متغيرات بيئة العملية. |
| [String](../../system/string/) [get_FileName](./get_filename/)() const | يسترجع اسم ملف العملية. |
| **bool** [get_RedirectStandardError](./get_redirectstandarderror/)() const | يسترجع الخاصية RedirectStandardError. |
| **bool** [get_RedirectStandardInput](./get_redirectstandardinput/)() const | يسترجع الخاصية RedirectStandardInput. |
| **bool** [get_RedirectStandardOutput](./get_redirectstandardoutput/)() const | يسترجع الخاصية RedirectStandardOutput. |
| **bool** [get_UseShellExecute](./get_useshellexecute/)() const | يسترجع الخاصية UseShellExecute. |
| [ProcessWindowStyle](../processwindowstyle/) [get_WindowStyle](./get_windowstyle/)() const | يسترجع نمط النافذة. |
| [String](../../system/string/) [get_WorkingDirectory](./get_workingdirectory/)() const | يسترجع دليل العمل للعملية. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يسترجع بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يسترجع النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
|  [ProcessStartInfo](./processstartinfo/)() | ينشئ كائن معلومات بدء فارغ. |
|  [ProcessStartInfo](./processstartinfo/)(const [String](../../system/string/)\&) | ينشئ كائن معلومات بدء. |
|  [ProcessStartInfo](./processstartinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينشئ كائن معلومات بدء. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) للحالة التي تكون فيها السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Arguments](./set_arguments/)(const [String](../../system/string/)\&) | يضبط معلمات العملية. |
| void [set_CreateNoWindow](./set_createnowindow/)(**bool**) | يضبط الخاصية NoWindow. |
| void [set_FileName](./set_filename/)(const [String](../../system/string/)\&) | يضبط اسم ملف العملية. |
| void [set_RedirectStandardError](./set_redirectstandarderror/)(**bool**) | يضبط الخاصية RedirectStandardError. |
| void [set_RedirectStandardInput](./set_redirectstandardinput/)(**bool**) | يضبط الخاصية RedirectStandardInput. |
| void [set_RedirectStandardOutput](./set_redirectstandardoutput/)(**bool**) | يضبط الخاصية RedirectStandardOutput. |
| void [set_UseShellExecute](./set_useshellexecute/)(**bool**) | يضبط الخاصية UseShellExecute. |
| void [set_WindowStyle](./set_windowstyle/)([ProcessWindowStyle](../processwindowstyle/)) | يضبط نمط النافذة. |
| void [set_WorkingDirectory](./set_workingdirectory/)(const [String](../../system/string/)\&) | يضبط دليل العمل للعملية. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النموذجي رقم n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يسترجع القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحريّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [System::Diagnostics](../)
* المكتبة [Aspose.Slides](../../)