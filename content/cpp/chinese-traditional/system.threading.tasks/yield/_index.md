---
title: Yield()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個可等待的任務，當等待時會非同步地讓出回當前上下文。
type: docs
weight: 222
url: /zh-hant/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() 函式

建立一個可等待的任務，當等待時會非同步地讓出回當前上下文。

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```

### 回傳值

一個可等待的 YieldAwaitable，可用於讓出控制權。

## 說明

此方法可強制非同步方法讓出控制權，允許在繼續之前處理其他待處理的工作。

## 另見

* 類別 [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* 命名空間 [System::Threading::Tasks](../)
* 程式庫 [Aspose.Slides](../../)