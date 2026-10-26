---
title: WhenAny()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個任務，當任一提供的任務完成時即會完成。
type: docs
weight: 209
url: /zh-hant/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) 函式

建立一個任務，會在任一提供的任務完成時完成。

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | 等待完成的任務。 |

### 傳回值

表示所提供任務之一完成的任務。

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) 函式

建立一個任務，會在任一提供的任務完成時完成。

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 等待完成的任務。 |

### 傳回值

表示所提供任務之一完成的任務。

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) 函式

建立一個任務，會在任一提供的任務完成時完成。

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TResult | 已完成任務結果的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | 等待完成的任務。 |

### 傳回值

當任一任務完成時，回傳第一個已完成的任務。

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) 函式

建立一個任務，會在任一提供的任務完成時完成。

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TResult | 已完成任務結果的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | 等待完成的任務。 |

### 傳回值

當任一任務完成時，回傳第一個已完成的任務。

## 另請參閱

* 型別定義 [RTaskPtr](../../system/rtaskptr/)
* 型別定義 [TaskPtr](../../system/taskptr/)
* 型別定義 [SharedPtr](../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../system/arrayptr/)
* 類別 [IEnumerable](../../system.collections.generic/ienumerable/)
* 命名空間 [System::Threading::Tasks](../)
* 程式庫 [Aspose.Slides](../../)