---
title: SortedDictionary
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إعلان مسبق لنوع القاموس المرتب.
type: docs
weight: 521
url: /ar/system.collections.generic/sorteddictionary/
---
## فئة SortedDictionary

إعلان مسبق لنوع القاموس المرتب.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفتاح. |
| TValue | نوع القيمة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey&, const TValue&) | يضيف زوج المفتاح-القيمة إلى الحاوية. |
| virtual void [Add](../icollection/add/)(const T&) | يضيف العنصر إلى المجموعة. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | يحصل على المؤشر الذي يشير إلى العنصر الأول (إن وجد) في المجموعة. لا يمكن استخدام هذا المؤشر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) يرجع نسخة من الكائن من النوع T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | يحصل على المؤشر الذي يشير إلى العنصر الأول (إن وجد) في نسخة المجموعة المؤهلة بـ const. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | يحصل على المؤشر الذي يشير إلى أول عنصر مؤهل بـ const (إن وجد) في المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | يحصل على المؤشر الذي يشير مباشرة بعد آخر عنصر مؤهل بـ const (إن وجد) في المجموعة. |
| virtual void [Clear](../icollection/clear/)() | يحذف جميع العناصر من المجموعة. |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | يفحص ما إذا كان العنصر موجودًا في المجموعة. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | يفحص ما إذا كان الحاوية تحتوي على المفتاح. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | ينسخ محتويات القاموس إلى عناصر مصفوفة موجودة. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | يحصل على مؤشر عكسي إلى آخر عنصر مؤهل بـ const في المجموعة (الأول في الاتجاه العكسي). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | يحصل على مؤشر عكسي لعنصر غير موجود مؤهل بـ const قبل بداية المجموعة. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | يحصل على المؤشر الذي يشير مباشرة بعد آخر عنصر (إن وجد) في المجموعة. لا يمكن استخدام هذا المؤشر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) يرجع نسخة من الكائن من النوع T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | يحصل على المؤشر الذي يشير مباشرة بعد آخر عنصر (إن وجد) في نسخة المجموعة المؤهلة بـ const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaNانين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | يحاكي مقارنة النقطة العائمة بأسلوب C# للنوع double حيث تُعتبر NaNانين متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)<[System::Collections::Generic::IComparer](../icomparer/)<TKey>> [get_Comparer](./get_comparer/)() const | يحصل على IComparer<TKey> المستخدم لترتيب عناصر SortedDictionary<TKey,TValue>. |
| virtual int [get_Count](../icollection/get_count/)() const | يحصل على عدد العناصر في المجموعة. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | يفحص ما إذا كان حجم المجموعة ثابتًا. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | يفحص ما إذا كانت المجموعة للقراءة فقط. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | يفحص ما إذا كان الحاوية آمنة للمتعددة الخيوط. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TKey>> [get_Keys](../idictionary/get_keys/)() const | يصل إلى مجموعة المفاتيح. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | يحصل على الكائن الذي تتم من خلاله مزامنة المجموعة. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TValue>> [get_Values](../idictionary/get_values/)() const | يصل إلى مجموعة القيم. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد الإشارات المرتبطة بالكائن. |
| static [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>> [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | دالة الوصول إلى الكائن الوحيد. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | يحصل على المُعدد للتجول عبر القاموس الحالي. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | يعيد القيمة إذا وجدت؛ أو **Value()** خلاف ذلك. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | يعيد القيمة إذا وجدت؛ أو **defaultValue** خلاف ذلك. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | يعيد القيمة إذا وجدت؛ أو **null** خلاف ذلك، وهذا منطقي فقط للأنواع المرجعية. |
| [ICollection](../icollection/icollection/)() | منشئ افتراضي. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | منشئ نسخ. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | منشئ نقل. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | دالة جلب. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | دالة ضبط. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | يطبق دالة تجميع على تسلسل. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تفي بشرط. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | يحدد ما إذا كان هناك أي عنصر في التسلسل أو يفي بشرط. |
| T [LINQ_Average](../ienumerable/linq_average/)() | يحسب متوسط قيم رقمية في التسلسل. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | يحسب متوسط تسلسل القيم التي يتم الحصول عليها عبر استدعاء دالة تحويل على كل عنصر من عناصر التسلسل المدخل. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | يحوّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>>) | يدمج تسلسلين. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../ienumerable/linq_count/)() | يعيد عدد العناصر في التسلسل (محسوب عبر العد المباشر). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | يعيد عدد العناصر في التسلسل التي تفي بالشرط المحدد. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | يعيد العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | يعيد العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)() | يعيد العنصر الأول في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | يعيد العنصر الأول في التسلسل الذي يفي بالشرط المحدد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | يعيد العنصر الأول في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | يعيد العنصر الأول في التسلسل الذي يفي بشرط أو قيمة افتراضية إذا لم يُعثر على مثل هذا العنصر. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | يجمع عناصر التسلسل في مجموعات. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | يجمع عناصر التسلسل في مجموعات. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | يعيد العنصر الأخير في التسلسل. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | يعيد العنصر الأخير في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | ينفّذ دالة تحويل على كل عنصر في تسلسل عام ويعيد القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | ينفّذ دالة تحويل على كل عنصر في تسلسل عام ويعيد القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | يصفّي عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | يرتب عناصر التسلسل بترتيب تصاعدي وفقًا لقيم المفتاح التي يحددها keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | يرتب عناصر التسلسل بترتيب تنازلي وفقًا لقيم المفتاح التي يحددها keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | يعكس ترتيب العناصر في التسلسل. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | يحوّل عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | يحوّل كل عنصر في التسلسل إلى شكل جديد باستخدام فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | يُسقط كل عنصر من التسلسل ويجمع التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتصلة من بداية التسلسل ويعيد البقية. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | يعيد عددًا محددًا من العناصر المتصلة من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | يصفّي تسلسلًا بناءً على الدالة الشرطية المحددة. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | عامل إسناد نقل. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | عامل إسناد نقل. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | عامل إسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | يحصل على مؤشر عكسي إلى آخر عنصر في المجموعة (الأول في الاتجاه العكسي). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | يحصل على مؤشر عكسي إلى آخر عنصر في المجموعة المؤهلة بـ const (الأول في الاتجاه العكسي). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | يقارن الكائنات بالإشارة. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | يقارن كائن نوع القيمة بالإشارة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة والـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالات السلاسل. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | يزيل المفتاح من الحاوية. |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | يحذف العنصر من المجموعة. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلص عدّاد الإشارة المشتركة بالقيمة المحددة. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | يحصل على مؤشر عكسي لعنصر غير موجود قبل بداية المجموعة. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | يحصل على مؤشر عكسي لعنصر غير موجود قبل بداية المجموعة المؤهلة بـ const. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط معامل القالب رقم n كإشارة ضعيفة (بدلاً من المشتركة). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلص ويعيد عدّاد الإشارة المشتركة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| [SortedDictionary](./sorteddictionary/)() | يبني قاموسًا فارغًا. |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>>) | يبني قاموسًا فارغًا. |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>) | منشئ نسخ. |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>, const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>>) | منشئ نسخ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | يبحث عن القيمة ويسترجعها إذا وجدت. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | يحصل على تنفيذ begin const iterator للحاوية الحالية. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | يحصل على تنفيذ begin iterator للحاوية الحالية. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | يحصل على تنفيذ end const iterator للحاوية الحالية. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | يحصل على تنفيذ end iterator للحاوية الحالية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلص عدّاد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استعمل مؤشرات ذكية أو ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُحرّر جميع هياكل البيانات الداخلية. |

