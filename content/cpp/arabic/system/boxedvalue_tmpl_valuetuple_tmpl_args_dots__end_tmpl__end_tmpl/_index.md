---
title: BoxedValue< ValueTuple< Args... > >
second_title: مرجع API لـ Aspose.Slides للـ C++
description: نسخة معبأة من مجموعة القيم.
type: docs
weight: 118
url: /ar/system/boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/
---
## BoxedValue< ValueTuple< Args... > > فئة

نسخة معبأة من مجموعة القيم.

```cpp
template<typename...>class BoxedValue< ValueTuple< Args... > > : public System::Runtime::CompilerServices::ITuple
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| الاسم | أنواع عناصر مجموعة Args. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const [ValueT](../valuetuple/)\&) | ينشئ كائن [BoxedValue](../boxedvalue/) يمثل القيمة المحددة المعبأة. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | يحدد مساواة القيم المعبأة التي يمثلها الكائن الحالي والكائن المحدد. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع على نمط C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانين مساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانين مساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| int [GetHashCode](./gethashcode/)() const override | يرجع رمز تجزئة للكائن الحالي. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | يحصل على النوع الفعلي للكائن. |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | يرجع العنصر في الموضع المحدد. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل مثالًا لنوع موصوف بواسطة targetType. مكافئ لمعامل 'is' في C#. |
| **bool** [is](./is/)() const | يحدد ما إذا كان نوع القيمة المعبأة التي يمثلها الكائن الحالي هو **V**. |
| void [Lock](../object/lock/)() | ينفذقفل العبارة C# lock(). استدع مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | مكافئ لطريقة C# [Object.MemberwiseClone()](../object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../object/object/)([Object](../object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعياً كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصص [Object::ReferenceEquals](../object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n كمؤشر ضعيف (بدلًا من المشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../object/sharedcount/)() const | يحصل على القيمة الحالية للعداد المرجعي المشترك. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | يقلل عداد المرجع المشترك ويعيده. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | يرجع تمثيل السلسلة للقيمة المعبأة. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ينفذ بنية C# typeof([System.Object](../object/)). |
| const [ValueT](../valuetuple/)\& [unbox](./unbox/)() const | يفك التجميع عن القيمة المعبأة. |
| void [Unlock](../object/unlock/)() | ينفذ فك القفل لعبارة C# lock(). استدع مباشرة أو استخدم كائن الحراسة [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [ITuple](../../system.runtime.compilerservices/ituple/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)