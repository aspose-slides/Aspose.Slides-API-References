---
title: SmartPtr
second_title: Aspose.Slides for C++ API 參考文件
description: "指標類別，用於封裝在堆上分配的類型。用它來管理繼承 Object 的類別的記憶體。此指標類別遵循侵入式指標語意。參考計數儲存在 Object 本身或與 Object 實例緊密相連的計數結構中。無論如何，所有 SmartPtr 實例都形成單一所有權群組，與 std::shared_ptr 類別的行為不同。將原始指標轉換為 SmartPtr 是安全的，前提是有其他 SmartPtr 實例持有對同一物件的共享參考。SmartPtr 類別的實例可以處於兩種狀態：共享指標與弱指標。為了保持物件存活，應確保共享參考計數為正。弱指標與共享指標皆可用於存取指向的物件（呼叫方法、讀寫欄位等），但弱指標不參與共享指標的參考計數。當最後一個 'shared' SmartPtr 指標被銷毀時，Object 會被刪除。因此，請確保在沒有其他共享 SmartPtr 指標指向該物件時（例如物件建構或銷毀期間）不會發生此情況。使用 System::Object::ThisProtector 監護物件（於 C++ 程式碼）或 CppCTORSelfReference、CppSelfReference 屬性（於 C# 程式碼）來解決此問題。同樣，請使用 System::WeakPtr 指標類別或 System::SmartPtrMode::Weak 指標模式（於 C++ 程式碼）或 CppWeakPtr 屬性（於 C# 程式碼）來斷開循環參考。如果兩個或以上的物件使用 'shared' 指標互相參考，它們將永遠不會被刪除。如果需要在執行時切換指標類型（弱或共享），請使用 System::SmartPtr<T>::set_Mode() 方法或 System::DynamicWeakPtr 類別。SmartPtr 類別不包含任何虛擬方法。除非您自行建立記憶體管理策略，否則不應繼承它。此類型是一個用於管理其他物件刪除的指標。它應分配在堆疊上，並以值或 const 參考傳遞給函式。"
type: docs
weight: 1236
url: /zh-hant/system/smartptr/
---
## SmartPtr 類別


指向類別，用於封裝在堆疊上配置的型別。使用它來管理繼承 [Object](../object/) 的類別的記憶體。此指標類型遵循侵入式指標語意。參考計數器要麼儲存在 [Object](../object/) 本身，要麼儲存在與 [Object](../object/) 實例緊密相關的計數結構中。無論如何，所有 [SmartPtr](./) 實例都形成單一擁有權群組，無論它們如何被建立，這與 std::shared_ptr 類別的行為不同。將原始指標轉換為 [SmartPtr](./) 是安全的，前提是還有其他 [SmartPtr](./) 實例持有對同一物件的共享引用。[SmartPtr](./) 類別實例可以處於兩種狀態之一：shared pointer（共享指標）和 weak pointer（弱指標）。要保持物件存活，應確保指向它的共享引用計數為正。弱指標和共享指標都可用於存取指向的物件（呼叫方法、讀寫欄位等），但弱指標不參與共享指標的參考計數。當最後一個指向它的 'shared' [SmartPtr](./) 指標被銷毀時，[Object](../object/) 會被刪除。因此，請確保在沒有其他共享 [SmartPtr](./) 指標指向物件時（例如在物件建構或銷毀期間）不會發生此情況。使用 System::Object::ThisProtector 守護物件（於 C++ 程式碼中）或 CppCTORSelfReference 或 CppSelfReference 屬性（於 C# 程式碼中）來解決此問題。類似地，請使用 [System::WeakPtr](../weakptr/) 指標類別或 [System::SmartPtrMode::Weak](../smartptrmode/) 指標模式（於 C++ 程式碼中）或 CppWeakPtr 屬性（於 C# 程式碼中）來斷開循環引用。如果兩個或以上的物件使用 'shared' 指標相互引用，它們將永遠不會被刪除。如果在執行期間需要切換指標類型（弱或共享），請使用 [System::SmartPtr<T>::set_Mode()](./set_mode/) 方法或 [System::DynamicWeakPtr](../dynamicweakptr/) 類別。[SmartPtr](./) 類別不包含任何虛擬方法。只有在您自行建立記憶體管理策略時才應繼承它。此類型是一個指標，用於管理其他物件的刪除。它應該在堆疊上分配，並以值或 const 參照傳遞給函式。

