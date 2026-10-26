---
title: DefaultBoxedValue
second_title: مرجع API Aspose.Slides للـ C++
description: "تنفيذ فئة BoxedValue. يسمح بتعريف تخصيصات BoxingValue دون تكرار الشيفرة المشتركة. يجب إنشاء كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبب أخطاء وقت التشغيل أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 274
url: /ar/system/defaultboxedvalue/
---
## DefaultBoxedValue فئة


[BoxedValue](../boxedvalue/) تنفيذ فئة. يسمح بتعريف تخصيصات BoxingValue دون تكرار الشيفرة المشتركة. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../makeobject/) فقط. لا تقم أبدًا بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبب أخطاء وقت التشغيل أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | يبني مثيلًا جديدًا من فئة [DefaultBoxedValue](./) التي تمثّل القيمة المحددة. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | يحدد مساواة القيم المعبأة التي تمثّلها الكائنات الحالية والمحددة. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانان متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يُعادل NaN أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانان متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يُعادل NaN أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| int [GetHashCode](./gethashcode/)() const override | يعيد قيمة تجزئة (hash code) للكائن الحالي. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | يحصل على النوع الفعلي للكائن. |
| **bool** [is](./is/)() const | يحدد ما إذا كان نوع القيمة المعبأة التي يمثّلها الكائن الحالي هو **V**. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلًا من النوع الموصوف بـ targetType. تماثل عامل 'is' في C#. |
| void [Lock](../object/lock/)() | ينفّذ قفل عبارة lock() في C#. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | تماثل طريقة [Object.MemberwiseClone()](../object/memberwiseclone/) في C#. يتيح استنساخ الأنواع المخصّصة. |
|  [Object](../object/object/)() | يُنشئ كائنًا. يهيّء جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | بناء نسخ. لا ينسخ أي شيء فعليًا، بل يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائنًا من نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n'th كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| [String](../string/) [ToString](./tostring/)() const override | يعيد تمثيل السلسلة للقيمة المعبأة. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ينفّذ بنية C# typeof([System.Object](../object/)). |
| const T\& [unbox](./unbox/)() const | يفك تعبئة القيمة المعبأة. |
| void [Unlock](../object/unlock/)() | ينفّذ فك قفل عبارة lock() في C#. استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضاً

* فئة [Object](../object/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)