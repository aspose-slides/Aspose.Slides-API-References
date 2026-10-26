---
title: TcpClient()
second_title: Aspose.Slides C++ API 參考
description: 建立新實例。
type: docs
weight: 235
url: /zh-hant/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) 建構式


建立新實例。

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 套接字所綁定的端點。 |

## TcpClient::TcpClient() 建構式


建立新實例。

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) 建構式


建立新實例。

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | 位址族群。 |

## TcpClient::TcpClient(String, int32_t) 建構式


建立新實例。

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 要連接的遠端主機名稱。 |
| port | **int32_t** | 要連接的遠端主機埠號。 |

## 另請參閱

* 列舉 [AddressFamily](../../addressfamily/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPEndPoint](../../../system.net/ipendpoint/)
* 類別 [TcpClient](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)