---
title: DictionaryPtr
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: Dictionary 指標類別，具備運算子重載。此類型是用來管理其他物件刪除的指標。它應該在堆疊上分配，並以值或 const 參考傳遞給函式。
type: docs
weight: 170
url: /zh-hant/system.collections.generic/dictionaryptr/
---
## DictionaryPtr 類別

[Dictionary](../dictionary/) 指標類別，具備運算子重載。此類型是用來管理其他物件刪除的指標。它應該在堆疊上分配，並以值或常量參考傳遞給函式。

```cpp
template<typename T,typename V>class DictionaryPtr : public System::SmartPtr<Dictionary<T, V>>
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 鍵類型。 |
| V | 值類型。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | 取得底層集合的 [begin()](../../system/smartptr/begin/) 方法。僅在 SmartPtr_ 為具備 [begin()](../../system/smartptr/begin/) 方法的特化類型時編譯。 |
| auto [begin](../../system/smartptr/begin/)() const | 取得底層集合的 [begin()](../../system/smartptr/begin/) 方法。僅在 SmartPtr_ 為具備 [begin()](../../system/smartptr/begin/) 方法的特化類型時編譯。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 將指標轉型為其本身類型。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 static_cast 將指標轉型為基底類型。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 dynamic_cast 將指標轉型為衍生類型。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 dynamic_cast 將指標轉型為衍生類型。 |
| auto [cbegin](../../system/smartptr/cbegin/)() const | 取得底層集合的 [cbegin()](../../system/smartptr/cbegin/) 方法。僅在 SmartPtr_ 為具備 [cbegin()](../../system/smartptr/cbegin/) 方法的特化類型時編譯。 |
| auto [cend](../../system/smartptr/cend/)() const | 取得底層集合的 [cend()](../../system/smartptr/cend/) 方法。僅在 SmartPtr_ 為具備 [cend()](../../system/smartptr/cend/) 方法的特化類型時編譯。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | 使用 const_cast 將指標所指物件轉型為不同類型。 |
|  [DictionaryPtr](./dictionaryptr/)() | 初始化為空指標。 |
|  [DictionaryPtr](./dictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[Dictionary](../dictionary/)\<T, V\>\>\&) | 轉換指標類型。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | 使用 dynamic_cast 將指標所指物件轉型為不同類型。 |
| auto [end](../../system/smartptr/end/)() | 取得底層集合的 [end()](../../system/smartptr/end/) 方法。僅在 SmartPtr_ 為具備 [end()](../../system/smartptr/end/) 方法的特化類型時編譯。 |
| auto [end](../../system/smartptr/end/)() const | 取得底層集合的 [end()](../../system/smartptr/end/) 方法。僅在 SmartPtr_ 為具備 [end()](../../system/smartptr/end/) 方法的特化類型時編譯。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | 取得指向的物件。 |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | 取得指標模式。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | 取得指向的物件，但會斷言指標處於共享模式。 |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | 取得指向物件的共享指標數量（含目前指標），並斷言目前指標為共享模式。 |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | 在指向物件上呼叫 [GetHashCode()](../../system/smartptr/gethashcode/)。 |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | 取得目前參考的物件（若存在），否則拋出例外。 |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | 取得指向的物件（若存在），否則返回 nullptr。等同於 [get()](../../system/smartptr/get/)。 |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | 取得參考的物件。 |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | 取得指向的物件（若存在），否則返回 nullptr。等同於 [get()](../../system/smartptr/get/)。 |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | 檢查指向的物件是否為特定類型或其子類型。遵循 C# 的 `is` 語意。 |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | 檢查指標是否指向除所有者之外的其他物件（由別名建構子建立）。 |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | 檢查指標是否處於共享模式。 |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | 檢查指標是否處於弱引用模式。 |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | 檢查指標是否為非空。 |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | 檢查指標是否為空。 |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | 取得指向物件的參考。斷言指標非空。 |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | 允許存取參考物件的成員。 |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | 為 [SmartPtr](../../system/smartptr/) 類別提供小於比較語意。 |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | 為 [SmartPtr](../../system/smartptr/) 類別提供小於比較語意。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | 將 [SmartPtr](../../system/smartptr/) 物件以移動賦值。x 變為不可用。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | 將 [SmartPtr](../../system/smartptr/) 物件以拷貝賦值。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | 將 [SmartPtr](../../system/smartptr/) 物件以拷貝賦值，並執行必要的型別轉換。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | 將原始指標指派給 [SmartPtr](../../system/smartptr/) 物件。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | 將指標值設定為 nullptr。 |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | 檢查指標是否指向 nullptr。 |
| V\& [operator[]](./operator[]/)(const X\&) const | 用於鍵類型轉換的存取運算子。 |
| V\& [operator[]](./operator[]/)(const T\&) const | 存取運算子。 |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | 移除別名（由別名建構子建立），確保指標在共享或弱引用模式下仍管理或追蹤相同物件。 |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | 設定指向的物件。 |
| void [reset](../../system/smartptr/reset/)() | 使指標指向 nullptr。 |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | 設定指標模式。可能會改變參考物件的引用計數。 |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 在指向的物件（若存在）上呼叫 SetTemplateWeakPtr() 方法。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | 建立所需模式的 [SmartPtr](../../system/smartptr/) 物件。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | 建立所需模式的空指標 [SmartPtr](../../system/smartptr/) 物件。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 建立指向指定物件的 [SmartPtr](../../system/smartptr/)，或將原始指標轉換為 [SmartPtr](../../system/smartptr/)。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | 複製建構 [SmartPtr](../../system/smartptr/) 物件。兩個指標之後指向相同物件。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 複製建構 [SmartPtr](../../system/smartptr/) 物件。兩個指標之後指向相同物件。若允許，會執行型別轉換。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | 移動建構 [SmartPtr](../../system/smartptr/) 物件。實質上交換兩個指標（若模式相同）。呼叫後 x 可能不可用。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 透過建立不同類型的新陣列，將參考陣列的型別轉換。此功能在 C# 中的陣列型別轉換在 C++ 不支援時使用。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | 初始化為空陣列。用於翻譯某些 C# 程式碼結構。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 建構一個 [SmartPtr](../../system/smartptr/)，與初始 ptr 的所有權資訊共享，但持有不相關且未管理的指標 p。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | 使用 static_cast 將指標所指物件轉型為不同類型。 |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | 將任意指標類型轉換為指向 [Object](../../system/object/) 的指標。無需 Pointee_ 類型為完整。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | 取得 Pointee_ 類型的 [System::TypeInfo](../../system/typeinfo/) 物件的快捷方式。 |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | 銷毀 [SmartPtr](../../system/smartptr/) 物件。若需要，會減少指向物件的引用計數並刪除物件。 |

## 另見

* 類別 [SmartPtr](../../system/smartptr/)
* 命名空間 [System::Collections::Generic](../)
* 函式庫 [Aspose.Slides](../../)