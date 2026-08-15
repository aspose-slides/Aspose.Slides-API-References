---
title: Array
second_title: Aspose.Slides for C++ API 參考
description: "表示陣列資料結構的類別。此類別的物件只能使用 System::MakeArray() 與 System::MakeObject() 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別封裝在 System::SmartPtr 指標中，並使用此指標作為參數傳遞給函式。"
type: docs
weight: 14
url: /zh-hant/system/array/
---
## Array 類別


表示陣列資料結構的類別。此類別的物件應僅使用 [System::MakeArray()](../makearray/) 與 [System::MakeObject()](../makeobject/) 函式來配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```


### 範本參數

| Parameter | Description |
| --- | --- |
| T | 陣列元素的類型 |
## 方法

| Method | Description |
| --- | --- |
| void [Add](./add/)(const T&) override | 不支援，因為當前物件所表示的陣列為唯讀。 |
|  [Array](./array/)() | 建構一個空的陣列。 |
|  [Array](./array/)(int, const T&) | 填充建構子。 |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | 填充建構子。 |
|  [Array](./array/)(int, const T) | 填充建構子。 |
|  [Array](./array/)(**vector_t**\&&) | 移動建構子。 |
|  [Array](./array/)(const **vector_t**\&) | 複製建構子。 |
|  [Array](./array/)(const std::vector\<Q\>\&) | 建構一個 [Array](./) 物件，並以從 std::vector 物件複製的值填入；該 std::vector 之值類型與 **T** 相同，但與 **UnderlyingType** 不同。 |
|  [Array](./array/)(std::vector\<Q\>\&&) | 建構一個 [Array](./) 物件，並以從 std::vector 物件移動的值填入；該 std::vector 之值類型與 **T** 相同，但與 **UnderlyingType** 不同。 |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | 建構一個 [Array](./) 物件，並以指定的 initializer list（包含 **UnderlyingType** 類型的元素）填入。 |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | 建構一個 [Array](./) 物件，並以指定的陣列（包含 **UnderlyingType** 類型的元素）填入。 |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | 建構一個 [Array](./) 物件，並以指定的 initializer list（包含 bool 類型的元素）填入。 |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | 將陣列轉換為唯讀集合。 |
| [iterator](./iterator/) [begin](./begin/)() | 傳回指向容器第一個元素的疊代器。如果容器為空，傳回的疊代器將等於 [end()](./end/)。 |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 傳回指向 const 限定容器第一個元素的疊代器。如果容器為空，傳回的疊代器將等於 [end()](./end/)。 |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | 在已排序的陣列中執行二分搜尋。 |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | 未實作。 |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | 傳回指向容器第一個 const 限定元素的疊代器。如果容器為空，傳回的疊代器將等於 [cend()](./cend/)。 |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | 傳回指向容器最後一個元素之後之元素的疊代器。此元素作為占位符；若嘗試存取將導致未定義的行為。 |
| void [Clear](./clear/)() override | 不支援，因為當前物件所表示的陣列為唯讀。 |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 將指定陣列中從 **startIndex** 索引開始的 **count** 個值以預設值取代。 |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | 複製陣列。 |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 從 [System.Array](./) 複製一段元素，起始於指定的來源。 |
| **bool** [Contains](./contains/)(const T\&) const override | 判斷指定項目是否在陣列中。 |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | 建構一個新的 [Array](./) 物件，並使用指定的轉換委派將指定陣列的元素轉換為 **OutputType** 類型後填入。 |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | 建構一個新的 [Array](./) 物件，並使用指定的轉換函式物件將指定陣列的元素轉換為 **OutputType** 類型後填入。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 將指定數量的元素從來源陣列複製到目標陣列。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 將指定數量的元素從來源陣列檢視複製到目標陣列。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | 將指定數量的元素從來源陣列複製到目標陣列檢視。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | 將指定數量的元素從來源陣列檢視複製到目標陣列檢視。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 將指定數量的元素從堆疊上的來源陣列複製到目標陣列。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | 將指定數量的元素從來源陣列複製到堆疊上的目標陣列。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | 將指定數量的元素從堆疊上的來源陣列複製到堆疊上的目標陣列。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 將指定數量的元素從來源陣列的指定索引起複製到目標陣列的指定位置。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 將指定數量的元素從來源陣列檢視的指定索引起複製到目標陣列的指定位置。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | 將指定數量的元素從來源陣列的指定索引起複製到目標陣列檢視的指定位置。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | 將指定數量的元素從來源陣列檢視的指定索引起複製到目標陣列檢視的指定位置。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 將指定數量的元素從堆疊上的來源陣列的指定索引起複製到目標陣列的指定位置。 |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | 將指定數量的元素從來源陣列的指定索引起複製到堆疊上的目標陣列的指定位置。 |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | 將指定數量的元素從堆疊上的來源陣列的指定索引起複製到堆疊上的目標陣列的指定位置。 |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | 將指定數量的元素從來源陣列檢視的指定索引起複製到堆疊上的目標陣列。 |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | 將目前陣列的所有元素複製到指定的目標陣列。元素會從由 arrayIndex 參數指定的索引開始插入到目標陣列中。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | 將目前陣列的所有元素複製到指定的目標陣列。元素會從由 dstIndex 參數指定的索引開始插入到目標陣列中。 |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | 將目前陣列的所有元素複製到指定的目標陣列檢視。元素會從由 dstIndex 參數指定的索引開始插入到目標陣列檢視中。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | 將指定數量的元素從目前陣列的指定位置複製到指定的目標陣列。元素會從由 dstIndex 參數指定的索引開始插入到目標陣列中。 |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | 將指定數量的元素從目前陣列的指定位置複製到指定的目標陣列檢視。元素會從由 dstIndex 參數指定的索引開始插入到目標陣列檢視中。 |
| int [Count](./count/)() const | 傳回代表陣列所有維度中全部元素總數的數字。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 傳回指向反向容器第一個元素的逆向疊代器。它對應於非反向容器的最後一個元素。如果容器為空，傳回的疊代器等於 [crend()](./crend/)。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 傳回指向反向容器最後一個元素之後之元素的逆向疊代器。它對應於非反向容器的第一個元素之前的元素。此元素作為占位符，若嘗試存取將導致未定義行為。 |
| **vector_t**\& [data](./data/)() | 傳回用於儲存陣列元素的內部資料結構的參考。 |
| const **vector_t**\& [data](./data/)() const | 傳回用於儲存陣列元素的內部資料結構的常量參考。 |
| vector_t::pointer [data_ptr](./data_ptr/)() | 傳回指向儲存陣列元素的記憶體緩衝區起始位置的原始指標。 |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | 傳回指向儲存陣列元素的記憶體緩衝區起始位置的常量原始指標。 |
| [iterator](./iterator/) [end](./end/)() | 傳回指向容器最後一個元素之後之元素的疊代器。此元素作為占位符，若嘗試存取將導致未定義行為。 |
| [const_iterator](./const_iterator/) [end](./end/)() const | 傳回指向 const 限定容器最後一個元素之後之元素的疊代器。此元素作為占位符，若嘗試存取將導致未定義行為。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，其中兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 規範 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | 判斷指定的 [Array](./) 物件是否包含符合指定謂詞要求的元素。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 在指定的陣列中搜尋符合指定謂詞條件的第一個元素。 |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 取得所有符合指定謂詞所定義條件的元素。 |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 在指定的陣列中搜尋符合指定謂詞條件的第一個元素。 |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | 對指定陣列的每個元素執行指定的動作。 |
| int [get_Count](./get_count/)() const override | 回傳陣列的大小。 |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | 檢查集合是否具有固定大小。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | 表示陣列是否為唯讀。 |
| **int32_t** [get_Length](./get_length/)() const override | 回傳 32 位元整數，表示陣列所有維度中元素的總數。 |
| **int64_t** [get_LongLength](./get_longlength/)() const | 回傳 64 位元整數，表示陣列所有維度中元素的總數。 |
| **int32_t** [get_Rank](./get_rank/)() const | 未實作。 |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | 取得集合所同步的物件。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 取得與物件相關的參考計數資料結構。 |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | 回傳指向 **Enumerator** 物件的指標，該物件提供對目前物件所表示陣列元素的 IEnumerator 介面。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| int [GetLength](./getlength/)(int) | 回傳指定維度中的元素數量。 |
| **int64_t** [GetLongLength](./getlonglength/)(int) | 回傳指定維度中的元素數量，型別為 64 位元整數。 |
| int [GetLowerBound](./getlowerbound/)(int) const | 回傳指定維度的下界。 |
| size_t [GetSizeTLength](./getsizetlength/)() const | 回傳 std::size_t 變數，表示陣列所有維度中元素的總數。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../object/gettype/) 呼叫。 |
| int [GetUpperBound](./getupperbound/)(int) | 回傳指定維度的上界。 |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | 預設建構子。 |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | 複製建構子。 |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | 移動建構子。 |
| T [idx_get](./idx_get/)(int) const override | 回傳指定索引處的項目。 |
| void [idx_set](./idx_set/)(int, T) override | 將指定值設定為陣列在指定索引處的項目。 |
| int [IndexOf](./indexof/)(const T\&) const override | 判斷指定項目在陣列中第一次出現的索引。 |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | 判斷指定項目在陣列中第一次出現的索引。 |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | 判斷指定項目在陣列中從指定索引開始第一次出現的索引。 |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | 判斷指定項目在陣列中由起始索引及範圍內元素數目所定義的範圍內第一次出現的索引。 |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | 以指定陣列的值填滿目前物件所表示的陣列。 |
| void [Initialize](./initialize/)() | 以 **T** 類型的預設建構物件填滿陣列。 |
| void [Insert](./insert/)(int, const T\&) override | 不支援，因為目前物件所表示的陣列為唯讀。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | 判斷指定項目在由起始索引及範圍內元素數目所定義之陣列範圍中最後一次出現的索引。 |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | 判斷指定項目在陣列中從指定索引開始最後一次出現的索引。 |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | 判斷指定項目在陣列中最後一次出現的索引。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | 對序列套用累加函式。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判斷序列的所有元素是否符合條件。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判斷序列是否存在任何元素或符合條件的元素。 |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | 計算透過在輸入序列的每個元素上呼叫轉換函式所獲得之值序列的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 將元素轉型為指定類型。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 串接兩個序列。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 判斷序列是否包含指定的值。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 回傳序列中元素的數量（以直接計數方式計算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | 回傳符合指定條件的序列元素數量。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 回傳序列中指定索引處的元素。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 回傳序列中指定索引處的元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 回傳序列的第一個元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | 回傳符合指定條件的序列第一個元素。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 回傳序列的第一個元素，若序列為空則回傳預設值。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 回傳符合條件的序列第一個元素，若未找到則回傳預設值。 |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | 將序列的元素分組。 |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | 將序列的元素分組。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 回傳序列的最後一個元素。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 回傳序列的最後一個元素，若序列為空則回傳預設值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | 對泛型序列的每個元素呼叫轉換函式，並回傳最大的結果值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | 對泛型序列的每個元素呼叫轉換函式，並回傳最小的結果值。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 根據指定類型過濾序列的元素。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | 根據 keySelector 所選擇的鍵值，以升序排序序列的元素。 |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | 根據 keySelector 所選擇的鍵值，以降序排序序列的元素。 |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 顛倒序列中元素的順序。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | 轉換序列的元素。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | 結合元素索引，將序列的每個元素轉換為新形式。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 對序列的每個元素進行投影，並將產生的序列合併為單一序列。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 跳過序列起始處指定數目的連續元素，並回傳其餘部分。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 回傳序列起始處指定數目的連續元素。 |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 從序列建立陣列。 |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 從序列建立 List<T>。 |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根據指定謂詞過濾序列。 |
| void [Lock](../object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../lockcontext/) 守衛物件。 |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | 使用 [operator<()](../operator_less/) 比較元素，以找出陣列中最大的元素。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | 使用 [operator<()](../operator_less/) 比較元素，以找出陣列中最小的元素。 |
|  [Object](../object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../object/object/)([Object](../object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | 移動指派運算子。 |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | 移動指派運算子。 |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | 回傳指定索引處的項目。 |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | 回傳指定索引處的項目。 |
| void * [raw_data_ptr](./raw_data_ptr/)() override | 回傳單維陣列第一個元素的指標。對多維陣列而言結果未定義。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 回傳反轉容器第一個元素的反向迭代器。它對應於未反轉容器的最後一個元素。若容器為空，回傳的迭代器等於 [rend()](./rend/)。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | 傳回指向反轉容器中第一個元素的反向迭代器。它對應於未反轉容器中的最後一個元素。如果容器為空，傳回的迭代器等於 [rend()](./rend/)。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值類型物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 的特殊化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) 的特殊化，用於字串的情況。 |
| **bool** [Remove](./remove/)(const T\&) override | 不支援，因為目前物件所代表的陣列是唯讀的。 |
| void [RemoveAt](./removeat/)(int) override | 不支援，因為目前物件所代表的陣列是唯讀的。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 傳回指向反轉容器中最後一個元素之後的元素的反向迭代器。它對應於未反轉容器中第一個元素之前的元素。此元素作為佔位符，試圖存取它會導致未定義的行為。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | 傳回指向反轉容器中最後一個元素之後的元素的反向迭代器。它對應於未反轉容器中第一個元素之前的元素。此元素作為佔位符，試圖存取它會導致未定義的行為。 |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | 將指定陣列的大小變更為指定的值，或以指定的大小建立新陣列。 |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | 反轉指定陣列中的元素。 |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 反轉指定陣列中一段範圍的元素。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 使陣列將儲存的指標視為弱參考（若適用）。 |
| void [SetValue](./setvalue/)(const T\&, int) | 設定指定索引處元素的值。 |
| int [SharedCount](../object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | 使用預設比較器對指定陣列中的元素進行排序。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 使用預設比較器對指定陣列中一段範圍的元素進行排序。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | 使用指定的比較器對指定陣列中的元素進行排序。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | 未實作。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | 使用指定的比較對指定陣列中的元素進行排序。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | 對兩個陣列進行排序，一個包含鍵，另一個包含相對應的項目，排序依據鍵陣列的值，該陣列的元素使用 operator< 進行比較。 |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | 對兩個陣列進行排序，一個包含鍵，另一個包含相對應的項目，排序依據鍵陣列的值，該陣列的元素使用預設比較器進行比較。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | [Object.ToString()](../object/tostring/) 方法的 C# 類比。啟用將自訂物件轉換為字串。 |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 判斷指定陣列中的所有元素是否符合指定謂詞所定義的條件。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 實作 C# typeof([System.Object](../object/)) 結構。 |
| void [Unlock](../object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../lockcontext/) 監護物件。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 取得目前容器的 const begin 迭代器實作。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 取得目前容器的 begin 迭代器實作。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 取得目前容器的 const end 迭代器實作。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 取得目前容器的 end 迭代器實作。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | 解構函式。 |
| virtual  [~Object](../object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 類型別名

| 別名 | 描述 |
| --- | --- |
| [ValueType](./valuetype/) | 陣列元素類型的別名。 |
| [UnderlyingType](./underlyingtype/) | 表示陣列中每個元素之類型的別名。 |
| [EnumerablePtr](./enumerableptr/) | 指向包含 **T** 類型元素之 IEnumerable 物件的共享指標類型的別名。 |
| [EnumeratorPtr](./enumeratorptr/) | 指向包含 **T** 類型元素之 IEnumerator 物件的共享指標類型的別名。 |
| [iterator](./iterator/) | 迭代器類型。 |
| [const_iterator](./const_iterator/) | 常量迭代器類型。 |
| [reverse_iterator](./reverse_iterator/) | 反向迭代器類型。 |
| [const_reverse_iterator](./const_reverse_iterator/) | 常量反向迭代器類型。 |
## 備註



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // 建立並填充陣列。
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // 列印陣列項目。
  Print(arrayPtr);

  // 以升序排序陣列項目。
  Array<int32_t>::Sort(arrayPtr);

  // 列印陣列項目。
  Print(arrayPtr);

  // 列印陣列項目的計數。
  std::cout << arrayPtr->get_Length() << std::endl;

  // 列印等於 4 的項目索引。
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // 調整陣列大小。
  Array<int32_t>::Resize(arrayPtr, 3);

  // 列印陣列項目。
  Print(arrayPtr);

  return 0;
}
/*
此程式碼範例會產生以下輸出：
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## 另請參閱

* 類別 [ArrayBase](../arraybase/)
* 類別 [IList](../../system.collections.generic/ilist/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)