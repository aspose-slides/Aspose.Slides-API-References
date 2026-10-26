---
title: QueueUserWorkItem()
second_title: Aspose.Slides C++ API 參考文件
description: 將工作項目加入佇列。
type: docs
weight: 1
url: /zh-hant/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) 方法

將工作項目加入佇列。

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | 要執行的回呼函式。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 回呼函式參數。 |

### 傳回值

永遠傳回 true。

## 另請參閱

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [ThreadPoolImpl](../)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)