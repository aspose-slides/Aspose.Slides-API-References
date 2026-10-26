---
title: SetSynchronizationContext()
second_title: Aspose.Slides for C++ API 參考
description: 設定目前執行緒的同步上下文。
type: docs
weight: 53
url: /zh-hant/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) method


設定目前執行緒的同步上下文。

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | 要為目前執行緒設定的同步上下文。 |
## 備註



傳入 nullptr 會清除目前執行緒的同步上下文。 

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [SynchronizationContext](../)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)