## التعريفات النوعية

| التعريف النوعي | الوصف |
| --- | --- |
| [KeyCollection](./keycollection/) | نوع مجموعة المفاتيح. |
| [ValueCollection](./valuecollection/) | نوع مجموعة القيم. |
| [map_t](./map_t/) | نوع البيانات الأساسي. |
| [this_t](./this_t/) | نوع الذات. |
| [Ptr](./ptr/) | نوع المؤشر. |
| [KVPair](./kvpair/) | نوع زوج المفتاح-القيمة. |
| [IEnumerablePtr](./ienumerableptr/) | مجموعة من العناصر المتشابهة. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** نوع. |
| [iterator](./iterator/) | نوع المؤشر. |
| [const_iterator](./const_iterator/) | نوع المؤشر الثابت. |
| [reverse_iterator](./reverse_iterator/) | نوع المؤشر العكسي. |
| [const_reverse_iterator](./const_reverse_iterator/) | نوع المؤشر العكسي الثابت. |

## ملاحظات

فئة القاموس المرتب التي تغلف خريطة STL. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تُنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيتسبب ذلك في أخطاء وقت التشغيل أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

## أنظر أيضًا

* فئة [BaseDictionary](../basedictionary/)
* نطاق [System::Collections::Generic](../)
* مكتبة [Aspose.Slides](../../)