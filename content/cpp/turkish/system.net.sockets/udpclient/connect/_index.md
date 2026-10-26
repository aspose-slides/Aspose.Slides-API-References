---
title: Connect()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ana bilgisayarda belirtilen bağlantı noktasına bir bağlantı kurar.
type: docs
weight: 66
url: /tr/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) metodu

Belirtilen ana bilgisayarda belirtilen bağlantı noktasına bir bağlantı kurar.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Bağlanmak istediğiniz uzak DNS ana bilgisayarının adı. |
| port | **int32_t** | İletişim kurmak istediğiniz yerel bağlantı noktası numarası. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metodu

Belirtilen adresteki ana bilgisayara belirtilen bağlantı noktasında bir bağlantı kurar.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Veri gönderilecek uzak ana bilgisayarın [IPAddress](../../../system.net/ipaddress/)'ı. |
| port | **int32_t** | İletişim kurmak istediğiniz yerel bağlantı noktası numarası. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) metodu

Uzak bir uç noktaya bağlantı kurar.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | UDP bağlantısını bağlayacağınız uç nokta. |

## Diğer Bölümler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)