---
title: LinkedList
second_title: Aspose.Slides for C++ API 參考
description: LinkedList 前向宣告。
type: docs
weight: 404
url: /zh-hant/system.collections.generic/linkedlist/
---
## LinkedList 類別


[LinkedList](./) forward declaration.

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 包含的值類型。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| void [Add](./add/)(const T\&) override | 將 **元素** 新增至列表的末端。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | 將 **元素** 插入於列表中 **節點** 之後。 |
| void [AddAfter](./addafter/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | 將 **新節點** 插入於列表中 **節點** 之後。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const T\&) | 將 **元素** 插入於列表中 **節點** 之前。 |
| void [AddBefore](./addbefore/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | 將 **新節點** 插入於列表中 **節點** 之前。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddFirst](./addfirst/)(const T\&) | 將 **元素** 新增至列表的開頭。 |
| void [AddFirst](./addfirst/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | 將 **新節點** 新增至列表的開頭。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [AddLast](./addlast/)(const T\&) | 將 **元素** 新增至列表的末端。 |
| void [AddLast](./addlast/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | 將 **新節點** 新增至列表的末端。 |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | 取得集合中第一個元素的 iterator。 |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | 取得 const 限定集合中第一個元素的 iterator。 |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | 取得集合中第一個 const 限定元素的 iterator。 |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | 取得集合結束之後的虛構 const 限定元素的 iterator。 |
| void [Clear](./clear/)() override | 刪除列表中的所有元素。 |
| **bool** [Contains](./contains/)(const T\&) const override | 檢查 **元素** 是否存在於列表中。 |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | 將容器資料複製到現有陣列元素中。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 取得集合中最後一個 const 限定元素的反向 iterator（反向的第一個）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 取得集合開始之前的虛構 const 限定元素的反向 iterator。 |
| [iterator](../ienumerable/iterator/) [end](./end/)() | 取得集合結束之後的虛構元素的 iterator。 |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | 取得 const 限定集合結束之後的虛構元素的 iterator。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使 IEC 60559:1989 規定 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使 IEC 60559:1989 規定 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [Find](./find/)(const T\&) const | 以正向搜尋**元素**於列表中。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [FindLast](./findlast/)(const T\&) const | 以反向搜尋**元素**於列表中。 |
| int [get_Count](./get_count/)() const override | 取得列表中元素的個數。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_First](./get_first/)() const | 取得列表中第一個元素的指標。 |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | 檢查集合是否唯讀。 |
| [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\> [get_Last](./get_last/)() const | 取得列表中最後一個元素的指標。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | 取得集合同步所透過的物件。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](./getenumerator/)() override | 取得用於遍歷目前 [LinkedList](./) 的列舉子。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
|  [ICollection](../icollection/icollection/)() | 預設建構子。 |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | 複製建構子。 |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | 移動建構子。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。C# `is` 運算子的類比。 |
|  [LinkedList](./linkedlist/)() | 建立空的 [LinkedList](./)。 |
|  [LinkedList](./linkedlist/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>\&) | 複製建構子。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 在序列上套用累加函式。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判斷序列的所有元素是否符合條件。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判斷序列中是否存在符合條件的任意元素。 |
| T [LINQ_Average](../ienumerable/linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 計算透過在輸入序列每個元素上呼叫轉換函式取得的值的平均值。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 將元素轉型為指定類型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 將兩個序列串接。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | 判斷序列是否包含指定值。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | 以直接計數方式返回序列中的元素數量。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回滿足指定條件的序列元素數量。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | 依索引返回序列中的元素。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | 依索引返回序列中的元素。 |
| T [LINQ_First](../ienumerable/linq_first/)() | 返回序列的第一個元素。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 返回滿足指定條件的序列第一個元素。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | 返回序列的第一個元素；若序列為空則返回預設值。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 返回符合條件的第一個元素；若無符合者則返回預設值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 對序列的元素進行分組。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 對序列的元素進行分組。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | 返回序列的最後一個元素。 |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | 返回序列的最後一個元素；若序列為空則返回預設值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 在泛型序列的每個元素上呼叫轉換函式，返回最大結果值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 在泛型序列的每個元素上呼叫轉換函式，返回最小結果值。 |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | 根據指定類型篩選序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 依照 keySelector 所選取的鍵值，以升冪排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 依照 keySelector 所選取的鍵值，以降冪排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | 反轉序列中元素的順序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 轉換序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 依據元素的索引，將序列的每個元素轉換為新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | 對序列的每個元素進行投影，並將產生的序列合併為一個序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | 從序列開始跳過指定數量的連續元素，返回剩餘部分。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | 從序列開始返回指定數量的連續元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | 從序列建立陣列。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | 從序列建立 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 以指定的謂詞過濾序列。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | 移動指派運算子。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | 移動指派運算子。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 取得集合最後一個元素的反向 iterator（反向的第一個）。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | 取得 const 限定集合最後一個元素的反向 iterator（反向的第一個）。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況的特化。 |
| **bool** [Remove](./remove/)(const T\&) override | 從列表中移除第一個出現的指定 **元素**。 |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[LinkedListNode](../linkedlistnode/)\<T\>\>\&) | 從列表中移除節點。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 以指定值減少共享參考計數。 |
| void [RemoveFirst](./removefirst/)() | 移除列表的第一個節點。 |
| void [RemoveLast](./removelast/)() | 移除列表的最後一個節點。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 取得集合開始之前的虛構元素的反向 iterator。 |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | 取得 const 限定集合開始之前的虛構元素的反向 iterator。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。請勿直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並返回共享參考計數。請勿直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 取得目前容器的 const begin iterator 實作。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 取得目前容器的 begin iterator 實作。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 取得目前容器的 const end iterator 實作。 |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 取得目前容器的 end iterator 實作。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。請勿直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。請勿直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~ICollection](../icollection/~icollection/)() | 解構函式。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [list_t](./list_t/) | 基礎資料類型。 |
| [iterator](./iterator/) | 迭代器類型。 |
| [const_iterator](./const_iterator/) | 常量迭代器類型。 |
| [reverse_iterator](./reverse_iterator/) | 反向迭代器類型。 |
| [const_reverse_iterator](./const_reverse_iterator/) | 常量反向迭代器類型。 |
## 備註


Linked list container。實作 std::list 的包裝。此類別的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此型別的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝於 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。


```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // 建立 LinkedList 類別的實例。
  auto list = MakeObject<LinkedList<int>>();

  // 填充鏈結串列。
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // 列印鏈結串列的項目。
  for (const auto item: list)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
此程式碼範例產生以下輸出：
1 15 25 30
*/
```

## 另請參閱

* 類別 [Object](../../system/object/)
* 類別 [ICollection](../icollection/)
* 類別 [Invalidatable](../../system.collections/invalidatable/)
* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)