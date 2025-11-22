---
title: SafeInvoke()
second_title: Aspose.Slides for C++ API Reference
description: Implementation of '?.' operator translation.
type: docs
weight: 2575
url: /system/safeinvoke/
---
## System::SafeInvoke(T0, T1) function


Implementation of '?.' operator translation.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 expr, T1 func)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T0 | expression type. |
| T1 | Type of lambda encapsulating 'WhenTrue' expression. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | T0 | expression value. |
| func | T1 | 'WhenTrue' expression bound to functor. |

### Return Value

If expr value is not null, returns func called with its value as first argument, otherwise returns null.

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)