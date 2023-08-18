---
title: MakeScopeGuard()
second_title: Aspose.Slides for C++ API Reference
description: A factory function that creates instances of ScopedGuard class.
type: docs
weight: 2406
url: /system/makescopeguard/
---
## System::MakeScopeGuard(F) function


A factory function that creates instances of ScopedGuard class.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| The | type of the function object to be invoked by the constructed ScopedGuard object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| f | F | The function object to pass to ScopedGuard class' constructor. |

### Return Value

A new instance of ScopedGuard class

## See Also

* Struct [ScopeGuard](../scopeguard/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)