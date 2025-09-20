---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API Reference
description: Gets an awaiter for this result task for use with Await.
type: docs
weight: 53
url: /system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const method


Gets an awaiter for this result task for use with Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### Return Value

Runtime::CompilerServices::ResultTaskAwaiter<T> An awaiter instance that returns the result
## Remarks



When awaited, the coroutine will resume with the result value available 

## See Also

* Class [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)