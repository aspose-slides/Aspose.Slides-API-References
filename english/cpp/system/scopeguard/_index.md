---
title: ScopeGuard
second_title: Aspose.Slides for C++ API Reference
description: The service class that provides services for running a particular function object when an instance of the class goes out of scope.
type: docs
weight: 1730
url: /cpp/system/scopeguard/
---
## ScopeGuard struct


The service class that provides services for running a particular function object when an instance of the class goes out of scope.

```cpp
template<typename F>class ScopeGuard
```


### Template parameters

| Parameter | Description |
| --- | --- |
| F | The type of the function object invoked by the instances of the ScopedGuard class |
## Methods

| Method | Description |
| --- | --- |
|  [ScopeGuard](./scopeguard/)(F) | Constructs an instance that is set up to invoke the specified function object. |
|  [~ScopeGuard](./~scopeguard/)() | Invokes the function object passed to the constructor. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)