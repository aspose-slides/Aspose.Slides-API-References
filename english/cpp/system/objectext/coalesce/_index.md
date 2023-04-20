---
title: Coalesce()
second_title: Aspose.Slides for C++ API Reference
description: Implementation of '?' operator translation for non-nullable types.
type: docs
weight: 170
url: /cpp/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) method


Implementation of '?' operator translation for non-nullable types.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T0 | LHS value. |
| func | T1 | RHS expression. |

### Return Value

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) method


Implementation of '?' operator translation for nullable types.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS value. |
| func | T1 | RHS expression. |

### Return Value

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## See Also

* Class [ObjectExt](../)
* Class [Nullable](../../nullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)