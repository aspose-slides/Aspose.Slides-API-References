---
title: UnmanagedMemoryStream()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat instance baru dari UnmanagedMemoryStream.
type: docs
weight: 118
url: /id/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) konstruktor


Membuat instance baru dari [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pointer | **uint8_t** * | Pointer ke buffer yang tidak dikelola |
| length | **int64_t** | Ukuran buffer yang tidak dikelola dalam byte |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) konstruktor


Membuat instance baru dari [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pointer | **uint8_t** * | Pointer ke buffer yang tidak dikelola |
| length | **int64_t** | Ukuran buffer yang tidak dikelola dalam byte |
| capacity | **int64_t** | Jumlah total memori yang dialokasikan ke stream |
| access | [FileAccess](../../fileaccess/) | Menentukan apakah stream harus hanya-baca, hanya-tulis, atau keduanya |

## Lihat Juga

* Enum [FileAccess](../../fileaccess/)
* Kelas [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Perpustakaan [Aspose.Slides](../../../)