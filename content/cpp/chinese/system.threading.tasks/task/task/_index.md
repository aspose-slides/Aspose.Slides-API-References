---
title: Task()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个带有待执行操作的 Task。
type: docs
weight: 1
url: /zh/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) 构造函数

使用要执行的操作构造一个 [Task](../)。

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | 异步执行的操作 |

## Task::Task(const Action<>\&, const CancellationToken\&) 构造函数

使用操作和取消令牌构造一个 [Task](../)。

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | 异步执行的操作 |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | 用于监视取消请求的令牌 |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) 构造函数

使用有状态的操作和状态对象构造一个 [Task](../)。

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | 执行的操作（接受状态对象） |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 传递给操作的用户定义状态对象 |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) 构造函数

使用有状态的操作、状态和取消令牌构造一个 [Task](../)。

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | 执行的操作（接受状态对象） |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 传递给操作的用户定义状态对象 |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | 用于监视取消请求的令牌 |

## Task::Task() 构造函数

用于创建未初始化任务的内部构造函数。

```cpp
System::Threading::Tasks::Task::Task()
```

## 参见

* 类型定义 [Action](../../../system/action/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Task](../)
* 类 [CancellationToken](../../../system.threading/cancellationtoken/)
* 类 [Object](../../../system/object/)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)