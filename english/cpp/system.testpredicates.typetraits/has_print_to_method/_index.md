---
title: has_print_to_method
second_title: Aspose.Slides for C++ API Reference
description: "Checks for overload of PrintTo function that accepts given type as first argument. If an overload exists, inherits std::true_type, otherwise inheirts std::false_type."
type: docs
weight: 27
url: /cpp/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct


Checks for overload of PrintTo function that accepts given type as first argument. If an overload exists, inherits std::true_type, otherwise inheirts std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type to check. |
| Enable | Formal argument for SFINAE to work. |

## See Also

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.Slides](../../)
