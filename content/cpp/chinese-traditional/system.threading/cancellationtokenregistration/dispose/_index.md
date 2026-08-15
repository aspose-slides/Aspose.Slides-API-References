---
title: Dispose()
second_title: Aspose.Slides for C++ API 參考
description: 解除註冊並從相關的 CancellationTokenSource 中移除回呼函式。呼叫此方法後，已註冊的回呼函式將不再在相關的 CancellationTokenSource 被取消時被呼叫。
type: docs
weight: 1
url: /zh-hant/system.threading/cancellationtokenregistration/dispose/
---
## CancellationTokenRegistration::Dispose() 方法


解除註冊並從相關的 [CancellationTokenSource](../../cancellationtokensource/) 中移除回呼函式。呼叫此方法後，已註冊的回呼函式將不再在相關的 [CancellationTokenSource](../../cancellationtokensource/) 被取消時被呼叫。

```cpp
void System::Threading::CancellationTokenRegistration::Dispose()
```

## 備註



安全地多次呼叫此方法——隨後的呼叫不會產生任何影響。 

## 另見

* 類別 [CancellationTokenRegistration](../)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)