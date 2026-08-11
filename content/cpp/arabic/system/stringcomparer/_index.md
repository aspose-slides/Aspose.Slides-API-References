---
title: StringComparer
second_title: Aspose.Slides لـ C++ مرجع API
description: "يقارن السلاسل باستخدام أوضاع مقارنة مختلفة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبدًا بإنشاء مثال من هذا النوع على المكدس أو باستخدام عامل new، حيث سيسفر ذلك عن أخطاء وقت تشغيل و/أو أخطاء تأكيد. دائمًا قم بلف هذه الفئة داخل مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 1288
url: /ar/system/stringcomparer/
---
## StringComparer فئة

Compares strings using different comparison modes. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringComparer : public virtual System::Object,
                       public System::Collections::Generic::IComparer<String>,
                       public System::Collections::Generic::IEqualityComparer<String>
```

## الطرق

| Method | Description |
| --- | --- |
| int [Compare](./compare/)([args_type](./args_type/), [args_type](./args_type/)) const override | يقارن سلسلتين باستخدام الإعدادات الحالية. |
| static [StringComparerPtr](../stringcomparerptr/) [Create](./create/)(const [System::SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **bool**) | ينشئ مقارنًا خاصًا بالثقافة. |
| **bool** [Equals](./equals/)([String](../string/), [String](../string/)) const override | يتحقق مما إذا كانت سلسلتان متساويتان باستخدام الإعدادات الحالية. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا للمواصفة IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار NaNين متساويين رغم أنه وفقًا للمواصفة IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | للغرض الداخلي فقط. |
| static [StringComparerPtr](../stringcomparerptr/) [get_CurrentCulture](./get_currentculture/)() | كائن وحيد لمقارن الثقافة الحالية. |
| static [StringComparerPtr](../stringcomparerptr/) [get_CurrentCultureIgnoreCase](./get_currentcultureignorecase/)() | كائن وحيد لمقارن الثقافة الحالية غير حسّاس لحالة الأحرف. |
| static [StringComparerPtr](../stringcomparerptr/) [get_InvariantCulture](./get_invariantculture/)() | كائن وحيد لمقارن الثقافة غير المتغيرة. |
| static [StringComparerPtr](../stringcomparerptr/) [get_InvariantCultureIgnoreCase](./get_invariantcultureignorecase/)() | كائن وحيد لمقارن الثقافة غير المتغيرة غير حسّاس لحالة الأحرف. |
| static [StringComparerPtr](../stringcomparerptr/) [get_Ordinal](./get_ordinal/)() | كائن وحيد لمقارن ترتيبي. |
| static [StringComparerPtr](../stringcomparerptr/) [get_OrdinalIgnoreCase](./get_ordinalignorecase/)() | كائن وحيد لمقارن ترتيبي غير حسّاس لحالة الأحرف. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يعيد بنية عداد المرجع المرتبط بالكائن. |
| int [GetHashCode](./gethashcode/)([String](../string/)) const override | يعيد رمز التجزئة للسلسلة. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يعيد النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثالًا للنوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيّئ جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيّئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يُقلّص عداد المرجع المشترك بالقيمة المحددة. |
|  [RTTI_INFO_TEMPLATE_CLASS](../../system.collections.generic/iequalitycomparer/rtti_info_template_class/)([System::Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<T\>, System::BaseTypesInfo\<[System::Object](../object/)\>) | معلومات RTTI. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يعيد القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | يُقلّص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | نظير طريقة C# [Object.ToString()](../object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ينفّذ بناء C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | يُقلّص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## الأنواع المعرفة

| التعريف | الوصف |
| --- | --- |
| [args_type](./args_type/) | نوع الوسيط. |

## انظر أيضًا

* الفئة [Object](../object/)
* الفئة [IComparer](../../system.collections.generic/icomparer/)
* الفئة [IEqualityComparer](../../system.collections.generic/iequalitycomparer/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)