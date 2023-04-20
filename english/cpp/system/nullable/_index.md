---
title: Nullable
second_title: Aspose.Slides for C++ API Reference
description: Forward declaration.
type: docs
weight: 1028
url: /cpp/system/nullable/
---
## Nullable class


Forward declaration.

```cpp
template<typename T>class Nullable
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The underlying value type which is extended by the [Nullable](./) class |
## Methods

| Method | Description |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Determines if the value represented by the current object is equal to the value represented by the specified [Nullable](./) object. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Determines whether the current object represents any value. |
| T [get_Value](./get_value/)() const | Returns a copy of the value represented by the current object. |
| int [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Returns the value represented by the current object or the specified value if the value represented by the current object is null. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Determines if the current object represents a null-value. |
|  [Nullable](./nullable/)() | Constructs an instance that represents null-value. |
|  [Nullable](./nullable/)(std::nullptr_t) | Constructs an instance that represents null. |
|  [Nullable](./nullable/)(const T1\&) | Constructs an instance of [Nullable](./) class that represents the specified value converted (if necessary) to the value of the underlying type T. |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Constructs an instance that represents a value that is represented by the specified [Nullable](./) object. The specified nullable object may represent a value of different type than the underlying type of the constructed instance in which case the represented value is converted to a value of type T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Helper function to check if this and **other** are both not nulls and call a lambda if so. Used in implementation.s. |
|  [operator const T &](./operator_const_t__and/)() const | Returns a constant reference to the value represented by the current object. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determines if the value represented by the current object is not null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Determines if the value represented by the current object is not equal to the specified value. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Determines if the value represented by the current object is not equal to the value represented by the specified [Nullable](./) object. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Applies [operator&=()](./operator_and_equal/) to the value represented by the current object using the specified value as a right-side argument. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Returns a default constructed instance of Nullable<T> class. |
| auto [operator+](./operator_plus/)(const T1\&) const | Sums nullable and non-nullable values. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Sums nullable values. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Resets the current object so that it represents a null-value. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Applies [operator+=()](./operator_plus_equal/) to the value represented by the current object using the specified value as a right-side argument. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Applies [operator+=()](./operator_plus_equal/) to the value represented by the current object using the value represented by the specified [Nullable](./) object as the right-side argument. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Subtracts nullable and null-pointed values. |
| auto [operator-](./operator_minus/)(const T1\&) const | Subtracts nullable and non-nullable values. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Subtracts nullable values. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Returns an instance of [Nullable](./) class that represents a null-value. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Applies [operator-=()](./operator_minus_equal/) to the value represented by the current object using the specified value as a right-side argument. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Applies [operator-=()](./operator_minus_equal/) to the value represented by the current object using the value represented by the specified [Nullable](./) object as the right-side argument. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Always returns false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Determines if the value represented by the current object is less than the specified value by applying [operator<()](./operator_less/) to these values. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Determines if the value represented by the current object is less than the value represented by the specified [Nullable](./) object by applying [operator<()](./operator_less/) to these values. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Always returns false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Determines if the value represented by the current object is less or equal to the specified value by applying [operator<=()](./operator_less_equal/) to these values. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Determines if the value represented by the current object is less or equal to the value represented by the specified [Nullable](./) object by applying [operator<=()](./operator_less_equal/) to these values. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Assigns a null to the current object. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Replaces the object's currently represented value with the specified one. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Replaces the object's currently represented value with the specified one. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determines if the value represented by the current object is null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Determines if the value represented by the current object is equal to the specified value. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Determines if the value represented by the current object is equal to the value represented by the specified [Nullable](./) object. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Always returns false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Determines if the value represented by the current object is greater than the specified value by applying [operator>()](./operator_greater/) to these values. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Determines if the value represented by the current object is greater than the value represented by the specified [Nullable](./) object by applying [operator>()](./operator_greater/) to these values. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Always returns false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Determines if the value represented by the current object is greater or equal to the value represented by the specified object by applying [operator>=()](./operator_greater_equal/) to these values. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Determines if the value represented by the current object is greater or equal to the value represented by the specified [Nullable](./) object by applying [operator>=()](./operator_greater_equal/) to these values. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Applies [operator|=()](./operator_or_equal/) to the value represented by the current object using the specified value as a right-side argument. |
| void [reset](./reset/)() | Sets the currently represented value to null. |
| [String](../string/) [ToString](./tostring/)() const | Converts the value represented by the current object to string. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | An alias for a type of the value represented by this class. |
## Remarks


Represents a value of the specified type that can be assigned null. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)