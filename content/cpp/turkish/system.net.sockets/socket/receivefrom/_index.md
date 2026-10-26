---
title: ReceiveFrom()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.
type: docs
weight: 690
url: /tr/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden offset. |
| size | **int32_t** | Alınacak bayt sayısı; bu baytlar 'offset' indeksinden itibaren belirtilen bayt dizisine atanır. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden offset. |
| size | **int32_t** | Alınacak bayt sayısı; bu baytlar 'offset' indeksinden itibaren belirtilen bayt dizisine atanır. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Alınan verilerin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden offset. |
| size | **int32_t** | Alınacak bayt sayısı; bu baytlar 'offset' indeksinden itibaren belirtilen bayt dizisine atanır. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| size | **int32_t** | Alınacak bayt sayısı; bu baytlar 'offset' indeksinden itibaren belirtilen bayt dizisine atanır. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| size | **int32_t** | Alınacak bayt sayısı; bu baytlar 'offset' indeksinden itibaren belirtilen bayt dizisine atanır. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Alınan verilerin atanacağı bayt dizisi. |
| size | **int32_t** | Alınacak bayt sayısı; bu baytlar 'offset' indeksinden itibaren belirtilen bayt dizisine atanır. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Alınan verilerin atanacağı bayt dizisi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) metodu


Belirtilen uç noktadan verileri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Alınan verilerin atanacağı bayt dizisi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Uzak uç nokta. |

### Dönüş Değeri

Alınan bayt sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)