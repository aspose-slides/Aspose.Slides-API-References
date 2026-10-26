---
title: Index
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili indeks ke dalam koleksi. Indeks dapat berasal dari awal atau dari akhir. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi secara nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 1015
url: /id/system/index/
---
## Index kelas


Mewakili indeks ke dalam koleksi. Indeks dapat berasal dari awal atau dari akhir. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi secara nilai atau referensi. Jangan pernah gunakan kelas [System::SmartPtr](../smartptr/) untuk mengelola objek tipe ini.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Menentukan apakah instance saat ini dan [Index](./) yang ditentukan mewakili posisi yang sama. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Membuat [Index](./) yang relatif terhadap akhir koleksi. |
| static constexpr [Index](./) [get_End](./get_end/)() | Mendapatkan objek [Index](./) yang mewakili akhir suatu koleksi. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Mendapatkan nilai yang menunjukkan apakah indeks berasal dari akhir. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Mendapatkan objek [Index](./) yang mewakili awal suatu koleksi. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Mendapatkan nilai indeks. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk indeks saat ini. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Mengonversi [Index](./) saat ini menjadi offset dari awal koleksi dengan panjang yang ditentukan. |
| constexpr [Index](./index/)() | Membuat instance yang mewakili awal suatu koleksi. |
| constexpr [Index](./index/)(**int32_t**) | Membuat instance yang mewakili posisi yang ditentukan dari awal koleksi. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Membuat instance yang mewakili indeks yang ditentukan. |

## Lihat Juga

* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)