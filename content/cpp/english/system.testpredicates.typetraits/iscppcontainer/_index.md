---
title: IsCppContainer
second_title: Aspose.Slides for C++ API Reference
description: "Checks if specific type is STL-style container. To do so, checks for iterator and const_iterator member types existance. If both exist, inherits std::true_type, otherwise inherits std::false_type."
type: docs
weight: 40
url: /system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct


Checks if specific type is STL-style container. To do so, checks for iterator and const_iterator member types existance. If both exist, inherits std::true_type, otherwise inherits std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type to check. |
| Enable | Formal argument for SFINAE to work. |

## See Also

* Namespace [System::TestPredicates::TypeTraits](../)
* Library [Aspose.Slides](../../)