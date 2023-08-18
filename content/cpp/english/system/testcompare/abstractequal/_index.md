---
title: AbstractEqual()
second_title: Aspose.Slides for C++ API Reference
description: Compares two collections of unknown type.
type: docs
weight: 14
url: /system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) method


Compares two collections of unknown type.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Collection element type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | LHS collection. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | RHS collection. |

### Return Value

true if collections match (e. g. both are null), or if sizes match and elements match, false otherwise.

## See Also

* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [TestCompare](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)