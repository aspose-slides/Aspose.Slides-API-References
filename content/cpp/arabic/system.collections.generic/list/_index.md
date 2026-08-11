---
title: List
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إعلان مسبق للـ List.
type: docs
weight: 430
url: /ar/system.collections.generic/list/
---
## List فئة

[List](./) إعلان مسبق.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| T | نوع العنصر. |

## الطرق

| طريقة | وصف |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | خاص بـ C++. |
| void [Add](./add/)(const T\&) override | يضيف العنصر إلى نهاية القائمة. |
| void [AddInitializer](./addinitializer/)(int, const T *) | يضيف عناصر إلى القائمة؛ يستخدم عند تحويل المبدئات. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | يضيف جميع العناصر من المجموعة (أو نفسها) إلى نهاية القائمة الحالية. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | يحصل على مرجع للقراءة فقط لهذا التجميع. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | يحصل على مؤشِر إلى العنصر الأول في التجميع. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | يحصل على مؤشِر إلى العنصر الأول في التجميع المؤهل كـ const. |
| int [BinarySearch](./binarysearch/)(const T\&) const | يبحث عن عنصر في قائمة مرتبة. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | يبحث عن عنصر في قائمة مرتبة. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | يبحث عن عنصر في قائمة مرتبة. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | يحصل على مؤشِر إلى العنصر الأول المؤهل كـ const في التجميع. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | يحصل على مؤشِر لعنصر غير موجود مؤهل كـ const خلف نهاية التجميع. |
| void [Clear](./clear/)() override | يحذف جميع العناصر. |
| **bool** [Contains](./contains/)(const T\&) const override | يتحقق مما إذا كان العنصر موجودًا في القائمة. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | ينشئ قائمة من العناصر محوَّلة إلى نوع مختلف. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | ينسخ عناصر القائمة إلى عناصر مصفوفة موجودة. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | ينسخ جميع العناصر إلى عناصر مصفوفة موجودة. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | ينسخ العناصر بدءًا من الفهرس المحدد إلى عناصر مصفوفة موجودة. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | يحصل على مؤشِر عكسي إلى العنصر الأخير المؤهل كـ const في التجميع (الأول في الاتجاه العكسي). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | يحصل على مؤشِر عكسي لعنصر غير موجود مؤهل كـ const قبل بداية التجميع. |
| [vector_t](./vector_t/)\& [data](./data/)() | دالة وصول إلى بنية البيانات الأساسية. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | دالة وصول إلى بنية البيانات الأساسية. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | يحصل على مؤشِر لعنصر غير موجود خلف نهاية التجميع. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | يحصل على مؤشِر لعنصر غير موجود خلف نهاية التجميع المؤهل كـ const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتَبر NaNانين متساويين رغم أن وفقًا لـ IEC 60559:1989 لا يُعَد NaN مساويًا لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة الثنائية (double) بأسلوب C# حيث يُعتَبر NaNانين متساويين رغم أن وفقًا لـ IEC 60559:1989 لا يُعَد NaN مساويًا لأي قيمة، بما فيها NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | يتحقق مما إذا كان هناك عنصر يطابق شرطًا محددًا في القائمة. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | يبحث عن عنصر يطابق شرطًا محددًا. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | يبحث عن عناصر تلتزم بشرط محدد. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | يبحث عن عنصر يطابق شرطًا محددًا. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | يبحث عن عنصر يطابق شرطًا محددًا. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | يبحث عن عنصر يطابق شرطًا محددًا. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | يبحث عن العنصر الأخير الذي يطابق شرطًا محددًا. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | يطبق الإجراء على جميع العناصر في القائمة. |
| int [get_Capacity](./get_capacity/)() const | يحصل على سعة القائمة الحالية. |
| int [get_Count](./get_count/)() const override | يحصل على عدد العناصر في القائمة الحالية. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | يتحقق مما إذا كان التجAggregation بحجم ثابت. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | يتحقق مما إذا كان التجAggregation للقراءة فقط. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | يحصل على الكائن الذي يتم من خلاله مزامنة التجAggregation. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجعية المرتبطة بالكائن. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | يحصل على عداد لتكرار عناصر القائمة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | ينشئ شريحة من القائمة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | بناء افتراضي. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | منشئ نسخة. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | منشئ نقل. |
| T [idx_get](./idx_get/)(int) const override | يحصل على العنصر في موضع محدد. |
| void [idx_set](./idx_set/)(int, T) override | يضبط العنصر في موضع محدد. |
| int [IndexOf](./indexof/)(const T\&) const override | يحصل على الفهرس الأول للعنصر المحدد. |
| int [IndexOf](./indexof/)(const T\&, int) const | يبحث عن عنصر محدد في القائمة. |
| void [Insert](./insert/)(int, const T\&) override | يدخل العنصر في الموضع المحدد. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | يدخل نطاق بيانات في موضع محدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموضح بـ targetType. تماثل عامل C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للظهور الأخير داخل القائمة بأكملها. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للظهور الأخير ضمن نطاق العناصر في [List](./) الممتد من العنصر الأول إلى الفهرس المحدد. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للظهور الأخير ضمن نطاق العناصر في [List](./) الذي يحتوي على عدد محدد من العناصر وينتهي عند الفهرس المحدد. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة تراكمية على تسلسل. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تفي بشرط. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان أي عنصر من التسلسل موجودًا أو يفي بشرط. |
| T [LINQ_Average](../ienumerable/linq_average/)() | يحسب متوسط تسلسل من القيم الرقمية. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب متوسط تسلسل القيم التي يتم الحصول عليها عبر استدعاء دالة تحويل على كل عنصر من التسلسل المدخل. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | يحوّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | يدمج سلسلتين. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | يحدد إذا ما كانت السلسلة تحتوي على قيمة محددة. |
| int [LINQ_Count](../ienumerable/linq_count/)() | يعيد عدد العناصر في السلسلة (محسوبًا عبر العد المباشر). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يعيد عدد العناصر في السلسلة التي تفي بالشرط المحدد. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | يعيد العنصر في فهرس محدد داخل سلسلة. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | يعيد العنصر في فهرس محدد داخل سلسلة. |
| T [LINQ_First](../ienumerable/linq_first/)() | يعيد العنصر الأول في السلسلة. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يعيد العنصر الأول في السلسلة الذي يفي بالشرط المحدد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | يعيد العنصر الأول في السلسلة، أو قيمة افتراضية إذا كانت السلسلة فارغة. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يعيد العنصر الأول في السلسلة الذي يفي بشرط أو قيمة افتراضية إذا لم يُعثر على مثل هذا العنصر. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يجمّع عناصر السلسلة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يجمّع عناصر السلسلة. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | يعيد العنصر الأخير في السلسلة. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | يعيد العنصر الأخير في السلسلة، أو قيمة افتراضية إذا كانت السلسلة فارغة. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يقوم باستدعاء دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة العظمى الناتجة. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يقوم باستدعاء دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة الصغرى الناتجة. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | يفلتر عناصر السلسلة بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر السلسلة بترتيب تصاعدي وفقًا لقيم المفتاح التي يختارها keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر السلسلة بترتيب تنازلي وفقًا لقيم المفتاح التي يختارها keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | يعكس ترتيب العناصر في السلسلة. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحول عناصر السلسلة. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحول كل عنصر من السلسلة إلى صيغة جديدة بإدماج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | يط��ق كل عنصر من السلسلة ويجمع التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتالية من بداية السلسلة ويعيد البقية. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | يعيد عددًا محددًا من العناصر المتتالية من بداية السلسلة. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | يفلتر تسلسلًا بناءً على الشرط المحدد. |
|  [List](./list/)() | ينشئ قائمة فارغة. |
|  [List](./list/)(int) | ينشئ قائمة بسعة محددة مسبقًا. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | منشئ نسخة. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيّء كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيّء كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | عامل إسناد النقل. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | عامل إسناد النقل. |
| vector_t::reference [operator[]](./operator[]/)(int) | دالة وصول. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | دالة وصول. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | يحصل على مؤشِر عكسي إلى العنصر الأخير في التجAggregation (الأول في الاتجاه العكسي). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | يحصل على مؤشِر عكسي إلى العنصر الأخير في التجAggregation المؤهل كـ const (الأول في الاتجاه العكسي). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| **bool** [Remove](./remove/)(const T\&) override | يزيل النسخة الأولى من العنصر المحدد من القائمة. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | يزيل جميع العناصر التي تطابق الشرط المحدد. |
| void [RemoveAt](./removeat/)(int) override | يزيل العنصر في الموضع المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [RemoveRange](./removerange/)(int, int) | يزيل شريحة من القائمة. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | يحصل على مؤشِر عكسي لعنصر غير موجود قبل بداية التجAggregation. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | يحصل على مؤشِر عكسي لعنصر غير موجود قبل بداية التجAggregation المؤهل كـ const. |
| void [Reverse](./reverse/)() | يعكس ترتيب عناصر القائمة بأكملها. |
| void [Reverse](./reverse/)(int, int) | يعكس ترتيب عناصر شريحة القائمة. |
| void [set_Capacity](./set_capacity/)(int) | يضبط سعة القائمة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النائي من القالب كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل الإشارات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ استخدم مؤشرات ذكية أو ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | يرتب العناصر في القائمة. |
| void [Sort](./sort/)() | يرتب العناصر في القائمة باستخدام المقارن الافتراضي. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | يرتب العناصر في شريحة القائمة. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | يرتب العناصر في القائمة. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | يحول القائمة إلى مصفوفة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| void [TrimExcess](./trimexcess/)() | يضبط سعة القائمة لتتناسب مع حجمها. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | يحدد ما إذا كان كل عنصر في التجAggregation يطابق الشروط المحددة بالشرط المحدد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن [LockContext](../../system/lockcontext/) الحارس. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | يحصل على تنفيذ بداية المؤشر الثابت للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | يحصل على تنفيذ بداية المؤشر للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | يحصل على تنفيذ نهاية المؤشر الثابت للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | يحصل على تنفيذ نهاية المؤشر للحاوية الحالية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## تعريفات نوع

