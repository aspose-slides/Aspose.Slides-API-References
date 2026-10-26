---
title: FileSystemInfo
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "الفئة الأساسية لـ FileInfo و DirectoryInfo. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء في الفرضيات. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 300
url: /ar/system.io/filesysteminfo/
---
## FileSystemInfo فئة

الفئة الأساسية لـ [FileInfo](../fileinfo/) و [DirectoryInfo](../directoryinfo/). يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغّل new، لأن ذلك سيؤدي إلى أخطاء زمن التشغيل أو أخطاء في الفرضيات. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class FileSystemInfo : public System::Object
```

## الطرق

| Method | Description |
| --- | --- |
| virtual void [Delete](./delete/)() | يحذف الكيان الذي تمثله الكائن الحالي. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 ينص على أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للغرض الداخلي فقط. |
| virtual void [Finalize](./finalize/)() | لا يفعل شيئًا. |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | يعيد سمات الكيان الذي تمثله الكائن الحالي. |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | يعيد وقت إنشاء الكيان الذي تمثله الكائن الحالي كوقت محلي. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | يعيد وقت إنشاء الكيان الذي تمثله الكائن الحالي كوقت UTC. |
| virtual **bool** [get_Exists](./get_exists/)() | يحدد ما إذا كان الكيان المشار إليه بالمسار الذي تمثله الكائن الحالي موجودًا. |
| [String](../../system/string/) [get_Extension](./get_extension/)() | يعيد امتداد الملف الذي تمثله الكائن الحالي. |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | يعيد الاسم الكامل (بما في ذلك المسار) للكيان الذي تمثله الكائن الحالي. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | يعيد وقت آخر وصول للكيان الذي تمثله الكائن الحالي كوقت محلي. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | يعيد وقت آخر وصول للكيان الذي تمثله الكائن الحالي كوقت UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | يعيد وقت آخر كتابة للكيان الذي تمثله الكائن الحالي كوقت محلي. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | يعيد وقت آخر كتابة للكيان الذي تمثله الكائن الحالي كوقت UTC. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | يعيد اسمًا للكيان الذي تمثله الكائن الحالي. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | التحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعبير C# lock(). استدعِه مباشرة أو استخدم الكائن [LockContext](../../system/lockcontext/) كحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ كل البنى الداخلية للبيانات. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [Refresh](./refresh/)() | يعيد تحديث حالة الكائن الحالي. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد الإشارة المشتركة بالقيمة المحددة. |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | يضبط السمات المحددة على الكيان الذي تمثله الكائن الحالي. |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | يضبط وقت إنشاء الكيان الذي تمثله الكائن الحالي كوقت محلي. |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | يضبط وقت إنشاء الكيان الذي تمثله الكائن الحالي كوقت UTC. |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | يضبط وقت آخر وصول للكيان الذي تمثله الكائن الحالي كوقت محلي. |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | يضبط وقت آخر وصول للكيان الذي تمثله الكائن الحالي كوقت UTC. |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | يضبط وقت آخر كتابة للكيان الذي تمثله الكائن الحالي كوقت محلي. |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | يضبط وقت آخر كتابة للكيان الذي تمثله الكائن الحالي كوقت UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغيّر القالبية الـ n'th إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل تعبير C# lock(). استدعِه مباشرة أو استخدم الكائن [LockContext](../../system/lockcontext/) كحارس. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector بدلًا من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر كل البنى الداخلية للبيانات. |

## أنظر أيضًا

* فئة [Object](../../system/object/)
* مساحة الاسم [System::IO](../)
* مكتبة [Aspose.Slides](../../)