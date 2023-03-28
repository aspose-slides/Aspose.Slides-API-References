---
title: GroupCollectionPtr
second_title: Aspose.Slides for C++ API Reference
description: Group collection pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.
type: docs
weight: 53
url: /cpp/system.text.regularexpressions/groupcollectionptr/
---
## GroupCollectionPtr class


[Group](../group/) collection pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class GroupCollectionPtr : public System::SmartPtr<GroupCollection>
```

## Methods

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accessor for [begin()](../../system/smartptr/begin/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [begin()](../../system/smartptr/begin/) method. |
| auto [begin](../../system/smartptr/begin/)() const | Accessor for [begin()](../../system/smartptr/begin/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [begin()](../../system/smartptr/begin/) method. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Casts pointer to its type itself. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Casts pointer to base type using static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Casts pointer to derived type dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Casts pointer to derived type dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accessor for [cbegin()](../../system/smartptr/cbegin/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [cbegin()](../../system/smartptr/cbegin/) method. |
| auto [cend](../../system/smartptr/cend/)() const | Accessor for [cend()](../../system/smartptr/cend/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [cend()](../../system/smartptr/cend/) method. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Casts pointer to different type using const_cast on pointed object. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Casts pointer to different type using dynamic_cast on pointed object. |
| auto [end](../../system/smartptr/end/)() | Accessor for [end()](../../system/smartptr/end/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [end()](../../system/smartptr/end/) method. |
| auto [end](../../system/smartptr/end/)() const | Accessor for [end()](../../system/smartptr/end/) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [end()](../../system/smartptr/end/) method. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Gets pointed object. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Gets pointer mode. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Gets pointed object, but asserts that pointer is in shared mode. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Gets number of shared pointers existing to referenced object, including current one. Asserts current pointer being in shared mode. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Calls [GetHashCode()](../../system/smartptr/gethashcode/) on pointed object. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Gets currently referenced object (if any) or throws. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Gets pointed object (if any) or nullptr. Same as [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Gets referenced object. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Gets pointed object (if any) or nullptr. Same as [get()](../../system/smartptr/get/). |
|  [GroupCollectionPtr](./groupcollectionptr/)() | Null pointer constructor. |
|  [GroupCollectionPtr](./groupcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[GroupCollection](../groupcollection/)\>\&) | Type convesion constructor. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Checks if pointed object is of specific type or its child type. Follows C# 'is' semantics. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Checks if pointer is pointed to another object than owned (created by an aliasing constructor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Checks if pointer is in shared mode. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Checks if pointer is in weak mode. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Checks if pointer is not null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Checks if pointer is null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Gets reference to pointed object. Asserts that pointer is not null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Allows to access members of referenced object. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Provides less-compare semantics for [SmartPtr](../../system/smartptr/) class. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Provides less-compare semantics for [SmartPtr](../../system/smartptr/) class. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Move-assigns [SmartPtr](../../system/smartptr/) object. x becomes unusable. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Copy-assigns [SmartPtr](../../system/smartptr/) object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Copy-assigns [SmartPtr](../../system/smartptr/) object. Does required type conversions. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Assigns raw pointer to [SmartPtr](../../system/smartptr/) object. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Sets pointer value to nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Checks if pointer points to nullptr. |
| [GroupPtr](../groupptr/) [operator[]](./operator[]/)(size_t) const | [Group](../group/) accessor. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Removes aliasing (created by an aliasing constructor) from pointer, makes sure it manages (if shared) or tracks (if weak) the same object it points to. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Sets pointed object. |
| void [reset](../../system/smartptr/reset/)() | Makes pointer pointing to nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Sets pointer mode. May alter referenced object's reference counts. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Calls SetTemplateWeakPtr() method on pointed object (if any). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Creates [SmartPtr](../../system/smartptr/) object of required mode. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Creates null-pointer [SmartPtr](../../system/smartptr/) object of required mode. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Creates [SmartPtr](../../system/smartptr/) pointing to specified object, or converts raw pointer to [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Copy constructs [SmartPtr](../../system/smartptr/) object. Both pointers point to the same object afterwards. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Copy constructs [SmartPtr](../../system/smartptr/) object. Both pointers point to the same object afterwards. Performs type conversion if allowed. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Move constructs [SmartPtr](../../system/smartptr/) object. Effectively, swaps two pointers, if they are both of same mode. x may be unusable after call. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Converts type of referenced array by creating a new array of different type. Useful if in C# there is an array type cast which is unsupported in C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initializes empty array. Used to translate some C# code constructs. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Constructs a [SmartPtr](../../system/smartptr/) which shares ownership information with the initial value of ptr, but holds an unrelated and unmanaged pointer p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Casts pointer to different type using static_cast on pointed object. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Converts any pointer type to pointer to [Object](../../system/object/). Doesn't require Pointee_ type to be complete. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Shortcut to get [System::TypeInfo](../../system/typeinfo/) object for the Pointee_ type. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Destroys [SmartPtr](../../system/smartptr/) object. If required, decreases pointed object's reference counter and deletes object. |
## See Also

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.Slides](../../)
