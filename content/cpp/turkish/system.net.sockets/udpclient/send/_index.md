---
title: Send()
second_title: Aspose.Slides for C++ API Referansı
description: Uzak uç noktadaki ana bilgisayara bir UDP datagramı gönderir.
type: docs
weight: 79
url: /tr/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) metod

Uzaktaki uç noktadaki ana bilgisayara bir UDP datagramı gönderir.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek [Byte](../../../system/byte/) tipinde bir dizi |
| bytes | **int32_t** | Datagramdaki bayt sayısı |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | [IPEndPoint](../../../system.net/ipendpoint/) tipinde bir nesne, datagramı gönderecek ana bilgisayar ve bağlantı noktasını temsil eder |

### Dönüş Değeri

Gönderilen bayt sayısı.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) metod

Belirtilen uzak ana bilgisayardaki belirtilen bağlantı noktasına bir UDP datagramı gönderir.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek [Byte](../../../system/byte/) tipinde bir dizi |
| bytes | **int32_t** | Datagramdaki bayt sayısı |
| hostname | [String](../../../system/string/) | Uzak ana bilgisayarın adı |
| port | **int32_t** | Uzak bir bağlantı noktası numarası |

### Dönüş Değeri

Gönderilen bayt sayısı.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) metod

Uzak bir ana bilgisayara bir UDP datagramı gönderir.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek [Byte](../../../system/byte/) tipinde bir dizi |
| bytes | **int32_t** | Datagramdaki bayt sayısı |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPEndPoint](../../../system.net/ipendpoint/)
* Sınıf [UdpClient](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)