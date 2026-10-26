---
title: Receive()
second_title: Aspose.Slides for C++ API Referansı
description: Soketten veri alır ve belirtilen bayt dizisine yazar.
type: docs
weight: 664
url: /tr/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verinin atanacağı bayt dizisi. |
| size | **int32_t** | Alınacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Alınan verinin atanacağı bayt dizisi. |
| size | **int32_t** | Alınacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Alınan verinin atanacağı bayt dizisi. |
| size | **int32_t** | Alınacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verinin atanacağı bayt dizisi. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Alınan verinin atanacağı bayt dizisi. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Alınan verinin atanacağı bayt dizisi. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verinin atanacağı bayt dizisi. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Alınan verinin atanacağı bayt dizisi. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Alınan verinin atanacağı bayt dizisi. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verinin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt olarak ofset. |
| size | **int32_t** | 'offset' indisinden başlayarak belirtilen bayt dizisine atanacak alınacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Alınan verinin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt olarak ofset. |
| size | **int32_t** | 'offset' indisinden başlayarak belirtilen bayt dizisine atanacak alınacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Alınan verinin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt olarak ofset. |
| size | **int32_t** | 'offset' indisinden başlayarak belirtilen bayt dizisine atanacak alınacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verinin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt olarak ofset. |
| size | **int32_t** | 'offset' indisinden başlayarak belirtilen bayt dizisine atanacak alınacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| errorCode | [SocketError](../../socketerror/)\& | Alma işlemi başarısız olduğunda hata kodunun atanacağı çıktı parametresi. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Alınan verinin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt olarak ofset. |
| size | **int32_t** | 'offset' indisinden başlayarak belirtilen bayt dizisine atanacak alınacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| errorCode | [SocketError](../../socketerror/)\& | Alma işlemi başarısız olduğunda hata kodunun atanacağı çıktı parametresi. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metot


Soketten veri alır ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Alınan verinin atanacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt olarak ofset. |
| size | **int32_t** | 'offset' indisinden başlayarak belirtilen bayt dizisine atanacak alınacak bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| errorCode | [SocketError](../../socketerror/)\& | Alma işlemi başarısız olduğunda hata kodunun atanacağı çıktı parametresi. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metot


Soketten veri alır ve belirtilen bayt dizilerine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Alınan verinin atanacağı bayt dizileri. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metot


Soketten veri alır ve belirtilen bayt dizilerine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Alınan verinin atanacağı bayt dizileri. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metot


Soketten veri alır ve belirtilen bayt dizilerine yazar.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Alınan verinin atanacağı bayt dizileri. |
| socketFlags | [SocketFlags](../../socketflags/) | Alma davranışı. |
| errorCode | [SocketError](../../socketerror/)\& | Alma işlemi başarısız olduğunda hata kodunun atanacağı çıktı parametresi. |

### Dönüş Değeri

Alınan bayt sayısı.

## Ayrıca Bakınız

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)