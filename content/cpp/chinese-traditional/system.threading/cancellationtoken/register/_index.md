---
title: Register()
second_title: Aspose.Slides for C++ API 參考
description: 註冊一個回呼，當要求取消時將會被呼叫。
type: docs
weight: 40
url: /zh-hant/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const method


註冊一個回呼，當要求取消時將會被呼叫。

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | 取消請求時將執行的 Action<>。 |

### 返回值

一個 [CancellationTokenRegistration](../../cancellationtokenregistration/) 物件，可用於取消註冊此回呼。

## 備註



如果取消已經被請求，回呼將會立即被呼叫。

回呼應該是短暫且非阻塞的，因為它會在呼叫 [CancellationTokenSource](../../cancellationtokensource/) 上的 Cancel() 的執行緒上執行。

## 另請參閱

* Typedef [Action](../../../system/action/)
* Class [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)