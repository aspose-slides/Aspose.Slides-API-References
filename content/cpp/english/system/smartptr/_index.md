---
title: SmartPtr
second_title: Aspose.Slides for C++ API Reference
description: "Pointer class to wrap types being allocated on heap. Use it to manage memory for classes inheriting Object. This pointer type follows intrusive pointer semantics. Reference counter is stored either in Object itself or in counter structure which is tied to Object instance tightly. In any case, all SmartPtr instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to SmartPtr is safe given there are other SmartPtr instances holding shared references to the same object. SmartPtr class instance can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. Object is being deleted when the last 'shared' SmartPtr pointer to it is being destroyed. So, make sure that this doesn't happen when no other shared SmartPtr pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using System::WeakPtr pointer class or System::SmartPtrMode::Weak pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using 'shared' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use System::SmartPtr<T>::set_Mode() method or System::DynamicWeakPtr class. SmartPtr class doesn't contain any virtual methods. You should only inherit it if you're creating a memory management strategy of your own. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference."
type: docs
weight: 1119
url: /system/smartptr/
---
## SmartPtr class


Pointer class to wrap types being allocated on heap. Use it to manage memory for classes inheriting [Object](../object/). This pointer type follows intrusive pointer semantics. Reference counter is stored either in [Object](../object/) itself or in counter structure which is tied to [Object](../object/) instance tightly. In any case, all [SmartPtr](./) instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to [SmartPtr](./) is safe given there are other [SmartPtr](./) instances holding shared references to the same object. [SmartPtr](./) class instance can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. [Object](../object/) is being deleted when the last 'shared' [SmartPtr](./) pointer to it is being destroyed. So, make sure that this doesn't happen when no other shared [SmartPtr](./) pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using [System::WeakPtr](../weakptr/) pointer class or [System::SmartPtrMode::Weak](../smartptrmode/) pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using 'shared' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use [System::SmartPtr<T>::set_Mode()](./set_mode/) method or [System::DynamicWeakPtr](../dynamicweakptr/) class. [SmartPtr](./) class doesn't contain any virtual methods. You should only inherit it if you're creating a memory management strategy of your own. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class SmartPtr
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of the pointed object. Must be either [System::Object](../object/) or subclass of it. |
## Methods

| Method | Description |
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
## Typedefs

| Typedef | Description |
| --- | --- |
| [Pointee_](./pointee_/) | Pointed type. |
| [SmartPtr_](./smartptr_/) | Specialized smart pointer type. |
| [ArrayType](./arraytype/) | Same as Pointee_, if it is a specialization of [System::Array](../array/), and void otherwise. |
| [ValueType](./valuetype/) | Storage type of pointed array. Only meaningful if T is a specialization of [System::Array](../array/). |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)