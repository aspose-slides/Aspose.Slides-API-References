---
title: CancellationTokenRegistration
second_title: Aspose.Slides for C++ API 參考
description: 表示取消代碼標記回呼的註冊。
type: docs
weight: 27
url: /zh-hant/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration 類別

表示取消代碼標記回呼的註冊。

```cpp
class CancellationTokenRegistration
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [Dispose](./dispose/)() | 釋放註冊並從相關的 [CancellationTokenSource](../cancellationtokensource/) 中移除回呼。呼叫此方法後，當相關的 [CancellationTokenSource](../cancellationtokensource/) 被取消時，已註冊的回呼將不再被呼叫。 |

## 備註

此類別允許從取消代碼標記中取消註冊回呼。釋放時，它會從相關的 [CancellationTokenSource](../cancellationtokensource/) 中移除回呼。此類別不應直接建立──它由 [CancellationToken](../cancellationtoken/) 註冊方法回傳。

## 另見

* 命名空間 [System::Threading](../)
* 函式庫 [Aspose.Slides](../../)