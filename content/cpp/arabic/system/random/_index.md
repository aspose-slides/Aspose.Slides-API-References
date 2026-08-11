---
title: Random
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل مولد أعداد عشوائية شبه عشوائية. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject() function. لا تقم مطلقًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام العامل new، حيث سيتسبب ذلك في أخطاء وقت تشغيل و/أو أعطال تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr pointer واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 1184
url: /ar/system/random/
---
## فئة عشوائية


يمثل مولد أعداد عشوائية شبه عشوائي. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../makeobject/). لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت تشغيل و/أو أعطال في التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class Random : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة نقطية عائمة بأسلوب C# حيث يُعتبر NaNان من نوعين NaN متساوين بالرغم من أنه وفقًا لـ IEC 60559:1989 NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة نقطية مزدوجة بأسلوب C# حيث يُعتبر NaNان من نوعين NaN متساوين بالرغم من أنه وفقًا لـ IEC 60559:1989 NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مماثل للمشغل 'is' في C#. |
| **bool** [IsNull](./isnull/)() const | دائمًا يُعيد false. |
| void [Lock](../object/lock/)() | ينفّذ قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| virtual **int32_t** [Next](./next/)() | يعيد عددًا عشوائيًا غير سالب أقل من القيمة القصوى int32. |
| virtual **int32_t** [Next](./next/)(**int32_t**) | يعيد عددًا عشوائيًا غير سالب أقل من الحد الأقصى المحدد. |
| virtual **int32_t** [Next](./next/)(**int32_t**, **int32_t**) | يعيد عددًا عشوائيًا ضمن النطاق المحدد. |
| virtual void [NextBytes](./nextbytes/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | يملء عناصر مصفوفة البايتات المحددة بأعداد عشوائية. |
| virtual **double** [NextDouble](./nextdouble/)() | يعيد عددًا عشوائيًا بين 0.0 و 1.0. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
|  [Random](./random/)() | يهيئ نسخة جديدة باستخدام قيمة بذرة افتراضية تعتمد على الوقت. |
|  [Random](./random/)(**int32_t**) | يهيئ نسخة جديدة من الفئة [System.Random](./) باستخدام قيمة البذرة المحددة. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n ليكون مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | يقلل ويُعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ينفذ بناء C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | ينفذ إلغاء قفل جملة C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## ملاحظات



```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // احصل على رقم شهر عشوائي واطبعه.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // املأ المصفوفة بأعداد عشوائية.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // اطبع المصفوفة.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
مثال الشيفرة هذا ينتج المخرجات التالية:
Month: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## انظر أيضًا

* الفئة [Object](../object/)
* مساحة الاسم [System](../)
* المكتبة [Aspose.Slides](../../)