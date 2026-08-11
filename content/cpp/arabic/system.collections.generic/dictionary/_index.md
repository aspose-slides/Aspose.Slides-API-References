---
title: Dictionary
second_title: مرجع API لـ Aspose.Slides للـ C++
description: إعلان مسبق لفئة Dictionary.
type: docs
weight: 144
url: /ar/system.collections.generic/dictionary/
---
## فئة القاموس

الإعلان المسبق لـ [Dictionary](./) فئة.

```cpp
template<typename TKey,typename TValue>class Dictionary : public System::Collections::Generic::BaseDictionary<std::unordered_map<TKey, TValue, EqualityComparerHashAdapter<TKey>, EqualityComparerAdapter<TKey>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TKey | نوع المفتاح. |
| TValue | نوع القيمة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey\&, const TValue\&) | يضيف زوج المفتاح والقيمة إلى الحاوية. |
| virtual void [Add](../icollection/add/)(const T\&) | يضيف عنصرًا إلى المجموعة. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | يعيد مؤشرًا يشير إلى العنصر الأول (إن وجد) في المجموعة. لا يمكن استخدام هذا المؤشر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) يعيد كائن نسخة من T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | يعيد مؤشرًا يشير إلى العنصر الأول (إن وجد) من النسخة الثابتة للمجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | يعيد مؤشرًا يشير إلى أول عنصر ثابت (إن وجد) في المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | يعيد مؤشرًا يشير مباشرةً بعد آخر عنصر ثابت (إن وجد) في المجموعة. |
| virtual void [Clear](../icollection/clear/)() | يحذف جميع العناصر من المجموعة. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | يتحقق مما إذا كان العنصر موجودًا في المجموعة. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey\&) const | يتحقق مما إذا كان الحاوية تحتوي على المفتاح. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | ينسخ محتويات القاموس إلى عناصر مصفوفة موجودة. |
| [Dictionary](./dictionary/)() | ينشئ قاموسًا فارغًا. |
| [Dictionary](./dictionary/)(const [map_t](./map_t/)\&) | ينسخ البيانات من الخريطة. |
| [Dictionary](./dictionary/)(int) | إصدار زائد يتوافق مع إنشاء قاموس مُخصص مسبقًا؛ لا يقوم بأي تخصيص فعليًا. |
| [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&) | منشئ النسخ. |
| [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<TKey\>\>\&) | منشئ النسخ. |
| [Dictionary](./dictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<TKey\>\>\&) | ينشئ قاموسًا فارغًا. |
| [Dictionary](./dictionary/)(int, const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<TKey\>\>\&) | ينشئ قاموسًا فارغًا. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | يعيد مؤشرًا يشير مباشرةً بعد آخر عنصر (إن وجد) في المجموعة. لا يمكن استخدام هذا المؤشر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) يعيد كائن نسخة من T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | يعيد مؤشرًا يشير مباشرةً بعد آخر عنصر (إن وجد) من النسخة الثابتة للمجموعة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة أعداد نقطية بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أن IEC 60559:1989 تقول إن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة أعداد مزدوجة بأسلوب C# حيث يُعتبر NaNانان متساويين رغم أن IEC 60559:1989 تقول إن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual int [get_Count](../icollection/get_count/)() const | يعيد عدد العناصر في المجموعة. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | يتحقق مما إذا كان حجم المجموعة ثابتًا. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | يتحقق مما إذا كانت المجموعة للقراءة فقط. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | يتحقق مما إذا كانت الحاوية آمنة للخطوط المتعددة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | يصل إلى مجموعة المفاتيح. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | يعيد الكائن الذي تُزامن من خلاله المجموعة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | يصل إلى مجموعة القيم. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يعيد بنية عداد المرجع المرتبطة بالكائن. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | ينشئ كائن تعداد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يعيد النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&) const | يرجع القيمة إذا تم العثور عليها؛ أو **Value()** غير ذلك. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&, const TValue\&) const | يرجع القيمة إذا تم العثور عليها؛ أو **defaultValue** غير ذلك. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey\&) const | يرجع القيمة إذا تم العثور عليها؛ أو **null** غير ذلك، وهو منطقي فقط للأنواع المرجعية. |
| [ICollection](../icollection/icollection/)() | منشئ افتراضي. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | منشئ النسخ. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | منشئ النقل. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey\&) const | دالة جالب. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey\&, TValue) | دالة وضع. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة تراكم على تسلسل. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تفي بشرط. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان أي عنصر من التسلسل موجودًا أو يفي بشرط. |
| T [LINQ_Average](../ienumerable/linq_average/)() | يحسب المتوسط لتسلسل من القيم الرقمية. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب متوسط تسلسل القيم التي يتم الحصول عليها عبر استدعاء دالة تحويل على كل عنصر من التسلسل الإدخالي. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | يحوّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | يُسلسِل سلسلتين. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../ienumerable/linq_count/)() | يرجع عدد العناصر في التسلسل (محسوبًا عبر العد المباشر). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرجع عدد العناصر في التسلسل التي تفي بالشرط المحدد. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | يرجع العنصر في الفهرس المحدد داخل التسلسل. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | يرجع العنصر في الفهرس المحدد داخل التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)() | يرجع العنصر الأول في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرجع العنصر الأول في التسلسل الذي يفي بالشرط المحدد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | يرجع العنصر الأول في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يرجع العنصر الأول في التسلسل الذي يفي بشرط أو قيمة افتراضية إذا لم يُعثر على عنصر كهذا. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يجمع عناصر التسلسل. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يجمع عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | يرجع العنصر الأخير في التسلسل. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | يرجع العنصر الأخير في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يستدعي دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يستدعي دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | يفلتر عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر التسلسل بترتيب تصاعدي وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر التسلسل بترتيب تنازلي وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | يعكس ترتيب عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحوّل عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحوّل كل عنصر من التسلسل إلى شكل جديد عبر دمج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | يعرض كل عنصر من التسلسل ويجمع التسلسلات الناتجة إلى تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتجاورة من بداية التسلسل ويعيد البقية. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | يرجع عددًا محددًا من العناصر المتجاورة من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | يفلتر تسلسلًا بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيء جميع بنى البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | عامل إسناد النقل. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | عامل إسناد النقل. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيء كائنًا جديدًا ويتيح إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey\&) | يزيل المفتاح من الحاوية. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | يحذف العنصر من المجموعة. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط المتغير النمطي الـ n إلى مؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يعيد القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey\&, TValue\&) const | يبحث عن القيمة ويسترجعها إذا وجدت. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ تعبير C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعِه مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | يعيد تنفيذ مبدئ المؤشر الثابت للعنصر الحالي. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | يعيد تنفيذ مبدئ المؤشر للعنصر الحالي. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | يعيد تنفيذ نهاية المؤشر الثابت للعنصر الحالي. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | يعيد تنفيذ نهاية المؤشر للعنصر الحالي. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## تعريفات الأنواع

| التعريف | الوصف |
| --- | --- |
| [KeyCollection](./keycollection/) | مجموعة المفاتيح التي سيتم استخراجها. |
| [ValueCollection](./valuecollection/) | مجموعة القيم التي سيتم استخراجها. |
| [map_t](./map_t/) | نوع البيانات الأساسي. |
| [Ptr](./ptr/) | نوع المؤشر. |
| [KVPair](./kvpair/) | نوع زوج المفتاح والقيمة. |
| [IEnumerablePtr](./ienumerableptr/) | مؤشر إلى واجهة قابلة للتعداد. |
| [IEnumeratorPtr](./ienumeratorptr/) | مؤشر إلى المُعدِّد. |

## ملاحظات

[Dictionary](./) الذي يربط القيم بالمفاتيح. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، لأنها ستؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
#include <system/collections/dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // إنشاء مثيل فئة Dictionary.
  auto dictionary = MakeObject<Dictionary<int, String>>();

  // ملء القاموس.
  dictionary->Add(0, u"Foo");
  dictionary->Add(1, u"Bar");
  dictionary->Add(2, u"Baz");

  // طباعة عناصر القاموس.
  for (const auto &pair: dictionary)
  {
    std::cout << pair.get_Key() << " - " << pair.get_Value() << std::endl;
  }

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
0 - Foo
1 - Bar
2 - Baz
*/
```

## انظر أيضًا

* الفئة [BaseDictionary](../basedictionary/)
* النطاق [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)