---
title: RandomNumberGenerator
second_title: Aspose.Slides للغة C++ مرجع API
description: "فئة تجريدية لمولدات الأعداد العشوائية لتوريثها. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التحقق. احزم دائماً هذه الفئة داخل مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 352
url: /ar/system.security.cryptography/randomnumbergenerator/
---
## RandomNumberGenerator فئة

فئة تجريدية لمولدات الأعداد العشوائية لتوريثها. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام operator new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التحقق. احزم دائماً هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كوسيط.

```cpp
class RandomNumberGenerator : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static [System::SharedPtr](../../system/sharedptr/)\<[RandomNumberGenerator](./)\> [Create](./create/)() | ينشئ مثيلاً للتنفيذ الافتراضي لمولد أعداد عشوائية تشفيرية يمكن استخدامه لتوليد بيانات عشوائية. غير مُنفّذ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطة عائمة بأسلوب C# حيث تُعتبر NaN مزدوجة متساوية على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطة عائمة بأسلوب C# حيث تُعتبر NaN مزدوجة متساوية على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا تساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual void [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يملأ عناصر المصفوفة الموجودة ببايتات عشوائية. |
| virtual void [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | يملأ شريحة المصفوفة الموجودة ببايتات عشوائية. |
| virtual void [GetBytes](./getbytes/)(System::Details::ArrayView\<**uint8_t**\>) | يملأ عناصر عرض المصفوفة الموجود ببايتات عشوائية. |
| virtual void [GetBytes](./getbytes/)(System::Details::ArrayView\<**uint8_t**\>, int, int) | يملأ شريحة عرض المصفوفة الموجودة ببايتات عشوائية. |
| void [GetBytes](./getbytes/)(System::Details::StackArray\<**uint8_t**, N\>\&) | يملأ عناصر مصفوفة المكدس الموجودة ببايتات عشوائية. |
| void [GetBytes](./getbytes/)(System::Details::StackArray\<**uint8_t**, N\>\&, int, int) | يملأ شريحة مصفوفة المكدس الموجودة ببايتات عشوائية. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual void [GetNonZeroBytes](./getnonzerobytes/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يملأ عناصر المصفوفة الموجودة ببايتات عشوائية غير صفرية. |
| virtual void [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<**uint8_t**\>) | يملأ عناصر عرض المصفوفة الموجودة ببايتات عشوائية غير صفرية. |
| void [GetNonZeroBytes](./getnonzerobytes/)(System::Details::StackArray\<**uint8_t**, N\>\&) | يملأ عناصر مصفوفة المكدس الموجودة ببايتات عشوائية غير صفرية. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموضح بواسطة targetType. مماثل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِها مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيّء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا يقوم بنسخ أي شيء فعلياً، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا يقوم بنسخ أي شيء فعلياً، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِها مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [Object](../../system/object/)
* نطاق [System::Security::Cryptography](../)
* مكتبة [Aspose.Slides](../../)