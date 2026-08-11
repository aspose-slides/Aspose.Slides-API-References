---
title: IListImplRefType
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "نموذج أولي ينفّذ واجهة System::Collections::IList على كائن System::Collections::Generic::List تنفيذ لأنواع المراجع."
type: docs
weight: 131
url: /ar/system.collections/ilistimplreftype/
---
## IListImplRefType فئة


نموذج أولي ينفّذ الواجهة [System::Collections::IList](../ilist/) على كائن [System::Collections::Generic::List](../../system.collections.generic/list/) تنفيذ لأنواع المراجع.

```cpp
template<typename T>class IListImplRefType : public virtual System::Collections::IList
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| int [Add](./add/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يضيف العنصر إلى نهاية القائمة. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [BoxValue](./boxvalue/)([System::SharedPtr](../../system/sharedptr/)\<T\>) | تحويل مرجع النوع إلى قيمة كائن. |
| void [Clear](./clear/)() override | يحذف جميع العناصر. |
| **bool** [Contains](./contains/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) const override | يتحقق مما إذا كان العنصر موجودًا في القائمة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات وفقًا لسيناريوهات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تعتبر NaN مساوية لبعضها البعض رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تعتبر NaN مساوية لبعضها البعض رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| int [get_Count](./get_count/)() const override | [ICollection.get_Count()](../icollection/get_count/) تنفيذ طرق يحصل على عدد العناصر في المجموعة. |
| virtual **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() const | يحصل على قيمة تشير إلى ما إذا كانت القائمة ذات حجم ثابت. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::IEnumerator](../ienumerator/)\> [GetEnumerator](./getenumerator/)() override | [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) تنفيذ Returns an enumerator that iterates through a collection. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن تجزئة الكائنات المخصّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)(int, int) const override | يحصل على العنصر في الفهرس المحدد. |
|  [IListImplRefType](./ilistimplreftype/)([System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<T\>\>\>) | ينشئ نسخة جديدة من الكائن. |
| int [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) const override | يحصل على فهرس الظهور الأول للعنصر في الحاوية. |
| void [Insert](./insert/)(int, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يدرج العنصر في الموضع المحدد، محوّلاً العناصر الأخرى. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعبير C# lock() . استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن استنساخ الأنواع المخصّصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يتهيئ كائنًا جديدًا ويُمكّن بناء نسخ الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يتهيئ كائنًا جديدًا ويُمكّن بناء نسخ الفئات المشتقة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [Remove](./remove/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يزيل أول نسخة من العنصر المحدد من القائمة. |
| void [RemoveAt](./removeat/)(int) override | يزيل العنصر في الموضع المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيط القالب الخامس كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل عدّاد المرجع المشترك ويعيده. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن تحويل الكائنات المخصّصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| static [System::SharedPtr](../../system/sharedptr/)\<T\> [UnboxValue](./unboxvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | تحويل قيمة الكائن إلى مرجع نوع معين. |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل تعبير C# lock() . استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضا

* فئة [IList](../ilist/)
* نطاق [System::Collections](../)
* مكتبة [Aspose.Slides](../../)