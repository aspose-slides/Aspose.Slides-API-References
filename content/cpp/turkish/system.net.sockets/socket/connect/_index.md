---
title: Connect()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen uzak uç noktasına bir bağlantı kurar.
type: docs
weight: 560
url: /tr/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) yöntemi


Belirtilen uzak uç noktasına bir bağlantı kurar.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) yöntemi


Belirtilen uzak uç noktasına bir bağlantı kurar.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Uzak ana bilgisayarın IP adresi. |
| port | **int32_t** | Uzak ana bilgisayarın bağlantı noktası numarası. |

## Socket::Connect(String, int32_t) yöntemi


Belirtilen uzak uç noktasına bir bağlantı kurar.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | [String](../../../system/string/) | Uzak ana bilgisayar adı. |
| port | **int32_t** | Uzak ana bilgisayarın bağlantı noktası numarası. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) yöntemi


Belirtilen uzak uç noktasına bir bağlantı kurar.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Uzak ana bilgisayarın IP adresleri. |
| port | **int32_t** | Uzak ana bilgisayarın bağlantı noktası numarası. |

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* sınıf [EndPoint](../../../system.net/endpoint/)
* sınıf [Socket](../)
* sınıf [IPAddress](../../../system.net/ipaddress/)
* sınıf [String](../../../system/string/)
* ad alanı [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)