---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 參考
description: 為此任務設定 awaiter。
type: docs
weight: 92
url: /zh-hant/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const 方法

設定此工作階段的 awaiter。

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true 以嘗試將續行重新封送回原始捕獲的情境；否則為 false。 |

### 返回值

ConfiguredResultValueTaskAwaitable<T> 物件，用於設定此工作階段的 awaiter 行為。

## 參見

* 類別 [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* 類別 [ResultValueTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 程式庫 [Aspose.Slides](../../../)