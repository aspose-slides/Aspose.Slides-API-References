---
title: MemoryStream()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat instance baru dari kelas MemoryStream dengan kapasitas awal sebesar 0.
type: docs
weight: 1
url: /id/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() konstruktor


Membuat instance baru dari kelas [MemoryStream](../) dengan kapasitas awal sebesar 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) konstruktor


Membuat instance baru dari kelas [MemoryStream](../) yang mewakili aliran berbasis buffer memori dengan ukuran yang ditentukan.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| capacity_ | int | Ukuran dalam byte dari buffer memori yang terkait dengan aliran yang diwakili oleh objek yang sedang dibuat |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) konstruktor


Membuat instance baru dari kelas [MemoryStream](../) yang mewakili aliran memori yang terhubung ke buffer memori yang ditentukan. Sebuah parameter menentukan apakah aliran dapat ditulis.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte yang akan digunakan sebagai buffer memori yang menjadi dasar aliran yang diwakili oleh objek yang sedang dibuat |
| writable | **bool** | Menentukan apakah aliran harus dapat ditulis |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) konstruktor


Membuat instance baru dari kelas [MemoryStream](../) yang mewakili aliran memori yang terhubung ke segmen buffer memori yang ditentukan, dimulai pada indeks yang ditentukan dan mencakup jumlah elemen yang ditentukan. Parameter menentukan apakah aliran dapat ditulis dan apakah metode GetBytes() dapat dipanggil.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte, segmen mana yang akan digunakan sebagai buffer memori yang menjadi dasar aliran yang diwakili oleh objek yang sedang dibuat |
| index | int | Indeks berbasis 0 dari elemen dalam **content** dimana segmen dimulai |
| count | int | Jumlah elemen **content** yang termasuk dalam segmen |
| writable | **bool** | Menentukan apakah aliran harus dapat ditulis |
| publiclyVisible | **bool** | Menentukan apakah buffer memori yang mendasari harus tersedia bagi pemanggil metode GetByte() |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [MemoryStream](../)
* Ruang nama [System::IO](../../)
* Perpustakaan [Aspose.Slides](../../../)