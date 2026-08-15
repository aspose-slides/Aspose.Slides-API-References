---
title: HashSetPtr
second_title: Aspose.Slides for C++ API 參考
description: 指向用於保留 HashSet 參考的指標。此類型是一個用來管理其他物件刪除的指標。應於堆疊上分配，並以值或 const 參考方式傳遞給函式。
type: docs
weight: 235
url: /zh-hant/system.collections.generic/hashsetptr/
---
## HashSetPtr 類別

Pointer to keep [HashSet](../hashset/) references. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## Methods

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | 取得底層集合的 [begin()](../../system/smartptr/begin/) 方法的存取子。僅在 SmartPtr_ 為具備 [begin()](../../system/smartptr/begin/) 方法的特化類型時才會編譯。 |
| auto [begin](../../system/smartptr/begin/)() const | 取得底層集合的 [begin()](../../system/smartptr/begin/) 方法的存取子。僅在 SmartPtr_ 為具備 [begin()](../../system/smartptr/begin/) 方法的特化類型時才會編譯。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 將指標轉型為其自身類型。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 static_cast 將指標轉型為基底類型。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 dynamic_cast 將指標轉型為衍生類型。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 dynamic_cast 将指標轉型為衍生類型。 |
| auto [cbegin](../../system/smartptr/cbegin/)() const | 取得底層集合的 [cbegin()](../../system/smartptr/cbegin/) 方法的存取子。僅在 SmartPtr_ 為具備 [cbegin()](../../system/smartptr/cbegin/) 方法的特化類型時才會編譯。 |
| auto [cend](../../system/smartptr/cend/)() const | 取得底層集合的 [cend()](../../system/smartptr/cend/) 方法的存取子。僅在 SmartPtr_ 為具備 [cend()](../../system/smartptr/cend/) 方法的特化類型時才會編譯。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | 使用 const_cast 將指標轉型為不同類型的指向物件。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | 使用 dynamic_cast 將指標轉型為不同類型的指向物件。 |
| auto [end](../../system/smartptr/end/)() | 取得底層集合的 [end()](../../system/smartptr/end/) 方法的存取子。僅在 SmartPtr_ 為具備 [end()](../../system/smartptr/end/) 方法的特化類型時才會編譯。 |
| auto [end](../../system/smartptr/end/)() const | 取得底層集合的 [end()](../../system/smartptr/end/) 方法的存取子。僅在 SmartPtr_ 為具備 [end()](../../system/smartptr/end/) 方法的特化類型時才會編譯。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | 取得指向的物件。 |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | 取得指標模式。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | 取得指向的物件，但會斷言指標處於共享模式。 |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | 取得指向物件的共享指標數量（包含目前此指標），並斷言目前指標處於共享模式。 |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | 在指向的物件上呼叫 [GetHashCode()](../../system/smartptr/gethashcode/)。 |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | 取得目前參照的物件（若有），若無則拋出例外。 |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | 取得指向的物件（若有），若無則返回 nullptr。與 [get()](../../system/smartptr/get/) 相同。 |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | 取得參照的物件。 |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | 取得指向的物件（若有），若無則返回 nullptr。與 [get()](../../system/smartptr/get/) 相同。 |
|  [HashSetPtr](./hashsetptr/)() | 空指標建構子。 |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | 複製建構子。 |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | 檢查指向的物件是否為特定類型或其子類型。遵循 C# 'is' 語意。 |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | 檢查指標是否指向非擁有的其他物件（由別名建構子建立）。 |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | 檢查指標是否處於共享模式。 |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | 檢查指標是否處於弱引用模式。 |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | 檢查指標是否不為 null。 |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | 檢查指標是否為 null。 |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | 取得指向物件的參考。若指標為 null 則會斷言。 |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | 允許存取參照物件的成員。 |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | 為 [SmartPtr](../../system/smartptr/) 類別提供小於比較語意。 |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | 為 [SmartPtr](../../system/smartptr/) 類別提供小於比較語意。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | 將 [SmartPtr](../../system/smartptr/) 物件以移動賦值。x 變為無法使用。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | 以複製賦值方式設定 [SmartPtr](../../system/smartptr/) 物件。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | 以複製賦值方式設定 [SmartPtr](../../system/smartptr/) 物件。執行必要的型別轉換。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | 為 [SmartPtr](../../system/smartptr/) 物件指派原始指標。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | 將指標值設定為 nullptr。 |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | 檢查指標是否指向 nullptr。 |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | 移除指標的別名（由別名建構子建立），確保其管理（若為共享）或追蹤（若為弱）同一指向的物件。 |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | 設定指向的物件。 |
| void [reset](../../system/smartptr/reset/)() | 使指標指向 nullptr。 |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | 設定指標模式。可能會變更參照物件的參考計數。 |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 在指向的物件（若有）上呼叫 SetTemplateWeakPtr() 方法。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | 建立所需模式的 [SmartPtr](../../system/smartptr/) 物件。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | 建立所需模式的空指標 [SmartPtr](../../system/smartptr/) 物件。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 建立指向指定物件的 [SmartPtr](../../system/smartptr/)，或將原始指標轉換為 [SmartPtr](../../system/smartptr/)。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | 複製建構 [SmartPtr](../../system/smartptr/) 物件。之後兩個指標皆指向相同的物件。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 複製建構 [SmartPtr](../../system/smartptr/) 物件。之後兩個指標皆指向相同的物件。若允許則執行型別轉換。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | 移動建構 [SmartPtr](../../system/smartptr/) 物件。實質上交換兩個指標（若兩者模式相同），呼叫後 x 可能無法使用。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 透過建立不同類型的新陣列來轉換參照陣列的類型。若 C# 中有不支援於 C++ 的陣列型別轉換時，此功能很有用。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | 初始化空陣列。用於翻譯某些 C# 程式碼結構。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 建構一個 [SmartPtr](../../system/smartptr/)，其擁有權資訊與 ptr 的初始值共享，但持有一個不相關且未受管理的指標 p。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | 使用 static_cast 將指標轉型為不同類型的指向物件。 |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | 將任意指標類型轉換為指向 [Object](../../system/object/) 的指標。不需要 Pointee_ 類型為完整類型。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | 取得 Pointee_ 類型之 [System::TypeInfo](../../system/typeinfo/) 物件的快捷方式。 |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | 銷毀 [SmartPtr](../../system/smartptr/) 物件。如有需要，會減少指向物件的參考計數並刪除該物件。 |

## 參見

* 類別 [SmartPtr](../../system/smartptr/)
* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)