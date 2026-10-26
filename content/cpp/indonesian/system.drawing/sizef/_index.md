---
title: SizeF
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili pasangan nilai floating point presisi tunggal yang mewakili lebar dan tinggi sebuah gambar. Tipe ini harus dialokasikan di stack dan diteruskan ke fungsi dengan nilai atau dengan referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 287
url: /id/system.drawing/sizef/
---
## SizeF kelas

Mewakili pasangan nilai floating point presisi tunggal yang mewakili lebar dan tinggi sebuah gambar. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau dengan referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../../system/smartptr/) untuk mengelola objek tipe ini.

```cpp
class SizeF
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Mengembalikan objek [SizeF](./) baru yang merupakan hasil penjumlahan objek [SizeF](./) yang ditentukan, yaitu nilai lebar yang sama dengan jumlah nilai lebar objek yang ditentukan dan nilai tinggi yang sama dengan jumlah nilai tinggi objek yang ditentukan. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Menentukan apakah objek saat ini dan objek yang ditentukan sama, yaitu mewakili pasangan nilai lebar dan tinggi yang sama. |
| **float** [get_Height](./get_height/)() const | Mengembalikan nilai tinggi yang diwakili oleh objek saat ini. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Menentukan apakah nilai lebar dan tinggi keduanya sama dengan 0. |
| **float** [get_Width](./get_width/)() const | Mengembalikan nilai lebar yang diwakili oleh objek saat ini. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
| [operator PointF](./operator_pointf/)() const | Mengonversi objek saat ini menjadi sebuah instance objek [Point](../point/) dengan menginisialisasi koordinat X dan Y-nya menggunakan nilai lebar dan tinggi objek saat ini secara berurutan. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Menambahkan nilai lebar dan tinggi objek [SizeF](./) yang ditentukan ke nilai lebar dan tinggi objek [SizeF](./) saat ini secara berurutan. |
| void [set_Height](./set_height/)(**float**) | Mengatur nilai tinggi yang diwakili oleh objek saat ini. |
| void [set_Width](./set_width/)(**float**) | Mengatur nilai lebar yang diwakili oleh objek saat ini. |
| [SizeF](./sizef/)() | Membuat objek [SizeF](./) baru dan menginisialisasi nilai lebar dan tingginya dengan 0. |
| [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Membuat objek [SizeF](./) baru dan menginisialisasi nilai lebar dan tinggi dengan nilai koordinat X dan Y dari titik yang ditentukan secara berurutan. |
| [SizeF](./sizef/)(**float**, **float**) | Membuat objek [SizeF](./) baru dan menginisialisasinya dengan nilai yang ditentukan. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Mengembalikan objek [SizeF](./) baru yang merupakan hasil pengurangan **size2** dari **size1**, yaitu nilai lebar yang merupakan hasil pengurangan nilai lebar **size2** dari nilai lebar **size1** dan nilai tinggi yang merupakan hasil pengurangan nilai tinggi **size2** dari nilai tinggi **size1**. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Mengonversi objek saat ini menjadi sebuah instance objek [Point](../point/) dengan menginisialisasi koordinat X dan Y-nya menggunakan nilai lebar dan tinggi objek saat ini secara berurutan. |
| [Size](../size/) [ToSize](./tosize/)() const | Membuat objek [Size](../size/) dari objek [SizeF](./) saat ini dengan memotong nilai lebar dan tinggi objek [SizeF](./) ke nilai integer terdekat yang lebih rendah. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari pasangan nilai lebar dan tinggi yang diwakili oleh objek saat ini. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Empty](./empty/) | Instansi kosong dari kelas [SizeF](./) yang nilai lebar dan tingginya adalah 0. |

## Lihat Juga

* ruang nama [System::Drawing](../)
* Perpustakaan [Aspose.Slides](../../)