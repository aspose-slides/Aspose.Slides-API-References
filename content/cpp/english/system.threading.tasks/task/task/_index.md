---
title: Task()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a Task with an action to execute.
type: docs
weight: 1
url: /system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) constructor


Constructs a [Task](../) with an action to execute.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | The action to execute asynchronously |

## Task::Task(const Action<>\&, const CancellationToken\&) constructor


Constructs a [Task](../) with an action and cancellation token.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | The action to execute asynchronously |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token to monitor for cancellation requests |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) constructor


Constructs a [Task](../) with a stateful action and state object.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | The action to execute (accepts state object) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | User-defined state object passed to the action |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) constructor


Constructs a [Task](../) with stateful action, state, and cancellation token.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | The action to execute (accepts state object) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | User-defined state object passed to the action |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token to monitor for cancellation requests |

## Task::Task() constructor


Internal constructor for creating uninitialized tasks.

```cpp
System::Threading::Tasks::Task::Task()
```

## See Also

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)