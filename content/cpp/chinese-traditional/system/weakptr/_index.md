---
title: WeakPtr
second_title: Aspose.Slides for C++ API 參考
description: "在建構時設定自身為弱模式的 System::SmartPtr 子類別。請注意，此類別不保證其實例在整個生命週期都保持弱模式，因為 set_Mode() 仍可存取。此類型是一個用於管理其他物件刪除的指標。它應該在堆疊上分配，並以值或 const 參考傳遞給函式。"
type: docs
weight: 1496
url: /zh-hant/system/weakptr/
---
## WeakPtr 類別


Subclass of [System::SmartPtr](../smartptr/) which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as [set_Mode()](../smartptr/set_mode/) is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | 被指向類型。 |
## 方法

| Method | Description |
| --- | --- |
| auto [begin](../smartptr/begin/)() | 存取底層集合的 [begin()](../smartptr/begin/) 方法。僅在 SmartPtr_ 為具備 [begin()](../smartptr/begin/) 方法的專門化類型時編譯。 |
| auto [begin](../smartptr/begin/)() const | 存取底層集合的 [begin()](../smartptr/begin/) 方法。僅在 SmartPtr_ 為具備 [begin()](../smartptr/begin/) 方法的專門化類型時編譯。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 將指標轉型為其本身的類型。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用 static_cast 將指標轉型為基底類型。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用 dynamic_cast 將指標轉型為衍生類型。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | 使用 dynamic_cast 將指標轉型為衍生類型。 |
| auto [cbegin](../smartptr/cbegin/)() const | 存取底層集合的 [cbegin()](../smartptr/cbegin/) 方法。僅在 SmartPtr_ 為具備 [cbegin()](../smartptr/cbegin/) 方法的專門化類型時編譯。 |
| auto [cend](../smartptr/cend/)() const | 存取底層集合的 [cend()](../smartptr/cend/) 方法。僅在 SmartPtr_ 為具備 [cend()](../smartptr/cend/) 方法的專門化類型時編譯。 |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | 使用 const_cast 將指標轉型為不同類型。 |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | 使用 dynamic_cast 將指標轉型為不同類型。 |
| auto [end](../smartptr/end/)() | 存取底層集合的 [end()](../smartptr/end/) 方法。僅在 SmartPtr_ 為具備 [end()](../smartptr/end/) 方法的專門化類型時編譯。 |
| auto [end](../smartptr/end/)() const | 存取底層集合的 [end()](../smartptr/end/) 方法。僅在 SmartPtr_ 為具備 [end()](../smartptr/end/) 方法的專門化類型時編譯。 |
| **bool** [expired](./expired/)() const | 檢查被參考的物件是否已被刪除。 |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | 取得指向的物件。 |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | 取得指標模式。 |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | 取得指向的物件，但會斷言指標處於共享模式。 |
| int [get_shared_count](../smartptr/get_shared_count/)() const | 取得指向同一物件的共享指標數量（包含目前此指標），並斷言目前指標為共享模式。 |
| [Object](../object/) * [get_weak](./get_weak/)() const | 取得被參考的物件，並斷言指標處於弱模式。 |
| int [GetHashCode](../smartptr/gethashcode/)() const | 在指向的物件上呼叫 [GetHashCode()](../smartptr/gethashcode/)。 |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | 取得目前被參考的物件（若有），若無則拋出例外。 |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | 取得指向的物件（若有），若無則返回 nullptr。與 [get()](../smartptr/get/) 相同。 |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | 取得被參考的物件。 |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | 取得指向的物件（若有），若無則返回 nullptr。與 [get()](../smartptr/get/) 相同。 |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | 檢查指向的物件是否為特定類型或其子類型。遵循 C# 的 'is' 語意。 |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | 檢查指標是否指向非擁有的其他物件（由別名建構子建立）。 |
| **bool** [IsShared](../smartptr/isshared/)() const | 檢查指標是否處於共享模式。 |
| **bool** [IsWeak](../smartptr/isweak/)() const | 檢查指標是否處於弱模式。 |
| explicit  [operator bool](../smartptr/operator_bool/)() const | 檢查指標是否非 null。 |
| **bool** [operator!](../smartptr/operator_not/)() const | 檢查指標是否為 null。 |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | 取得指向物件的參考，並斷言指標非 null。 |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | 允許存取被參考物件的成員。 |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | 為 [SmartPtr](../smartptr/) 類別提供小於比較語意。 |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | 為 [SmartPtr](../smartptr/) 類別提供小於比較語意。 |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | 將值指派給弱指標，呼叫 SmartPtr_ 的特定賦值運算子。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | 將 [SmartPtr](../smartptr/) 物件以移動方式賦值。x 變為不可使用。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | 將 [SmartPtr](../smartptr/) 物件以拷貝方式賦值。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | 將 [SmartPtr](../smartptr/) 物件以拷貝方式賦值，執行必要的型別轉換。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | 將原始指標指派給 [SmartPtr](../smartptr/) 物件。 |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | 將指標值設為 nullptr。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 檢查弱指標是否為 null。 |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | 移除別名（由別名建構子建立）的指標，確保其管理（若為共享）或追蹤（若為弱）相同的物件。 |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | 設定指向的物件。 |
| void [reset](../smartptr/reset/)() | 使指標指向 nullptr。 |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | 設定指標模式。可能會改變被參考物件的引用計數。 |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 在指向的物件（若有）上呼叫 SetTemplateWeakPtr() 方法。 |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | 建立指定模式的 [SmartPtr](../smartptr/) 物件。 |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | 建立指定模式的空指標 [SmartPtr](../smartptr/) 物件。 |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 建立指向指定物件的 [SmartPtr](../smartptr/)，或將原始指標轉換為 [SmartPtr](../smartptr/)。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | 以拷貝方式建構 [SmartPtr](../smartptr/) 物件。建構後兩個指標指向相同的物件。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | 以拷貝方式建構 [SmartPtr](../smartptr/) 物件。建構後兩個指標指向相同的物件。若允許則執行型別轉換。 |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | 以移動方式建構 [SmartPtr](../smartptr/) 物件。實際上會交換兩個指標（若模式相同），呼叫後 x 可能不可使用。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | 透過建立不同類型的新陣列，轉換被參考陣列的型別。若在 C# 中有陣列型別轉換而 C++ 不支援時，此方法很有用。 |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | 初始化空陣列。用於翻譯某些 C# 程式碼結構。 |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | 建構一個 [SmartPtr](../smartptr/)，其所有權資訊與 ptr 的初始值共享，但持有與指標 p 無關且未受管理的指標。 |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | 使用 static_cast 將指標轉型為不同類型。 |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | 將任意指標型別轉換為指向 [Object](../object/) 的指標。無需 Pointee_ 類型完整。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | 取得 Pointee_ 類型之 [System::TypeInfo](../typeinfo/) 物件的快捷方式。 |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | 建立 null 指標。 |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | 建立指向給定物件的弱指標。 |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | 建立指向與 ptr 相同指標的弱指標。 |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | 建立指向與 x 相同指標的弱指標。 |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | 以拷貝方式建構弱指標。 |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | 以拷貝方式建構弱指標。 |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | 以移動方式建構弱指標。 |
|  [~SmartPtr](../smartptr/~smartptr/)() | 銷毀 [SmartPtr](../smartptr/) 物件。如有需要，減少指向物件的引用計數並刪除物件。 |
## 型別別名

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | 對應 [SmartPtr](../smartptr/) 類別的別名。 |
| [WeakPtr_](./weakptr_/) | 自身型別的別名。 |
| [Pointee_](./pointee_/) | 指向的型別。 |

## 參見

* 類別 [SmartPtr](../smartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)