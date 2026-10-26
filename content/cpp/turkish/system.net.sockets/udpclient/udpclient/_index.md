---
title: UdpClient()
second_title: Aspose.Slides for C++ API Referansı
description: UdpClient sınıfının yeni bir örneğini başlatır.
type: docs
weight: 27
url: /tr/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() yapıcı

Yeni bir [UdpClient](../) sınıfı örneği başlatır.

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) yapıcı

Yeni bir [UdpClient](../) sınıfı örneği başlatır.

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | soketin adresleme şemasını belirten değer. |

## UdpClient::UdpClient(int32_t) yapıcı

Yeni bir [UdpClient](../) sınıfı örneği başlatır.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| port | **int32_t** | iletişim kurmak istediğiniz yerel bağlantı noktası numarası. |

## UdpClient::UdpClient(int32_t, AddressFamily) yapıcı

Yeni bir [UdpClient](../) sınıfı örneği başlatır.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| port | **int32_t** | iletişim kurmak istediğiniz yerel bağlantı noktası numarası. |
| family | [AddressFamily](../../addressfamily/) | soketin adresleme şemasını belirten değer. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) yapıcı

Yeni bir [UdpClient](../) sınıfı örneği başlatır. param local EP UDP bağlantısını bağladığınız yerel uç nokta.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) yapıcı

Belirtilen portta belirtilen uzak ana bilgisayara bağlanarak yeni bir [UdpClient](../) sınıfı örneği oluşturur.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Bağlanmak istediğiniz uzak DNS ana bilgisayarının adı. |
| port | **int32_t** | iletişim kurmak istediğiniz yerel bağlantı noktası numarası. |

## Diğer Bağlantılar

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [UdpClient](../)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)