---
title: BaseDictionary
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: "يُنفّذ شفرة مشتركة لهياكل بيانات شبيهة بالقاموس المختلفة (مثل Dictionary, SortedDictionary). لا ينبغي استخدامه مباشرةً، إلا عبر الوراثة عند تعريف الحاويات. يجب إنشاء كائنات هذه الفئة باستخدام دالة System::MakeObject() فقط. لا تُنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام operator new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال تأكيد. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 53
url: /ar/system.collections.generic/basedictionary/
---
## BaseDictionary فئة

ينفّذ شفرة مشتركة لهياكل بيانات شبيهة بالقاموس المختلفة (مثل [Dictionary](../dictionary/)، [SortedDictionary](../sorteddictionary/)). لا ينبغي استخدامه مباشرةً، إلا من خلال الوراثة عند تعريف الحاويات. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام operator new، حيث سيؤدي ذلك إلى أخطاء في وقت التشغيل و/أو أعطال في التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريرها إلى الدوال كمعامل.

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| Map | نوع الخريطة الأساسي. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | خاص بـ C++. |
| void [Add](./add/)(const key_t\&, const mapped_t\&) override | يضيف زوج المفتاح-القيمة إلى القاموس. |
| [BaseDictionary](./basedictionary/)() | ينشئ هيكل بيانات فارغ. |
| [BaseDictionary](./basedictionary/)(int, const Args\&...) | منشئ توجيه لنقل الوسائط إلى منشئ الخريطة الأساسي. |
| [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *, const Args\&...) | منشئ نسخ. |
| [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *) | منشئ نسخ. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | يرجع مكرراً إلى غلاف KVPair للعنصر المفتاح-القيمة في الحاوية. مُنفذ بنمط C# - يجب أن يُعيد المكرّر كائن KVPair مع واجهة get_Key() و get_Value(). إذا كانت الحاوية فارغة، سيكون المكرّر المرجع مساويًا لـ [end()](../ienumerable/end/). |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | يحصل على مكرّر يشير إلى العنصر الأول (إن وجد) في المجموعة. لا يمكن استخدام هذا المكرّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) تُرجع نسخة من الكائن من النوع T. |
| stl_const_iterator [cbegin](./cbegin/)() const | يرجع مكرراً إلى العنصر الأول في الحاوية. مُنفذ بنمط STL. إذا كانت الحاوية فارغة، سيكون المكرّر المرجع مساويًا لـ [end()](../ienumerable/end/). |
| stl_const_iterator [cend](./cend/)() const | يرجع مكرراً إلى العنصر الذي يلي العنصر الأخير في الحاوية. مُنفذ بنمط STL. هذا العنصر يعمل كعنصر نائب؛ أي محاولة للوصول إليه تؤدي إلى سلوك غير معرف. |
| void [Clear](./clear/)() override | يحذف جميع العناصر. |
| **bool** [ContainsKey](./containskey/)(const key_t\&) const override | يفحص ما إذا كان المفتاح موجودًا في القاموس. |
| **bool** [ContainsValue](./containsvalue/)(const mapped_t\&) | يفحص ما إذا كانت القيمة موجودة في القاموس. يستخدم operator == لمقارنة القيم. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | ينسخ محتويات القاموس إلى عناصر المصفوفة الحالية. |
| Map\& [data](./data/)() | مستخرج تخزين البيانات الأساسي. |
| const Map\& [data](./data/)() const | مستخرج تخزين البيانات الأساسي. |
| [const_iterator](./const_iterator/) [end](./end/)() const | يرجع مكرراً إلى غلاف KVPair للعنصر المفتاح-القيمة الذي يلي العنصر الأخير في الحاوية. مُنفذ بنمط C# - يجب أن يُعيد المكرّر كائن KVPair مع واجهة get_Key() و get_Value(). هذا العنصر يعمل كعنصر نائب؛ أي محاولة للوصول إليه تؤدي إلى سلوك غير معرف. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | يحصل على مكرّر يشير مباشرة بعد العنصر الأخير (إن وجد) في المجموعة. لا يمكن استخدام هذا المكرّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../ienumerable/getenumerator/) تُرجع نسخة من الكائن من النوع T. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN مساوية ل NaN على الرغم من أن IEC 60559:1989 تنص على أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN مساوية ل NaN على الرغم من أن IEC 60559:1989 تنص على أن NaN غير مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **int32_t** [get_Count](./get_count/)() const override | يحصل على عدد العناصر. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | يفحص ما إذا كان حجم المجموعة ثابتًا. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | يفحص ما إذا كانت المجموعة للقراءة فقط. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | يفحص ما إذا كانت الحاوية خالية من التضارب (thread-safe). |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | يصل إلى مجموعة المفاتيح. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | يحصل على الكائن الذي يتم من خلاله مزامنة المجموعة. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | يصل إلى مجموعة القيم. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[KeyValuePair](../keyvaluepair/)\<key_t, mapped_t\>\>\> [GetEnumerator](./getenumerator/)() | ينشئ نسخة من المُعدد، يجب أن تُنفّذ في الفئة الفرعية. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مماثل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مماثل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | يرجع القيمة إذا وجدت؛ أو **Value()** غير ذلك. |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | يرجع القيمة إذا وجدت؛ أو **defaultValue** غير ذلك. |
| mapped_t [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | يرجع القيمة إذا وجدت؛ أو **null** غير ذلك. لا معنى له إلا للأنواع المرجعية. |
| [ICollection](../icollection/icollection/)() | منشئ افتراضي. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | منشئ نسخ. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | منشئ نقل. |
| mapped_t [idx_get](./idx_get/)(const key_t\&) const override | دالة جلب ذات مفتاح. |
| void [idx_set](./idx_set/)(const key_t\&, mapped_t) override | دالة ضبط ذات مفتاح. تُغيّر أو تُنشئ العنصر. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. مماثل لمعامل C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبّق دالة تجميع على تسلسل. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدّد ما إذا كان جميع عناصر التسلسل تُلبّي شرطًا. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | يحدّد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدّد ما إذا كان هناك أي عنصر في التسلسل أو يُلبّي شرطًا. |
| T [LINQ_Average](../ienumerable/linq_average/)() | يحسب متوسط قيم رقمية في تسلسل. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب متوسط قيم في تسلسل يتم الحصول عليها عبر استدعاء دالة تحويل لكل عنصر في التسلسل المدخل. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | يحوّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | يرابط تسلسلين. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | يحدّد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../ienumerable/linq_count/)() | يرُد عدد العناصر في التسلسل (محسوبًا عبر العد المباشر). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرُد عدد العناصر في التسلسل التي تُلبّي الشرط المحدد. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | يرُد العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | يرُد العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)() | يرُد العنصر الأول في التسلسل. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرُد العنصر الأول في التسلسل الذي يُلبّي الشرط المحدد. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | يرُد العنصر الأول في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يرُد العنصر الأول في التسلسل الذي يُلبّي شرطًا أو قيمة افتراضية إذا لم يُعثر على مثل هذا العنصر. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يُجّمّع عناصر تسلسل. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يُجّمّع عناصر تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | يرُد العنصر الأخير في تسلسل. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | يرُد العنصر الأخير في تسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يستدعي دالة تحويل على كل عنصر من تسلسل عام ويُعيد أقصى قيمة ناتجة. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يستدعي دالة تحويل على كل عنصر من تسلسل عام ويُعيد أصغرى قيمة ناتجة. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | يُرشّح عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر تسلسل تصاعديًا وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر تسلسل تنازليًا وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | يعكس ترتيب عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحوِّل عناصر تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحوِّل كل عنصر في تسلسل إلى صيغة جديدة مع دمج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | يُسقط كل عنصر من تسلسل ويُدمج التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتالية من بداية تسلسل ويُعيد البقية. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | يرُد عددًا محددًا من العناصر المتتالية من بداية تسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | يرشح تسلسلًا بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | يُنفّذ قفل بيان C# lock(). يُستدعى مباشرةً أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مماثل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يُهيّئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا في الواقع، فقط يُهيّئ كائنًا جديدًا ويُمكّن إنشاء نسخ فرعية. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | عامل إسناد نقل. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | عامل إسناد نقل. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل إسناد. لا ينسخ شيئًا في الواقع، فقط يُهيّئ كائنًا جديدًا ويُمكّن إنشاء نسخ فرعية. |
| virtual mapped_t\& [operator[]](./operator[]/)(const key_t\&) | دالة وصول. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| **bool** [Remove](./remove/)(const key_t\&) override | يزيل مفتاحًا محددًا من القاموس. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يُقّلل عدّاد المرجع المشترك بقيمة محددة. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقّلل ويُعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مماثل لطريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| **bool** [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | يبحث عن قيمة ذات مفتاح ويسترجعها إذا وجدت. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يُنفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يُنفّذ إلغاء قفل بيان C# lock(). يُستدعى مباشرةً أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | يحصل على تنفيذ مكرّر البداية الثابت للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | يحصل على تنفيذ مكرّر البداية للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | يحصل على تنفيذ مكرّر النهاية الثابت للحاوية الحالية. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | يحصل على تنفيذ مكرّر النهاية للحاوية الحالية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقّلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | المدمر. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## التعريفات

| تعريف نوع | الوصف |
| --- | --- |
| [map_t](./map_t/) | نوع الخريطة الداخلي. |
| [KeyCollection](./keycollection/) | تأكد من أننا نستخدم المخصص الصحيح مع نوع التخزين الأساسي. |
| [ValueCollection](./valuecollection/) | مجموعة القيم. |
| [KVPair](./kvpair/) | نوع زوج المفتاح-القيمة. |
| [BaseType](./basetype/) | واجهة مُنفّذة. |
| [iterator](./iterator/) | نوع المكرّر. |
| [const_iterator](./const_iterator/) | نوع المكرّر الثابت. |

## انظر أيضًا

* الفئة [IDictionary](../idictionary/)
* النطاق [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)