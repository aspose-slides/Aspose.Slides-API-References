---
title: DBNull
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل قيمة غير موجودة. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقوم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغّل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال التحقق. احرص دائماً على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 248
url: /ar/system/dbnull/
---
## DBNull فئة


يمثّل قيمة غير موجودة. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../makeobject/) فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغّل new، لأن ذلك سيتسبب في أخطاء وقت التشغيل أو أخطاء التحقق. احرص دائماً على تغليف هذه الفئة في المؤشر [System::SmartPtr](../smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class DBNull : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN مساوية ل NaN رغم أن IEC 60559:1989 لا تعتبر NaN مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN مساوية ل NaN رغم أن IEC 60559:1989 لا تعتبر NaN مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../object/gethashcode/). يتيح تجزئة (hashing) الكائنات المخصّصة. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل نداء C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | يتحقق إذا كان الكائن يمثل نسخة من النوع الموصوف بالـ targetType. تماثل عامل C# 'is'. |
| void [Lock](../object/lock/)() | يطبق عبارة القفل C# lock(). استدعِها مباشرة أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصّصة. |
|  [Object](../object/object/)() | ينشئ الكائن. يهيّء جميع هياكل البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ إنشاء الفئات الفرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ إنشاء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع قيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص خاص لـ [Object::ReferenceEquals](../object/referenceequals/) في حالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص خاص لـ [Object::ReferenceEquals](../object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضع الوسيط القالب رقم n كمؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزداد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../object/tostring/). يتيح تحويل الكائنات المخصّصة إلى سلسلة. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | يطبق بناء C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | يطبق فك القفل لعبارة C# lock(). استدعِها مباشرة أو استخدم كائن الحارس [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزداد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## الحقول

| الحقل | الوصف |
| --- | --- |
| static [Value](./value/) | مؤشر مشترك إلى نسخة من [DBNull](./). |

## انظر أيضًا

* الفئة [Object](../object/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)