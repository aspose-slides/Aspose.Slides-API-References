---
title: CancellationToken
second_title: Aspose.Slides for C++ API 參考文件
description: 傳遞應取消操作的通知。此類別提供跨執行緒之合作取消機制，使一個執行緒能通知其他執行緒應取消作業。
type: docs
weight: 14
url: /zh-hant/system.threading/cancellationtoken/
---
## CancellationToken 類別

傳遞應取消操作的通知。此類別提供跨執行緒之合作取消的機制，使一個執行緒能通知其他執行緒應取消作業。

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | 預設建構函式。 |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | 取得此 token 是否能處於已取消狀態。 |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | 取得此 token 是否已要求取消。 |
| static [CancellationToken](./) [get_None](./get_none/)() | 傳回一個空的 [System::Threading::CancellationToken](./) 值。 |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | 註冊一個在要求取消時將被呼叫的回呼函式。 |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | 若已要求取消，拋出 OperationCanceledException。 |

## 備註

只能透過其關聯的 [CancellationTokenSource](../cancellationtokensource/) 來取消 [CancellationToken](./)。

## 另請參閱

* 命名空間 [System::Threading](../)
* 函式庫 [Aspose.Slides](../../)