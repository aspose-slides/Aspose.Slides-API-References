---
title: WhenAll()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個任務，當所有提供的任務完成時即結束。
type: docs
weight: 196
url: /zh-hant/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) 函式

建立一個任務，當所有提供的任務完成時即結束。

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 等待完成的任務。 |

### 返回值

代表所有提供任務完成的任務。

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) 函式

建立一個任務，當所有提供的任務完成時即結束。

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | 等待完成的任務。 |

### 返回值

代表所有提供任務完成的任務。

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) 函式

建立一個任務，當所有提供的任務完成時即結束。

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TResult | 已完成任務結果的型別。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | 等待完成的任務。 |

### 返回值

當所有任務完成時，返回所有結果陣列的任務。

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) 函式

建立一個任務，當所有提供的任務完成時即結束。

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TResult | 已完成任務結果的型別。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | 等待完成的任務。 |

### 返回值

當所有任務完成時，返回所有結果陣列的任務。

## 另見

* 類型別名 [TaskPtr](../../system/taskptr/)
* 類型別名 [ArrayPtr](../../system/arrayptr/)
* 類型別名 [SharedPtr](../../system/sharedptr/)
* 類型別名 [RTaskPtr](../../system/rtaskptr/)
* 類別 [IEnumerable](../../system.collections.generic/ienumerable/)
* 命名空間 [System::Threading::Tasks](../)
* 程式庫 [Aspose.Slides](../../)