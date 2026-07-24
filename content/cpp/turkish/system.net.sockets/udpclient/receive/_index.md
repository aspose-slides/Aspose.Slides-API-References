---
title: Receive()
second_title: Aspose.Slides için C++ API Referansı
description: Bir sunucu tarafından gönderilen bir datagramı döndürür.
type: docs
weight: 92
url: /tr/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) method

Bir sunucu tarafından gönderilen bir datagramı döndürür.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Alınan verinin gönderildiği uzak ana bilgisayarı temsil eden bir [IPEndPoint](../../../system.net/ipendpoint/). |

### Dönüş Değeri

Alınan verinin atanacağı bir bayt dizisi.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPEndPoint](../../../system.net/ipendpoint/)
* Sınıf [UdpClient](../)
* Ad alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)