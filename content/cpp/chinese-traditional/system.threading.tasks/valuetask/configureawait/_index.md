---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 參考
description: 為此任務配置 awaiter。
type: docs
weight: 79
url: /zh-hant/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const 方法

為此任務配置 awaiter。

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true 表示嘗試將後續操作重新調度回原始捕獲的上下文；false 表示不這麼做。 |

### 返回值

ConfiguredValueTaskAwaitable 一個配置 awaiter 行為的物件，用於此任務。

## 另見

* 類別 [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* 類別 [ValueTask](../)
* 命名空間 [System::Threading::Tasks](../../)
* 函式庫 [Aspose.Slides](../../../)