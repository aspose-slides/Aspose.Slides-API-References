---
title: ObjectExt
second_title: Aspose.Slides for C++ API Reference
description: Provides static methods that emulate C# Object methods called for non-Object C++ types (strings, numbers, etc.). This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 1093
url: /system/objectext/
---
## ObjectExt class


Provides static methods that emulate C# [Object](../object/) methods called for non-Object C++ types (strings, numbers, etc.). This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class ObjectExt : public System::ObjectType
```

## Methods

| Method | Description |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Converts array fundamental values (which C# does implicitly but C++ apparently does not). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Boxes value types for converting to [Object](../object/). Implementation for enum types. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Boxes value types for converting to [Object](../object/). Implementation for non-enum types. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Boxes [Nullable](../nullable/) types for converting to [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Boxes string values. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Boxes enum types for being propagated as [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Implementation of '??' operator translation for non-nullable types. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Implementation of '??' operator translation for nullable types. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementation of '??' operator translation for non-nullable types. Overload for case if RT2 is convertable to RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Substitution for C# [Object.Equals](../object/equals/) calls working for any type in C++. Overload for smart pointer types. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Substitution for C# [Object.Equals](../object/equals/) calls working for any type in C++. Overload for structure types. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Substitution for C# [Object.Equals](../object/equals/) calls working for any type in C++. Overload for scalar types. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Substitution for C# [Object.Equals](../object/equals/) calls working for any type in C++. Overload for string literal with string comparison. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Implements [GetHashCode()](./gethashcode/) calls; works on both [Object](../object/) subclasses and unrelated types. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implements typeof() translation. Overload for smart pointers. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implements typeof() translation. Overload for structures. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implements typeof() translation. Overload for exceptions. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implements typeof() translation. Overload for primitive types. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implements typeof() translation. Overload for [Nullable](../nullable/) types. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for primitive types. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for enum types. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for structures and pointers. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for structures and pointers. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Implements typeof() translation. Overload for string type. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implements typeof() translation. Overload for **uint8_t**. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implements 'is' operator translation. Specialization for pointer types optimized for 'final' classes. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implements 'is' operator translation. Specialization for pointer types. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implements 'is' operator translation. Specialization for value types. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implements 'is' operator translation. Specialization for unconvertible types. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implements 'is' operator translation. Specialization for pointer types. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Implements 'is' operator translation. Specialization for exception wrapper types. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implements 'is' operator translation. Specialization for nullable types. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implements 'is' operator translation. Specialization for boxable types with == operator defined. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implements 'is' operator translation. Specialization for boxable types without defined ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Implements 'is' operator translation. Specialization value types boxed to interfaces. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implements 'is' operator translation. Specialization for enum types. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Implements 'is' operator translation. Specialization for enum types vs weak pointers. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Implements 'is' operator translation. Specialization for [Nullable](../nullable/) type. |
| static **bool** [Is](./is/)(const char16_t *) | Implements 'is' operator translation. Specialization for string literal. |
| static **bool** [Is](./is/)(**int32_t**) | Implements 'is' operator translation. Specialization for integer literal. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Checks if object is a boxed value. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Converts [Object](../object/) to unknown type, handling both smart pointer type and bpxed value situations. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Converts [Object](../object/) to unknown type, handling both smart pointer type and boxed value situations. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Substitution for C# ToString method to work on any C++ type. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Substitution for C# ToString method to work on any C++ type. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Substitution for C# ToString method to work on any C++ type. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Substitution for C# ToString method to work on any C++ type. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Substitution for C# ToString method to work on any C++ type. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Substitution for C# ToString method to work on any C++ type. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Substitution for C# ToString method to work on any C++ type. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Substitution for C# ToString method to work on any C++ type. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Substitution for C# ToString method to work on any C++ type. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Substitution for C# ToString method to work on any C++ type. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Unboxes value types after converting to [Object](../object/). Implementation for enum types. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Unboxes value types after converting to [Object](../object/). Implementation for non-enum & non-nullable types. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Unboxes value types after converting to [Object](../object/). Implementation for non-enum & non-nullable types. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Unboxes enum types to integer. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Converts enum types. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Unboxes string values. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Unboxes string from boxed value. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Unboxes object to nullable type. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Checks whether unknown type object is nullptr. Overload for non-scalar types. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Checks whether unknown type object is nullptr. Overload for scalar types. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Converts unknown type to [Object](../object/), handling both smart pointer type and value type situations. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Converts unknown type to [Object](../object/), handling both smart pointer type and value type situations. |
## See Also

* Class [ObjectType](../objecttype/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)