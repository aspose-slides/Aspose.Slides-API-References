---
title: IsBoxable
second_title: Aspose.Slides for C++ API Reference
description: Template predicate that checks if boxing of the specified type is supported.
type: docs
weight: 1600
url: /system/isboxable/
---
## IsBoxable struct


Template predicate that checks if boxing of the specified type is supported.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type to check |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)