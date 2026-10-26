---
title: Rectangle
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili area persegi panjang pada gambar yang didefinisikan sebagai koordinat X dan Y integer dari sudut kiri atas serta lebar dan tingginya. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 235
url: /id/system.drawing/rectangle/
---
## Kelas Rectangle

Mewakili area persegi panjang pada gambar yang didefinisikan sebagai koordinat X dan Y integer dari sudut kiri atasnya serta lebar dan tingginya. Tipe ini seharusnya dialokasikan di stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah gunakan [System::SmartPtr](../../system/smartptr/) kelas untuk mengelola objek tipe ini.

```cpp
class Rectangle
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Membuat objek [Rectangle](./) dari objek [RectangleF](../rectanglef/) yang ditentukan dengan membulatkan nilai lokasi dan ukuran objek [RectangleF](../rectanglef/) ke nilai integer berikutnya yang lebih tinggi. |
| **bool** [Contains](./contains/)(int, int) const | Menentukan apakah titik yang ditentukan berada di dalam persegi panjang yang diwakili oleh objek saat ini. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Menentukan apakah titik yang ditentukan berada di dalam persegi panjang yang diwakili oleh objek saat ini. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Menentukan apakah persegi panjang yang ditentukan berada di dalam persegi panjang yang diwakili oleh objek saat ini. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Menentukan apakah persegi panjang yang diwakili oleh objek saat ini dan objek yang ditentukan identik. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Membuat objek [Rectangle](./) baru yang mewakili persegi panjang dengan lokasi tepi yang ditentukan. |
| int [get_Bottom](./get_bottom/)() const | Mengembalikan koordinat y dari tepi bawah persegi panjang yang diwakili oleh objek saat ini. |
| int [get_Height](./get_height/)() const | Mengembalikan tinggi persegi panjang yang diwakili oleh objek saat ini. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Menentukan apakah koordinat X dan Y dari sudut kiri atas persegi panjang yang diwakili oleh objek saat ini serta lebar dan tingginya memiliki nilai 0. |
| int [get_Left](./get_left/)() const | Mengembalikan koordinat X dari tepi kiri persegi panjang yang diwakili oleh objek saat ini. |
| [Point](../point/) [get_Location](./get_location/)() const | Mengembalikan sebuah instance kelas [Point](../point/) yang menentukan lokasi sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| int [get_Right](./get_right/)() const | Mengembalikan koordinat X dari tepi kanan persegi panjang yang diwakili oleh objek saat ini. |
| [Size](../size/) [get_Size](./get_size/)() const | Mengembalikan sebuah instance kelas [Size](../size/) yang menentukan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini. |
| int [get_Top](./get_top/)() const | Mengembalikan koordinat Y dari tepi atas persegi panjang yang diwakili oleh objek saat ini. |
| int [get_Width](./get_width/)() const | Mengembalikan lebar persegi panjang yang diwakili oleh objek saat ini. |
| int [get_X](./get_x/)() const | Mengembalikan koordinat X dari sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| int [get_Y](./get_y/)() const | Mengembalikan koordinat Y dari sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash dari objek saat ini. |
| void [Inflate](./inflate/)(int, int) | Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditambah ke kedua arah dengan jumlah yang ditentukan. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditambah ke kedua arah dengan jumlah yang ditentukan oleh nilai lebar dan tinggi dari objek ukuran yang ditentukan secara bersesuaian. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek yang ditentukan, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditambah ke kedua arah dengan jumlah yang ditentukan. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Menggantikan persegi panjang yang diwakili oleh objek saat ini dengan persegi panjang yang merupakan hasil perpotongan dengan persegi panjang yang diwakili oleh objek yang ditentukan. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Mengembalikan persegi panjang yang merupakan hasil perpotongan dari persegi panjang yang ditentukan. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Menentukan apakah persegi panjang yang diwakili oleh objek saat ini dan objek yang ditentukan berpotongan. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Menggeser posisi persegi panjang yang diwakili oleh objek saat ini dengan jumlah yang ditentukan. |
| void [Offset](./offset/)(int, int) | Menggeser posisi persegi panjang yang diwakili oleh objek saat ini dengan jumlah yang ditentukan. |
| [operator RectangleF](./operator_rectanglef/)() const | Mengembalikan objek [RectangleF](../rectanglef/) yang mewakili persegi panjang yang setara dengan persegi panjang yang diwakili oleh objek saat ini. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Selalu mengembalikan true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Selalu mengembalikan false. |
| [Rectangle](./rectangle/)() | Membuat instance baru dari objek [Rectangle](./) yang mewakili persegi panjang dengan koordinat X dan Y serta nilai lebar dan tinggi diatur ke 0. |
| [Rectangle](./rectangle/)(int, int, int, int) | Membuat instance baru dari objek [Rectangle](./) yang mewakili persegi panjang dengan koordinat sudut kiri atas yang ditentukan serta lebar dan tinggi. |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Membuat instance baru dari objek [Rectangle](./) yang mewakili persegi panjang dengan koordinat sudut kiri atas yang ditentukan sebagai instance kelas [Point](../point/) dan lebar serta tingginya sebagai instance kelas [Size](../size/). |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Membuat instance baru dari objek [Rectangle](./) yang mewakili persegi panjang yang setara dengan yang ditentukan. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Membuat objek [Rectangle](./) dari objek [RectangleF](../rectanglef/) yang ditentukan dengan membulatkan nilai lokasi dan ukuran objek [RectangleF](../rectanglef/) ke nilai integer terdekat. |
| void [set_Height](./set_height/)(int) | Mengatur tinggi persegi panjang yang diwakili oleh objek saat ini. |
| void [set_Location](./set_location/)([Point](../point/)) | Mengatur lokasi sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| void [set_Size](./set_size/)([Size](../size/)) | Mengatur lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini. |
| void [set_Width](./set_width/)(int) | Mengatur lebar persegi panjang yang diwakili oleh objek saat ini. |
| void [set_X](./set_x/)(int) | Mengatur koordinat X sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| void [set_Y](./set_y/)(int) | Mengatur koordinat Y sudut kiri atas persegi panjang yang diwakili oleh objek saat ini. |
| [String](../../system/string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari objek saat ini. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Membuat objek [Rectangle](./) dari objek [RectangleF](../rectanglef/) yang ditentukan dengan memotong nilai lokasi dan ukuran objek [RectangleF](../rectanglef/) ke nilai integer berikutnya yang lebih rendah. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Mengembalikan persegi panjang yang merupakan hasil penggabungan (union) dari persegi panjang yang ditentukan. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Empty](./empty/) | Sebuah persegi panjang kosong, yaitu persegi panjang yang nilai lokasi dan ukurannya nol. |

## Lihat Juga

* Namespace [System::Drawing](../)
* Perpustakaan [Aspose.Slides](../../)