---
title: HttpRequestHeaders
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يمثل مجموعة رؤوس 'Request'. يجب إنشاء كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبب أخطاء وقت التشغيل أو أخطاء تأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 118
url: /ar/system.net.http.headers/httprequestheaders/
---
## HttpRequestHeaders فئة

يمثل مجموعة رؤوس 'Request'. يجب إنشاء كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأن ذلك سيسبّب أخطاء وقت التشغيل أو أخطاء تأكيد. يجب دائماً تغليف هذه الفئة في مؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريرها إلى الدوال كمعامل.

```cpp
class HttpRequestHeaders : public System::Net::Http::Headers::HttpHeaders
```

## طرق

| طريقة | وصف |
| --- | --- |
| void [Add](../httpheaders/add/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | يتحقق من صحة زوج اسم-قيمة جديد ويضيفه إلى المجموعة الحالية. |
| void [Add](../httpheaders/add/)([String](../../system/string/), [String](../../system/string/)) | يتحقق من صحة زوج اسم-قيمة جديد ويضيفه إلى المجموعة الحالية. |
| void [AddHeaders](./addheaders/)([System::SharedPtr](../../system/sharedptr/)\<[HttpHeaders](../httpheaders/)\>) override | يقوم بدمج نسخة HttpHeaders-class المحددة مع الحالية. |
| static void [AddKnownHeaders](./addknownheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) | يضيف الرؤوس المعروفة إلى المجموعة المحددة. |
| void [AddParsedValue](../httpheaders/addparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يحصل على الرأس بالاسم المحدد ويضيف قيمة مُحللة إلى الرأس. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | يحصل على مؤشرات إلى العنصر الأول (إن وجد) في المجموعة. لا يمكن استخدام هذا المؤشر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) يُعيد نسخة من الكائن من النوع T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | يحصل على مؤشرات إلى العنصر الأول (إن وجد) من نسخة المجموعة المؤهلة بـ const. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | يحصل على مؤشرات إلى العنصر الأول المؤهل بـ const (إن وجد) في المجموعة. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | يحصل على مؤشرات إلى ما يلي العنصر الأخير المؤهل بـ const (إن وجد) في المجموعة. |
| void [Clear](../httpheaders/clear/)() | يزيل جميع العناصر من المجموعة. |
| **bool** [Contains](../httpheaders/contains/)([String](../../system/string/)) |  |
| **bool** [ContainsParsedValue](../httpheaders/containsparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | يتحقق مما إذا كان الرأس يحتوي على القيمة المحددة. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | يحصل على مؤشرات إلى ما يلي العنصر الأخير (إن وجد) في المجموعة. لا يمكن استخدام هذا المؤشر لتغيير الكائن المشار إليه لأن [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) يُعيد نسخة من الكائن من النوع T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | يحصل على مؤشرات إلى ما يلي العنصر الأخير (إن وجد) في نسخة المجموعة المؤهلة بـ const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN-ان متساويتين رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يُحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر NaN-ان متساويتين رغم أنه وفقًا لـ IEC 60559:1989 لا تكون NaN مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](../mediatypewithqualityheadervalue/)\>\>\> [get_Accept](./get_accept/)() | إرجاع قيمة رأس 'Accept'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[StringWithQualityHeaderValue](../stringwithqualityheadervalue/)\>\>\> [get_AcceptCharset](./get_acceptcharset/)() | إرجاع قيمة رأس 'Accept-Charset'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[StringWithQualityHeaderValue](../stringwithqualityheadervalue/)\>\>\> [get_AcceptEncoding](./get_acceptencoding/)() | إرجاع قيمة رأس 'Accept-Encoding'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[StringWithQualityHeaderValue](../stringwithqualityheadervalue/)\>\>\> [get_AcceptLanguage](./get_acceptlanguage/)() | إرجاع قيمة رأس 'Accept-Language'. |
| [System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\> [get_Authorization](./get_authorization/)() | الحصول على قيمة رأس 'Authorization'. |
| [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](../cachecontrolheadervalue/)\> [get_CacheControl](./get_cachecontrol/)() | الحصول على قيمة رأس 'Cache-Control'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Connection](./get_connection/)() | إرجاع قيمة رأس 'Connection'. |
| [Nullable](../../system/nullable/)\<**bool**\> [get_ConnectionClose](./get_connectionclose/)() | الحصول على قيمة تُظهر ما إذا كانت قيمة رأس 'Connection' تحتوي على 'Close'. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_Date](./get_date/)() | الحصول على قيمة رأس 'Date'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](../namevaluewithparametersheadervalue/)\>\>\> [get_Expect](./get_expect/)() | إرجاع قيمة رأس 'Expect'. |
| [Nullable](../../system/nullable/)\<**bool**\> [get_ExpectContinue](./get_expectcontinue/)() | الحصول على قيمة تُظهر ما إذا كانت قيمة رأس 'Expect' تحتوي على 'Continue'. |
| [String](../../system/string/) [get_From](./get_from/)() | الحصول على قيمة رأس 'From'. |
| [String](../../system/string/) [get_Host](./get_host/)() | الحصول على قيمة رأس 'Host'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[EntityTagHeaderValue](../entitytagheadervalue/)\>\>\> [get_IfMatch](./get_ifmatch/)() | إرجاع قيمة رأس 'If-Match'. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_IfModifiedSince](./get_ifmodifiedsince/)() | الحصول على قيمة رأس 'If-Modified-Since'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[EntityTagHeaderValue](../entitytagheadervalue/)\>\>\> [get_IfNoneMatch](./get_ifnonematch/)() | إرجاع قيمة رأس 'If-None-Match'. |
| [System::SharedPtr](../../system/sharedptr/)\<[RangeConditionHeaderValue](../rangeconditionheadervalue/)\> [get_IfRange](./get_ifrange/)() | الحصول على قيمة رأس 'If-Range'. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_IfUnmodifiedSince](./get_ifunmodifiedsince/)() | الحصول على قيمة رأس 'If-Unmodified-Since'. |
| [Nullable](../../system/nullable/)\<**int32_t**\> [get_MaxForwards](./get_maxforwards/)() | الحصول على قيمة رأس 'Max-Forwards'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Pragma](./get_pragma/)() | إرجاع قيمة رأس 'Pragma'. |
| [System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\> [get_ProxyAuthorization](./get_proxyauthorization/)() | الحصول على قيمة رأس 'Proxy-Authorization'. |
| [System::SharedPtr](../../system/sharedptr/)\<[RangeHeaderValue](../rangeheadervalue/)\> [get_Range](./get_range/)() | الحصول على قيمة رأس '[Range](../../system/range/)'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Referrer](./get_referrer/)() | الحصول على قيمة رأس 'Referer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[TransferCodingWithQualityHeaderValue](../transfercodingwithqualityheadervalue/)\>\>\> [get_TE](./get_te/)() | إرجاع قيمة رأس 'TE'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Trailer](./get_trailer/)() | إرجاع قيمة رأس 'Trailer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](../transfercodingheadervalue/)\>\>\> [get_TransferEncoding](./get_transferencoding/)() | إرجاع قيمة رأس 'Transfer-Encoding'. |
| [Nullable](../../system/nullable/)\<**bool**\> [get_TransferEncodingChunked](./get_transferencodingchunked/)() | الحصول على قيمة تُظهر ما إذا كانت قيمة رأس 'Transfer-Encoding' تحتوي على 'Chunked'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ProductHeaderValue](../productheadervalue/)\>\>\> [get_Upgrade](./get_upgrade/)() | إرجاع قيمة رأس 'Upgrade'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ProductInfoHeaderValue](../productinfoheadervalue/)\>\>\> [get_UserAgent](./get_useragent/)() | إرجاع قيمة رأس 'User-Agent'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ViaHeaderValue](../viaheadervalue/)\>\>\> [get_Via](./get_via/)() | إرجاع قيمة رأس 'Via'. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[WarningHeaderValue](../warningheadervalue/)\>\>\> [get_Warning](./get_warning/)() | إرجاع قيمة رأس 'Warning'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | الحصول على بنية عداد المرجع المرتبط بالكائن. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\>\>\> [GetEnumerator](../httpheaders/getenumerator/)() override | الحصول على مُعدد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/)) | إرجاع تمثيل نصي للقيم بحسب اسم الرأس المحدد. |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | إرجاع تمثيل نصي للقيم بحسب اسم الرأس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [String](../../system/string/)\>\>\> [GetHeaderStrings](../httpheaders/getheaderstrings/)() | إرجاع مجموعة تحتوي على تمثيلات نصية لقيم الرؤوس. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetParsedValues](../httpheaders/getparsedvalues/)([String](../../system/string/)) | إرجاع القيم المُحللة بحسب اسم الرأس المحدد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | الحصول على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [GetValues](../httpheaders/getvalues/)([String](../../system/string/)) | إرجاع القيم المقابلة بحسب الاسم المحدد. |
|  [HttpRequestHeaders](./httprequestheaders/)() | إنشاء نسخة جديدة. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | التحقق مما إذا كان الكائن يمثل نسخة من النوع الموضح بـ targetType. نظير معامل C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | تطبيق دالة تراكم على تسلسل. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | تحديد ما إذا كانت جميع عناصر التسلسل تُلبي الشرط. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | تحديد ما إذا كان التسلسل يحتوي على أي عناصر. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | تحديد ما إذا كان أي عنصر من التسلسل موجود أو يُلبي الشرط. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | حساب متوسط التسلسل للقيم الرقمية. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | حساب متوسط التسلسل للقيم التي يتم الحصول عليها باستدعاء دالة تحويل على كل عنصر من التسلسل المدخل. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | تحويل العناصر إلى النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | دمج تسلسلين. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | تحديد ما إذا كان التسلسل يحتوي على قيمة محددة. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | إرجاع عدد العناصر في التسلسل (محسوب عبر العد المباشر). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | إرجاع عدد العناصر في التسلسل التي تُلبي الشرط المحدد. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | إرجاع العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | إرجاع العنصر عند الفهرس المحدد في التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | إرجاع أول عنصر في التسلسل. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | إرجاع أول عنصر في التسلسل الذي يُلبي الشرط المحدد. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | إرجاع أول عنصر في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | إرجاع أول عنصر في التسلسل الذي يُلبي الشرط أو قيمة افتراضية إذا لم يُعثر على مثل هذا العنصر. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | تجميع عناصر التسلسل. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | تجميع عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | إرجاع العنصر الأخير في التسلسل. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | إرجاع العنصر الأخير في التسلسل، أو قيمة افتراضية إذا كان التسلسل فارغًا. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | استدعاء دالة تحويل على كل عنصر من تسلسل عام وإرجاع القيمة القصوى الناتجة. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | استدعاء دالة تحويل على كل عنصر من تسلسل عام وإرجاع القيمة الدنيا الناتجة. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | تصفية عناصر التسلسل وفق النوع المحدد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | فرز عناصر التسلسل بترتيب تصاعدي بحسب قيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | فرز عناصر التسلسل بترتيب تنازلي بحسب قيم المفتاح المختارة بواسطة keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | عكس ترتيب العناصر في التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | تحويل عناصر التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | تحويل كل عنصر في التسلسل إلى شكل جديد باستخدام فهرس العنصر. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | إسقاط كل عنصر من التسلسل ودمج التسلسلات الناتجة في تسلسل واحد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | تخطي عدد محدد من العناصر المتتالية من بداية التسلسل وإرجاع البقية. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | إرجاع عدد محدد من العناصر المتتالية من بداية التسلسل. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | إنشاء مصفوفة من التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | إنشاء List<T> من التسلسل. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | تصفية التسلسل بناءً على الشرط المحدد. |
| void [Lock](../../system/object/lock/)() | تنفيذ عملية القفل lock() في C# . استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | إنشاء كائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشيء نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\> [ParsedValuesAsList](../httpheaders/parsedvaluesaslist/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | تحويل القيم المُحللة إلى قائمة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | مقارنة الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | مقارنة الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقارنة كائن نوع القيمة بالمرجع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) في حالة السلاسل. |
| **bool** [Remove](../httpheaders/remove/)([String](../../system/string/)) | محاولة إزالة عنصر بالاسم المحدد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تقليل عداد المرجع المشترك بالقيمة المحددة. |
| **bool** [RemoveParsedValue](../httpheaders/removeparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | الحصول على رأس بالاسم المحدد وإزالة قيمة مُحللة من الرأس. |
| void [set_Authorization](./set_authorization/)([System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\>) | ضبط قيمة رأس 'Authorization'. |
| void [set_CacheControl](./set_cachecontrol/)([System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](../cachecontrolheadervalue/)\>) | ضبط قيمة رأس 'Cache-Control'. |
| void [set_ConnectionClose](./set_connectionclose/)([Nullable](../../system/nullable/)\<**bool**\>) | ضبط قيمة تُظهر ما إذا كانت قيمة رأس 'Connection' تحتوي على 'Close'. |
| void [set_Date](./set_date/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | ضبط قيمة رأس 'Date'. |
| void [set_ExpectContinue](./set_expectcontinue/)([Nullable](../../system/nullable/)\<**bool**\>) | ضبط قيمة تُظهر ما إذا كانت قيمة رأس 'Expect' تحتوي على 'Continue'. |
| void [set_From](./set_from/)([String](../../system/string/)) | ضبط قيمة رأس 'From'. |
| void [set_Host](./set_host/)([String](../../system/string/)) | ضبط قيمة رأس 'Host'. |
| void [set_IfModifiedSince](./set_ifmodifiedsince/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | ضبط قيمة رأس 'If-Modified-Since'. |
| void [set_IfRange](./set_ifrange/)([System::SharedPtr](../../system/sharedptr/)\<[RangeConditionHeaderValue](../rangeconditionheadervalue/)\>) | ضبط قيمة رأس 'If-Range'. |
| void [set_IfUnmodifiedSince](./set_ifunmodifiedsince/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | ضبط قيمة رأس 'If-Unmodified-Since'. |
| void [set_MaxForwards](./set_maxforwards/)([Nullable](../../system/nullable/)\<**int32_t**\>) | ضبط قيمة رأس 'Max-Forwards'. |
| void [set_ProxyAuthorization](./set_proxyauthorization/)([System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\>) | ضبط قيمة رأس 'Proxy-Authorization'. |
| void [set_Range](./set_range/)([System::SharedPtr](../../system/sharedptr/)\<[RangeHeaderValue](../rangeheadervalue/)\>) | ضبط قيمة رأس '[Range](../../system/range/)'. |
| void [set_Referrer](./set_referrer/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ضبط قيمة رأس 'Referer'. |
| void [set_TransferEncodingChunked](./set_transferencodingchunked/)([Nullable](../../system/nullable/)\<**bool**\>) | ضبط قيمة تُظهر ما إذا كانت قيمة رأس 'Transfer-Encoding' تحتوي على 'Chunked'. |
| void [SetConfiguration](../httpheaders/setconfiguration/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<HttpHeaderParser\>\>\>, [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) |  |
| void [SetOrRemoveParsedValue](../httpheaders/setorremoveparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | الحصول على رأس بالاسم المحدد وضبط أو إزالة قيمته. سيُزال قيمة الرأس عندما تكون معلمة 'value' تساوي nullptr، وإلا سيتم ضبط قيمة مُحللة. |
| void [SetParsedValue](../httpheaders/setparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | الحصول على رأس بالاسم المحدد وضبط قيمة مُحللة لل رأس. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ضبط الوسيط القالب الــ n'th إلى مؤشر ضعيف (بدلاً من مشترك). يتيح تبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | الحصول على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | زيادة عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | تقليل وإرجاع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| [String](../../system/string/) [ToString](../httpheaders/tostring/)() const override | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى نص. |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [String](../../system/string/)) | محاولة إضافة زوج اسم-قيمة جديد إلى المجموعة الحالية. |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | إضافة مجموعة من أزواج الاسم-القيمة إلى المجموعة الحالية. |
| **bool** [TryGetValues](../httpheaders/trygetvalues/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&) | محاولة الحصول على القيم المقابلة بحسب الاسم المحدد. |
| **bool** [TryParseAndAddValue](../httpheaders/tryparseandaddvalue/)([String](../../system/string/), [String](../../system/string/)) | محاولة تحليل القيمة المحددة وإضافتها إلى قيم الرأس. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | تنفيذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفيذ عملية فك القفل lock() في C# . استدعِها مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | الحصول على تنفيذ بداية iterator الثابت للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | الحصول على تنفيذ بداية iterator للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | الحصول على تنفيذ نهاية iterator الثابت للحاوية الحالية. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | الحصول على تنفيذ نهاية iterator للحاوية الحالية. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | زيادة عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | تقليل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | تدمير الكائن. تحرير جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* فئة [HttpHeaders](../httpheaders/)
* مساحة الاسم [System::Net::Http::Headers](../)
* مكتبة [Aspose.Slides](../../)