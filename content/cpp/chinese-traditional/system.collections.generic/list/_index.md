---
title: List
second_title: Aspose.Slides for C++ API 參考
description: List 前向宣告。
type: docs
weight: 430
url: /zh-hant/system.collections.generic/list/
---
## List 類別

[List](./) 前向宣告。

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 元素類型。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++ 專用。 |
| void [Add](./add/)(const T\&) override | 將元素加入列表的末端。 |
| void [AddInitializer](./addinitializer/)(int, const T *) | 將元素加入列表；於翻譯初始化式時使用。 |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | 將集合（或自身）中的所有元素加入目前列表的末端。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | 取得此集合的唯讀參考。 |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | 取得集合第一個元素的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | 取得 const 限定集合第一個元素的迭代器。 |
| int [BinarySearch](./binarysearch/)(const T\&) const | 在已排序的列表中搜尋項目。 |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | 在已排序的列表中搜尋項目。 |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | 在已排序的列表中搜尋項目。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | 取得集合之第一個 const 限定元素的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | 取得集合末端之後的不存在的 const 限定元素的迭代器。 |
| void [Clear](./clear/)() override | 刪除全部元素。 |
| **bool** [Contains](./contains/)(const T\&) const override | 檢查列表中是否存在項目。 |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | 建立一個元素已轉換為不同類型的列表。 |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | 將列表元素複製至現有的陣列元素中。 |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | 將全部元素複製至現有的陣列元素中。 |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | 從指定索引開始，將元素複製至現有的陣列元素中。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 取得集合最後一個 const 限定元素的反向迭代器（反向的第一個）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 取得集合開始之前的不存在的 const 限定元素的反向迭代器。 |
| [vector_t](./vector_t/)\& [data](./data/)() | 底層資料結構存取函式。 |
| const [vector_t](./vector_t/)\& [data](./data/)() const | 底層資料結構存取函式。 |
| [iterator](../ienumerable/iterator/) [end](./end/)() | 取得集合末端之後的不存在元素的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | 取得 const 限定集合末端之後的不存在元素的迭代器。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較引用類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | 檢查列表中是否存在符合特定謂詞的元素。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | 尋找符合特定謂詞的元素。 |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | 尋找符合特定謂詞的元素集合。 |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | 尋找符合特定謂詞的元素。 |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | 尋找符合特定謂詞的元素。 |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | 尋找符合特定謂詞的元素。 |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | 尋找符合特定謂詞的最後一個元素。 |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | 對列表中所有元素套用動作。 |
| int [get_Capacity](./get_capacity/)() const | 取得目前列表的容量。 |
| int [get_Count](./get_count/)() const override | 取得目前列表中的元素數量。 |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | 檢查集合是否為固定大小。 |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | 檢查集合是否唯讀。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | 取得集合同步所使用的物件。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | 取得列舉子以遍歷列表元素。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 類似 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| **ThisPtr** [GetRange](./getrange/)(int, int) | 建立列表的切片。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。類似 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
|  [ICollection](../icollection/icollection/)() | 預設建構子。 |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | 複製建構子。 |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | 移動建構子。 |
| T [idx_get](./idx_get/)(int) const override | 取得特定位置的元素。 |
| void [idx_set](./idx_set/)(int, T) override | 設定特定位置的元素。 |
| int [IndexOf](./indexof/)(const T\&) const override | 取得特定項目的第一個索引。 |
| int [IndexOf](./indexof/)(const T\&, int) const | 在列表中尋找特定項目。 |
| void [Insert](./insert/)(int, const T\&) override | 在指定位置插入項目。 |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | 在特定位置插入資料範圍。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型描述的實例。類似 C# 'is' 運算子。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | 搜尋指定物件並返回其在整個列表中最後一次出現的零基索引。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | 搜尋指定物件並返回其在 [List](./) 中，從第一個元素至指定索引範圍內最後一次出現的零基索引。 |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | 搜尋指定物件並返回其在 [List](./) 中，包含指定元素數量且以指定索引結束的範圍內最後一次出現的零基索引。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 對序列套用累加函式。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判斷序列的所有元素是否滿足條件。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判斷序列中是否存在任何元素或其是否滿足條件。 |
| T [LINQ_Average](../ienumerable/linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 計算透過對輸入序列每個元素呼叫轉換函式取得之值序列的平均值。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 將元素轉型為指定的類型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 串接兩個序列。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | 判斷序列是否包含指定的值。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | 返回序列中元素的數量（透過直接計數計算）。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回符合指定條件的序列元素數量。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | 返回序列中指定索引的元素。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | 返回序列中指定索引的元素。 |
| T [LINQ_First](../ienumerable/linq_first/)() | 返回序列的第一個元素。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回符合指定條件的序列第一個元素。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | 返回序列的第一個元素；若序列為空則返回預設值。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 返回符合條件的序列第一個元素；若未找到則返回預設值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 將序列的元素分組。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 將序列的元素分組。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | 返回序列的最後一個元素。 |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | 返回序列的最後一個元素；若序列為空則返回預設值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對泛型序列的每個元素呼叫轉換函式，並返回最大結果值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對泛型序列的每個元素呼叫轉換函式，並返回最小結果值。 |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | 根據指定類型過濾序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 依 keySelector 所選鍵值，以升冪排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 依 keySelector 所選鍵值，以降冪排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | 反轉序列中元素的順序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 轉換序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 根據元素索引，將序列的每個元素轉換為新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | 投影序列的每個元素並將產生的序列合併為單一序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | 從序列起始處跳過指定數量的連續元素，並返回其餘部分。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | 返回序列起始處指定數量的連續元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | 從序列建立陣列。 |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | 從序列建立 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根據指定謂詞過濾序列。 |
|  [List](./list/)() | 建立空列表。 |
|  [List](./list/)(int) | 建立具預先定義容量的列表。 |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | 複製建構子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 類似 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | 移動賦值運算子。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | 移動賦值運算子。 |
| vector_t::reference [operator[]](./operator[]/)(int) | 存取函式。 |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | 存取函式。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 取得集合最後一個元素的反向迭代器（反向的第一個）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | 取得 const 限定集合最後一個元素的反向迭代器（反向的第一個）。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況的特化。 |
| **bool** [Remove](./remove/)(const T\&) override | 從列表中移除第一個出現的特定項目。 |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | 移除所有符合特定謂詞的元素。 |
| void [RemoveAt](./removeat/)(int) override | 移除指定位置的項目。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定值。 |
| void [RemoveRange](./removerange/)(int, int) | 移除列表的切片。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 取得集合開始之前的不存在元素的反向迭代器。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | 取得 const 限定集合開始之前的不存在元素的反向迭代器。 |
| void [Reverse](./reverse/)() | 反轉整個列表的元素順序。 |
| void [Reverse](./reverse/)(int, int) | 反轉列表切片的元素順序。 |
| void [set_Capacity](./set_capacity/)(int) | 設定列表容量。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫；應使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不要直接呼叫；應使用智慧指標或 ThisProtector。 |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | 對列表中的元素排序。 |
| void [Sort](./sort/)() | 使用預設比較器對列表元素排序。 |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | 對列表切片的元素排序。 |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | 對列表中的元素排序。 |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | 將列表轉換為陣列。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 類似 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉為字串。 |
| void [TrimExcess](./trimexcess/)() | 將列表容量調整為符合其大小。 |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | 判斷集合中所有元素是否符合指定謂詞的條件。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 取得目前容器的 const begin 迭代器實作。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 取得目前容器的 begin 迭代器實作。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 取得目前容器的 const end 迭代器實作。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 取得目前容器的 end 迭代器實作。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；應使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；應使用智慧指標或 ThisProtector。 |
| virtual  [~ICollection](../icollection/~icollection/)() | 解構函式。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [ValueType](./valuetype/) | 此型別。 |
| [BaseType](./basetype/) | 介面型別。 |
| [vector_t](./vector_t/) | 底層資料型別。 |
| [iterator](./iterator/) | 迭代器型別。 |
| [const_iterator](./const_iterator/) | 常量迭代器型別。 |
| [reverse_iterator](./reverse_iterator/) | 反向迭代器型別。 |
| [const_reverse_iterator](./const_reverse_iterator/) | 常量反向迭代器型別。 |
| [IEnumerablePtr](./ienumerableptr/) | 保存相同類型元素的容器。 |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** 型別。 |

## 備註

[List](./) - 用於翻譯後程式碼的 std::vector 包裝器。需為元素類型實作 operator ==。此類別的物件只能透過 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤或斷言失敗。請始終將此類別包裹於 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // 建立第一個列表。
  auto list1 = MakeObject<List<int>>();

  // 填充第一個列表。
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // 排序第一個列表。
  // 第一個列表的項目將為: {-5, 1, 3, 8}
  list1->Sort();

  // 移除索引 2 處的項目。
  // 第一個列表的項目將為: {-5, 1, 8}
  list1->RemoveAt(2);

  // 在索引 1 插入項目。
  // 第一個列表的項目將為: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // 建立第二個列表。
  auto list2 = MakeObject<List<int>>();

  // 填充第二個列表。
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // 將第二個列表的元素附加到第一個列表。
  list1->AddRange(list2);

  // 列印第一個列表的項目。
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
此程式範例產生以下輸出：
- 5 15 1 8 10 20 30
*/
```

## 另見

* Class [Object](../../system/object/)
* Class [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)