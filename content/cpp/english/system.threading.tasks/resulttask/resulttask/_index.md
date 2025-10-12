---
title: ResultTask()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a ResultTask with a function that returns a value.
type: docs
weight: 1
url: /system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) constructor


Constructs a [ResultTask](../) with a function that returns a value.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | The function to execute asynchronously that returns a result |

## ResultTask::ResultTask() constructor


Internal implementation. Not for user code.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Remarks


Internal constructor for creating uninitialized result tasks 
## ResultTask::ResultTask(const T\&) constructor


Internal constructor for creating result tasks with specified result.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## See Also

* Class [Func](../../../system/func/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)