---
title: BaseDictionary
second_title: Aspose.Slides for C++ API 參考
description: "實作各種類似字典資料結構的共用程式碼（例如 Dictionary、SortedDictionary）。不應直接使用，僅在定義容器時用於繼承。本類別的物件只能透過 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，否則會導致執行期錯誤或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 53
url: /zh-hant/system.collections.generic/basedictionary/
---
## BaseDictionary 類別

實作各種類似字典資料結構的共用程式碼（例如 [Dictionary](../dictionary/)、[SortedDictionary](../sorteddictionary/)）。不應直接使用，僅在定義容器時透過繼承使用。本類別的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行期錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| Map | Underlying map type. |

## 方法

| 方法 | 描述 |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | C++ 特有。 |
| void [Add](./add/)(const key_t\&, const mapped_t\&) override | 將鍵值對加入字典。 |
| [BaseDictionary](./basedictionary/)() | 建立空的資料結構。 |
| [BaseDictionary](./basedictionary/)(int, const Args\&...) | 轉發建構函式，將參數推送至底層 map 建構函式。 |
| [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *, const Args\&...) | 複製建構函式。 |
| [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *) | 複製建構函式。 |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 傳回指向容器中鍵值元素之 KVPair 包裝器的迭代器。以 C# 風格實作——迭代器應傳回具有 get_Key() 與 get_Value() 介面的 KVPair 物件。若容器為空，傳回的迭代器將等於 [end()](../ienumerable/end/)。 |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | 取得指向集合首個元素（若有）的迭代器。此迭代器無法用於變更所參考的物件，因為 [GetEnumerator()](../ienumerable/getenumerator/) 會傳回 T 的複本物件。 |
| stl_const_iterator [cbegin](./cbegin/)() const | 傳回指向容器第一個元素的迭代器。以 STL 風格實作。若容器為空，傳回的迭代器將等於 [end()](../ienumerable/end/)。 |
| stl_const_iterator [cend](./cend/)() const | 傳回指向容器最後一個元素之後之元素的迭代器。以 STL 風格實作。此元素作為佔位符；嘗試存取會導致未定義行為。 |
| void [Clear](./clear/)() override | 刪除所有元素。 |
| **bool** [ContainsKey](./containskey/)(const key_t\&) const override | 檢查字典中是否存在該鍵。 |
| **bool** [ContainsValue](./containsvalue/)(const mapped_t\&) | 檢查字典中是否存在該值。使用 operator == 進行比較。 |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | 將字典內容複製到現有的陣列元素中。 |
| Map\& [data](./data/)() | 底層資料儲存存取器。 |
| const Map\& [data](./data/)() const | 底層資料儲存存取器。 |
| [const_iterator](./const_iterator/) [end](./end/)() const | 傳回指向容器最後一個元素之後之鍵值元素之 KVPair 包裝器的迭代器。以 C# 風格實作——迭代器應傳回具有 get_Key() 與 get_Value() 介面的 KVPair 物件。此元素作為佔位符；嘗試存取會導致未定義行為。 |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | 取得指向集合最後一個元素之後的迭代器（若有）。此迭代器無法用於變更所參考的物件，因為 [GetEnumerator()](../ienumerable/getenumerator/) 會傳回 T 的複本物件。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 以 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **int32_t** [get_Count](./get_count/)() const override | 取得元素數量。 |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | 檢查集合大小是否固定。 |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | 檢查集合是否唯讀。 |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | 檢查容器是否為執行緒安全。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | 存取鍵集合。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | 取得用於同步集合的物件。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | 存取值集合。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關的參考計數資料結構。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[KeyValuePair](../keyvaluepair/)\<key_t, mapped_t\>\>\> [GetEnumerator](./getenumerator/)() | 建立列舉器實例，應由子類別實作。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 類似 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。類似 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | 若找到則傳回值；否則傳回 **Value()**。 |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | 若找到則傳回值；否則傳回 **defaultValue**。 |
| mapped_t [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | 若找到則傳回值；否則傳回 **null**。僅對參考型別有意義。 |
| [ICollection](../icollection/icollection/)() | 預設建構函式。 |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | 複製建構函式。 |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | 移動建構函式。 |
| mapped_t [idx_get](./idx_get/)(const key_t\&) const override | 具鍵的取得函式。 |
| void [idx_set](./idx_set/)(const key_t\&, mapped_t) override | 具鍵的設定函式。修改或建立元素。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。類似 C# 的 'is' 運算子。 |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 對序列套用累加函式。 |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判斷序列中的所有元素是否符合條件。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判斷序列中是否存在任一元素或符合條件。 |
| T [LINQ_Average](../ienumerable/linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 計算透過對輸入序列每個元素呼叫轉換函式取得之值的平均值。 |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 將元素轉型為指定類型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 串接兩個序列。 |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | 判斷序列是否包含指定的值。 |
| int [LINQ_Count](../ienumerable/linq_count/)() | 傳回序列中元素的數量（透過直接計數計算）。 |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 傳回符合指定條件的序列元素數量。 |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | 傳回序列中指定索引的元素。 |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | 傳回序列中指定索引的元素。 |
| T [LINQ_First](../ienumerable/linq_first/)() | 傳回序列的第一個元素。 |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 傳回符合指定條件的序列第一個元素。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | 傳回序列的第一個元素，若序列為空則傳回預設值。 |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 傳回符合條件的序列第一個元素，若找不到則傳回預設值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 將序列的元素分組。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 將序列的元素分組。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | 傳回序列的最後一個元素。 |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | 傳回序列的最後一個元素，若序列為空則傳回預設值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對泛型序列的每個元素呼叫轉換函式，並傳回最大結果值。 |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對泛型序列的每個元素呼叫轉換函式，並傳回最小結果值。 |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | 根據指定類型過濾序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 依 keySelector 選取的鍵值，以升序排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 依 keySelector 選取的鍵值，以降序排序序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | 顛倒序列中元素的順序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 轉換序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 將序列的每個元素結合其索引，轉換為新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | 投影序列的每個元素，並將產生的序列合併為單一序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | 從序列開頭跳過指定數量的連續元素，並傳回其餘部分。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | 從序列開頭傳回指定數量的連續元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | 從序列建立陣列。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | 從序列建立 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根據指定的條件式過濾序列。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 類似 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | 移動指派運算子。 |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | 移動指派運算子。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| virtual mapped_t\& [operator[]](./operator[]/)(const key_t\&) | 存取函式。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況的特化。 |
| **bool** [Remove](./remove/)(const key_t\&) override | 從字典中移除指定鍵。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定值。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 類似 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| **bool** [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | 尋找具鍵的值，若找到則取得。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 取得目前容器的 begin const 迭代器實作。 |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 取得目前容器的 begin 迭代器實作。 |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 取得目前容器的 end const 迭代器實作。 |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 取得目前容器的 end 迭代器實作。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~ICollection](../icollection/~icollection/)() | 解構函式。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 描述 |
| --- | --- |
| [map_t](./map_t/) | 內部 map 類型。 |
| [KeyCollection](./keycollection/) | 確保使用正確的分配器與底層儲存類型。 |
| [ValueCollection](./valuecollection/) | 值的集合。 |
| [KVPair](./kvpair/) | 鍵值對類型。 |
| [BaseType](./basetype/) | 已實作的介面。 |
| [iterator](./iterator/) | 迭代器類型。 |
| [const_iterator](./const_iterator/) | 常量迭代器類型。 |

## 另請參閱

* 類別 [IDictionary](../idictionary/)
* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)