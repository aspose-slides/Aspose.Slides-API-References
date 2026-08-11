---
title: ICollection
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "واجهة لتجميع العناصر. يجب إنشاء كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبدًا بإنشاء مثال لهذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء زمن التشغيل أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 248
url: /ar/system.collections.generic/icollection/
---
## ICollection فئة

واجهة تجميع العناصر. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء مثال من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء زمن التشغيل أو أخطاء تأكيد. احرص دائمًا على تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريرها إلى الدوال كمعامل.

```cpp
template<typename T>class ICollection : public virtual System::Collections::Generic::IEnumerable<T>
```

## الطرق

| الطريقة | الوصف |
| --- | |
| virtual void [Add](./add/)(const T\&) | يضيف العنصر إلى المجموعة. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | يحصل على مؤشّر يشير إلى العنصر الأول (إن وجد) في المجموعة. لا يمكن استخدام هذا المؤشّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) يُعيد نسخة من T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | يحصل على مؤشّر يشير إلى العنصر الأول (إن وجد) في المثيل المؤهل بـ const في المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | يحصل على مؤشّر يشير إلى أول عنصر مؤهل بـ const (إن وجد) في المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | يحصل على مؤشّر يشير إلى ما بعد آخر عنصر مؤهل بـ const (إن وجد) في المجموعة. |
| virtual void [Clear](./clear/)() | يحذف جميع العناصر من المجموعة. |
| virtual **bool** [Contains](./contains/)(const T\&) const | يتحقق مما إذا كان العنصر موجودًا في المجموعة. |
| virtual void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | ينسخ جميع عناصر المجموعة إلى عناصر مصفوفة موجودة. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | يحصل على مؤشّر يشير إلى ما بعد آخر عنصر (إن وجد) في المجموعة. لا يمكن استخدام هذا المؤشّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) يُعيد نسخة من T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | يحصل على مؤشّر يشير إلى ما بعد آخر عنصر (إن وجد) في المثيل المؤهل بـ const في المجموعة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان متساويين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| virtual int [get_Count](./get_count/)() const | يحصل على عدد العناصر في المجموعة. |
| virtual **bool** [get_IsReadOnly](./get_isreadonly/)() const | يتحقق مما إذا كانت المجموعة للقراءة فقط. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() const | يحصل على الكائن الذي يتم من خلاله مزامنة المجموعة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | يحصل على المُعدِّد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICollection](./icollection/)() | منشئ افتراضي. |
| [ICollection](./icollection/)(const [ICollection](./)\&) | منشئ نسخ. |
| [ICollection](./icollection/)([ICollection](./)\&&) | منشئ نقل. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثالًا للنوع الموصوف بـ targetType. مماثل للمشغل C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة تراكم على تسلسل. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تفي بشرط. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان هناك أي عنصر في التسلسل أو يفي بشرط. |
| T [LINQ_Average](../ienumerable/linq_average/)() | يحسب متوسط تسلسل القيم الرقمية. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب متوسط تسلسل القيم التي يتم الحصول عليها باستدعاء دالة تحويل على كل عنصر في التسلسل المدخل. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | يحوّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | يجمع سلسلتين. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../ienumerable/linq_count/)() | يعيد عدد العناصر في التسلسل (محسوبًا عبر العد المباشر). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يعيد عدد العناصر في التسلسل التي تفي بالشرط المحدد. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | يعيد العنصر عند الفهرس المحدد في تسلسل. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | يعيد العنصر عند الفهرس المحدد في تسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)() | يعيد العنصر الأول في تسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يعيد العنصر الأول في تسلسل الذي يفي بالشرط المحدد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | يعيد العنصر الأول في تسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يعيد العنصر الأول في التسلسل الذي يفي بشرط أو قيمة افتراضية إذا لم يُعثَر على عنصر كهذا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يجمع عناصر تسلسل. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يجمع عناصر تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | يعيد العنصر الأخير في تسلسل. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | يعيد العنصر الأخير في تسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | يفلتر عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر تسلسل بترتيب تصاعدي وفق قيم المفتاح التي يحددها keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر تسلسل بترتيب تنازلي وفق قيم المفتاح التي يحددها keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | يعكس ترتيب العناصر في تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحوّل عناصر تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحوّل كل عنصر في تسلسل إلى صيغة جديدة باستخدام فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | يُسقط كل عنصر في تسلسل ويجمع التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتابعة من بداية تسلسل ويعيد الباقي. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | يعيد عددًا محددًا من العناصر المتتابعة من بداية تسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | يفلتر تسلسل بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | يُطبق قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطيفة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يتهيئ جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكن من إنشاء نسخ في الفئات الفرعية. |
| [ICollection](./)\& [operator=](./operator_equal/)([ICollection](./)\&&) | عامل إسناد نقل. |
| [ICollection](./)\& [operator=](./operator_equal/)(const [ICollection](./)\&) | عامل إسناد نقل. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل إسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويمكن من إنشاء نسخ في الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| virtual **bool** [Remove](./remove/)(const T\&) | يحذف العنصر من المجموعة. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يتيح تحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُطبق إلغاء قفل بيان C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | يحصل على تنفيذ مؤشّر البداية const للمحتوى الحالي. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | يحصل على تنفيذ مؤشّر البداية للمحتوى الحالي. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | يحصل على تنفيذ مؤشّر النهاية const للمحتوى الحالي. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | يحصل على تنفيذ مؤشّر النهاية للمحتوى الحالي. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~ICollection](./~icollection/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## تعريفات الأنواع

| التعريف | الوصف |
| --- | |
| [ValueType](./valuetype/) | اسم نوع القيمة. |
| [ThisType](./thistype/) | اسم نوع المجموعة. |

## أنظر أيضًا

* الفئة [IEnumerable](../ienumerable/)
* النطاق [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)