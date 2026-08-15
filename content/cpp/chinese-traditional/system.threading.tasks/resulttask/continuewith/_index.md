---
title: ContinueWith()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個在結果任務完成時執行的延續。
type: docs
weight: 40
url: /zh-hant/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) 方法

建立一個在結果任務完成時執行的延續。

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | 當此任務完成時要執行的 Action，接收此結果任務 |

### 返回值

TaskPtr 代表延續的新的任務

## 備註

此延續的 Action 接收此 [ResultTask](../) 以存取結果值 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) 方法

建立一個在結果任務完成時執行的延續。

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TNewResult | 任務延續的結果類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | 當此任務完成時取得延續結果的 Function，接收此結果任務 |

### 返回值

RTaskPtr 代表延續的新的任務

## 備註

此延續的 Function 接收此 [ResultTask](../) 以存取結果值 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) 方法

建立一個在任務完成時執行的延續。

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | 當此任務完成時要執行的 Action |

### 返回值

TaskPtr 代表延續的新的任務

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) 方法

建立一個在任務完成時執行的延續。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TResult | 任務結果的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | 當此任務完成時取得結果的 Function |

### 返回值

RTaskPtr 代表延續的新的任務

## 另見

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)