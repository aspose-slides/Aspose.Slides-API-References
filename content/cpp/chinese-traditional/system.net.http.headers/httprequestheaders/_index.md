---
title: HttpRequestHeaders
second_title: Aspose.Slides for C++ API 參考
description: "表示「Request」標頭的集合。此類的物件只能使用 System::MakeObject() 函式分配。絕不要在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 118
url: /zh-hant/system.net.http.headers/httprequestheaders/
---
## HttpRequestHeaders 類別


表示「Request」標頭的集合。此類的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式分配。絕不要在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝為 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。

```cpp
class HttpRequestHeaders : public System::Net::Http::Headers::HttpHeaders
```

## 方法

| Method | Description |
| --- | --- |
| void [Add](../httpheaders/add/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | 驗證新的名稱-值對，並將其新增到目前的集合中。 |
| void [Add](../httpheaders/add/)([String](../../system/string/), [String](../../system/string/)) | 驗證新的名稱-值對，並將其新增到目前的集合中。 |
| void [AddHeaders](./addheaders/)([System::SharedPtr](../../system/sharedptr/)\<[HttpHeaders](../httpheaders/)\>) override | 將指定的 HttpHeaders 類別實例與當前實例串接。 |
| static void [AddKnownHeaders](./addknownheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) | 將已知的標頭新增至指定的集合中。 |
| void [AddParsedValue](../httpheaders/addparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 依指定名稱取得標頭，並將解析後的值新增至該標頭。 |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | 取得指向集合第一個元素（若有）的迭代器。此迭代器無法用於變更所參照的物件，因為 [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) 會回傳 T 的副本物件。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | 取得指向常量限定集合之第一個元素（若有）的迭代器。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | 取得指向常量限定集合之第一個常量元素（若有）的迭代器。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | 取得指向常量限定集合最後一個常量元素之後的迭代器（若有）。 |
| void [Clear](../httpheaders/clear/)() | 移除集合中的所有項目。 |
| **bool** [Contains](../httpheaders/contains/)([String](../../system/string/)) |  |
| **bool** [ContainsParsedValue](../httpheaders/containsparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 檢查標頭是否包含指定的值。 |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | 取得指向集合最後一個元素之後的迭代器（若有）。此迭代器無法用於變更所參照的物件，因為 [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) 會回傳 T 的副本物件。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | 取得指向常量限定集合最後一個元素之後的迭代器（若有）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](../mediatypewithqualityheadervalue/)\>\>\> [get_Accept](./get_accept/)() | 回傳「Accept」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[StringWithQualityHeaderValue](../stringwithqualityheadervalue/)\>\>\> [get_AcceptCharset](./get_acceptcharset/)() | 回傳「Accept-Charset」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[StringWithQualityHeaderValue](../stringwithqualityheadervalue/)\>\>\> [get_AcceptEncoding](./get_acceptencoding/)() | 回傳「Accept-Encoding」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[StringWithQualityHeaderValue](../stringwithqualityheadervalue/)\>\>\> [get_AcceptLanguage](./get_acceptlanguage/)() | 回傳「Accept-Language」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\> [get_Authorization](./get_authorization/)() | 取得「Authorization」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](../cachecontrolheadervalue/)\> [get_CacheControl](./get_cachecontrol/)() | 取得「Cache-Control」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Connection](./get_connection/)() | 回傳「Connection」標頭的值。 |
| [Nullable](../../system/nullable/)\<**bool**\> [get_ConnectionClose](./get_connectionclose/)() | 取得指示「Connection」標頭值是否包含「Close」的布林值。 |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_Date](./get_date/)() | 取得「Date」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](../namevaluewithparametersheadervalue/)\>\>\> [get_Expect](./get_expect/)() | 回傳「Expect」標頭的值。 |
| [Nullable](../../system/nullable/)\<**bool**\> [get_ExpectContinue](./get_expectcontinue/)() | 取得指示「Expect」標頭值是否包含「Continue」的布林值。 |
| [String](../../system/string/) [get_From](./get_from/)() | 取得「From」標頭的值。 |
| [String](../../system/string/) [get_Host](./get_host/)() | 取得「Host」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[EntityTagHeaderValue](../entitytagheadervalue/)\>\>\> [get_IfMatch](./get_ifmatch/)() | 回傳「If-Match」標頭的值。 |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_IfModifiedSince](./get_ifmodifiedsince/)() | 取得「If-Modified-Since」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[EntityTagHeaderValue](../entitytagheadervalue/)\>\>\> [get_IfNoneMatch](./get_ifnonematch/)() | 回傳「If-None-Match」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[RangeConditionHeaderValue](../rangeconditionheadervalue/)\> [get_IfRange](./get_ifrange/)() | 取得「If-Range」標頭的值。 |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_IfUnmodifiedSince](./get_ifunmodifiedsince/)() | 取得「If-Unmodified-Since」標頭的值。 |
| [Nullable](../../system/nullable/)\<**int32_t**\> [get_MaxForwards](./get_maxforwards/)() | 取得「Max-Forwards」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Pragma](./get_pragma/)() | 回傳「Pragma」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\> [get_ProxyAuthorization](./get_proxyauthorization/)() | 取得「Proxy-Authorization」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[RangeHeaderValue](../rangeheadervalue/)\> [get_Range](./get_range/)() | 取得「[Range](../../system/range/)」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Referrer](./get_referrer/)() | 取得「Referer」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[TransferCodingWithQualityHeaderValue](../transfercodingwithqualityheadervalue/)\>\>\> [get_TE](./get_te/)() | 回傳「TE」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[String](../../system/string/)\>\> [get_Trailer](./get_trailer/)() | 回傳「Trailer」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](../transfercodingheadervalue/)\>\>\> [get_TransferEncoding](./get_transferencoding/)() | 回傳「Transfer-Encoding」標頭的值。 |
| [Nullable](../../system/nullable/)\<**bool**\> [get_TransferEncodingChunked](./get_transferencodingchunked/)() | 取得指示「Transfer-Encoding」標頭值是否包含「Chunked」的布林值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ProductHeaderValue](../productheadervalue/)\>\>\> [get_Upgrade](./get_upgrade/)() | 回傳「Upgrade」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ProductInfoHeaderValue](../productinfoheadervalue/)\>\>\> [get_UserAgent](./get_useragent/)() | 回傳「User-Agent」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[ViaHeaderValue](../viaheadervalue/)\>\>\> [get_Via](./get_via/)() | 回傳「Via」標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpHeaderValueCollection](../httpheadervaluecollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[WarningHeaderValue](../warningheadervalue/)\>\>\> [get_Warning](./get_warning/)() | 回傳「Warning」標頭的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\>\>\> [GetEnumerator](../httpheaders/getenumerator/)() override | 取得列舉子。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等價物。啟用自訂物件的雜湊。 |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/)) | 依指定的標頭名稱回傳值的字串表示。 |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 依指定的標頭名稱回傳值的字串表示。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [String](../../system/string/)\>\>\> [GetHeaderStrings](../httpheaders/getheaderstrings/)() | 回傳包含標頭值字串表示的集合。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetParsedValues](../httpheaders/getparsedvalues/)([String](../../system/string/)) | 依指定的標頭名稱回傳已解析的值。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的等價物。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [GetValues](../httpheaders/getvalues/)([String](../../system/string/)) | 依指定名稱回傳對應的值。 |
|  [HttpRequestHeaders](./httprequestheaders/)() | 建構新實例。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。C# 「is」運算子的等價物。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 對序列套用累加函式。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判斷序列的所有元素是否符合條件。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判斷是否存在符合條件的任一元素。 |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 計算透過對輸入序列每個元素呼叫轉換函式取得的值的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 將元素轉型為指定型別。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 將兩個序列串接。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 判斷序列是否包含指定的值。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 回傳序列中元素的數量（透過直接計數計算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 回傳符合指定條件的序列元素數量。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 依指定索引回傳序列中的元素。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 依指定索引回傳序列中的元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 回傳序列的第一個元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 回傳符合指定條件的序列第一個元素。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 回傳序列的第一個元素；若序列為空則回傳預設值。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 回傳符合條件的序列第一個元素；若不存在則回傳預設值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 對序列的元素進行分組。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 對序列的元素進行分組。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 回傳序列的最後一個元素。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 回傳序列的最後一個元素；若序列為空則回傳預設值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對每個元素呼叫轉換函式，回傳最大的結果值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對每個元素呼叫轉換函式，回傳最小的結果值。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 依指定類型過濾序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 依 keySelector 選出的鍵值，以升序排序序列元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 依 keySelector 選出的鍵值，以降序排序序列元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 反轉序列中元素的順序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 轉換序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 透過結合元素索引，將序列的每個元素轉換為新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 對每個元素投影並將產生的序列合併為一個序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 從序列起始處跳過指定數量的連續元素，並回傳剩餘部分。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 從序列起始處回傳指定數量的連續元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 依序列建立陣列。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 依序列建立 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 依指定的謂詞過濾序列。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的等價物。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\> [ParsedValuesAsList](../httpheaders/parsedvaluesaslist/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 將已解析的值轉換為列表。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況的特化。 |
| **bool** [Remove](../httpheaders/remove/)([String](../../system/string/)) | 嘗試依指定名稱移除項目。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| **bool** [RemoveParsedValue](../httpheaders/removeparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 依指定名稱取得標頭，並從標頭中移除解析後的值。 |
| void [set_Authorization](./set_authorization/)([System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\>) | 設定「Authorization」標頭的值。 |
| void [set_CacheControl](./set_cachecontrol/)([System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](../cachecontrolheadervalue/)\>) | 設定「Cache-Control」標頭的值。 |
| void [set_ConnectionClose](./set_connectionclose/)([Nullable](../../system/nullable/)\<**bool**\>) | 設定指示「Connection」標頭值是否包含「Close」的布林值。 |
| void [set_Date](./set_date/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | 設定「Date」標頭的值。 |
| void [set_ExpectContinue](./set_expectcontinue/)([Nullable](../../system/nullable/)\<**bool**\>) | 設定指示「Expect」標頭值是否包含「Continue」的布林值。 |
| void [set_From](./set_from/)([String](../../system/string/)) | 設定「From」標頭的值。 |
| void [set_Host](./set_host/)([String](../../system/string/)) | 設定「Host」標頭的值。 |
| void [set_IfModifiedSince](./set_ifmodifiedsince/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | 設定「If-Modified-Since」標頭的值。 |
| void [set_IfRange](./set_ifrange/)([System::SharedPtr](../../system/sharedptr/)\<[RangeConditionHeaderValue](../rangeconditionheadervalue/)\>) | 設定「If-Range」標頭的值。 |
| void [set_IfUnmodifiedSince](./set_ifunmodifiedsince/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | 設定「If-Unmodified-Since」標頭的值。 |
| void [set_MaxForwards](./set_maxforwards/)([Nullable](../../system/nullable/)\<**int32_t**\>) | 設定「Max-Forwards」標頭的值。 |
| void [set_ProxyAuthorization](./set_proxyauthorization/)([System::SharedPtr](../../system/sharedptr/)\<[AuthenticationHeaderValue](../authenticationheadervalue/)\>) | 設定「Proxy-Authorization」標頭的值。 |
| void [set_Range](./set_range/)([System::SharedPtr](../../system/sharedptr/)\<[RangeHeaderValue](../rangeheadervalue/)\>) | 設定「[Range](../../system/range/)」標頭的值。 |
| void [set_Referrer](./set_referrer/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 設定「Referer」標頭的值。 |
| void [set_TransferEncodingChunked](./set_transferencodingchunked/)([Nullable](../../system/nullable/)\<**bool**\>) | 設定指示「Transfer-Encoding」標頭值是否包含「Chunked」的布林值。 |
| void [SetConfiguration](../httpheaders/setconfiguration/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<HttpHeaderParser\>\>\>, [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) |  |
| void [SetOrRemoveParsedValue](../httpheaders/setorremoveparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 依指定名稱取得標頭並設定或移除其值。當「value」參數為 nullptr 時會移除標頭值；否則會設定解析後的值。 |
| void [SetParsedValue](../httpheaders/setparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 依指定名稱取得標頭並設定解析後的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並回傳共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](../httpheaders/tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 方法的等價物。啟用將自訂物件轉換為字串。 |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [String](../../system/string/)) | 嘗試將新的名稱-值對加入目前的集合。 |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | 將名稱-值對集合加入目前的集合。 |
| **bool** [TryGetValues](../httpheaders/trygetvalues/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&) | 嘗試依指定名稱取得對應的值。 |
| **bool** [TryParseAndAddValue](../httpheaders/tryparseandaddvalue/)([String](../../system/string/), [String](../../system/string/)) | 嘗試解析指定的值並將其加入標頭值。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | 取得目前容器的 const 起始迭代子實作。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | 取得目前容器的起始迭代子實作。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | 取得目前容器的 const 結束迭代子實作。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | 取得目前容器的結束迭代子實作。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 另請參閱

* Class [HttpHeaders](../httpheaders/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.Slides](../../)