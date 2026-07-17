---
title: WhenAll()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个任务，当所有提供的任务完成时，该任务将完成。
type: docs
weight: 196
url: /zh/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) 函数

创建一个任务，当所有提供的任务完成时，该任务将完成。

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 等待完成的任务。 |

### 返回值

一个表示所有提供的任务已完成的任务。

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) 函数

创建一个任务，当所有提供的任务完成时，该任务将完成。

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | 等待完成的任务。 |

### 返回值

一个表示所有提供的任务已完成的任务。

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) 函数

创建一个任务，当所有提供的任务完成时，该任务将完成。

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TResult | 已完成任务结果的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | 等待完成的任务。 |

### 返回值

一个在所有任务完成时返回所有结果数组的任务。

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) 函数

创建一个任务，当所有提供的任务完成时，该任务将完成。

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TResult | 已完成任务结果的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | 等待完成的任务。 |

### 返回值

一个在所有任务完成时返回所有结果数组的任务。

## 另请参阅

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)