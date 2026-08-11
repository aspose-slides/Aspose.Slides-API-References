---
title: _KeyList
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "تنفّذ قائمة مفاتيح القاموس. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التحقق. دائمًا احwrap هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 14
url: /ar/system.collections.generic/_keylist/
---
## _KeyList فئة

يُنفّذ قائمة مفاتيح القاموس. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تُنشئ أبداً مثيلاً من هذا النوع على المكدس أو باستخدام عامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل أو أخطاء التأكيد. قم دائماً بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل.

```cpp
template<typename Dict>class _KeyList : public System::Collections::Generic::_KeyCollection<Dict>
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| Dict | نوع [Dictionary](../dictionary/). |

## Methods

| طريقة | الوصف |
| --- | --- |
|  [_KeyCollection](../_keycollection/_keycollection/)(const typename Dict::Ptr\&) | يهيئ مجموعة تُشير إلى القاموس المحدد. |
|  [_KeyList](./_keylist/)(const typename Dict::Ptr\&) | يهيئ مجموعة تُشير إلى القاموس المحدد. |
| void [Add](../ikvcollection/add/)(const T\&) override | يضيف عنصراً إلى الحاوية. |
|  [BaseKVCollection](../basekvcollection/basekvcollection/)(const typename Dict::Ptr\&) | ينشئ مجموعة. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | يحصل على مُؤشِّر يبدأ من العنصر الأول (إن وُجد) في المجموعة. لا يمكن استخدام هذا المُؤشِّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) تُعيد نسخة من الكائن من النوع T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | يحصل على مُؤشِّر يبدأ من العنصر الأول (إن وُجد) في النسخة المتقرفة بـ const من المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | يحصل على مُؤشِّر يبدأ من العنصر الأول المتقرف بـ const (إن وُجد) في المجموعة. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | يحصل على مُؤشِّر بعد آخر عنصر متقرف بـ const (إن وُجد) في المجموعة. |
| void [Clear](../ikvcollection/clear/)() override | يحذف جميع العناصر من الحاوية. |
| **bool** [Contains](./contains/)(const [TKey](../_keycollection/tkey/)\&) const override | يتحقق إذا كان المفتاح المحدد موجوداً في المجموعة. |
| void [CopyTo](../basekvcollection/copyto/)([ArrayPtr](../../system/arrayptr/)\<KV\>, int) override | ينسخ البيانات إلى عناصر المصفوفة الموجودة. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | يحصل على مُؤشِّر بعد آخر عنصر (إن وُجد) في المجموعة. لا يمكن استخدام هذا المُؤشِّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) تُعيد نسخة من الكائن من النوع T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | يحصل على مُؤشِّر بعد آخر عنصر (إن وُجد) في النسخة المتقرفة بـ const من المجموعة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين بالرغم من أن IEC 60559:1989 لا تعتبر NaN مساويًا لأي قيمة. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNين متساويين بالرغم من أن IEC 60559:1989 لا تعتبر NaN مساويًا لأي قيمة. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| int [get_Count](../basekvcollection/get_count/)() const override | يحصل على عدد العناصر. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | يتحقق ما إذا كانت المجموعة ذات حجم ثابت. |
| **bool** [get_IsReadOnly](../ikvcollection/get_isreadonly/)() const override | يتحقق إذا كانت الحاوية للقراءة فقط. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | يحصل على الكائن الذي تُزامن عبره المجموعة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّّ المرجع المرتبطة بالكائن. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[TKey](../_keycollection/tkey/)\>\> [GetEnumerator](../_keycollection/getenumerator/)() override | يحصل على عدِّاد يجري عبر المفاتيح. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ما يعادل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصَّصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. ما يعادل نداء C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | المنشئ الافتراضي. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | منشئ النسخ. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | منشئ النقل. |
| [TKey](../_keycollection/tkey/) [idx_get](./idx_get/)(int) const override | يحصل على المفتاح في الموضع المحدد. |
| void [idx_set](../ikvcollection/idx_set/)(int, T) override | دالة الضبط. |
| int [IndexOf](../ikvcollection/indexof/)(const T\&) const override | يحصل على فهرس العنصر في الحاوية. |
| void [Insert](../ikvcollection/insert/)(int, const T\&) override | يُدرج العنصر في الموضع المحدد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق إذا كان الكائن يمثل مثيلاً للنوع الموصوف بـ targetType. ما يعادل عامل C# `is`. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة المجمّع على تسلسل. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدِّد ما إذا جميع عناصر التسلسل تفي بشرط. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | يحدِّد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدِّد ما إذا كان أي عنصر في التسلسل موجودًا أو يفي بشرط. |
| T [LINQ_Average](../ienumerable/linq_average/)() | يحسب متوسط تسلسل القيم العددية. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب متوسط تسلسل القيم التي تُستخرج عبر استدعاء دالة تحويل على كل عنصر من التسلسل المدخل. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | يحوِّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | يدمج سلسلتين. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | يحدِّد إذا كان التسلسل يحتوي على القيمة المحددة. |
| int [LINQ_Count](../ienumerable/linq_count/)() | يرجع عدد العناصر في التسلسل (محسوبًا عن طريق العدّ المباشر). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرجع عدد العناصر في التسلسل التي تُوفي بالشرط المحدد. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | يرجع العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | يرجع العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)() | يرجع العنصر الأول في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرجع العنصر الأول في التسلسل الذي يفي بالشرط المحدد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | يرجع العنصر الأول في التسلسل، أو القيمة الافتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يرجع العنصر الأول في التسلسل الذي يوفي بشرط أو القيمة الافتراضية إذا لم يُعثر على مثل هذا العنصر. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يجمع عناصر التسلسل. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يجمع عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | يرجع العنصر الأخير في التسلسل. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | يرجع العنصر الأخير في التسلسل، أو القيمة الافتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يستدعي دالة تحويل على كل عنصر من تسلسل عام ويُعيد القيمة العظمى الناتجة. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يستدعي دالة تحويل على كل عنصر من تسلسل عام ويُعيد القيمة الصغرى الناتجة. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | يُرشّح عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يفرز عناصر التسلسل بترتيب تصاعدي وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يفرز عناصر التسلسل بترتيب تنازلي وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | يعكس ترتيب عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحوِّل عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحوِّل كل عنصر من التسلسل إلى صيغة جديدة عبر دمج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | يُسقط كل عنصر من التسلسل ويجَمِّع التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتالية من بداية التسلسل ويُعيد الباقي. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | يُعيد عددًا محددًا من العناصر المتتالية من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | يُنشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | يُنشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | يُرشّح تسلسل بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل C# lock() . استدعِه مباشرة أو استخدم كائن المراقبة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ما يعادل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصَّصة. |
|  [Object](../../system/object/object/)() | يُنشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ البُنى الفرعية. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | عامل إسناد النقل. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | عامل إسناد النقل. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل إسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ البُنى الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن قيم بقيمة nullptr بالمرجع. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) للحالة التي يكون فيها السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| **bool** [Remove](../ikvcollection/remove/)(const T\&) override | يزيل العنصر من الحاوية. |
| void [RemoveAt](../ikvcollection/removeat/)(int) override | يزيل العنصر في الموضع المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| void [SetTemplateWeakPtr](../basekvcollection/settemplateweakptr/)(**uint32_t**) override | يتيح التجميع، لكنه لا يفعل شيئًا فعليًا لأن هذا الهيكل لا يمتلك بيانات. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ما يعادل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصَّصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل C# lock() . استدعِه مباشرة أو استخدم كائن المراقبة [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<[TKey](../_keycollection/tkey/)\> * [virtualizeBeginConstIterator](../_keycollection/virtualizebeginconstiterator/)() const override | يحصل على تنفيذ البدء بالمؤشر const للعنصر الحالي. |
| System::Details::VirtualizedIteratorBase\<[TKey](../_keycollection/tkey/)\> * [virtualizeBeginIterator](../_keycollection/virtualizebeginiterator/)() override | يحصل على تنفيذ البدء بالمؤشر للعنصر الحالي. |
| System::Details::VirtualizedIteratorBase\<[TKey](../_keycollection/tkey/)\> * [virtualizeEndConstIterator](../_keycollection/virtualizeendconstiterator/)() const override | يحصل على تنفيذ النهاية بالمؤشر const للعنصر الحالي. |
| System::Details::VirtualizedIteratorBase\<[TKey](../_keycollection/tkey/)\> * [virtualizeEndIterator](../_keycollection/virtualizeenditerator/)() override | يحصل على تنفيذ النهاية بالمؤشر للعنصر الحالي. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | المُدمِّر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يُفرغ جميع بنى البيانات الداخلية. |

## Typedefs

| تعريف النوع | الوصف |
| --- | --- |
| [TKey](./tkey/) | نوع المفتاح. |

## See Also

* Class [_KeyCollection](../_keycollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)