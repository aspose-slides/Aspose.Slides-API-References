---
title: HttpContentHeaders
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل مجموعة رؤوس 'Content'. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا غلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 66
url: /ar/system.net.http.headers/httpcontentheaders/
---
## فئة HttpContentHeaders

يمثل مجموعة رؤوس 'Content'. يجب تخصيص كائنات هذه الفئة باستخدام وظيفة [System::MakeObject()](../../system/makeobject/) فقط. لا تُنشئ أبدًا نسخة من هذا النوع على المكدس أو باستخدام المشغّل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class HttpContentHeaders : public System::Net::Http::Headers::HttpHeaders
```

## طرق

| طريقة | وصف |
| --- | --- |
| void [Add](../httpheaders/add/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | يتحقق من صحة زوج اسم-قيمة جديد ويضيفه إلى المجموعة الحالية. |
| void [Add](../httpheaders/add/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من صحة زوج اسم-قيمة جديد ويضيفه إلى المجموعة الحالية. |
| virtual void [AddHeaders](../httpheaders/addheaders/)([System::SharedPtr](../../system/sharedptr/)\<[HttpHeaders](../httpheaders/)\>) | يقوم بدمج نسخة HttpHeaders-class المحددة مع الحالية. |
| static void [AddKnownHeaders](./addknownheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) | يضيف الرؤوس المعروفة إلى المجموعة المحددة. |
| void [AddParsedValue](../httpheaders/addparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحصل على رأس وفق الاسم المحدد ويضيف قيمة مُحلَّلة إلى الرأس. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | يحصل على مكرِّر يشير إلى العنصر الأول (إن وجد) في المجموعة. لا يمكن استخدام هذا المكرِّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) تُعيد نسخة من T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | يحصل على مكرِّر يشير إلى العنصر الأول (إن وجد) في النسخة المؤهَّلة بـ const من المجموعة. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | يحصل على مكرِّر يشير إلى أول عنصر مؤهَّل بـ const (إن وجد) في المجموعة. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | يحصل على مكرِّر يشير مباشرةً بعد آخر عنصر مؤهَّل بـ const (إن وجد) في المجموعة. |
| void [Clear](../httpheaders/clear/)() | يزيل جميع العناصر من المجموعة. |
| **bool** [Contains](../httpheaders/contains/)([String](../../system/string/)) |  |
| **bool** [ContainsParsedValue](../httpheaders/containsparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يتحقق مما إذا كان الرأس يحتوي على القيمة المحددة. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | يحصل على مكرِّر يشير مباشرةً بعد آخر عنصر (إن وجد) في المجموعة. لا يمكن استخدام هذا المكرّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) تُعيد نسخة من T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | يحصل على مكرِّر يشير مباشرةً بعد آخر عنصر (إن وجد) في النسخة المؤهَّلة بـ const من المجموعة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN-ان متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN-ان متساويتين رغم أن معيار IEC 60559:1989 يحدد أن NaN ليست مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_Allow](./get_allow/)() | يحصل على قيمة رأس 'Allow'. |
| [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](../contentdispositionheadervalue/)\> [get_ContentDisposition](./get_contentdisposition/)() | يحصل على قيمة رأس 'Content-Disposition'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_ContentEncoding](./get_contentencoding/)() | يحصل على قيمة رأس 'Content-Encoding'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_ContentLanguage](./get_contentlanguage/)() | يحصل على قيمة رأس 'Content-Language'. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_ContentLength](./get_contentlength/)() | يحصل على قيمة رأس 'Content-Length'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_ContentLocation](./get_contentlocation/)() | يحصل على قيمة رأس 'Content-Location'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_ContentMD5](./get_contentmd5/)() | يحصل على قيمة رأس 'Content-MD5'. |
| [System::SharedPtr](../../system/sharedptr/)\<[ContentRangeHeaderValue](../contentrangeheadervalue/)\> [get_ContentRange](./get_contentrange/)() | يحصل على قيمة رأس 'Content-Range'. |
| [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\> [get_ContentType](./get_contenttype/)() | يحصل على قيمة رأس 'Content-Type'. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_Expires](./get_expires/)() | يحصل على قيمة رأس 'Expires'. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_LastModified](./get_lastmodified/)() | يحصل على قيمة رأس 'Last-Modified'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عدّاد المرجع المرتبطة بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\>\>\> [GetEnumerator](../httpheaders/getenumerator/)() override | يحصل على المكرّر. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/)) | يعيد تمثيلًا نصيًا للقيم حسب اسم الرأس المحدد. |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يعيد تمثيلًا نصيًا للقيم حسب اسم الرأس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [String](../../system/string/)\>\>\> [GetHeaderStrings](../httpheaders/getheaderstrings/)() | يعيد مجموعة تحتوي على تمثيلات نصية لقيم الرؤوس. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetParsedValues](../httpheaders/getparsedvalues/)([String](../../system/string/)) | يعيد القيم المحللة حسب اسم الرأس المحدد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [GetValues](../httpheaders/getvalues/)([String](../../system/string/)) | يعيد القيم المقابلة حسب الاسم المحدد. |
|  [HttpContentHeaders](./httpcontentheaders/)([HeaderFunc](../headerfunc/)\<[Nullable](../../system/nullable/)\<**int64_t**\>\>) | يبني نسخة جديدة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الذي يصفه targetType. نظير للمشغل C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | يطبق دالة تجميع على تسلسل. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدد ما إذا كانت جميع عناصر التسلسل تفي بشرط. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | يحدد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدد ما إذا كان هناك أي عنصر في التسلسل أو يفي بشرط. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | يحسب المتوسط لتسلسل من القيم الرقمية. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب المتوسط لتسلسل من القيم التي يتم الحصول عليها عبر استدعاء دالة تحويل على كل عنصر من التسلسل المدخل. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | يحول العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | يلصق تسلسلين. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | يحدد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | يعيد عدد العناصر في التسلسل (محسوبًا بالعد المباشر). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يعيد عدد العناصر في التسلسل التي تفي بالشرط المحدد. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | يعيد العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | يعيد العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | يعيد العنصر الأول في التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يعيد أول عنصر في التسلسل يفي بالشرط المحدد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | يعيد أول عنصر في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يعيد أول عنصر في التسلسل يفي بشرط أو قيمة افتراضية إذا لم يُعثر على مثل هذا العنصر. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يجمع عناصر التسلسل. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يجمع عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | يعيد آخر عنصر في التسلسل. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | يعيد آخر عنصر في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | يفلتر عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر التسلسل بترتيب تصاعدي وفق قيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر التسلسل بترتيب تنازلي وفق قيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | يعكس ترتيب العناصر في التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحوّل عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحوّل كل عنصر من التسلسل إلى شكل جديد من خلال دمج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | يسقط كل عنصر من التسلسل ويجمع التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتتالية من بداية التسلسل ويعيد البقية. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | يعيد عددًا محددًا من العناصر المتتالية من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | يفلتر تسلسلًا وفق الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدع مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ من الفئات المشتقة. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\> [ParsedValuesAsList](../httpheaders/parsedvaluesaslist/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحول القيم المحللة إلى قائمة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| **bool** [Remove](../httpheaders/remove/)([String](../../system/string/)) | يحاول إزالة عنصر حسب الاسم المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| **bool** [RemoveParsedValue](../httpheaders/removeparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحصل على رأس وفق الاسم المحدد ويزيل قيمة مُحلَّلة من الرأس. |
| void [set_ContentDisposition](./set_contentdisposition/)([System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](../contentdispositionheadervalue/)\>) | يضبط قيمة رأس 'Content-Disposition'. |
| void [set_ContentLength](./set_contentlength/)([Nullable](../../system/nullable/)\<**int64_t**\>) | يضبط قيمة رأس 'Content-Length'. |
| void [set_ContentLocation](./set_contentlocation/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يضبط قيمة رأس 'Content-Location'. |
| void [set_ContentMD5](./set_contentmd5/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | يضبط قيمة رأس 'Content-MD5'. |
| void [set_ContentRange](./set_contentrange/)([System::SharedPtr](../../system/sharedptr/)\<[ContentRangeHeaderValue](../contentrangeheadervalue/)\>) | يضبط قيمة رأس 'Content-Range'. |
| void [set_ContentType](./set_contenttype/)([System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>) | يضبط قيمة رأس 'Content-Type'. |
| void [set_Expires](./set_expires/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | يضبط قيمة رأس 'Expires'. |
| void [set_LastModified](./set_lastmodified/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | يضبط قيمة رأس 'Last-Modified'. |
| void [SetConfiguration](../httpheaders/setconfiguration/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<HttpHeaderParser\>\>\>, [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) |  |
| void [SetOrRemoveParsedValue](../httpheaders/setorremoveparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحصل على رأس وفق الاسم المحدد ويضبط قيمته أو يزيلها. سيتم إزالة قيمة الرأس عندما يكون معامل 'value' هو nullptr، وإلا سيتم ضبط قيمة مُحلَّة. |
| void [SetParsedValue](../httpheaders/setparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحصل على رأس وفق الاسم المحدد ويضبط قيمة مُحلَّة لل رأس. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n'th كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عدّاد المرجع المشترك. لا يجب استدعاؤه مباشرةً؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](../httpheaders/tostring/)() const override | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [String](../../system/string/)) | يحاول إضافة زوج اسم-قيمة جديد إلى المجموعة الحالية. |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | يضيف مجموعة من أزواج الاسم-القيمة إلى المجموعة الحالية. |
| **bool** [TryGetValues](../httpheaders/trygetvalues/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&) | يحاول الحصول على القيم المقابلة حسب الاسم المحدد. |
| **bool** [TryParseAndAddValue](../httpheaders/tryparseandaddvalue/)([String](../../system/string/), [String](../../system/string/)) | يحاول تحليل القيمة المحددة وإضافتها إلى قيم الرأس. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ تركيبة C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل بيان C# lock(). استدع مباشرةً أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | يحصل على تنفيذ begin const iterator للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | يحصل على تنفيذ begin iterator للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | يحصل على تنفيذ end const iterator للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | يحصل على تنفيذ end iterator للحاوية الحالية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ استعن بالمؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عدّاد المرجع الضعيف. لا يجب استدعاؤه مباشرةً؛ استعن بالمؤشرات الذكية أو ThisProte Protector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [HttpHeaders](../httpheaders/)
* النطاق [System::Net::Http::Headers](../)
* المكتبة [Aspose.Slides](../../)