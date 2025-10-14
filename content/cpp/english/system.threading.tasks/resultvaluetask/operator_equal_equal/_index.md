---
title: operator==()
second_title: Aspose.Slides for C++ API Reference
description: Equality operator for ResultValueTask.
type: docs
weight: 131
url: /system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const method


Equality operator for [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | The other [ResultValueTask](../) to compare with this instance. |

### Return Value

bool True if both tasks have the same result value or reference the same underlying task; otherwise, false.
## Remarks



If either instance contains a direct result value, compares the results directly. Otherwise, compares the underlying task pointers. 
## See Also

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)