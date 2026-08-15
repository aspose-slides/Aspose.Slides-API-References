---
title: HttpContentHeaders
second_title: Aspose.Slides for C++ API 參考文件
description: "表示 'Content' 標頭的集合。此類別的物件只能使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或 斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為引數傳遞給函式。"
type: docs
weight: 66
url: /zh-hant/system.net.http.headers/httpcontentheaders/
---
## HttpContentHeaders 類別


Represents the collection of the 'Content' headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpContentHeaders : public System::Net::Http::Headers::HttpHeaders
```

## 方法

| Method | Description |
| --- | --- |
| void [Add](../httpheaders/add/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | 驗證新的名稱-值對並將其加入目前的集合。 |
| void [Add](../httpheaders/add/)([String](../../system/string/), [String](../../system/string/)) | 驗證新的名稱-值對並將其加入目前的集合。 |
| virtual void [AddHeaders](../httpheaders/addheaders/)([System::SharedPtr](../../system/sharedptr/)\<[HttpHeaders](../httpheaders/)\>) | 將指定的 HttpHeaders 類別實例與目前的實例串接。 |
| static void [AddKnownHeaders](./addknownheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) | 將已知的標頭新增至指定的集合。 |
| void [AddParsedValue](../httpheaders/addparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 根據指定的名稱取得標頭，並將已解析的值新增至該標頭。 |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | 取得指向集合第一個元素（若存在）的迭代器。此迭代器無法用於變更被參照的物件，因為 [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) 會回傳 T 的拷貝物件。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | 取得指向 const 限定之集合實例的第一個元素（若存在）的迭代器。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | 取得指向集合中第一個 const 限定元素（若存在）的迭代器。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | 取得指向集合中最後一個 const 限定元素之後的迭代器（若存在）。 |
| void [Clear](../httpheaders/clear/)() | 從集合中移除所有項目。 |
| **bool** [Contains](../httpheaders/contains/)([String](../../system/string/)) |  |
| **bool** [ContainsParsedValue](../httpheaders/containsparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 檢查該標頭是否包含指定的值。 |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | 取得指向集合最後一個元素之後的迭代器（若存在）。此迭代器無法用於變更被參照的物件，因為 [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) 會回傳 T 的拷貝物件。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | 取得指向 const 限定之集合實例的最後一個元素之後的迭代器（若存在）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_Allow](./get_allow/)() | 取得 'Allow' 標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](../contentdispositionheadervalue/)\> [get_ContentDisposition](./get_contentdisposition/)() | 取得 'Content-Disposition' 標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_ContentEncoding](./get_contentencoding/)() | 取得 'Content-Encoding' 標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_ContentLanguage](./get_contentlanguage/)() | 取得 'Content-Language' 標頭的值。 |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_ContentLength](./get_contentlength/)() | 取得 'Content-Length' 標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_ContentLocation](./get_contentlocation/)() | 取得 'Content-Location' 標頭的值。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_ContentMD5](./get_contentmd5/)() | 取得 'Content-MD5' 標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ContentRangeHeaderValue](../contentrangeheadervalue/)\> [get_ContentRange](./get_contentrange/)() | 取得 'Content-Range' 標頭的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\> [get_ContentType](./get_contenttype/)() | 取得 'Content-Type' 標頭的值。 |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_Expires](./get_expires/)() | 取得 'Expires' 標頭的值。 |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_LastModified](./get_lastmodified/)() | 取得 'Last-Modified' 標頭的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\>\>\>\> [GetEnumerator](../httpheaders/getenumerator/)() override | 取得列舉器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊功能。 |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/)) | 依指定的標頭名稱返回值的字串表示。 |
| [String](../../system/string/) [GetHeaderString](../httpheaders/getheaderstring/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 依指定的標頭名稱返回值的字串表示。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<[String](../../system/string/), [String](../../system/string/)\>\>\> [GetHeaderStrings](../httpheaders/getheaderstrings/)() | 返回包含標頭值字串表示的集合。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetParsedValues](../httpheaders/getparsedvalues/)([String](../../system/string/)) | 返回依指定標頭名稱解析的值。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [GetValues](../httpheaders/getvalues/)([String](../../system/string/)) | 依指定名稱返回相對應的值。 |
|  [HttpContentHeaders](./httpcontentheaders/)([HeaderFunc](../headerfunc/)\<[Nullable](../../system/nullable/)\<**int64_t**\>\>) | 建立新實例。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。C# 'is' 運算子的類比。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 對序列套用累加函式。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判斷序列的所有元素是否皆符合條件。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判斷序列中是否有任何元素存在或符合條件。 |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 計算透過對輸入序列的每個元素呼叫變換函式而取得之值的序列的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 將元素轉型為指定的類型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 連接兩個序列。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 判斷序列是否包含指定的值。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 返回序列中元素的數量（透過直接計數計算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回符合指定條件的序列元素數量。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 返回序列中指定索引處的元素。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 返回序列中指定索引處的元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 返回序列的第一個元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回符合指定條件的序列第一個元素。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 返回序列的第一個元素，若序列為空則返回預設值。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 返回符合條件之序列第一個元素，若未找到則返回預設值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 將序列的元素分組。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 將序列的元素分組。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 返回序列的最後一個元素。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 返回序列的最後一個元素，若序列為空則返回預設值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對一般序列的每個元素呼叫變換函式，並返回最大的結果值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對一般序列的每個元素呼叫變換函式，並返回最小的結果值。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 根據指定類型過濾序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 根據 keySelector 所選取的鍵值，以升序排列序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 根據 keySelector 所選取的鍵值，以降序排列序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 顛倒序列中元素的順序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 轉換序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 結合元素索引，將序列的每個元素轉換為新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 投射序列的每個元素，並將產生的序列合併為一個序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 跳過序列開頭指定數量的連續元素，並返回其餘部分。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 返回序列開頭指定數量的連續元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 從序列建立陣列。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 從序列建立 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根據指定的謂詞過濾序列。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守衛物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂類型的克隆功能。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何東西，只是初始化新物件，並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件，並允許子類別的複製建構。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\> [ParsedValuesAsList](../httpheaders/parsedvaluesaslist/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 將解析的值轉換為清單。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| **bool** [Remove](../httpheaders/remove/)([String](../../system/string/)) | 嘗試依指定名稱移除項目。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| **bool** [RemoveParsedValue](../httpheaders/removeparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 依指定名稱取得標頭，並從該標頭移除已解析的值。 |
| void [set_ContentDisposition](./set_contentdisposition/)([System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](../contentdispositionheadervalue/)\>) | 設定 'Content-Disposition' 標頭的值。 |
| void [set_ContentLength](./set_contentlength/)([Nullable](../../system/nullable/)\<**int64_t**\>) | 設定 'Content-Length' 標頭的值。 |
| void [set_ContentLocation](./set_contentlocation/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 設定 'Content-Location' 標頭的值。 |
| void [set_ContentMD5](./set_contentmd5/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 設定 'Content-MD5' 標頭的值。 |
| void [set_ContentRange](./set_contentrange/)([System::SharedPtr](../../system/sharedptr/)\<[ContentRangeHeaderValue](../contentrangeheadervalue/)\>) | 設定 'Content-Range' 標頭的值。 |
| void [set_ContentType](./set_contenttype/)([System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>) | 設定 'Content-Type' 標頭的值。 |
| void [set_Expires](./set_expires/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | 設定 'Expires' 標頭的值。 |
| void [set_LastModified](./set_lastmodified/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | 設定 'Last-Modified' 標頭的值。 |
| void [SetConfiguration](../httpheaders/setconfiguration/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<HttpHeaderParser\>\>\>, [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::HashSet](../../system.collections.generic/hashset/)\<[String](../../system/string/)\>\>) |  |
| void [SetOrRemoveParsedValue](../httpheaders/setorremoveparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 依指定名稱取得標頭，並設定或移除其值。當 'value' 參數為 nullptr 時，標頭值將被移除；否則將設定已解析的值。 |
| void [SetParsedValue](../httpheaders/setparsedvalue/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 依指定名稱取得標頭，並設定已解析的值至該標頭。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；應使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；應使用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](../httpheaders/tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用自訂物件轉為字串。 |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [String](../../system/string/)) | 嘗試將新的名稱-值對加入目前的集合。 |
| **bool** [TryAddWithoutValidation](../httpheaders/tryaddwithoutvalidation/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>) | 將一組名稱-值對集合加入目前的集合。 |
| **bool** [TryGetValues](../httpheaders/trygetvalues/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&) | 嘗試依指定名稱取得相對應的值。 |
| **bool** [TryParseAndAddValue](../httpheaders/tryparseandaddvalue/)([String](../../system/string/), [String](../../system/string/)) | 嘗試解析指定的值並將其新增至標頭值。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守衛物件。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | 取得目前容器的 begin const 迭代器實作。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | 取得目前容器的 begin 迭代器實作。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | 取得目前容器的 end const 迭代器實作。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | 取得目前容器的 end 迭代器實作。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；應使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；應使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [HttpHeaders](../httpheaders/)
* 命名空間 [System::Net::Http::Headers](../)
* 函式庫 [Aspose.Slides](../../)