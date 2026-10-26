---
title: Write()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis array byte yang ditentukan ke aliran.
type: docs
weight: 404
url: /id/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) metode


Menulis array byte yang ditentukan ke aliran.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte yang akan ditulis. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode


Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi byte yang akan ditulis |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** dimana subrentang yang akan ditulis dimulai |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) metode


Menulis array byte yang ditentukan ke aliran.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Array byte yang akan ditulis. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode


Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Array yang berisi byte yang akan ditulis |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** dimana subrentang yang akan ditulis dimulai |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)