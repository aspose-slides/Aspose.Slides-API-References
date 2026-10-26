---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API 參考
description: 取得此結果任務的 awaiter，以供 Await 使用。
type: docs
weight: 53
url: /zh-hant/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const 方法


取得此結果任務的 awaiter，以供 Await 使用。

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### 返回值

Runtime::CompilerServices::ResultTaskAwaiter<T> 返回結果的 awaiter 實例
## 備註



當被 await 時，協程將在結果值可用時繼續執行。

## 另見

* 類別 [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* 類別 [ResultTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)