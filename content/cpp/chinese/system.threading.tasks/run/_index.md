---
title: Run()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的工作排入线程池并返回该工作的 Task 句柄。
type: docs
weight: 157
url: /zh/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) 函数


将指定的工作排入线程池并返回一个 [Task](../task/) 句柄。

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | 要异步执行的工作。 |

### 返回值

一个代表已排入线程池执行的工作的 [Task](../task/)。

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) 函数


将指定的工作排入线程池并返回一个 [Task](../task/) 句柄。

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | 要异步执行的工作。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 用于在工作尚未启动时取消它的取消令牌。 |

### 返回值

一个代表已排入线程池执行的工作的 [Task](../task/)。

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) 函数


将指定的工作排入线程池并返回一个代理，用于函数返回的 [Task](../task/)。

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | 要异步执行的工作，返回一个 [Task](../task/)。 |

### 返回值

一个代表函数返回的 [Task](../task/) 代理的 [Task](../task/)。

## System::Threading::Tasks::Run(const Func\<TResult\>\&) 函数


将指定的工作排入线程池并返回一个 Task<TResult> 句柄。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TResult | 任务返回的结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | 要异步执行的工作。 |

### 返回值

一个代表已排入线程池执行的工作的 Task<TResult>。

## 参见

* 类型定义 [TaskPtr](../../system/taskptr/)
* 类型定义 [Action](../../system/action/)
* 类型定义 [RTaskPtr](../../system/rtaskptr/)
* 类 [CancellationToken](../../system.threading/cancellationtoken/)
* 类 [Func](../../system/func/)
* 命名空间 [System::Threading::Tasks](../)
* 库 [Aspose.Slides](../../)