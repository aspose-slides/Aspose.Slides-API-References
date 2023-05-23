---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 898
url: /cpp/system.testpredicates.typetraits/
---



## Structures

| Struct | Description |
| --- | --- |
| [has_data_method](./has_data_method/) | Checks if a type has data() method. If it does, inherits std::true_type, otherwise inherits std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Specialization for BitArray type which provides boost type which is inaccessible there. |
| [has_print_to_method](./has_print_to_method/) | Checks for overload of PrintTo function that accepts given type as first argument. If an overload exists, inherits std::true_type, otherwise inheirts std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Checks if specific type is STL-style container. To do so, checks for iterator and const_iterator member types existance. If both exist, inherits std::true_type, otherwise inherits std::false_type. |
| [IsEnumerable](./isenumerable/) | Checks if type has [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) specialization as basetype. If so, value member is set to true, otherwise it is set to false. |
| [LargestFPType](./largestfptype/) | Provides alias for longest floating point type provided. Ignores non-floating point types. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Checks that **T1** is arithmetic and **T2** is floating point, or vice versa. If so, sets value member to true, otherwise it is false. |
| [AnyOfDecimal](./anyofdecimal/) | Checks that at least one of type arguments is [System::Decimal](../system/decimal/). If so, sets value member to true, otherwise it is false. |
| [IsArray](./isarray/) | Checks if type is a [System::Array](../system/array/) specialization. If so, value member is set to true, otherwise it is set to false. |
| [IsList](./islist/) | Checks if type is a [System::Collections::Generic::List](../system.collections.generic/list/) specialization. If so, value member is set to true, otherwise it is set to false. |
| [BothArrayOrList](./botharrayorlist/) | Checks if both type arguments are arrays or lists. If so, value member is set to true, otherwise it is set to false. |
| [BothEnumerable](./bothenumerable/) | Checks if both type arguments are IEnumerable. If so, value member is set to true, otherwise it is set to false. |
