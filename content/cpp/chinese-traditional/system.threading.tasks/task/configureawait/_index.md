---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 參考
description: 設定此任務的 await 行為，以決定上下文捕獲的處理方式。
type: docs
weight: 144
url: /zh-hant/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const 方法

配置此任務的 await 行為，以決定如何處理上下文捕獲。

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | 是否在捕獲的上下文中繼續執行 |

### 返回值

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) 已配置的 awaitable

## 另請參閱

* 類別 [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* 類別 [Task](../)
* 命名空間 [System::Threading::Tasks](../../)
* 程式庫 [Aspose.Slides](../../../)