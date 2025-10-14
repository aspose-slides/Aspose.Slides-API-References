---
title: Delay()
second_title: Aspose.Slides for C++ API Reference
description: Creates a task that completes after a time delay.
type: docs
weight: 79
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




```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

## See Also

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)