---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API 參考
description: 取得此任務的 awaiter 以支援 await 表達式。
type: docs
weight: 118
url: /zh-hant/system.threading.tasks/resultvaluetask/getawaiter/
---
## ResultValueTask::GetAwaiter() const 方法


取得此任務之 awaiter 以支援 await 表達式。

```cpp
Runtime::CompilerServices::ResultValueTaskAwaiter<T> System::Threading::Tasks::ResultValueTask<T>::GetAwaiter() const
```


### 返回值

ResultValueTaskAwaiter<T> 此任務的 awaiter 實例。

## 備註



此方法使得能夠在 [ResultValueTask](../) 中使用 Await 方法。

## 參見

* 類別 [ResultValueTaskAwaiter](../../../system.runtime.compilerservices/resultvaluetaskawaiter/)
* 類別 [ResultValueTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 程式庫 [Aspose.Slides](../../../)