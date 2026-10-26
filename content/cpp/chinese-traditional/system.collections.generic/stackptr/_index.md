---
title: StackPtr
second_title: Aspose.Slides for C++ API 參考
description: 堆疊指標。此類型是用於管理其他物件刪除的指標。它應該在堆疊上配置，並以值或 const 參考方式傳遞給函式。
type: docs
weight: 612
url: /zh-hant/system.collections.generic/stackptr/
---
## StackPtr 類別


[Stack](../stack/) 指標。此類型是用於管理其他物件刪除的指標。它應該在堆疊上分配，並以值或 const 參考方式傳遞給函式。

```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Element type. |
## Methods

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | 存取底層集合的 [begin()](../../system/smartptr/begin/) 方法。僅在 SmartPtr_ 為具備 [begin()](../../system/smartptr/begin/) 方法的特化類型時編譯通過。 |
| auto [begin](../../system/smartptr/begin/)() const | 存取底層集合的 [begin()](../../system/smartptr/begin/) 方法。僅在 SmartPtr_ 為具備 [begin()](../../system/smartptr/begin/) 方法的特化類型時編譯通過。 |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 將指標轉型為其自身類型。 |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 static_cast 將指標轉型為基底類型。 |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 dynamic_cast 將指標轉型為衍生類型。 |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | 使用 dynamic_cast 將指標轉型為衍生類型。 |
| auto [cbegin](../../system/smartptr/cbegin/)() const | 存取底層集合的 [cbegin()](../../system/smartptr/cbegin/) 方法。僅在 SmartPtr_ 為具備 [cbegin()](../../system/smartptr/cbegin/) 方法的特化類型時編譯通過。 |
| auto [cend](../../system/smartptr/cend/)() const | 存取底層集合的 [cend()](../../system/smartptr/cend/) 方法。僅在 SmartPtr_ 為具備 [cend()](../../system/smartptr/cend/) 方法的特化類型時編譯通過。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | 使用 const_cast 將指向的物件轉型為不同類型的指標。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | 使用 dynamic_cast 將指向的物件轉型為不同類型的指標。 |
| auto [end](../../system/smartptr/end/)() | 存取底層集合的 [end()](../../system/smartptr/end/) 方法。僅在 SmartPtr_ 為具備 [end()](../../system/smartptr/end/) 方法的特化類型時編譯通過。 |
| auto [end](../../system/smartptr/end/)() const | 存取底層集合的 [end()](../../system/smartptr/end/) 方法。僅在 SmartPtr_ 為具備 [end()](../../system/smartptr/end/) 方法的特化類型時編譯通過。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | 取得指向的物件。 |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | 取得指標模式。 |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | 取得指向的物件，但會斷言指標處於共享模式。 |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | 取得參考物件上現有的共享指標數量（含目前這個）。會斷言目前指標處於共享模式。 |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | 在指向的物件上呼叫 [GetHashCode()](../../system/smartptr/gethashcode/)。 |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | 取得目前參考的物件（若存在），否則拋出例外。 |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | 取得指向的物件（若存在），否則返回 nullptr。與 [get()](../../system/smartptr/get/) 相同。 |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | 取得參考的物件。 |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | 取得指向的物件（若存在），否則返回 nullptr。與 [get()](../../system/smartptr/get/) 相同。 |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | 檢查指向的物件是否為特定類型或其子類型。遵循 C# 的 'is' 語意。 |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | 檢查指標是否指向除擁有物件之外的其他物件（由別名建構函式建立）。 |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | 檢查指標是否處於共享模式。 |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | 檢查指標是否處於弱引用模式。 |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | 檢查指標是否不為 null。 |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | 檢查指標是否為 null。 |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | 取得指向物件的參照。斷言指標不為 null。 |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | 允許存取參考物件的成員。 |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | 為 [SmartPtr](../../system/smartptr/) 類別提供小於比較語意。 |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | 為 [SmartPtr](../../system/smartptr/) 類別提供小於比較語意。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | 將 [SmartPtr](../../system/smartptr/) 物件以移動指派。x 變得不可使用。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | 將 [SmartPtr](../../system/smartptr/) 物件以拷貝指派。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | 將 [SmartPtr](../../system/smartptr/) 物件以拷貝指派。執行必要的型別轉換。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | 將原始指標指派給 [SmartPtr](../../system/smartptr/) 物件。 |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | 將指標值設定為 nullptr。 |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | 檢查指標是否指向 nullptr。 |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | 移除指標的別名（由別名建構函式建立），確保它在共享模式時管理或在弱引用模式時追蹤相同的物件。 |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | 設定指向的物件。 |
| void [reset](../../system/smartptr/reset/)() | 使指標指向 nullptr。 |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | 設定指標模式。可能會改變參考物件的參考計數。 |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | 在指向的物件（若存在）上呼叫 SetTemplateWeakPtr() 方法。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | 建立所需模式的 [SmartPtr](../../system/smartptr/) 物件。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | 建立所需模式的空指標 [SmartPtr](../../system/smartptr/) 物件。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 建立指向指定物件的 [SmartPtr](../../system/smartptr/)，或將原始指標轉換為 [SmartPtr](../../system/smartptr/)。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | 以拷貝方式建構 [SmartPtr](../../system/smartptr/) 物件。兩個指標之後指向相同的物件。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 以拷貝方式建構 [SmartPtr](../../system/smartptr/) 物件。兩個指標之後指向相同的物件。若允許則執行型別轉換。 |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | 以移動方式建構 [SmartPtr](../../system/smartptr/) 物件。若兩個指標模式相同，實際上會交換兩個指標。呼叫後 x 可能不可使用。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | 透過建立不同類型的新陣列，轉換參考陣列的類型。若 C# 中有陣列型別轉換而 C++ 不支援時此功能很有用。 |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | 初始化空陣列。用於轉譯某些 C# 程式碼結構。 |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | 建構一個與 ptr 初始值共享所有權資訊的 [SmartPtr](../../system/smartptr/)，但持有一個不相關且未受管理的指標 p。 |
|  [StackPtr](./stackptr/)() | 建構空指標。 |
|  [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | 建構指向特定堆疊的指標。 |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | 使用 static_cast 將指向的物件轉型為不同類型的指標。 |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | 將任意指標類型轉換為指向 [Object](../../system/object/) 的指標。不需要 Pointee_ 類型完整。 |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | 取得 Pointee_ 類型之 [System::TypeInfo](../../system/typeinfo/) 物件的快捷方式。 |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | 銷毀 [SmartPtr](../../system/smartptr/) 物件。如有需要，減少指向物件的參考計數並刪除物件。 |

## 另請參閱

* 類別 [SmartPtr](../../system/smartptr/)
* 命名空間 [System::Collections::Generic](../)
* 程式庫 [Aspose.Slides](../../)