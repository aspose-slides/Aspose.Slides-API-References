---
title: PointF
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili pasangan koordinat X dan Y dengan titik mengambang presisi tunggal pada bidang dua dimensi. Tipe ini harus dialokasikan pada stack dan dilewatkan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek dari tipe ini."
type: docs
weight: 222
url: /id/system.drawing/pointf/
---
## PointF kelas

Mewakili pasangan koordinat X dan Y dengan titik mengambang presisi tunggal pada bidang dua dimensi. Tipe ini harus dialokasikan pada stack dan dilewatkan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../../system/smartptr/) untuk mengelola objek dari tipe ini.

```cpp
class PointF
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Menambahkan nilai lebar dan tinggi dari objek [SizeF](../sizef/) yang ditentukan ke nilai koordinat X dan Y dari objek [PointF](./) yang ditentukan secara berkorespondensi. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Menambahkan nilai lebar dan tinggi dari objek [Size](../size/) yang ditentukan ke nilai koordinat X dan Y dari objek [PointF](./) yang ditentukan secara berkorespondensi. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Menentukan apakah objek saat ini dan objek yang ditentukan sama, yaitu mewakili pasangan nilai koordinat X dan Y yang sama. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Menentukan apakah kedua nilai koordinat X dan Y sama dengan 0. |
| **float** [get_X](./get_x/)() const | Mengembalikan nilai koordinat X yang diwakili oleh objek saat ini. |
| **float** [get_Y](./get_y/)() const | Mengembalikan nilai koordinat Y yang diwakili oleh objek saat ini. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
| **bool** [IsNull](./isnull/)() const | Selalu mengembalikan false. |
| explicit  [operator bool](./operator_bool/)() | Selalu mengembalikan true. |
|  [PointF](./pointf/)() | Membuat objek [PointF](./) baru dan menginisialisasi nilai koordinat X dan Y-nya dengan 0. |
|  [PointF](./pointf/)(**float**, **float**) | Membuat objek [PointF](./) baru dan menginisialisasinya dengan nilai yang ditentukan. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Membuat objek [PointF](./) baru dan menginisialisasi nilai koordinat X dan Y-nya dengan nilai lebar dan tinggi dari objek [SizeF](../sizef/) yang ditentukan secara berkorespondensi. |
| void [set_X](./set_x/)(**float**) | Mengatur nilai koordinat X yang diwakili oleh objek saat ini. |
| void [set_Y](./set_y/)(**float**) | Mengatur nilai koordinat Y yang diwakili oleh objek saat ini. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Mengurangkan nilai lebar dan tinggi dari objek [SizeF](../sizef/) yang ditentukan dari nilai koordinat X dan Y dari objek [PointF](./) yang ditentukan secara berkorespondensi. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Mengurangkan nilai lebar dan tinggi dari objek [Size](../size/) yang ditentukan dari nilai koordinat X dan Y dari objek [PointF](./) yang ditentukan secara berkorespondensi. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari pasangan nilai koordinat X dan Y yang diwakili oleh objek saat ini. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Empty](./empty/) | Instansi kosong dari kelas [PointF](./) yang nilai koordinat X dan Y-nya adalah 0. |

## Lihat Juga

* Ruang nama [System::Drawing](../)
* Perpustakaan [Aspose.Slides](../../)