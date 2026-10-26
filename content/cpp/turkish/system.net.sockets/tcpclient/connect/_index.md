---
title: Connect()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen uzak ana bilgisayara bir bağlantı kurar.
type: docs
weight: 248
url: /tr/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) metodu


Belirtilen uzak ana bilgisayara bir bağlantı kurar.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Bağlanılacak uzak ana bilgisayar adı. |
| port | **int32_t** | Bağlanılacak uzak ana bilgisayarın bağlantı noktası. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metodu


Belirtilen uzak ana bilgisayara bir bağlantı kurar.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Uzak ana bilgisayarın IP adresi. |
| port | **int32_t** | Bağlanılacak uzak ana bilgisayarın bağlantı noktası. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) metodu


Belirtilen uzak ana bilgisayara bir bağlantı kurar.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Bağlanılacak uzak ana bilgisayar. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metodu


Belirtilen uzak ana bilgisayara bir bağlantı kurar.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Uzak ana bilgisayarın IP adresleri. |
| port | **int32_t** | Bağlanılacak uzak ana bilgisayarın bağlantı noktası. |

## Ayrıca Bakın

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [TcpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)