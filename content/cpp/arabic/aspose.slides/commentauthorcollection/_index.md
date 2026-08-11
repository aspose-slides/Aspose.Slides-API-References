---
title: CommentAuthorCollection
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل مجموعة من مؤلفي التعليقات.
type: docs
weight: 443
url: /ar/aspose.slides/commentauthorcollection/
---
## CommentAuthorCollection فئة

يمثل مجموعة من مؤلفي التعليقات.

```cpp
class CommentAuthorCollection : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Presentation>>,
                                public Aspose::Slides::ICommentAuthorCollection
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [AddAuthor](./addauthor/)([System::String](../../system/string/), [System::String](../../system/string/)) override | إضافة مؤلف جديد في نهاية مجموعة. |
| [iterator](./iterator/) [begin](./begin/)() | يحصل على المتكرر الذي يشير إلى العنصر الأول (إن وجد) في المجموعة. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | يحصل على المتكرر الذي يشير إلى العنصر الأول (إن وجد) في النسخة المؤهلة بـ const من المجموعة. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | يحصل على المتكرر الذي يشير إلى العنصر الأول المؤهل بـ const (إن وجد) في المجموعة. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | يحصل على المتكرر الذي يشير مباشرة بعد العنصر الأخير المؤهل بـ const (إن وجد) في المجموعة. |
| void [Clear](./clear/)() override | يزيل جميع المؤلفين من مجموعة. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>\>, **int32_t**) override | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [iterator](./iterator/) [end](./end/)() | يحصل على المتكرر الذي يشير مباشرة بعد العنصر الأخير (إن وجد) في المجموعة. |
| [const_iterator](./const_iterator/) [end](./end/)() const | يحصل على المتكرر الذي يشير مباشرة بعد العنصر الأخير (إن وجد) في النسخة المؤهلة بـ const من المجموعة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمة NaN مساوية لقيمة NaN أخرى بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN مساويتين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>\> [FindByName](./findbyname/)([System::String](../../system/string/)) override | البحث عن مؤلف في مجموعة حسب الاسم. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>\> [FindByNameAndInitials](./findbynameandinitials/)([System::String](../../system/string/), [System::String](../../system/string/)) override | البحث عن مؤلف في مجموعة حسب الاسم والحروف الأولى. |
| **int32_t** [get_Count](./get_count/)() override | يحصل على عدد العناصر الفعلي الموجود في المجموعة. للقراءة فقط **int32_t**. |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للعمليات المتعددة). للقراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | يعيد جذر المزامنة. للقراءة فقط [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجع المرتبط بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>\>\> [GetEnumerator](./getenumerator/)() override | يعيد عدادًا (enumerator) يتنقل عبر المجموعة. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [idx_get](./idx_get/)(**int32_t**) override | يحصل على العنصر في الفهرس المحدد. للقراءة فقط [ICommentAuthor](../icommentauthor/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير معامل C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة تجميع على تسلسل. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تفي بشرط. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان أي عنصر من التسلسل موجودًا أو يفي بشرط. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | يحسب المتوسط لتسلسل من القيم العددية. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب المتوسط لتسلسل من القيم التي يتم الحصول عليها عبر استدعاء دالة تحويل على كل عنصر من تسلسل الإدخال. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | يحوّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | يلحِق تسلسلين. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | يعيد عدد العناصر في التسلسل (محسوب عبر العد المباشر). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يعيد عدد العناصر في التسلسل التي تفي بالشرط المحدد. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | يعيد العنصر في فهرس محدد داخل تسلسل. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | يعيد العنصر في فهرس محدد داخل تسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | يعيد العنصر الأول في تسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يعيد العنصر الأول في تسلسل يفي بالشرط المحدد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | يعيد العنصر الأول في تسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يعيد العنصر الأول في التسلسل الذي يفي بشرط أو قيمة افتراضية إذا لم يُعثر على مثل هذا العنصر. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يجمع عناصر تسلسل. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يجمع عناصر تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | يعيد العنصر الأخير في تسلسل. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | يعيد العنصر الأخير في تسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفّذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفّذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | يصفّي عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر تسلسل بترتيب تصاعدي وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر تسلسل بترتيب تنازلي وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | يعكس ترتيب عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحوّل عناصر تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحوّل كل عنصر من تسلسل إلى شكل جديد عبر دمج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | يُسقِط كل عنصر من تسلسل ويجمع التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتجاورة من بداية تسلسل ويعيد الباقي. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | يعيد عددًا محددًا من العناصر المتجاورة من بداية تسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | يصفّي تسلسل بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفلًا (lock()) في C#. استدعيه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | بناء نسخة نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويُمكّن إنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>) override | يزيل أول حدوث للمؤلف المحدد في مجموعة. |
| void [RemoveAt](./removeat/)(**int32_t**) override | يزيل المؤلف في الفهرس المحدد من المجموعة. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يُنزّل عداد المرجع المشترك بقيمة محددة. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | يضبط الوسيط القالب الـ n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>\> [ToArray](./toarray/)() override | ينشئ ويعيد مصفوفة تحتوي على جميع المؤلفين. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل C# lock(). استدعيه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | يحصل على المتكرر الذي يشير إلى العنصر الأول (إن وجد) من النسخة المؤهلة بـ const من المجموعة. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | يحصل على المتكرر الذي يشير إلى العنصر الأول (إن وجد) في المجموعة. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | يحصل على المتكرر الذي يشير مباشرة بعد العنصر الأخير (إن وجد) من النسخة المؤهلة بـ const من المجموعة. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | يحصل على المتكرر الذي يشير مباشرة بعد العنصر الأخير (إن وجد) في المجموعة. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## الأنواع المعرفة

| التعريف | الوصف |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | نوع مجموعة يُستخدم نوع المتكرر الخاص به كنوع المتكرر في المجموعة الحالية. |
| [iterator](./iterator/) | نوع المتكرر. |
| [const_iterator](./const_iterator/) | نوع المتكرر الثابت. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | نوع العنصر المُفترض افتراضيًا. |
| [virtualized_iterator](./virtualized_iterator/) | نوع افتراضي. |

## انظر أيضًا

* الفئة [DomObject](../domobject/)
* الفئة [ICommentAuthorCollection](../icommentauthorcollection/)
* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)