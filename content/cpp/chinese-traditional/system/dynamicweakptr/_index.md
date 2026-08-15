---
title: DynamicWeakPtr
second_title: Aspose.Slides for C++ API 參考
description: 智慧指標類別會追蹤已儲存物件的模板參數的指標模式，並在每次指派後更新。此類型是用於管理其他物件刪除的指標。它應該分配於堆疊上，並以值或 const 參考傳遞給函式。
type: docs
weight: 781
url: /zh-hant/system/dynamicweakptr/
---
## DynamicWeakPtr 類別

智慧指標類別會追蹤已儲存物件的模板參數的指標模式，並在每次指派後進行更新。此類型是用於管理其他物件刪除的指標。它應該分配於堆疊上，並以值或 const 參考傳遞給函式。

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Pointee | type. |
| trunkMode | Mode of smart pointer itself, shared or weak. |
| weakLeafs | Indexes of template arguments of stored type which should be set to weak pointer mode. |

## 方法

| 方法 | 說明 |
| --- | --- |
| auto [begin](../smartptr/begin/)() | 取得底層集合的 [begin()](../smartptr/begin/) 方法。僅在 SmartPtr_ 為具備 [begin()](../smartptr/begin/) 方法的特化型別時可編譯。 |
| auto [begin](../smartptr/begin/)() const | 取得底層集合的 [begin()](../smartptr/begin/) 方法。僅在 SmartPtr_ 為具備 [begin()](../smartptr/begin/) 方法的特化型別時可編譯。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 將指標轉型為其自身類型。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用 static_cast 將指標轉型為基底類型。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用 dynamic_cast 將指標轉型為衍生類型。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用 dynamic_cast 將指標轉型為衍生類型。 |
| auto [cbegin](../smartptr/cbegin/)() const | 取得底層集合的 [cbegin()](../smartptr/cbegin/) 方法。僅在 SmartPtr_ 為具備 [cbegin()](../smartptr/cbegin/) 方法的特化型別時可編譯。 |
| auto [cend](../smartptr/cend/)() const | 取得底層集合的 [cend()](../smartptr/cend/) 方法。僅在 SmartPtr_ 為具備 [cend()](../smartptr/cend/) 方法的特化型別時可編譯。 |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | 使用 const_cast 將指標轉型為不同類型。 |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | 使用 dynamic_cast 將指標轉型為不同類型。 |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | 建立空的智慧指標。 |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | 建立指向給定物件的智慧指標。 |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | 以複製建構方式建立智慧指標。 |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | 以複製建構方式建立智慧指標。 |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | 以複製建構方式建立智慧指標。 |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | 以移動建構方式建立智慧指標。 |
| auto [end](../smartptr/end/)() | 取得底層集合的 [end()](../smartptr/end/) 方法。僅在 SmartPtr_ 為具備 [end()](../smartptr/end/) 方法的特化型別時可編譯。 |
| auto [end](../smartptr/end/)() const | 取得底層集合的 [end()](../smartptr/end/) 方法。僅在 SmartPtr_ 為具備 [end()](../smartptr/end/) 方法的特化型別時可編譯。 |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | 取得指向的物件。 |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | 取得指標模式。 |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | 取得指向的物件，並斷言指標處於共享模式。 |
| int [get_shared_count](../smartptr/get_shared_count/)() const | 取得指向同一物件的共享指標數量（含目前的指標），並斷言目前指標為共享模式。 |
| int [GetHashCode](../smartptr/gethashcode/)() const | 對指向的物件呼叫 [GetHashCode()](../smartptr/gethashcode/)。 |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | 取得目前參照的物件（若有），否則拋出例外。 |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | 取得指向的物件（若有），若無則返回 nullptr。等同於 [get()](../smartptr/get/)。 |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | 取得參照的物件。 |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | 取得指向的物件（若有），若無則返回 nullptr。等同於 [get()](../smartptr/get/)。 |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | 檢查指向的物件是否為特定類型或其子類型。遵循 C# 的 'is' 語意。 |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | 檢查指標是否指向除擁有的物件之外的其他物件（由別名建構子建立）。 |
| **bool** [IsShared](../smartptr/isshared/)() const | 檢查指標是否處於共享模式。 |
| **bool** [IsWeak](../smartptr/isweak/)() const | 檢查指標是否處於弱引用模式。 |
| explicit  [operator bool](../smartptr/operator_bool/)() const | 檢查指標是否非空。 |
| **bool** [operator!](../smartptr/operator_not/)() const | 檢查指標是否為空。 |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | 取得指向物件的參照。斷言指標非空。 |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | 允許存取參照物件的成員。 |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | 提供 [SmartPtr](../smartptr/) 類別的較小比較語意。 |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | 提供 [SmartPtr](../smartptr/) 類別的較小比較語意。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | 以移動指派方式賦值智慧指標。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | 以複製指派方式賦值智慧指標。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | 以複製指派方式賦值智慧指標。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | 賦值智慧指標。 |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | 將智慧指標設定為空。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 檢查智慧指標是否為空。 |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | 移除指標的別名（由別名建構子建立），確保其（若為共享）管理或（若為弱）追蹤相同的指向物件。 |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | 設定指向的物件。 |
| void [reset](../smartptr/reset/)() | 使指標指向 nullptr。 |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | 設定指標模式。可能會改變被參照物件的參考計數。 |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 對指向的物件（若有）呼叫 SetTemplateWeakPtr() 方法。 |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | 建立所需模式的 [SmartPtr](../smartptr/) 物件。 |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 建立具有所需模式的空指標 [SmartPtr](../smartptr/) 物件。 |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 建立指向指定物件的 [SmartPtr](../smartptr/)，或將原始指標轉換為 [SmartPtr](../smartptr/)。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | 以複製建構方式建立 [SmartPtr](../smartptr/) 物件。兩個指標之後指向相同的物件。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | 以複製建構方式建立 [SmartPtr](../smartptr/) 物件。兩個指標之後指向相同的物件。若允許，會執行型別轉換。 |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | 以移動建構方式建立 [SmartPtr](../smartptr/) 物件。若兩指標模式相同，則交換兩指標。呼叫後 x 可能無法使用。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 透過建立不同類型的新陣列，將參照陣列的型別轉換。若在 C# 中有陣列型別轉換但 C++ 不支援時很有用。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | 初始化空陣列。用於翻譯某些 C# 代碼結構。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 建立一個 [SmartPtr](../smartptr/)，其與 ptr 的初始值共享所有權資訊，但持有不相關且未管理的指標 p。 |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | 使用 static_cast 將指標轉型為不同類型。 |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | 將任意指標類型轉換為指向 [Object](../object/) 的指標。無需 Pointee_ 類型完整。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | 取得 Pointee_ 類型之 [System::TypeInfo](../typeinfo/) 物件的快捷方式。 |
|  [~SmartPtr](../smartptr/~smartptr/)() | 銷毀 [SmartPtr](../smartptr/) 物件。如有需要，減少指向物件的參考計數並刪除物件。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) 基底類別別名。 |
| [DynamicWeakPtr_](./dynamicweakptr_/) | 自身類型別名。 |
| [Pointee_](./pointee_/) | 指向類型。 |

## 參見

* 類別 [SmartPtr](../smartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)