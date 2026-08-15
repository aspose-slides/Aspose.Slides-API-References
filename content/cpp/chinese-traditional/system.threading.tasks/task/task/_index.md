---
title: Task()
second_title: Aspose.Slides for C++ API 參考文件
description: 以要執行的動作建構 Task。
type: docs
weight: 1
url: /zh-hant/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) 建構函式

以要執行的動作建構 [Task](../)。

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | 要非同步執行的動作 |

## Task::Task(const Action<>\&, const CancellationToken\&) 建構函式

以動作與取消令牌建構 [Task](../)。

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | 要非同步執行的動作 |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | 用於監控取消請求的令牌 |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) 建構函式

以有狀態的動作與狀態物件建構 [Task](../)。

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | 要執行的動作（接受狀態物件） |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 傳遞給動作的使用者自訂狀態物件 |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) 建構函式

以有狀態的動作、狀態與取消令牌建構 [Task](../)。

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | 要執行的動作（接受狀態物件） |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 傳遞給動作的使用者自訂狀態物件 |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | 用於監控取消請求的令牌 |

## Task::Task() 建構函式

用於建立未初始化任務的內部建構函式。

```cpp
System::Threading::Tasks::Task::Task()
```

## 另請參閱

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)