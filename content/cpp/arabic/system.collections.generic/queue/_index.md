---
title: Queue
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إعلان مسبق لفئة Queue.
type: docs
weight: 469
url: /ar/system.collections.generic/queue/
---
## فئة Queue

[Queue](./) فئة إعلان مسبق.

```cpp
template<typename T>class Queue : public System::Collections::Generic::IEnumerable<T>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العنصر. |
## الأساليب

| الأسلوب | الوصف |
| --- | --- |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | يحصل على مكرّر يُشير إلى أول عنصر (إن وجد) في التجميع. لا يمكن استخدام هذا المكرّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) تُعيد نسخة من الكائن من نوع T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | يحصل على مكرّر يُشير إلى أول عنصر (إن وجد) في النسخة المتقيدة بالثوابت من التجميع. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | يحصل على مكرّر يُشير إلى أول عنصر ثابت (إن وجد) في التجميع. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | يحصل على مكرّر يُشير إلى ما بعد آخر عنصر ثابت (إن وجد) في التجميع. |
| virtual void [Clear](./clear/)() | يحذف جميع العناصر في الصف. |
| virtual **bool** [Contains](./contains/)(const T\&) const | يتحقق مما إذا كان الصف يحتوي على عنصر محدد باستخدام المشغل == لمقارنة العناصر. |
| [queue_t](./queue_t/)\& [data](./data/)() | مُدخل بنية البيانات الأساسية. |
| const [queue_t](./queue_t/)\& [data](./data/)() const | مُدخل بنية البيانات الأساسية. |
| T [Dequeue](./dequeue/)() | يحصل على عنصر من بداية الصف. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | يحصل على مكرّر يُشير إلى ما بعد آخر عنصر (إن وجد) في التجميع. لا يمكن استخدام هذا المكرّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) تُعيد نسخة من الكائن من نوع T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | يحصل على مكرّر يُشير إلى ما بعد آخر عنصر (إن وجد) في النسخة المتقيدة بالثوابت من التجميع. |
| void [Enqueue](./enqueue/)(const T\&) | يضيف عنصرًا إلى نهاية الصف. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNان مساويًا لـ NaN على الرغم من أن IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNان مساويًا لـ NaN على الرغم من أن IEC 60559:1989 لا يعتبر NaN مساويًا لأي قيمة. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual int [get_Count](./get_count/)() const | يحصل على عدد العناصر في الصف. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | يحصل على المُعدّد لتكرار عناصر الصف. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل عامل C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة المُراكم على تسلسل. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر تسلسل ما تلبية شرطًا ما. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان أي عنصر من التسلسل موجودًا أو يفي بشرط ما. |
| T [LINQ_Average](../ienumerable/linq_average/)() | يحسب متوسط تسلسل القيم الرقمية. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب متوسط تسلسل القيم التي تُستخرج عبر استدعاء دالة تحويل على كل عنصر من التسلسل الإدخالي. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | يحول العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | يدمج تسلسلين. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../ienumerable/linq_count/)() | يُعيد عدد العناصر في التسلسل (بحساب مباشر). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يُعيد عدد العناصر في التسلسل التي تُستوفي الشرط المحدد. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | يُعيد العنصر في الفهرس المحدد داخل التسلسل. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | يُعيد العنصر في الفهرس المحدد داخل التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)() | يُعيد أول عنصر في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يُعيد أول عنصر في التسلسل الذي يحقق الشرط المحدد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | يُعيد أول عنصر في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يُعيد أول عنصر في التسلسل يُستوفي شرطًا ما أو قيمة افتراضية إذا لم يُعثر على مثل هذا العنصر. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يجمع عناصر التسلسل في مجموعات. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يجمع عناصر التسلسل في مجموعات. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | يُعيد آخر عنصر في التسلسل. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | يُعيد آخر عنصر في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يستدعي دالة تحويل على كل عنصر من تسلسل عام ويُعيد القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يستدعي دالة تحويل على كل عنصر من تسلسل عام ويُعيد القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | يصفّي عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتّب عناصر التسلسل بترتيب تصاعدي وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتّب عناصر التسلسل بترتيب تنازلي وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | يعكس ترتيب عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يُحوّل عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يُحوّل كل عنصر من التسلسل إلى شكل جديد بإدراج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | يُسقِط كل عنصر من التسلسل ويجمع التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتابعة من بداية التسلسل ويُعيد ما تبقى. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | يُعيد عددًا محددًا من العناصر المتتابعة من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | يُصفّي تسلسل بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل C# lock() . استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) . يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يُنشئ كائنًا. يهيّء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغّل إسناد. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| T [Peek](./peek/)() | يحصل على عنصر من بداية الصف دون إزالته من الصف. |
|  [Queue](./queue/)() | يُنشئ صفًا فارغًا. |
|  [Queue](./queue/)(int) | يُنشئ صفًا فارغًا. |
|  [Queue](./queue/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>\&) | مُنشئ نسخة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضع المؤشر القالب الـ n كمرجع ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/) . يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل C# lock() . استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | يحصل على تنفيذ مكرّر البداية الثابت للوعاء الحالي. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | يحصل على تنفيذ مكرّر البداية للوعاء الحالي. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | يحصل على تنفيذ مكرّر النهاية الثابت للوعاء الحالي. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | يحصل على تنفيذ مكرّر النهاية للوعاء الحالي. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |
## التعريفات النوعية

| التعريف النوعي | الوصف |
| --- | --- |
| [ValueType](./valuetype/) | هذا النوع. |
| [queue_t](./queue_t/) | نوع البيانات الأساسي. |
| [IEnumerablePtr](./ienumerableptr/) | حاوية لعناصر من نفس النوع. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** النوع. |
## ملاحظات

[Queue](./) حاوية تغلف قائمة STL. يجب تخصيص كائنات هذه الفئة فقط باستخدام دالة [System::MakeObject()](../../system/makeobject/). لا تُنشئ نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أعطال تأكيد. دائمًا غلف هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل.

```cpp
#include <system/collections/queue.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void PrintItems(const SmartPtr<IEnumerable<int>> &queue)
{
  for (const int item: queue)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // إنشاء نسخة من فئة Queue.
  auto queue = MakeObject<Queue<int>>();

  // ملء الصف.
  queue->Enqueue(1);
  queue->Enqueue(2);
  queue->Enqueue(3);

  // طباعة العنصر الأول في الصف. طريقة Peek لا تُزيل العنصر من الصف.
  std::cout << queue->Peek() << std::endl;
  // طباعة عناصر الصف.
  PrintItems(queue);

  // طباعة العنصر الأول في الصف. طريقة Dequeue تُزيل العنصر من الصف.
  std::cout << queue->Dequeue() << std::endl;
  // طباعة عناصر الصف.
  PrintItems(queue);

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
1
1 2 3
1
2 3
*/
```

## انظر أيضاً

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)