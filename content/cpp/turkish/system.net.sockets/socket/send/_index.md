---
title: Send()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen veriyi sokete gönderir.
type: docs
weight: 638
url: /tr/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek veri. |
| size | **int32_t** | Belirtilen veriden gönderilmesi gereken bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Gönderilecek veri. |
| size | **int32_t** | Belirtilen veriden gönderilmesi gereken bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metodu


Belirtilen veriyi sokete gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Gönderilecek veri. |
| size | **int32_t** | Belirtilen veriden gönderilmesi gereken bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek veri. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Gönderilecek veri. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metodu


Belirtilen veriyi sokete gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Gönderilecek veri. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::ArrayPtr\<uint8_t\>) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek veri. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Gönderilecek veri. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) metodu


Belirtilen veriyi sokete gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Gönderilecek veri. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Verinin gönderileceği bayt dizileri koleksiyonu. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Verinin gönderileceği bayt dizileri koleksiyonu. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Verinin gönderileceği bayt dizileri koleksiyonu. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| errorCode | [SocketError](../../socketerror/)\& | Gönderme işlemi başarısız olduğunda hata kodunun atanacağı çıktı parametresi. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek veri. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden ofset. |
| size | **int32_t** | 'offset' parametresinden itibaren belirtilen dizideki bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Gönderilecek veri. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden ofset. |
| size | **int32_t** | 'offset' parametresinden itibaren belirtilen dizideki bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metodu


Belirtilen veriyi sokete gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Gönderilecek veri. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden ofset. |
| size | **int32_t** | 'offset' parametresinden itibaren belirtilen dizideki bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Gönderilecek veri. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden ofset. |
| size | **int32_t** | 'offset' parametresinden itibaren belirtilen dizideki bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| errorCode | [SocketError](../../socketerror/)\& | Gönderme işlemi başarısız olduğunda hata kodunun atanacağı çıktı parametresi. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metodu


Belirtilen veriyi sokete gönderir.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Gönderilecek veri. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden ofset. |
| size | **int32_t** | 'offset' parametresinden itibaren belirtilen dizideki bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| errorCode | [SocketError](../../socketerror/)\& | Gönderme işlemi başarısız olduğunda hata kodunun atanacağı çıktı parametresi. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metodu


Belirtilen veriyi sokete gönderir.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Gönderilecek veri. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden ofset. |
| size | **int32_t** | 'offset' parametresinden itibaren belirtilen dizideki bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderme davranışı. |
| errorCode | [SocketError](../../socketerror/)\& | Gönderme işlemi başarısız olduğunda hata kodunun atanacağı çıktı parametresi. |

### Dönüş Değeri

Gönderilen bayt sayısı.

## İlgili

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Socket](../)
* Sınıf [IList](../../../system.collections.generic/ilist/)
* Sınıf [ArraySegment](../../../system/arraysegment/)
* Ad alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)