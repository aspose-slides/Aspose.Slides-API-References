---
title: UdpClient()
second_title: Aspose.Slides for C++ API 參考
description: 初始化 UdpClient 類別的新執行個體。
type: docs
weight: 27
url: /zh-hant/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() 建構子

初始化 [UdpClient](../) 類別的新執行個體。

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) 建構子

初始化 [UdpClient](../) 類別的新執行個體。

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | 指定 socket 位址方案的值。 |

## UdpClient::UdpClient(int32_t) 建構子

初始化 [UdpClient](../) 類別的新執行個體。

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| port | **int32_t** | 您欲通訊的本機埠號。 |

## UdpClient::UdpClient(int32_t, AddressFamily) 建構子

初始化 [UdpClient](../) 類別的新執行個體。

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| port | **int32_t** | 您欲通訊的本機埠號。 |
| family | [AddressFamily](../../addressfamily/) | 指定 socket 位址方案的值。 |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) 建構子

初始化 [UdpClient](../) 類別的新執行個體。參數 local EP 為您綁定 UDP 連線的本地端點。

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) 建構子

建立 [UdpClient](../) 類別的新執行個體，並連接至指定的遠端主機與指定的埠號。

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 您欲連線的遠端 DNS 主機名稱。 |
| port | **int32_t** | 您欲通訊的本機埠號。 |

## 另請參閱

* 列舉 [AddressFamily](../../addressfamily/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [UdpClient](../)
* 類別 [IPEndPoint](../../../system.net/ipendpoint/)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)