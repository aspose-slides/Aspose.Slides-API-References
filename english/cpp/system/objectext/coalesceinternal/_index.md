---
title: CoalesceInternal()
second_title: Aspose.Slides for C++ API Reference
description: Implementation of '?' operator translation for non-nullable types. Overload for case if RT2 is convertable to RT1.
type: docs
weight: 157
url: /cpp/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) method


Implementation of '?' operator translation for non-nullable types. Overload for case if RT2 is convertable to RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | RT1 | LHS value. |
| func | F | RHS expression. |

### Return Value

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)