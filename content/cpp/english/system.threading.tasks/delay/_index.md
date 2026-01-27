---
title: Delay()
second_title: Aspose.Slides for C++ API Reference
description: Creates a task that completes after a time delay.
type: docs
weight: 105
url: /system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) function


Creates a task that completes after a time delay.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | The number of milliseconds to wait before completing the returned task, or -1 to wait indefinitely. |

### Return Value

A task that represents the time delay.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) function


Creates a task that completes after a time delay and can be cancelled.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | The number of milliseconds to wait before completing the returned task, or -1 to wait indefinitely. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | The cancellation token that can be used to cancel the delay. |

### Return Value

A task that represents the time delay.

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)