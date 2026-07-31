---
title: BitVector32
second_title: Aspose.Slides untuk C++ Referensi API
description: Menyediakan vektor bit ringan sederhana dengan akses integer atau Boolean yang mudah ke penyimpanan 32 bit.
type: docs
weight: 1
url: /id/system.collections.specialized/bitvector32/
---
## BitVector32 kelas

Menyediakan vektor bit ringan sederhana dengan akses integer mudah atau [Boolean](../../system/boolean/) ke penyimpanan 32 bit.

```cpp
class BitVector32
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Menginisialisasi instance kosong baru dari [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Menginisialisasi sebuah instance baru dari struktur [BitVector32](./) dengan data internal yang ditentukan. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Menginisialisasi sebuah instance baru dari struktur [BitVector32](./) dengan informasi dalam nilai yang ditentukan. |
| static **int32_t** [CreateMask](./createmask/)() | Membuat mask pertama dalam rangkaian. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Membuat mask berikutnya dalam rangkaian. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Membuat bagian pertama dalam rangkaian, dengan nilai maksimum yang ditentukan. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Membuat bagian berikutnya dalam rangkaian, dengan nilai maksimum yang ditentukan. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Menentukan apakah objek yang ditentukan sama dengan yang saat ini. |
| **int32_t** [get_Data](./get_data/)() | mengembalikan data mentah yang disimpan dalam vektor bit ini... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Mendapatkan nilai yang menunjukkan apakah semua bit yang ditentukan telah diatur. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Mendapatkan nilai untuk bagian yang ditentukan. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Mengatur nilai yang menunjukkan apakah semua bit yang ditentukan telah diatur. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Mengatur nilai untuk bagian yang ditentukan. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Mengonversi nilai yang direpresentasikan oleh parameter nilai menjadi string. |
| [String](../../system/string/) [ToString](./tostring/)() const | Mengonversi nilai yang direpresentasikan oleh objek saat ini menjadi string. |

## Lihat Juga

* Ruang nama [System::Collections::Specialized](../)
* Pustaka [Aspose.Slides](../../)