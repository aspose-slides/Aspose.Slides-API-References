---
title: TcpListener()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir örnek oluşturur.
type: docs
weight: 53
url: /tr/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) constructor

Yeni bir örnek oluşturur.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Dinleyici soketinin bağlanması gereken yerel uç nokta. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) constructor

Yeni bir örnek oluşturur.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Yerel IP adresi. |
| port | **int32_t** | Dinlenecek bir bağlantı noktası numarası. |

## TcpListener::TcpListener(int32_t) constructor

Yeni bir örnek oluşturur.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| port | **int32_t** | Dinlenecek bir bağlantı noktası numarası. |

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPEndPoint](../../../system.net/ipendpoint/)
* Sınıf [TcpListener](../)
* Sınıf [IPAddress](../../../system.net/ipaddress/)
* AdAlanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)