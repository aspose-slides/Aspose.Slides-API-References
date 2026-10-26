---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API 參考
description: 將工作項目放入佇列，該項目以無參數的回呼呈現。
type: docs
weight: 14
url: /zh-hant/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) 方法


將工作項目放入佇列，該項目以無參數的回呼呈現。

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | 用作工作的回呼函式。 |

### 返回值

永遠傳回 true。

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) 方法


將工作項目放入佇列，該項目以無參數的回呼呈現。

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | 用作工作的回呼函式。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 工作函式參數。 |

### 返回值

永遠傳回 true。

## 另請參閱

* 型別定義 [WaitCallback](../../waitcallback/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ThreadPool](../)
* 類別 [Object](../../../system/object/)
* 命名空間 [System::Threading](../../)
* 程式庫 [Aspose.Slides](../../../)