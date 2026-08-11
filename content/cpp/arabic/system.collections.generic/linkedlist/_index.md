---
title: LinkedList
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إعلان مسبق لـ LinkedList.
type: docs
weight: 404
url: /ar/system.collections.generic/linkedlist/
---
## فئة LinkedList

[LinkedList](./) إعلان مسبق.

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | نوع القيمة المتضمنة. |

## الطرق

| Method | Description |
| --- | --- |
| void [Add](./add/)(const T\&) override | يضيف **عنصر** إلى نهاية القائمة. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | يضيف **عنصر** بعد **عقدة** في القائمة. |
| void [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | يضيف **newNode** بعد **عقدة** في القائمة. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | يضيف **عنصر** قبل **عقدة** في القائمة. |
| void [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | يضيف **newNode** قبل **عقدة** في القائمة. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddFirst](./addfirst/)(const T\&) | يضيف **عنصر** إلى بداية القائمة. |
| void [AddFirst](./addfirst/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | يضيف **newNode** إلى بداية القائمة. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddLast](./addlast/)(const T\&) | يضيف **عنصر** إلى نهاية القائمة. |
| void [AddLast](./addlast/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | يضيف **newNode** إلى نهاية القائمة. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | يعطي مكرراً للعنصر الأول من المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | يعطي مكرراً للعنصر الأول من المجموعة المؤهَّلة كـ const. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | يعطي مكرراً إلى أول عنصر مؤهَّل كـ const في المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | يعطي مكرراً لعنصر غير موجود مؤهَّل كـ const خلف نهاية المجموعة. |
| void [Clear](./clear/)() override | يحذف جميع العناصر في القائمة. |
| **bool** [Contains](./contains/)(const T\&) const override | يتحقق مما إذا كان **عنصر** موجوداً في القائمة. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | ينسخ بيانات الحاوية إلى عناصر مصفوفة موجودة. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | يعطي مكرراً عكسياً إلى آخر عنصر مؤهَّل كـ const في المجموعة (الأول في الاتجاه العكسي). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | يعطي مكرراً عكسياً لعنصر غير موجود مؤهَّل كـ const قبل بداية المجموعة. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | يعطي مكرراً لعنصر غير موجود خلف نهاية المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | يعطي مكرراً لعنصر غير موجود خلف نهاية المجموعة المؤهَّلة كـ const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر القيمتين NaN متساويتين رغم أنه وفقاً لمعيار IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر القيمتين NaN متساويتين رغم أنه وفقاً لمعيار IEC 60559:1989 لا يُعتبر NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [Find](./find/)(const T\&) const | ينفّذ بحثًا باتجاه الأمام عن **عنصر** في القائمة. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [FindLast](./findlast/)(const T\&) const | ينفّذ بحثًا باتجاه العكس عن **عنصر** في القائمة. |
| int [get_Count](./get_count/)() const override | يعطي عدد العناصر في القائمة. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_First](./get_first/)() const | يعطي مؤشرًا إلى العنصر الأول في القائمة. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | يتحقق مما إذا كانت المجموعة للقراءة فقط. |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_Last](./get_last/)() const | يعطي مؤشرًا إلى آخر عنصر في القائمة. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | يعطي الكائن الذي تُزامن من خلاله المجموعة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يعطي هيكل بيانات عداد المرجع المرتبط بالكائن. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](./getenumerator/)() override | يعطي مُعدِّدًا للتكرار عبر [LinkedList](./) الحالي. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يعطي النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | منشئ افتراضي. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | منشئ نسخة. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | منشئ نقل. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. مماثل للمشغل C# 'is'. |
|  [LinkedList](./linkedlist/)() | ينشئ [LinkedList](./) فارغًا. |
|  [LinkedList](./linkedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>\&) | منشئ نسخة. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة تراكم على تسلسل. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تحقق شرطًا. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان أي عنصر من التسلسل موجودًا أو يحقق شرطًا. |
| T [LINQ_Average](../ienumerable/linq_average/)() | يحسب متوسط تسلسل القيم الرقمية. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب متوسط تسلسل القيم التي يتم الحصول عليها عبر استدعاء دالة تحويل على كل عنصر من تسلسل الإدخال. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | يحوّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | يدمج تسلسلين. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../ienumerable/linq_count/)() | يعطي عدد العناصر في التسلسل (محسوبًا عبر العد المباشر). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يعطي عدد العناصر في التسلسل التي تحقق الشرط المحدد. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | يعطي العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | يعطي العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)() | يعطي العنصر الأول من التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يعطي العنصر الأول من التسلسل الذي يحقق الشرط المحدد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | يعطي العنصر الأول من التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يعطي العنصر الأول من التسلسل الذي يحقق الشرط أو قيمة افتراضية إذا لم يُعثر على عنصر يطابق الشرط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يجمع عناصر التسلسل. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يجمع عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | يعطي العنصر الأخير من التسلسل. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | يعطي العنصر الأخير من التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفّذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفّذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | يصفِّي عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتّب عناصر التسلسل بترتيب تصاعدي وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتّب عناصر التسلسل بترتيب تنازلي وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | يعكس ترتيب عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحوِّل عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحوِّل كل عنصر من التسلسل إلى شكل جديد بإدراج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | يُسقِط كل عنصر من التسلسل ويجمع التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتجاورة من بداية التسلسل ويعيد الباقي. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | يعيد عددًا محددًا من العناصر المتجاورة من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | يصفِّي تسلسلًا بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | يُنفِّذ عملية القفل في تعبير C# lock(). استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّء جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويسمح بنسخ الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيّء كائنًا جديدًا ويسمح بنسخ الفئات المشتقة. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | عامل إسناد نقل. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | عامل إسناد نقل. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | يعطي مكرراً عكسياً إلى آخر عنصر في المجموعة (الأول في الاتجاه العكسي). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | يعطي مكرراً عكسياً إلى آخر عنصر في المجموعة المؤهَّلة كـ const (الأول في الاتجاه العكسي). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي مع nullptr بالمرجعية. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| **bool** [Remove](./remove/)(const T\&) override | يزيل أول ظهور للـ **عنصر** المحدد من القائمة. |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | يزيل **عقدة** من القائمة. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدد المراجع المشتركة بالقيمة المحددة. |
| void [RemoveFirst](./removefirst/)() | يزيل أول عقدة من القائمة. |
| void [RemoveLast](./removelast/)() | يزيل آخر عقدة من القائمة. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | يعطي مكرراً عكسياً لعنصر غير موجود قبل بدء المجموعة. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | يعطي مكرراً عكسياً لعنصر غير موجود قبل بدء المجموعة المؤهَّة كـ const. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n'th كمؤشر ضعيف (بدلاً من المشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يعطي القيمة الحالية لعداد المراجع المشتركة. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم مراكز ذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدد المراجع المشتركة. لا ينبغي استدعاؤه مباشرة؛ استخدم مراكز ذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفِّذ إلغاء القفل في تعبير C# lock(). استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | يعطي تنفيذ مكرّر البداية const للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | يعطي تنفيذ مكرّر البداية للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | يعطي تنفيذ مكرّر النهاية const للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | يعطي تنفيذ مكرّر النهاية للحاوية الحالية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم مراكز ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدد المراجع الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم مراكز ذكية أو ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## تعريفات الأنواع

| تعريف نوع | الوصف |
| --- | --- |
| [list_t](./list_t/) | نوع البيانات الأساسي. |
| [iterator](./iterator/) | نوع المكرّر. |
| [const_iterator](./const_iterator/) | نوع المكرّر الثابت. |
| [reverse_iterator](./reverse_iterator/) | نوع المكرّر العكسي. |
| [const_reverse_iterator](./const_reverse_iterator/) | نوع المكرّر العكسي الثابت. |

## ملاحظات

حاوية قائمة مرتبطة. تنفّذ غلافًا فوق std::list. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيسبّب أخطاء في وقت التشغيل و/أو أخطاء تأكيد. غلف هذه الفئة دائمًا بمؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // إنشاء مثيل من فئة LinkedList.
  auto list = MakeObject<LinkedList<int>>();

  // ملء القائمة المرتبطة.
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // طباعة عناصر القائمة المرتبطة.
  for (const auto item: list)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
1 15 25 30
*/
```

## انظر أيضًا

* فئة [Object](../../system/object/)
* فئة [ICollection](../icollection/)
* فئة [Invalidatable](../../system.collections/invalidatable/)
* نطاق [System::Collections::Generic](../)
* مكتبة [Aspose.Slides](../../)