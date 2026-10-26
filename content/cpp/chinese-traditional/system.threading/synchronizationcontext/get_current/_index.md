---
title: get_Current()
second_title: Aspose.Slides for C++ API 參考
description: 取得目前執行緒的同步上下文。
type: docs
weight: 40
url: /zh-hant/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() 方法

取得目前執行緒的同步上下文。

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```

### 返回值

SharedPtr<SynchronizationContext> 指向目前執行緒的同步上下文的共享指標。

## 備註

如果尚未為目前執行緒設定同步上下文，則回傳 null。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [SynchronizationContext](../)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)