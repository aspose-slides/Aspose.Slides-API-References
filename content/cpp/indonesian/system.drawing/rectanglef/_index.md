---
title: RectangleF
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili area persegi panjang dari sebuah gambar yang didefinisikan sebagai koordinat X dan Y bertipe floating point presisi tunggal dari sudut kiri atas serta lebar dan tingginya. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek dari tipe ini."
type: docs
weight: 248
url: /id/system.drawing/rectanglef/
---
## RectangleF kelas

Mewakili area persegi panjang dari sebuah gambar yang didefinisikan sebagai koordinat X dan Y bertipe floating point presisi tunggal dari sudut kiri atas serta lebar dan tinggi nya. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan [System::SmartPtr](../../system/smartptr/) kelas untuk mengelola objek dari tipe ini.

```cpp
class RectangleF
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Menentukan apakah titik yang ditentukan berada di dalam persegi panjang yang diwakili oleh objek saat ini. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Menentukan apakah titik yang ditentukan berada di dalam persegi panjang yang diwakili oleh objek saat ini. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Menentukan apakah persegi panjang yang ditentukan berada di dalam persegi panjang yang diwakili oleh objek saat ini. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Menentukan apakah persegi panjang yang diwakili oleh objek saat ini dan objek yang ditentukan identik. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Membuat objek [RectangleF](./) baru yang mewakili persegi panjang dengan lokasi tepi yang ditentukan. |
| **float** [get_Bottom](./get_bottom/)() const | Mengembalikan koordinat y dari tepi bawah persegi panjang yang diwakili oleh objek saat ini. |
| **float** [get_Height](./get_height/)() const | Mengembalikan tinggi persegi panjang yang diwakili oleh objek saat ini. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Menentukan apakah koordinat X dan Y dari sudut kiri atas persegi panjang yang diwakili oleh objek saat ini serta lebar dan tingginya memiliki nilai 0. |
| **float** [get_Left](./get_left/)() const | Mengembalikan koordinat X dari tepi kiri persegi panjang yang diwakili oleh objek saat ini. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Mengembalikan sebuah instance dari kelas [PointF](../pointf/) yang menentukan lokasi sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| **float** [get_Right](./get_right/)() const | Mengembalikan koordinat X dari tepi kanan persegi panjang yang diwakili oleh objek saat ini. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Mengembalikan sebuah instance dari kelas [SizeF](../sizef/) yang menentukan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini. |
| **float** [get_Top](./get_top/)() const | Mengembalikan koordinat Y dari tepi atas persegi panjang yang diwakili oleh objek saat ini. |
| **float** [get_Width](./get_width/)() const | Mengembalikan lebar persegi panjang yang diwakili oleh objek saat ini. |
| **float** [get_X](./get_x/)() const | Mengembalikan koordinat X dari sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| **float** [get_Y](./get_y/)() const | Mengembalikan koordinat Y dari sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash dari objek saat ini. |
| void [Inflate](./inflate/)(**float**, **float**) | Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditambah pada kedua arah dengan jumlah yang ditentukan. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditambah pada kedua arah dengan jumlah yang ditentukan oleh nilai lebar dan tinggi dari objek ukuran yang ditentukan secara bersesuaian. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek yang ditentukan, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditambah pada kedua arah dengan jumlah yang ditentukan. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Mengganti persegi panjang yang diwakili oleh objek saat ini dengan persegi panjang yang merupakan hasil irisan dengan persegi panjang yang diwakili oleh objek yang ditentukan. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Mengembalikan persegi panjang yang merupakan hasil irisan dari persegi panjang yang ditentukan. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Menentukan apakah persegi panjang yang diwakili oleh objek saat ini dan objek yang ditentukan beririsan. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Menggeser posisi persegi panjang yang diwakili oleh objek saat ini sebesar jumlah yang ditentukan. |
| void [Offset](./offset/)(**float**, **float**) | Menggeser posisi persegi panjang yang diwakili oleh objek saat ini sebesar jumlah yang ditentukan. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Selalu mengembalikan true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Selalu mengembalikan false. |
|  [RectangleF](./rectanglef/)() | Membuat sebuah instance baru dari objek [RectangleF](./) yang mewakili persegi panjang dengan koordinat X dan Y serta nilai lebar dan tinggi diatur ke 0. |
|  [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Membuat sebuah instance baru dari objek [RectangleF](./) yang mewakili persegi panjang dengan koordinat yang ditentukan dari sudut kiri atas serta lebar dan tinggi. |
|  [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Membuat sebuah instance baru dari objek [RectangleF](./) yang mewakili persegi panjang dengan koordinat sudut kiri atas yang ditentukan sebagai sebuah instance dari kelas [PointF](../pointf/) dan lebar serta tinggi sebagai sebuah instance dari kelas [SizeF](../sizef/). |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Membuat sebuah instance baru dari objek [RectangleF](./) yang mewakili persegi panjang yang setara dengan yang ditentukan. |
| void [set_Height](./set_height/)(**float**) | Mengatur tinggi persegi panjang yang diwakili oleh objek saat ini. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Mengatur lokasi sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Mengatur lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini. |
| void [set_Width](./set_width/)(**float**) | Mengatur lebar persegi panjang yang diwakili oleh objek saat ini. |
| void [set_X](./set_x/)(**float**) | Mengatur koordinat X dari sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| void [set_Y](./set_y/)(**float**) | Mengatur koordinat Y dari sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari objek saat ini. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Mengembalikan persegi panjang yang merupakan hasil gabungan dari persegi panjang yang ditentukan. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Empty](./empty/) | Sebuah persegi panjang kosong, yaitu persegi panjang yang nilai lokasi dan ukurannya adalah nol. |

## Lihat Juga

* Ruang nama [System::Drawing](../)
* Perpustakaan [Aspose.Slides](../../)