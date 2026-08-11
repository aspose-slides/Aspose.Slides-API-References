---
title: HttpResponseHeaders
second_title: Aspose.Slides للـ C++ مرجع API
description: "يمثل مجموعة رؤوس 'Response'. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغّل new، لأنه سيؤدي إلى أخطاء وقت التشغيل أو/أو أخطاء في التأكيد. دائمًا غلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 131
url: /ar/system.net.http.headers/httpresponseheaders/
---
## HttpResponseHeaders فئة

يمثل مجموعة رؤوس 'Response'. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغّل new، لأنه سيسبّب أخطاءً وقت التشغيل أو/و أخطاءً في التفويض. دائمًا غلف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class HttpResponseHeaders : public System::Net::Http::Headers::HttpHeaders
```

## الطرق

| Method | Description |
| --- | --- |
| void [Add](../httpheaders/add/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | يتحقق من زوج اسم-قيمة جديد ويضيفه إلى المجموعة الحالية. |
| void [Add](../httpheaders/add/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من زوج اسم-قيمة جديد ويضيفه إلى المجموعة الحالية. |
| void [AddHeaders](./addheaders/)([System::SharedPtr](../../system/sharedptr/)\<[HttpHeaders](../httpheaders/)\>) override | يقوم بدمج نسخة HttpHeaders-فئة المحددة مع النسخة الحالية. |
| static void [AddKnownHeaders](./addknownheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) | يضيف الرؤوس المعروفة إلى المجموعة المحددة. |
| void [AddParsedValue](../httpheaders/addparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحصل على رأس بالاسم المحدد ويضيف قيمة مُحلَّلة إلى الرأس. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | يحصل على مكرِّر يشير إلى العنصر الأول (إن وجد) في المجموعة. لا يمكن استخدام هذا المكرِّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) تُرجع كائن نسخة من T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | يحصل على مكرِّر يشير إلى العنصر الأول (إن وجد) في النسخة المؤهَّلة بـ const من المجموعة. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | يحصل على مكرِّر يشير إلى العنصر الأول المؤهَّل بـ const (إن وجد) في المجموعة. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | يحصل على مكرِّر يشير مباشرةً بعد العنصر الأخير المؤهَّل بـ const (إن وجد) في المجموعة. |
| void [Clear](../httpheaders/clear/)() | يزيل جميع العناصر من المجموعة. |
| **bool** [Contains](../httpheaders/contains/)([String](../../system/string/)) |  |
| **bool** [ContainsParsedValue](../httpheaders/containsparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يتحقق ما إذا كان الرأس يحتوي على القيمة المحددة. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | يحصل على مكرِّر يشير مباشرةً بعد العنصر الأخير (إن وجد) في المجموعة. لا يمكن استخدام هذا المكرِّر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) تُرجع كائن نسخة من T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | يحصل على مكرِّر يشير مباشرةً بعد العنصر الأخير (إن وجد) في النسخة المؤهَّلة بـ const من المجموعة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أنه وفقًا لـ IEC 60559:1989 فإن NaN غير مساوية لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين على الرغم من أنه وفقًا لـ IEC 60559:1989 فإن NaN غير مساوية لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_AcceptRanges](./get_acceptranges/)() | يرجع قيمة رأس 'Accept-Ranges'. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_Age](./get_age/)() | يحصل على قيمة رأس 'Age'. |
| [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](../cachecontrolheadervalue/)\> [get_CacheControl](./get_cachecontrol/)() | يحصل على قيمة رأس 'Cache-Control'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Connection](./get_connection/)() | يرجع قيمة رأس 'Connection'. |
| [Nullable](../../system/nullable/)\<**bool**\> [get_ConnectionClose](./get_connectionclose/)() | يحصل على قيمة تشير إلى ما إذا كانت قيمة رأس 'Connection' تحتوي على 'Close'. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_Date](./get_date/)() | يحصل على قيمة رأس 'Date'. |
| [System::SharedPtr](../../system/sharedptr/)\<[EntityTagHeaderValue](../entitytagheadervalue/)\> [get_ETag](./get_etag/)() | يحصل على قيمة رأس 'ETag'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Location](./get_location/)() | يحصل على قيمة رأس 'Location'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Pragma](./get_pragma/)() | يرجع قيمة رأس 'Pragma'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\>\>\> [get_ProxyAuthenticate](./get_proxyauthenticate/)() | يرجع قيمة رأس 'Proxy-Authenticate'. |
| [System::SharedPtr](../../system/sharedptr/)\<[RetryConditionHeaderValue](../retryconditionheadervalue/)\> [get_RetryAfter](./get_retryafter/)() | يحصل على قيمة رأس 'Retry-After'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ProductInfoHeaderValue](../productinfoheadervalue/)\>\>\> [get_Server](./get_server/)() | يرجع قيمة رأس 'Server'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Trailer](./get_trailer/)() | يرجع قيمة رأس 'Trailer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](../transfercodingheadervalue/)\>\>\> [get_TransferEncoding](./get_transferencoding/)() | يرجع قيمة رأس 'Transfer-Encoding'. |
| [Nullable](../../system/nullable/)\<**bool**\> [get_TransferEncodingChunked](./get_transferencodingchunked/)() | يحصل على قيمة تشير إلى ما إذا كانت قيمة رأس 'Transfer-Encoding' تحتوي على 'Chunked'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ProductHeaderValue](../productheadervalue/)\>\>\> [get_Upgrade](./get_upgrade/)() | يرجع قيمة رأس 'Upgrade'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Vary](./get_vary/)() | يرجع قيمة رأس 'Vary'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ViaHeaderValue](../viaheadervalue/)\>\>\> [get_Via](./get_via/)() | يرجع قيمة رأس 'Via'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[WarningHeaderValue](../warningheadervalue/)\>\>\> [get_Warning](./get_warning/)() | يرجع قيمة رأس 'Warning'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\>\>\> [get_WwwAuthenticate](./get_wwwauthenticate/)() | يرجع قيمة رأس 'WWW-Authenticate'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد المرجع المرتبط بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\>\>\>\> [GetEnumerator](../httpheaders/getenumerator/)() override | يحصل على المُعدِّد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصَّصة. |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/)) | يرجع تمثيلًا نصيًا للقيم بحسب اسم الرأس المحدد. |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يرجع تمثيلًا نصيًا للقيم بحسب اسم الرأس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [String](../../system/string/)\>\>\> [GetHeaderStrings](../httpheaders/getheaderstrings/)() | يرجع مجموعة تحتوي على تمثيلات نصية لقيم الرؤوس. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetParsedValues](../httpheaders/getparsedvalues/)([String](../../system/string/)) | يرجع القيم المُحلَّلة بحسب اسم الرأس المحدد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [GetValues](../httpheaders/getvalues/)([String](../../system/string/)) | يرجع القيم المرتبطة بحسب الاسم المحدد. |
| [HttpResponseHeaders](./httpresponseheaders/)() | يبني نسخة جديدة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير لمعامل C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | تطبق دالة مُجمع على تسلسل. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | يحدّد ما إذا كانت جميع عناصر التسلسل تحقق شرطًا. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | يحدّد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | يحدّد ما إذا كان أي عنصر من التسلسل موجود أو يحقق شرطًا. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | يحسب متوسط تسلسل القيم الرقمية. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحسب متوسط تسلسل القيم الذي يتم الحصول عليه عبر استدعاء دالة تحويل على كل عنصر من التسلسل المدخل. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | يحوّل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | يضمّن تسلسلين. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | يحدّد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | يرجع عدد العناصر في التسلسل (محسوبًا عبر العد المباشر). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرجع عدد العناصر في التسلسل التي تحقق الشرط المحدد. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | يرجع العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | يرجع العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | يرجع العنصر الأول من التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | يرجع العنصر الأول من التسلسل الذي يحقق الشرط المحدد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | يرجع العنصر الأول من التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | يرجع العنصر الأول من التسلسل الذي يحقق شرطًا أو قيمة افتراضية إذا لم يُعثر على مثل هذا العنصر. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | يُجَمِّع عناصر التسلسل. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | يُجَمِّع عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | يرجع العنصر الأخير من التسلسل. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | يرجع العنصر الأخير من التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفّذ دالة تحويل على كل عنصر من تسلسل عام ويعيد القيمة العظمى الناتجة. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | ينفّذ دالة تحويل على كل عنصر من تسلسل عام ويعيد أصغر قيمة ناتجة. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | يُصَفي عناصر التسلسل بناءً على النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر التسلسل تص Ascending وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | يرتب عناصر التسلسل تنازليًا وفقًا لقيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | يعكس ترتيب عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | يحوِّل عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | يحوِّل كل عنصر من التسلسل إلى شكل جديد بدمج فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | يسقط كل عنصر من التسلسل ويجمع التسلسل الناتج في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | يتخطى عددًا محددًا من العناصر المتجاورة من بداية التسلسل ويعيد البقية. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | يرجع عددًا محددًا من العناصر المتجاورة من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | ينشئ مصفوفة من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | ينشئ List<T> من تسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | يُرشّح تسلسلًا بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصَّصة. |
| [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات المشتقة. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\> [ParsedValuesAsList](../httpheaders/parsedvaluesaslist/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحوّل القيم المُحلَّلة إلى قائمة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي بـ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| **bool** [Remove](../httpheaders/remove/)([String](../../system/string/)) | يحاول إزالة عنصر بالاسم المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| **bool** [RemoveParsedValue](../httpheaders/removeparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحصل على رأس بالاسم المحدد ويزيل قيمة مُحلَّلة من الرأس. |
| void [set_Age](./set_age/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | يضبط قيمة رأس 'Age'. |
| void [set_CacheControl](./set_cachecontrol/)([System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](../cachecontrolheadervalue/)\>) | يضبط قيمة رأس 'Cache-Control'. |
| void [set_ConnectionClose](./set_connectionclose/)([Nullable](../../system/nullable/)\<**bool**\>) | يضبط قيمة تُشير إلى ما إذا كانت قيمة رأس 'Connection' تحتوي على 'Close'. |
| void [set_Date](./set_date/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | يضبط قيمة رأس 'Date'. |
| void [set_ETag](./set_etag/)([System::SharedPtr](../../system/sharedptr/)\<[EntityTagHeaderValue](../entitytagheadervalue/)\>) | يضبط قيمة رأس 'ETag'. |
| void [set_Location](./set_location/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | يضبط قيمة رأس 'Location'. |
| void [set_RetryAfter](./set_retryafter/)([System::SharedPtr](../../system/sharedptr/)\<[RetryConditionHeaderValue](../retryconditionheadervalue/)\>) | يضبط قيمة رأس 'Retry-After'. |
| void [set_TransferEncodingChunked](./set_transferencodingchunked/)([Nullable](../../system/nullable/)\<**bool**\>) | يضبط قيمة تُشير إلى ما إذا كانت قيمة رأس 'Transfer-Encoding' تحتوي على 'Chunked'. |
| void [SetConfiguration](../httpheaders/setconfiguration/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<HttpHeaderParser\>\>\>, [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) |  |
| void [SetOrRemoveParsedValue](../httpheaders/setorremoveparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحصل على رأس بالاسم المحدد ويضبط أو يزيل قيمته. سيتم إزالة قيمة الرأس عندما يكون معامل 'value' هو nullptr، وإلا سيتم ضبط قيمة مُحلَّلة. |
| void [SetParsedValue](../httpheaders/setparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحصل على رأس بالاسم المحدد ويضبط قيمة مُحلَّلة للرأس. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويُعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](../httpheaders/tostring/)() const override | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصَّصة إلى نص. |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [String](../../system/string/)) | يحاول إضافة زوج اسم-قيمة جديد إلى المجموعة الحالية. |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | يضيف مجموعة من أزواج الاسم-القيمة إلى المجموعة الحالية. |
| **bool** [TryGetValues](../httpheaders/trygetvalues/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&) | يحاول الحصول على القيم المقابلة بالاسم المحدد. |
| **bool** [TryParseAndAddValue](../httpheaders/tryparseandaddvalue/)([String](../../system/string/), [String](../../system/string/)) | يحاول تحليل القيمة المحددة وإضافتها إلى قيم الرأس. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحراس [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | يحصل على تنفيذ begin const iterator للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | يحصل على تنفيذ begin iterator للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | يحصل على تنفيذ end const iterator للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | يحصل على تنفيذ end iterator للحاوية الحالية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [HttpHeaders](../httpheaders/)
* النطاق [System::Net::Http::Headers](../)
* المكتبة [Aspose.Slides](../../)