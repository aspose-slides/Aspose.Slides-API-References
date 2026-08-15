---
title: ThreadPoolImpl
second_title: Aspose.Slides C++ API 參考
description: 執行緒池內部資料。這是一種由存取函式管理記憶體的單例類型。您不應直接建立它的實例。
type: docs
weight: 235
url: /zh-hant/system.threading/threadpoolimpl/
---
## ThreadPoolImpl 類別

[Thread](../thread/) pool 內部資料。這是一種由存取函式管理記憶體的單例類型。您不應直接建立它的實例。

```cpp
class ThreadPoolImpl
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | 取得可用執行緒的數量。 |
| static **bool**\& [GetInitialized](./getinitialized/)() | 取得初始化狀態的單例。 |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | 取得最大同時執行緒的數量。 |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | 取得池子建立的最小執行緒數量。 |
| void [JoinAll](./joinall/)() | 合併所有擁有的執行緒。無限等待。 |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | 將工作項目加入佇列。 |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | 設定池子擁有的執行緒數量。 |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | 設定池子擁有的最小執行緒數量。 |
|  [ThreadPoolImpl](./threadpoolimpl/)() | 建構函式。 |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | 解構函式。若執行緒尚未終止，則合併所有執行緒。 |

## 另請參閱

* 命名空間 [System::Threading](../)
* 程式庫 [Aspose.Slides](../../)