---
title: Send()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengirim data yang ditentukan ke soket.
type: docs
weight: 638
url: /id/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data yang akan dikirim. |
| size | **int32_t** | Jumlah byte dari data yang ditentukan yang harus dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data yang akan dikirim. |
| size | **int32_t** | Jumlah byte dari data yang ditentukan yang harus dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metode


Mengirim data yang ditentukan ke soket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data yang akan dikirim. |
| size | **int32_t** | Jumlah byte dari data yang ditentukan yang harus dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data yang akan dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data yang akan dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metode


Mengirim data yang ditentukan ke soket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data yang akan dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::ArrayPtr\<uint8_t\>) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data yang akan dikirim. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data yang akan dikirim. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) metode


Mengirim data yang ditentukan ke soket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data yang akan dikirim. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Sekumpulan array byte dari mana data harus dikirim. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Sekumpulan array byte dari mana data harus dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Sekumpulan array byte dari mana data harus dikirim. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| errorCode | [SocketError](../../socketerror/)\& | Parameter keluaran tempat kode kesalahan akan ditetapkan ketika operasi pengiriman gagal. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data yang akan dikirim. |
| offset | **int32_t** | Ofset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan dimulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data yang akan dikirim. |
| offset | **int32_t** | Ofset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan dimulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metode


Mengirim data yang ditentukan ke soket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data yang akan dikirim. |
| offset | **int32_t** | Ofset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan dimulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data yang akan dikirim. |
| offset | **int32_t** | Ofset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan dimulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| errorCode | [SocketError](../../socketerror/)\& | Parameter keluaran tempat kode kesalahan akan ditetapkan ketika operasi pengiriman gagal. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metode


Mengirim data yang ditentukan ke soket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Data yang akan dikirim. |
| offset | **int32_t** | Ofset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan dimulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| errorCode | [SocketError](../../socketerror/)\& | Parameter keluaran tempat kode kesalahan akan ditetapkan ketika operasi pengiriman gagal. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metode


Mengirim data yang ditentukan ke soket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Data yang akan dikirim. |
| offset | **int32_t** | Ofset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah byte dalam array yang ditentukan dimulai dari parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku pengiriman. |
| errorCode | [SocketError](../../socketerror/)\& | Parameter keluaran tempat kode kesalahan akan ditetapkan ketika operasi pengiriman gagal. |

### Nilai Kembali

Jumlah byte yang terkirim.

## Lihat Juga

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Socket](../)
* Kelas [IList](../../../system.collections.generic/ilist/)
* Kelas [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)