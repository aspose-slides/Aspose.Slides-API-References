---
title: WhenAny()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个任务，该任务将在任意提供的任务完成时完成。
type: docs
weight: 209
url: /zh/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) 函数


创建一个任务，该任务将在任意提供的任务完成时完成。

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | 要等待完成的任务。 |

### 返回值

一个表示已完成的提供的任务之一的任务。

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) 函数


创建一个任务，该任务将在任意提供的任务完成时完成。

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 要等待完成的任务。 |

### 返回值

一个表示已完成的提供的任务之一的任务。

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) 函数


创建一个任务，该任务将在任意提供的任务完成时完成。

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TResult | 已完成任务结果的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | 要等待完成的任务。 |

### 返回值

一个在任意任务完成时返回第一个已完成任务的任务。

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) 函数


创建一个任务，该任务将在任意提供的任务完成时完成。

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TResult | 已完成任务结果的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | 要等待完成的任务。 |

### 返回值

一个在任意任务完成时返回第一个已完成任务的任务。

## 另见

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)