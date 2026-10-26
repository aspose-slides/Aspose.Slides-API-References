---
title: IDictionary
second_title: Aspose.Slides for C++ API 參考
description: "用於類似字典容器的介面。此類的物件應僅使用 System::MakeObject() 函式進行配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 274
url: /zh-hant/system.collections.generic/idictionary/
---
## IDictionary 類別

介面用於類似字典的容器。此類的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式進行分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。

```cpp
template<typename TKey,typename TValue>class IDictionary : public System::Collections::Generic::ICollection<KeyValuePair<TKey, TValue>>
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| TKey | 鍵類型。 |
| TValue | 值類型。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [Add](./add/)(const TKey&, const TValue&) | 將鍵值對加入容器。 |
| virtual void [Add](../icollection/add/)(const T&) | 將元素加入集合。 |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | 取得指向集合中第一個元素（若有）的迭代器。此迭代器無法用於更改被參考的物件，因為 [GetEnumerator()](../ienumerable/getenumerator/) 會返回 T 的副本。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | 取得指向集合之 const 限定實例中第一個元素（若有）的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | 取得指向集合中第一個 const 限定元素（若有）的迭代器。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | 取得指向集合中最後一個 const 限定元素之後的迭代器（若有）。 |
| virtual void [Clear](../icollection/clear/)() | 刪除集合中的所有元素。 |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | 檢查集合中是否存在該元素。 |
| virtual **bool** [ContainsKey](./containskey/)(const TKey&) const | 檢查容器是否包含該鍵。 |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | 將字典內容複製到現有的陣列元素中。 |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | 取得指向集合中最後一個元素之後的迭代器（若有）。此迭代器無法用於更改被參考的物件，因為 [GetEnumerator()](../ienumerable/getenumerator/) 會返回 T 的副本。 |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | 取得指向 const 限定集合實例中最後一個元素之後的迭代器（若有）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | 僅供內部使用。 |
| virtual int [get_Count](../icollection/get_count/)() const | 取得集合中元素的數量。 |
| **bool** [get_IsFixedSize](./get_isfixedsize/)() const | 檢查集合大小是否固定。 |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | 檢查集合是否唯讀。 |
| **bool** [get_IsSynchronized](./get_issynchronized/)() const | 檢查容器是否為執行緒安全。 |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TKey>> [get_Keys](./get_keys/)() const | 存取鍵集合。 |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | 取得用於同步集合的物件。 |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TValue>> [get_Values](./get_values/)() const | 存取值集合。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual [SharedPtr](../../system/sharedptr/)<[IEnumerator](../ienumerator/)<T>> [GetEnumerator](../ienumerable/getenumerator/)() | 取得列舉器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual TValue [GetValueOrDefault](./getvalueordefault/)(const TKey&) const | 若找到則返回值；否則返回 **Value()**。 |
| virtual TValue [GetValueOrDefault](./getvalueordefault/)(const TKey&, const TValue&) const | 若找到則返回值；否則返回 **defaultValue**。 |
| virtual TValue [GetValueOrNull](./getvalueornull/)(const TKey&) const | 若找到則返回值；否則返回 **null**（僅對參考型別有意義）。 |
| [ICollection](../icollection/icollection/)() | 預設建構函式。 |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | 拷貝建構函式。 |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | 移動建構函式。 |
| virtual TValue [idx_get](./idx_get/)(const TKey&) const | 取得函式。 |
| virtual void [idx_set](./idx_set/)(const TKey&, TValue) | 設定函式。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | 對序列套用累加函式。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | 判斷序列的所有元素是否滿足條件。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | 判斷序列中是否存在任何元素或其是否滿足條件。 |
| T [LINQ_Average](../ienumerable/linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | 計算透過對輸入序列每個元素呼叫轉換函式所得到之值的平均值。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | 將元素轉型為指定的型別。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | 將兩個序列串接起來。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | 判斷序列是否包含指定的值。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | 返回序列中元素的數量（透過直接計數計算）。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | 返回符合指定條件的序列元素數量。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | 返回序列中指定索引處的元素。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | 返回序列中指定索引處的元素。 |
| T [LINQ_First](../ienumerable/linq_first/)() | 返回序列的第一個元素。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | 返回符合指定條件的序列的第一個元素。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | 返回序列的第一個元素；若序列為空則返回預設值。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | 返回符合條件的序列之第一個元素；若未找到則返回預設值。 |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | 對序列的元素進行分組。 |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | 對序列的元素進行分組。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | 返回序列的最後一個元素。 |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | 返回序列的最後一個元素；若序列為空則返回預設值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | 對通用序列的每個元素呼叫轉換函式，並返回最大的結果值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | 對通用序列的每個元素呼叫轉換函式，並返回最小的結果值。 |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | 根據指定的型別過濾序列的元素。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | 依據 keySelector 所選取的鍵值，以升序排列序列的元素。 |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | 依據 keySelector 所選取的鍵值，以降序排列序列的元素。 |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | 反轉序列中元素的順序。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | 轉換序列的元素。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | 結合元素索引，將序列的每個元素轉換為新形式。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | 將序列的每個元素投影，並將產生的序列合併為一個序列。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | 跳過序列開頭指定數量的連續元素，並返回其餘部分。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | 返回序列開頭指定數量的連續元素。 |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | 從序列建立陣列。 |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | 從序列建立 List<T>。 |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | 根據指定的謂詞過濾序列。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | 拷貝建構函式。實際上不複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | 移動賦值運算子。 |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | 移動賦值運算子。 |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | 賦值運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | 以參考方式比較物件。 |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | 以參考方式比較物件。 |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| virtual **bool** [Remove](./remove/)(const TKey&) | 從容器中移除鍵。 |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | 從集合中刪除元素。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| virtual **bool** [TryGetValue](./trygetvalue/)(const TKey&, TValue&) const | 搜尋值，若找到則取得。 |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | 取得目前容器之 begin const 迭代器的實作。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | 取得目前容器之 begin 迭代器的實作。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | 取得目前容器之 end const 迭代器的實作。 |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | 取得目前容器之 end 迭代器的實作。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [~ICollection](../icollection/~icollection/)() | 解構函式。 |
| virtual [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 描述 |
| --- | --- |
| [BaseType](./basetype/) | 基底介面型別。 |
| [KeyValuePairType](./keyvaluepairtype/) | 鍵值對型別。 |

## 另請參閱

* 類別 [ICollection](../icollection/)
* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)