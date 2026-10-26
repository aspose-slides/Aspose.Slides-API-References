---
title: SendTo()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen veriyi belirtilen uç noktaya gönderir.
type: docs
weight: 651
url: /tr/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek veri. |
| offset | **int32_t** | Belirtilen dizideki bayt cinsinden kayma. |
| size | **int32_t** | Belirtilen dizideki bayt sayısı; 'offset' parametresinden başlayarak. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Gönderilecek veri. |
| offset | **int32_t** | Belirtilen dizideki bayt cinsinden kayma. |
| size | **int32_t** | Belirtilen dizideki bayt sayısı; 'offset' parametresinden başlayarak. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Gönderilecek veri. |
| offset | **int32_t** | Belirtilen dizideki bayt cinsinden kayma. |
| size | **int32_t** | Belirtilen dizideki bayt sayısı; 'offset' parametresinden başlayarak. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek veri. |
| size | **int32_t** | Belirtilen dizideki bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Gönderilecek veri. |
| size | **int32_t** | Belirtilen dizideki bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Gönderilecek veri. |
| size | **int32_t** | Belirtilen dizideki bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek veri. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Gönderilecek veri. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Gönderilecek veri. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek veri. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Gönderilecek veri. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) metodu


Belirtilen veriyi belirtilen uç noktaya gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Gönderilecek veri. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)