---
title: Range
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili rentang dengan indeks mulai dan akhir. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 1197
url: /id/system/range/
---
## Range kelas

Mewakili rentang dengan indeks mulai dan akhir. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan [System::SmartPtr](../smartptr/) kelas untuk mengelola objek tipe ini.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Membuat rentang yang dimulai dari awal koleksi dan berakhir pada indeks akhir yang ditentukan. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Menentukan apakah rentang saat ini sama dengan rentang yang ditentukan. |
| static constexpr [Range](./) [get_All](./get_all/)() | Mengembalikan sebuah [Range](./) yang mewakili seluruh koleksi. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Mendapatkan indeks End. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Mendapatkan indeks Start. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk rentang saat ini. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Menghitung offset awal berbasis nol dan panjang untuk panjang koleksi yang ditentukan. |
| constexpr [Range](./range/)() | Membuat rentang kosong. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Membuat sebuah [Range](./) dari indeks awal dan akhir yang ditentukan. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Membuat rentang yang dimulai pada indeks awal yang ditentukan dan berlanjut hingga akhir koleksi. |

## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)