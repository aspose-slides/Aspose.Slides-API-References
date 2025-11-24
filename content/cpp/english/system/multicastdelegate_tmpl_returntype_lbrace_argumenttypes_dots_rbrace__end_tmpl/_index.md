---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API Reference
description: "Represents a collection of delegates. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 1054
url: /system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> class


Represents a collection of delegates. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ReturnType | Return type of the invokable entities pointed to by each delegate in the collection |
| ArgumentTypes | Argument list of the invokable entities pointed to by each delegate in the collection |
## Methods

| Method | Description |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NOT IMPLEMENTED. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Adds the specified delegate to the collection. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Adds the specified function object to the delegate collection. The function object is converted to the Callback delegate type before being added to the collection. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Adds the specified MulticastDelegate object to the delegate collection. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Adds the specified non-static method of the specified object to the delegate collection. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Adds the specified non-static method of the specified object to the delegate collection. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Removes the specified delegate from the delegate collection. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Removes the specified non-static method of the specified object from the delegate collection. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Removes the specified non-static method of the specified object from the delegate collection. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Removes the specified MulticastDelegate object from the delegate collection. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Removes all delegates from the delegate collection. |
| **bool** [empty](./empty/)() const | Determines whether the delegate collection is empty. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NOT IMPLEMENTED. |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Invokes all delegates currently present in the delegates collection. Delegates are invoked in the same order as they were added to the collection. The method blocks while the delegates are executed. |
| **bool** [IsNull](./isnull/)() const | Determines whether the delegate collection is empty. |
|  [MulticastDelegate](./multicastdelegate/)() | Constructs an empty collection. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Equivalent to defalt constructor. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Performs a shallow copy of the delegate collection. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Moving constructor. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Constructs an instance and puts the specified delegate to the delegates collection. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Constructs an instance and puts the specified value to the delegates collection. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Constructs an instance and puts the specified value to the delegates collection. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Determines whether the delegate collection is not empty. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Determines whether two instances of MulticastDelegate - the current object and the specified object - are inequal. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Invokes all delegates currently present in the delegates collection. Delegates are invoked in the same order as they were added to the collection. The operator blocks while the delegates are executed. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Adds the specified delegate to the collection. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Removes the specified delegate from the delegate collection. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Assigns the collection of delegates represented by the specified object to the current object. As a result both objects point to the same collection of delegates. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Moving assignment operator. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Determines whether the delegate collection is empty. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Determines whether two instances of MulticastDelegate - the current object and the specified object - are equal. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Cleans out contained callbacks that are empty (not actually calling anything). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returns a reference to the [TypeInfo](../typeinfo/) object representing the MulticastDelegate class type information. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Callback](./callback/) | The type of the delegates represented by the MulticastDelegate class. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)