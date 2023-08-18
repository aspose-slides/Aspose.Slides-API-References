---
title: Enum
second_title: Aspose.Slides for C++ API Reference
description: Provides methods that perform some operations on values of enum type. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 1444
url: /system/enum/
---
## Enum struct


Provides methods that perform some operations on values of enum type. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
template<class E,class Guard>class Enum
```


### Template parameters

| Parameter | Description |
| --- | --- |
| E | The type of enum on values of which the class handles |
| Guard | Service type argument whose purpose is to ensure that **E** is enumerable type |
## Methods

| Method | Description |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Performs the arithmetic comparison of the values of the specified enumeration constants. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Returns the name of the enumeration constant that has the specified value. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Returns the name of the enumeration constant that has the specified value. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Returns an array containing names of all members of enumeration **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Returns the underlying type of the enumeration. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Returns an array containing all members of enumeration **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Determines if the specified bits are set in a bitary representation of the specified enum value. |
| static **bool** [IsDefined](./isdefined/)(E) | Determines whether the specified value is a member of enumeration type **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Determines whether the specified value is a member of enumeration type **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Determines if the value with the specified name is among members of enum **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Converts the specfied string into equivalent enum constant. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Tries to convert the specified string into equivalent enum constant. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Tries to convert the specified string into equivalent enum constant. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias for the enum's underlying type. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)