---
title: ReceiveMessageFrom()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.
type: docs
weight: 677
url: /tr/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) yöntemi


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizideki bayt cinsinden ofset. |
| size | **int32_t** | Alınacak ve 'offset' dizininden belirtilen bayt dizisine atanacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Pakete ilişkin bilgilerin atanacağı çıktı parametresi. |

### Dönüş Değeri

Alınan baytların sayısı.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) yöntemi


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizideki bayt cinsinden ofset. |
| size | **int32_t** | Alınacak ve 'offset' dizininden belirtilen bayt dizisine atanacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Pakete ilişkin bilgilerin atanacağı çıktı parametresi. |

### Dönüş Değeri

Alınan baytların sayısı.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) yöntemi


Belirtilen uç noktadan veri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Alınan verilerin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizideki bayt cinsinden ofset. |
| size | **int32_t** | Alınacak ve 'offset' dizininden belirtilen bayt dizisine atanacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Pakete ilişkin bilgilerin atanacağı çıktı parametresi. |

### Dönüş Değeri

Alınan baytların sayısı.

## İlgili

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [EndPoint](../../../system.net/endpoint/)
* Sınıf [IPPacketInformation](../../ippacketinformation/)
* Sınıf [Socket](../)
* Ad alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)