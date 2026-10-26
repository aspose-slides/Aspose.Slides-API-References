---
title: Receive()
second_title: Referensi API Aspose.Slides untuk C++
description: Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.
type: docs
weight: 664
url: /id/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| size | **int32_t** | Jumlah byte yang akan diterima. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| size | **int32_t** | Jumlah byte yang akan diterima. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Array byte tempat data yang diterima akan ditempatkan. |
| size | **int32_t** | Jumlah byte yang akan diterima. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Array byte tempat data yang diterima akan ditempatkan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Array byte tempat data yang diterima akan ditempatkan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte di array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan ditempatkan ke array byte yang ditentukan mulai dari indeks ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte di array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan ditempatkan ke array byte yang ditentukan mulai dari indeks ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Array byte tempat data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte di array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan ditempatkan ke array byte yang ditentukan mulai dari indeks ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte di array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan ditempatkan ke array byte yang ditentukan mulai dari indeks ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| errorCode | [SocketError](../../socketerror/)\& | Parameter output tempat kode kesalahan akan ditempatkan ketika operasi penerimaan gagal. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Array byte tempat data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte di array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan ditempatkan ke array byte yang ditentukan mulai dari indeks ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| errorCode | [SocketError](../../socketerror/)\& | Parameter output tempat kode kesalahan akan ditempatkan ketika operasi penerimaan gagal. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Array byte tempat data yang diterima akan ditempatkan. |
| offset | **int32_t** | Offset dalam byte di array yang ditentukan. |
| size | **int32_t** | Jumlah byte yang akan diterima dan ditempatkan ke array byte yang ditentukan mulai dari indeks ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| errorCode | [SocketError](../../socketerror/)\& | Parameter output tempat kode kesalahan akan ditempatkan ketika operasi penerimaan gagal. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Array byte tempat data yang diterima akan ditempatkan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Array byte tempat data yang diterima akan ditempatkan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |

### Nilai Kembali

Jumlah byte yang diterima.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metode

Menerima data dari soket dan menuliskannya ke array byte yang ditentukan.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Array byte tempat data yang diterima akan ditempatkan. |
| socketFlags | [SocketFlags](../../socketflags/) | Perilaku penerimaan. |
| errorCode | [SocketError](../../socketerror/)\& | Parameter output tempat kode kesalahan akan ditempatkan ketika operasi penerimaan gagal. |

### Nilai Kembali

Jumlah byte yang diterima.

## Lihat Juga

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Socket](../)
* Kelas [IList](../../../system.collections.generic/ilist/)
* Kelas [ArraySegment](../../../system/arraysegment/)
* Ruang Nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)