| تعريف نوع | وصف |
| --- | --- |
| [ValueType](./valuetype/) | هذا النوع. |
| [BaseType](./basetype/) | نوع الواجهة. |
| [vector_t](./vector_t/) | نوع البيانات الأساسي. |
| [iterator](./iterator/) | نوع المؤشر. |
| [const_iterator](./const_iterator/) | نوع المؤشر الثابت. |
| [reverse_iterator](./reverse_iterator/) | نوع المؤشر العكسي. |
| [const_reverse_iterator](./const_reverse_iterator/) | نوع المؤشر العكسي الثابت. |
| [IEnumerablePtr](./ienumerableptr/) | حاوية تحتفظ بالعناصر من نفس النوع الذي نحمله. |
| [IEnumeratorPtr](./ienumeratorptr/) | نوع **Enumerator**. |

## الملاحظات

[List](./) - غلاف حول std::vector يُستخدم في الكود المترجم. يتطلب تنفيذ المشغل == لنوع العنصر. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء تشغيلية و/أو أخطاء تأكيد. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // إنشاء القائمة الأولى.
  auto list1 = MakeObject<List<int>>();

  // ملء القائمة الأولى.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // فرز القائمة الأولى.
  // ستصبح عناصر القائمة الأولى: {-5, 1, 3, 8}
  list1->Sort();

  // إزالة العنصر عند الفهرس 2.
  // ستصبح عناصر القائمة الأولى: {-5, 1, 8}
  list1->RemoveAt(2);

  // إدراج العنصر عند الفهرس 1.
  // ستصبح عناصر القائمة الأولى: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // إنشاء القائمة الثانية.
  auto list2 = MakeObject<List<int>>();

  // ملء القائمة الثانية.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // إلحاق العناصر من القائمة الثانية إلى الأولى.
  list1->AddRange(list2);

  // طباعة عناصر القائمة الأولى.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
- 5 15 1 8 10 20 30
*/
```

## انظر أيضًا

* فئة [Object](../../system/object/)
* فئة [IList](../ilist/)
* نطاق [System::Collections::Generic](../)
* مكتبة [Aspose.Slides](../../)