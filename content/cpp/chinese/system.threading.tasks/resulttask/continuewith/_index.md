---
title: ContinueWith()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个在结果任务完成时执行的后续操作。
type: docs
weight: 40
url: /zh/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) 方法


创建一个在结果任务完成时执行的后续操作。

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | 在此任务完成时执行的操作，接收此结果任务 |

### 返回值

TaskPtr 一个表示后续操作的新任务
## 备注



后续操作会接收此 [ResultTask](../) 以访问结果值 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) 方法


创建一个在结果任务完成时执行的后续操作。

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TNewResult | 任务后续的结果类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | 在此任务完成时获取后续结果的函数，接收此结果任务 |

### 返回值

RTaskPtr 一个表示后续操作的新任务
## 备注



后续函数会接收此 [ResultTask](../) 以访问结果值 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) 方法


创建一个在任务完成时执行的后续操作。

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | 在此任务完成时执行的操作 |

### 返回值

TaskPtr 一个表示后续操作的新任务

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) 方法


创建一个在任务完成时执行的后续操作。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TResult | 任务结果的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | 在此任务完成时获取结果的函数 |

### 返回值

RTaskPtr 一个表示后续操作的新任务

## 另请参考

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* 类 [ResultTask](../)
* 类 [Func](../../../system/func/)
* 命名空间 [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)