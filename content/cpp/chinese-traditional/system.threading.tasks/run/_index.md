---
title: Run()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的工作排入執行緒池執行，並返回該工作的 Task 句柄。
type: docs
weight: 157
url: /zh-hant/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) function

將指定的工作排入執行緒池執行，並返回一個 [Task](../task/) 句柄，用於該工作。

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | 要非同步執行的工作。 |

### 返回值

一個 [Task](../task/)，表示已排入執行緒池執行的工作。

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) function

將指定的工作排入執行緒池執行，並返回一個 [Task](../task/) 句柄，用於該工作。

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | 要非同步執行的工作。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 可用於在工作尚未開始時取消工作的取消代碼。 |

### 返回值

一個 [Task](../task/)，表示已排入執行緒池執行的工作。

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) function

將指定的工作排入執行緒池執行，並返回一個代理，用於函式返回的 [Task](../task/)。

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | 要非同步執行的工作，該工作返回一個 [Task](../task/)。 |

### 返回值

一個 [Task](../task/)，表示函式返回的 [Task](../task/) 的代理。

## System::Threading::Tasks::Run(const Func\<TResult\>\&) function

將指定的工作排入執行緒池執行，並返回一個 Task<TResult> 句柄，用於該工作。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| TResult | 任務返回之結果的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | 要非同步執行的工作。 |

### 返回值

一個 Task<TResult>，表示已排入執行緒池執行的工作。

## 參見

* 類型別名 [TaskPtr](../../system/taskptr/)
* 類型別名 [Action](../../system/action/)
* 類型別名 [RTaskPtr](../../system/rtaskptr/)
* 類別 [CancellationToken](../../system.threading/cancellationtoken/)
* 類別 [Func](../../system/func/)
* 命名空間 [System::Threading::Tasks](../)
* 函式庫 [Aspose.Slides](../../)