```cpp
template<class T>class SmartPtr
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Type of the pointed object. Must be either [System::Object](../object/) or subclass of it. |
## 方法

| 方法 | 說明 |
| --- | --- |
| auto [begin](./begin/)() | Accessor for [begin()](./begin/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [begin()](./begin/) method. |
| auto [begin](./begin/)() const | Accessor for [begin()](./begin/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [begin()](./begin/) method. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Casts pointer to its type itself. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Casts pointer to base type using static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Casts pointer to derived type dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Casts pointer to derived type dynamic_cast. |
| auto [cbegin](./cbegin/)() const | Accessor for [cbegin()](./cbegin/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [cbegin()](./cbegin/) method. |
| auto [cend](./cend/)() const | Accessor for [cend()](./cend/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [cend()](./cend/) method. |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Casts pointer to different type using const_cast on pointed object. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Casts pointer to different type using dynamic_cast on pointed object. |
| auto [end](./end/)() | Accessor for [end()](./end/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [end()](./end/) method. |
| auto [end](./end/)() const | Accessor for [end()](./end/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [end()](./end/) method. |
| [Pointee_](./pointee_/) * [get](./get/)() const | Gets pointed object. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Gets pointer mode. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Gets pointed object, but asserts that pointer is in shared mode. |
| int [get_shared_count](./get_shared_count/)() const | Gets number of shared pointers existing to referenced object, including current one. Asserts current pointer being in shared mode. |
| int [GetHashCode](./gethashcode/)() const | Calls [GetHashCode()](./gethashcode/) on pointed object. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Gets currently referenced object (if any) or throws. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Gets pointed object (if any) or nullptr. Same as [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Gets referenced object. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Gets pointed object (if any) or nullptr. Same as [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Checks if pointed object is of specific type or its child type. Follows C# 'is' semantics. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Checks if pointer is pointed to another object than owned (created by an aliasing constructor). |
| **bool** [IsShared](./isshared/)() const | Checks if pointer is in shared mode. |
| **bool** [IsWeak](./isweak/)() const | Checks if pointer is in weak mode. |
| explicit  [operator bool](./operator_bool/)() const | Checks if pointer is not null. |
| **bool** [operator!](./operator_not/)() const | Checks if pointer is null. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Gets reference to pointed object. Asserts that pointer is not null. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Allows to access members of referenced object. |
| **bool** [operator<](./operator_less/)(Y *) const | Provides less-compare semantics for [SmartPtr](./) class. |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Provides less-compare semantics for [SmartPtr](./) class. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Move-assigns [SmartPtr](./) object. x becomes unusable. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Copy-assigns [SmartPtr](./) object. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Copy-assigns [SmartPtr](./) object. Does required type conversions. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Assigns raw pointer to [SmartPtr](./) object. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Sets pointer value to nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Checks if pointer points to nullptr. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Removes aliasing (created by an aliasing constructor) from pointer, makes sure it manages (if shared) or tracks (if weak) the same object it points to. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Sets pointed object. |
| void [reset](./reset/)() | Makes pointer pointing to nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Sets pointer mode. May alter referenced object's reference counts. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Calls SetTemplateWeakPtr() method on pointed object (if any). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Creates [SmartPtr](./) object of required mode. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Creates null-pointer [SmartPtr](./) object of required mode. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Creates [SmartPtr](./) pointing to specified object, or converts raw pointer to [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Copy constructs [SmartPtr](./) object. Both pointers point to the same object afterwards. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Copy constructs [SmartPtr](./) object. Both pointers point to the same object afterwards. Performs type conversion if allowed. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Move constructs [SmartPtr](./) object. Effectively, swaps two pointers, if they are both of same mode. x may be unusable after call. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Converts type of referenced array by creating a new array of different type. Useful if in C# there is an array type cast which is unsupported in C++. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Initializes empty array. Used to translate some C# code constructs. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Constructs a [SmartPtr](./) which shares ownership information with the initial value of ptr, but holds an unrelated and unmanaged pointer p. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Casts pointer to different type using static_cast on pointed object. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Converts any pointer type to pointer to [Object](../object/). Doesn't require Pointee_ type to be complete. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Shortcut to get [System::TypeInfo](../typeinfo/) object for the Pointee_ type. |
|  [~SmartPtr](./~smartptr/)() | Destroys [SmartPtr](./) object. If required, decreases pointed object's reference counter and deletes object. |
## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Pointee_](./pointee_/) | Pointed type. |
| [SmartPtr_](./smartptr_/) | Specialized smart pointer type. |
| [ArrayType](./arraytype/) | Same as Pointee_, if it is a specialization of [System::Array](../array/), and void otherwise. |
| [ValueType](./valuetype/) | Storage type of pointed array. Only meaningful if T is a specialization of [System::Array](../array/). |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)