---
title: Receive()
second_title: Aspose.Slides for C++ API 參考
description: 傳回由伺服器傳送的資料報文。
type: docs
weight: 92
url: /zh-hant/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) 方法

傳回由伺服器傳送的資料報文。

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | 一個 [IPEndPoint](../../../system.net/ipendpoint/)，代表傳送資料的遠端主機。 |

### 回傳值

一個位元組陣列，用於指派接收的資料。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IPEndPoint](../../../system.net/ipendpoint/)
* 類別 [UdpClient](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)