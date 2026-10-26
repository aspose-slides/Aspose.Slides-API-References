---
title: Size
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili pasangan nilai integer yang mewakili lebar dan tinggi sebuah gambar. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau dengan referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 274
url: /id/system.drawing/size/
---
## Ukuran kelas

Mewakili pasangan nilai integer yang mewakili lebar dan tinggi sebuah gambar. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau dengan referensi. Jangan pernah menggunakan [System::SmartPtr](../../system/smartptr/) kelas untuk mengelola objek tipe ini.

```cpp
class Size
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Mengembalikan objek [Size](./) baru yang merupakan penjumlahan dari objek [Size](./) yang ditentukan, yaitu nilai lebar sama dengan jumlah nilai lebar objek yang ditentukan dan nilai tinggi sama dengan jumlah nilai tinggi objek yang ditentukan. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Membuat objek [Size](./) dari objek [SizeF](../sizef/) yang ditentukan dengan membulatkan nilai lebar dan tinggi objek [SizeF](../sizef/) ke nilai bilangan bulat berikutnya yang lebih tinggi. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Menentukan apakah objek saat ini dan objek yang ditentukan sama, yaitu mewakili pasangan nilai lebar dan tinggi yang sama. |
| int [get_Height](./get_height/)() const | Mengembalikan nilai tinggi yang diwakili oleh objek saat ini. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Menentukan apakah nilai lebar dan tinggi keduanya sama dengan 0. |
| int [get_Width](./get_width/)() const | Mengembalikan nilai lebar yang diwakili oleh objek saat ini. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
| [operator Point](./operator_point/)() const | Membuat instance objek [Point](../point/) dan menginisialisasi koordinat X dan Y-nya dengan nilai lebar dan tinggi objek saat ini secara berurutan. |
| [operator SizeF](./operator_sizef/)() const | Membuat instance objek [SizeF](../sizef/) dan menginisialisasinya dengan nilai lebar dan tinggi dari objek [Size](./) saat ini. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Membuat objek [Size](./) dari objek [SizeF](../sizef/) yang ditentukan dengan membulatkan nilai lebar dan tinggi objek [SizeF](../sizef/) ke nilai bulat terdekat. |
| void [set_Height](./set_height/)(int) | Mengatur nilai tinggi yang diwakili oleh objek saat ini. |
| void [set_Width](./set_width/)(int) | Mengatur nilai lebar yang diwakili oleh objek saat ini. |
| [Size](./size/)() | Membuat objek [Size](./) baru dan menginisialisasi nilai lebar dan tingginya dengan 0. |
| [Size](./size/)(const [Point](../point/)\&) | Membuat objek [Size](./) baru dan menginisialisasi nilai lebar dan tingginya dengan nilai koordinat X dan Y dari titik yang ditentukan secara berurutan. |
| [Size](./size/)(int, int) | Membuat objek [Size](./) baru dan menginisialisasinya dengan nilai yang ditentukan. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Mengembalikan objek [Size](./) baru yang merupakan hasil pengurangan **size2** dari **size1**, yaitu nilai lebar adalah hasil pengurangan nilai lebar **size2** dari nilai lebar **size1**, dan nilai tinggi adalah hasil pengurangan nilai tinggi **size2** dari nilai tinggi **size1**. |
| [String](../../system/string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari pasangan nilai lebar dan tinggi yang diwakili oleh objek saat ini. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Membuat objek [Size](./) dari objek [SizeF](../sizef/) yang ditentukan dengan memotong nilai lebar dan tinggi objek [SizeF](../sizef/) ke nilai bilangan bulat berikutnya yang lebih rendah. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Empty](./empty/) | Instansi kosong dari [Size](./) kelas yang nilai lebar dan tingginya adalah 0. |

## Lihat Juga

* Ruang nama [System::Drawing](../)
* Perpustakaan [Aspose.Slides](../../)