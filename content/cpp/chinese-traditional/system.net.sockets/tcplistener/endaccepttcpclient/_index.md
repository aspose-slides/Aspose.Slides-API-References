---
title: EndAcceptTcpClient()
second_title: Aspose.Slides for C++ API 參考
description: 等待直到指定的非同步接受操作完成。
type: docs
weight: 183
url: /zh-hant/system.net.sockets/tcplistener/endaccepttcpclient/
---
## TcpListener::EndAcceptTcpClient(System::SharedPtr\<IAsyncResult\>) 方法

等待直到指定的非同步接受操作完成。

```cpp
System::SharedPtr<TcpClient> System::Net::Sockets::TcpListener::EndAcceptTcpClient(System::SharedPtr<IAsyncResult> asyncResult)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 一個 [IAsyncResult](../../../system/iasyncresult/) 物件，代表非同步接受操作。 |

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [TcpClient](../../tcpclient/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [TcpListener](../)
* 命名空間 [System::Net::Sockets](../../)
* 程式庫 [Aspose.Slides](../../../)