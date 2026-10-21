---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides for C++ API Reference
description: "System::BoxedValueDetail namespace"
type: docs
weight: 287
url: /system.boxedvaluedetail/
---



## Classes

| Class | Description |
| --- | --- |
| [BoxedStringBase](./boxedstringbase/) | Additional base class for [BoxedValue](../system/boxedvalue/) for string to implement IEnumerator for char16_t interface. |
| [Comparable](./comparable/) | Simple implementation of IComparable\<\> |
| [NonBoxedStringBase](./nonboxedstringbase/) | Dummy base type non-string boxed types. |
| [NonComparable](./noncomparable/) | Dummy base type for boxed types what do not implement IComparable\<\> |
## Structures

| Struct | Description |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Template predicate that checks if boxed object should implement given interface by itself. |
| [ImplementsInterface\< String, IComparable\< String \> \>](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implements [IComparable](../system/icomparable/). |
| [ImplementsInterface\< T, IComparable\< T \> \>](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Template predicate that checks if boxed object should implement [IComparable](../system/icomparable/) interface by itself. |
## Functions

| Function | Description |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Determines the equality of the specified value using [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Determines the equality of the specified value using method [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals\< float \>](./equals_less_float__greater/)(**float**, **float**) | Compares two single-precision floating-point values. |
| **bool** [Equals\< double \>](./equals_less_double__greater/)(**double**, **double**) | Compares two double-precision floating-point values. |
