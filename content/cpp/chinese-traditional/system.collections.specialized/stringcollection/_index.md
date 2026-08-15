---
title: StringCollection
second_title: Aspose.Slides for C++ API 參考
description: "字串的索引清單。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用此指標將其作為參數傳遞給函式。"
type: docs
weight: 27
url: /zh-hant/system.collections.specialized/stringcollection/
---
## StringCollection 類別


字串的索引清單。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。

```cpp
class StringCollection : public System::Collections::Generic::IEnumerable<System::String>
```

## 方法

| Method | Description |
| --- | --- |
| int [Add](./add/)(const [System::String](../../system/string/)\&) | 將值新增至列表的末端。 |
| void [AddRange](./addrange/)(const [ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>\&) | 將元素加入容器。 |
| [iterator](./iterator/) [begin](./begin/)() | 傳回指向容器第一個元素的疊代器。若容器為空，傳回的疊代器將等於 [end()](./end/)。 |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 傳回指向 const 限定容器第一個元素的疊代器。若容器為空，傳回的疊代器將等於 [end()](./end/)。 |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | 傳回指向容器第一個 const 限定元素的疊代器。若容器為空，傳回的疊代器將等於 [cend()](./cend/)。 |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | 傳回指向容器最後一個元素之後之元素的疊代器。此元素充當占位符；嘗試存取將導致未定義的行為。 |
| void [Clear](./clear/)() | 刪除所有元素。 |
| **bool** [Contains](./contains/)(const [System::String](../../system/string/)\&) const | 檢查特定字串是否存在於容器中。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>\&, const **int32_t**) const | 將元素複製到現有陣列的元素中。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 傳回指向反向容器第一個元素的反向疊代器。它對應於未反向容器的最後一個元素。若容器為空，傳回的疊代器等於 [crend()](./crend/)。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 傳回指向反向容器最後一個元素之後之元素的反向疊代器。它對應於未反向容器的第一個元素之前的元素。此元素充當占位符，嘗試存取將導致未定義的行為。 |
| std::vector\<[System::String](../../system/string/)\>\& [data](./data/)() | 內部資料結構存取器。 |
| const std::vector\<[System::String](../../system/string/)\>\& [data](./data/)() const | 內部資料結構存取器。 |
| [iterator](./iterator/) [end](./end/)() | 傳回指向容器最後一個元素之後之元素的疊代器。此元素充當占位符；嘗試存取將導致未定義的行為。 |
| [const_iterator](./const_iterator/) [end](./end/)() const | 傳回指向 const 限定容器最後一個元素之後之元素的疊代器。此元素充當占位符；嘗試存取將導致未定義的行為。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| int [get_Count](./get_count/)() const | 取得集合中的元素數量。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::String](../../system/string/)\>\> [GetEnumerator](./getenumerator/)() override | 取得遍歷目前集合的列舉器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| [System::String](../../system/string/) [idx_get](./idx_get/)(int) const | 取得指定位置的值。 |
| void [idx_set](./idx_set/)(int, const [System::String](../../system/string/)\&) | 設定指定位置的值。 |
| int [IndexOf](./indexof/)(const [System::String](../../system/string/)\&) const | 在容器中搜尋特定字串。 |
| void [Insert](./insert/)(int, const [System::String](../../system/string/)\&) | 在容器中插入特定值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 對序列套用累加函式。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判斷序列的所有元素是否滿足條件。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判斷序列中是否有任意元素存在或滿足條件。 |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 計算透過對輸入序列的每個元素呼叫轉換函式取得之值的平均。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 將元素轉型為指定類型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 連接兩個序列。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 判斷序列是否包含指定值。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 傳回序列中元素的數量（透過直接計數計算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 傳回滿足指定條件的序列元素數量。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 傳回序列中指定索引的元素。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 傳回序列中指定索引的元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 傳回序列的第一個元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 傳回滿足指定條件的序列第一個元素。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 傳回序列的第一個元素；若序列為空，則傳回預設值。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 傳回符合條件的序列第一個元素；如果未找到符合的元素，則傳回預設值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 將序列的元素分組。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 將序列的元素分組。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 傳回序列的最後一個元素。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 傳回序列的最後一個元素；若序列為空，則傳回預設值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對通用序列的每個元素呼叫轉換函式，並傳回最大的結果值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對通用序列的每個元素呼叫轉換函式，並傳回最小的結果值。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 根據指定類型過濾序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 依照 keySelector 選取的鍵值，以升序排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 依照 keySelector 選取的鍵值，以降序排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 反轉序列中元素的順序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 轉換序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 將序列的每個元素結合其索引，轉換為新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 投影序列的每個元素，並將產生的序列合併為一個序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 跳過序列開頭指定數量的連續元素，並傳回其餘部分。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 傳回序列開頭指定數量的連續元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 從序列建立陣列。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 從序列建立 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根據指定的謂詞過濾序列。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的上鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) | 存取函式。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 傳回指向反向容器第一個元素的反向疊代器。它對應於未反向容器的最後一個元素。若容器為空，傳回的疊代器等於 [rend()](./rend/)。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | 傳回指向反向容器第一個元素的反向疊代器。它對應於未反向容器的最後一個元素。若容器為空，傳回的疊代器等於 [rend()](./rend/)。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，針對字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，針對字串的情況。 |
| void [Remove](./remove/)(const [System::String](../../system/string/)\&) | 移除指定字串的第一次出現。 |
| void [RemoveAt](./removeat/)(int) | 移除指定位置的元素。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定值。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 傳回指向反向容器最後一個元素之後之元素的反向疊代器。它對應於未反向容器的第一個元素之前的元素。此元素充當占位符，嘗試存取將導致未定義的行為。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | 傳回指向反向容器最後一個元素之後之元素的反向疊代器。它對應於未反向容器的第一個元素之前的元素。此元素充當占位符，嘗試存取將導致未定義的行為。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [StringCollection](./stringcollection/)() | 建構空的字串集合。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 结构。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 取得目前容器的 const 起始疊代器實作。 |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 取得目前容器的起始疊代器實作。 |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 取得目前容器的 const 結束疊代器實作。 |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 取得目前容器的結束疊代器實作。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| Typedef | Description |
| --- | --- |
| [iterator](./iterator/) | 疊代器類型。 |
| [const_iterator](./const_iterator/) | 常量疊代器類型。 |
| [reverse_iterator](./reverse_iterator/) | 反向疊代器類型。 |
| [const_reverse_iterator](./const_reverse_iterator/) | 常量反向疊代器類型。 |

## 另請參閱

* 類別 [IEnumerable](../../system.collections.generic/ienumerable/)
* 命名空間 [System::Collections::Specialized](../)
* 函式庫 [Aspose.Slides](../../)