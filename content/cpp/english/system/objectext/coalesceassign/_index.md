---
title: CoalesceAssign()
second_title: Aspose.Slides for C++ API Reference
description: Implementation of '??=' operator translation.
type: docs
weight: 183
url: /system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) method


Implementation of '??=' operator translation.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T0\& | LHS value. |
| func | T1 | RHS expression. |

### Return Value

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)