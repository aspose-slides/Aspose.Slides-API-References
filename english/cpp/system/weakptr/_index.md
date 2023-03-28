---
title: WeakPtr
second_title: Aspose.Slides for C++ API Reference
description: "Subclass of System::SmartPtr which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as set_Mode() is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference."
type: docs
weight: 1353
url: /cpp/system/weakptr/
---
## WeakPtr class


Subclass of [System::SmartPtr](../smartptr/) which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as [set_Mode()](../smartptr/set_mode/) is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Pointee type. |
## Methods

| Method | Description |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Accessor for [begin()](../smartptr/begin/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [begin()](../smartptr/begin/) method. |
| auto [begin](../smartptr/begin/)() const | Accessor for [begin()](../smartptr/begin/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [begin()](../smartptr/begin/) method. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Casts pointer to its type itself. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Casts pointer to base type using static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Casts pointer to derived type dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Casts pointer to derived type dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Accessor for [cbegin()](../smartptr/cbegin/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [cbegin()](../smartptr/cbegin/) method. |
| auto [cend](../smartptr/cend/)() const | Accessor for [cend()](../smartptr/cend/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [cend()](../smartptr/cend/) method. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Casts pointer to different type using const_cast on pointed object. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Casts pointer to different type using dynamic_cast on pointed object. |
| auto [end](../smartptr/end/)() | Accessor for [end()](../smartptr/end/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [end()](../smartptr/end/) method. |
| auto [end](../smartptr/end/)() const | Accessor for [end()](../smartptr/end/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [end()](../smartptr/end/) method. |
| **bool** [expired](./expired/)() const | Checks if referenced object was already deleted. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Gets pointed object. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Gets pointer mode. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Gets pointed object, but asserts that pointer is in shared mode. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Gets number of shared pointers existing to referenced object, including current one. Asserts current pointer being in shared mode. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Gets referenced object. Asserts that pointer is in weak mode. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Calls [GetHashCode()](../smartptr/gethashcode/) on pointed object. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Gets currently referenced object (if any) or throws. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Gets pointed object (if any) or nullptr. Same as [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Gets referenced object. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Gets pointed object (if any) or nullptr. Same as [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Checks if pointed object is of specific type or its child type. Follows C# 'is' semantics. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Checks if pointer is pointed to another object than owned (created by an aliasing constructor). |
| **bool** [IsShared](../smartptr/isshared/)() const | Checks if pointer is in shared mode. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Checks if pointer is in weak mode. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Checks if pointer is not null. |
| **bool** [operator!](../smartptr/operator_not/)() const | Checks if pointer is null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Gets reference to pointed object. Asserts that pointer is not null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Allows to access members of referenced object. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Provides less-compare semantics for [SmartPtr](../smartptr/) class. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Provides less-compare semantics for [SmartPtr](../smartptr/) class. |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Assigns value to weak pointer. Calls into specific assignment operator of SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Move-assigns [SmartPtr](../smartptr/) object. x becomes unusable. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Copy-assigns [SmartPtr](../smartptr/) object. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Copy-assigns [SmartPtr](../smartptr/) object. Does required type conversions. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Assigns raw pointer to [SmartPtr](../smartptr/) object. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Sets pointer value to nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Checks if weak pointer is null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Removes aliasing (created by an aliasing constructor) from pointer, makes sure it manages (if shared) or tracks (if weak) the same object it points to. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Sets pointed object. |
| void [reset](../smartptr/reset/)() | Makes pointer pointing to nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Sets pointer mode. May alter referenced object's reference counts. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Calls SetTemplateWeakPtr() method on pointed object (if any). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Creates [SmartPtr](../smartptr/) object of required mode. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Creates null-pointer [SmartPtr](../smartptr/) object of required mode. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Creates [SmartPtr](../smartptr/) pointing to specified object, or converts raw pointer to [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Copy constructs [SmartPtr](../smartptr/) object. Both pointers point to the same object afterwards. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Copy constructs [SmartPtr](../smartptr/) object. Both pointers point to the same object afterwards. Performs type conversion if allowed. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Move constructs [SmartPtr](../smartptr/) object. Effectively, swaps two pointers, if they are both of same mode. x may be unusable after call. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Converts type of referenced array by creating a new array of different type. Useful if in C# there is an array type cast which is unsupported in C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Initializes empty array. Used to translate some C# code constructs. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Constructs a [SmartPtr](../smartptr/) which shares ownership information with the initial value of ptr, but holds an unrelated and unmanaged pointer p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Casts pointer to different type using static_cast on pointed object. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Converts any pointer type to pointer to [Object](../object/). Doesn't require Pointee_ type to be complete. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Shortcut to get [System::TypeInfo](../typeinfo/) object for the Pointee_ type. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Creates null pointer. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Creates weak pointer to given object. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Creates weak pointer referencing same pointer ptr points to. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Creates weak pointer referencing same pointer x points to. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Copy-constructs weak pointer. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Copy-constructs weak pointer. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Move-constructs weak pointer. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Destroys [SmartPtr](../smartptr/) object. If required, decreases pointed object's reference counter and deletes object. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Alias for corresponding [SmartPtr](../smartptr/) class. |
| [WeakPtr_](./weakptr_/) | Alias for self type. |
| [Pointee_](./pointee_/) | Pointed type. |

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
