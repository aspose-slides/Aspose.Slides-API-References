---
title: Point
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili pasangan koordinat X dan Y integer dari sebuah titik pada bidang 2-dimensional. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau dengan referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek dari tipe ini."
type: docs
weight: 209
url: /id/system.drawing/point/
---
## Point kelas

Mewakili pasangan koordinat X dan Y integer dari sebuah titik pada bidang 2-dimensi. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau dengan referensi. Jangan pernah menggunakan kelas [System::SmartPtr](../../system/smartptr/) untuk mengelola objek dari tipe ini.

```cpp
class Point
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | Menambahkan nilai lebar dan tinggi dari objek [Size](../size/) yang ditentukan ke nilai koordinat X dan Y dari objek [Point](./) yang ditentukan secara bersamaan. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Membuat objek [Point](./) dari objek [PointF](../pointf/) yang ditentukan dengan membulatkan nilai koordinat X dan Y objek [PointF](../pointf/) ke nilai bilangan bulat lebih tinggi berikutnya. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Menentukan apakah objek saat ini dan objek yang ditentukan sama, yaitu mewakili pasangan nilai koordinat X dan Y yang sama. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Menentukan apakah kedua nilai koordinat X dan Y sama dengan 0. |
| int [get_X](./get_x/)() const | Mengembalikan nilai koordinat X yang diwakili oleh objek saat ini. |
| int [get_Y](./get_y/)() const | Mengembalikan nilai koordinat Y yang diwakili oleh objek saat ini. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash untuk objek saat ini. |
| size_t [getStdHash](./getstdhash/)() const | Mengembalikan nilai hash untuk objek saat ini. |
| **bool** [IsNull](./isnull/)() const | Selalu mengembalikan false. |
| void [Offset](./offset/)(int, int) | Menggeser nilai koordinat X dan Y yang diwakili oleh objek saat ini dengan nilai yang ditentukan. |
| void [Offset](./offset/)([Point](./)) | Menggeser koordinat X dan Y yang diwakili oleh objek saat ini dengan nilai koordinat X dan Y yang diwakili oleh objek [Point](./) yang ditentukan secara bersamaan. |
| [operator PointF](./operator_pointf/)() const | Membuat instance objek [PointF](../pointf/) dan menginisialisasinya dengan nilai koordinat X dan Y dari objek [Point](./) saat ini. |
| [operator Size](./operator_size/)() const | Membuat instance objek [Size](../size/) dan menginisialisasi nilai lebar dan tingginya dengan nilai koordinat X dan Y yang diwakili oleh objek saat ini secara bersamaan. |
| [Point](./point/)() | Membuat objek [Point](./) baru dan menginisialisasi nilai koordinat X dan Y-nya dengan 0. |
| [Point](./point/)(int, int) | Membuat objek [Point](./) baru dan menginisialisasinya dengan nilai yang ditentukan. |
| [Point](./point/)(const [Size](../size/)\&) | Membuat objek [Point](./) baru dan menginisialisasi nilai koordinat X dan Y-nya dengan nilai lebar dan tinggi dari objek [SizeF](../sizef/) yang ditentukan secara bersamaan. |
| [Point](./point/)(int) | Membuat objek [Point](./) baru dan menginisialisasi nilai koordinat X-nya dengan nilai yang dibentuk oleh 16 bit tinggi dari integer 32-bit yang ditentukan serta nilai koordinat Y-nya dengan nilai yang dibentuk oleh 16 bit rendah dari integer 32-bit yang ditentukan. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Membuat objek [Point](./) dari objek [PointF](../pointf/) yang ditentukan dengan membulatkan nilai koordinat X dan Y objek [PointF](../pointf/) ke nilai bilangan bulat terdekat. |
| void [set_X](./set_x/)(int) | Mengatur nilai koordinat X yang diwakili oleh objek saat ini. |
| void [set_Y](./set_y/)(int) | Mengatur nilai koordinat Y yang diwakili oleh objek saat ini. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | Mengurangi nilai lebar dan tinggi dari objek [Size](../size/) yang ditentukan dari nilai koordinat X dan Y objek [Point](./) yang ditentukan secara bersamaan. |
| [String](../../system/string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari pasangan nilai koordinat X dan Y yang diwakili oleh objek saat ini. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Membuat objek [Point](./) dari objek [PointF](../pointf/) yang ditentukan dengan memotong nilai koordinat X dan Y objek [PointF](../pointf/) ke nilai bilangan bulat lebih rendah berikutnya. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Empty](./empty/) | Sebuah instance kosong dari kelas [Point](./) yang nilai koordinat X dan Y-nya adalah 0. |

## Lihat Juga

* Namespace [System::Drawing](../)
* Perpustakaan [Aspose.Slides](../../)