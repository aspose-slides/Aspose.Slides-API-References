---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定此結果任務的 await 行為，以決定在捕獲上下文時的處理方式。
type: docs
weight: 27
url: /zh-hant/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const 方法

設定此結果任務的 await 行為，以決定在捕獲上下文時的行為方式。

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | 是否在捕獲的上下文上繼續執行 |

## 返回值

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> 為 result 配置的 awaitable

## 備註

此功能可對 async/await 模式中的上下文流進行細緻的控制。

## 另請參閱

* 類別 [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* 類別 [ResultTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)