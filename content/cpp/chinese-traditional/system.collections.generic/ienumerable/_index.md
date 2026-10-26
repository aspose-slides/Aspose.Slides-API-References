---
title: IEnumerable
second_title: Aspose.Slides for C++ API 參考
description: 提供列舉器以存取所包含元素的物件介面。
type: docs
weight: 287
url: /zh-hant/system.collections.generic/ienumerable/
---
## IEnumerable 類別

Interface of object providing enumerator on contained elements.

```cpp
template<typename T>class IEnumerable : public virtual System::Object
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 元素類型。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [iterator](./iterator/) [begin](./begin/)() | 取得指向集合第一個元素（若有）的迭代器。由於 [GetEnumerator()](./getenumerator/) 會回傳 T 的副本物件，此迭代器無法用來變更被參考的物件。 |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 取得指向集合之 const 限定實例的第一個元素（若有）的迭代器。 |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | 取得指向集合第一個 const 限定元素（若有）的迭代器。 |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | 取得指向集合最後一個 const 限定元素（若有）之後的迭代器。 |
| [iterator](./iterator/) [end](./end/)() | 取得指向集合最後一個元素（若有）之後的迭代器。由於 [GetEnumerator()](./getenumerator/) 會回傳 T 的副本物件，此迭代器無法用來變更被參考的物件。 |
| [const_iterator](./const_iterator/) [end](./end/)() const | 取得指向 const 限定集合實例最後一個元素（若有）之後的迭代器。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參照計數資料結構。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](./getenumerator/)() | 取得列舉器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| T [LINQ_Aggregate](./linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 對序列套用累加函式。 |
| **bool** [LINQ_All](./linq_all/)(std::function\<**bool**(T)>) | 判斷序列的所有元素是否滿足條件。 |
| **bool** [LINQ_Any](./linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](./linq_any/)(std::function\<**bool**(T)>) | 判斷序列是否有任一元素存在或滿足條件。 |
| T [LINQ_Average](./linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](./linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 計算透過對輸入序列每個元素呼叫轉換函式取得之值的平均值。 |
| ResultType [LINQ_Average](./linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_Cast](./linq_cast/)() | 將元素轉型為指定的類型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_Cast](./linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Concat](./linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\>) | 串接兩個序列。 |
| **bool** [LINQ_Contains](./linq_contains/)(T) | 判斷序列是否包含指定的值。 |
| int [LINQ_Count](./linq_count/)() | 回傳序列中元素的數量（透過直接計數計算）。 |
| int [LINQ_Count](./linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 回傳符合指定條件的序列元素數量。 |
| T [LINQ_ElementAt](./linq_elementat/)(int) | 回傳序列中指定索引處的元素。 |
| T [LINQ_ElementAtOrDefault](./linq_elementatordefault/)(int) | 回傳序列中指定索引處的元素。 |
| T [LINQ_First](./linq_first/)() | 回傳序列的第一個元素。 |
| T [LINQ_First](./linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 回傳符合指定條件的序列的第一個元素。 |
| T [LINQ_FirstOrDefault](./linq_firstordefault/)() | 回傳序列的第一個元素；若序列為空則回傳預設值。 |
| T [LINQ_FirstOrDefault](./linq_firstordefault/)(std::function\<**bool**(T)>) | 回傳符合條件的第一個元素；若未找到則回傳預設值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 將序列的元素分組。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 將序列的元素分組。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](./linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](./linq_last/)() | 回傳序列的最後一個元素。 |
| T [LINQ_LastOrDefault](./linq_lastordefault/)() | 回傳序列的最後一個元素；若序列為空則回傳預設值。 |
| ResultType [LINQ_Max](./linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對泛型序列的每個元素呼叫轉換函式，並回傳最大產生值。 |
| ResultType [LINQ_Max](./linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](./linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對泛型序列的每個元素呼叫轉換函式，並回傳最小產生值。 |
| ResultType [LINQ_Min](./linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_OfType](./linq_oftype/)() | 根據指定的類型過濾序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_OfType](./linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](./linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 根據 keySelector 所選的鍵值，將序列的元素以升序排序。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](./linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](./linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 根據 keySelector 所選的鍵值，將序列的元素以降序排序。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](./linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Reverse](./linq_reverse/)() | 顛倒序列中元素的順序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 轉換序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 根據元素的索引，將序列的每個元素轉換為新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_Select](./linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\> [LINQ_SelectMany](./linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<ResultType\>\>\>\&) | 將序列的每個元素投影，並將產生的序列合併為一個序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\> [LINQ_SelectMany](./linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Skip](./linq_skip/)(**int32_t**) | 跳過序列開頭指定數量的連續元素，並回傳剩餘部分。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Take](./linq_take/)(**int32_t**) | 回傳序列開頭指定數量的連續元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](./linq_toarray/)() | 從序列建立陣列。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](./linq_tolist/)() | 從序列建立 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](./)\<T\>\> [LINQ_Where](./linq_where/)(std::function\<**bool**(T)>) | 根據指定的斷言過濾序列。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何東西，只是初始化新物件，並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指定運算子。實際上不會複製任何東西，只是初始化新物件，並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參照計數。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const | 取得目前容器 const begin 迭代器的實作。 |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() | 取得目前容器 begin 迭代器的實作。 |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const | 取得目前容器 const end 迭代器的實作。 |
| virtual [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() | 取得目前容器 end 迭代器的實作。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [IEnumeratorType](./ienumeratortype/) | 列舉器類型。 |
| [ValueType](./valuetype/) |  |
| [iterator](./iterator/) | 迭代器類型。 |
| [const_iterator](./const_iterator/) | 常量迭代器類型。 |
| [virtualized_iterator](./virtualized_iterator/) | 內部迭代器基礎類型。 |
| [virtualized_iterator_element](./virtualized_iterator_element/) | 內部迭代器元素類型。 |

## 另見

* 類別 [Object](../../system/object/)
* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)