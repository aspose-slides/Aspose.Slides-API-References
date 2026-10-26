---
title: ITextFrameFormat class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/itextframeformat/
---
## Kelas ITextFrameFormat

Berisi properti pemformatan TextFrame.

Tipe ITextFrameFormat menampilkan anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`text_style`](/slides/python-net/id/aspose.slides/itextframeformat/text_style/) | Mengembalikan gaya teks.<br/>            Hanya-baca [`ITextStyle`](/slides/python-net/id/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/id/aspose.slides/itextframeformat/margin_left/) | Mengembalikan atau mengatur margin kiri (points) dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`margin_right`](/slides/python-net/id/aspose.slides/itextframeformat/margin_right/) | Mengembalikan atau mengatur margin kanan (points) dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`margin_top`](/slides/python-net/id/aspose.slides/itextframeformat/margin_top/) | Mengembalikan atau mengatur margin atas (points) dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`margin_bottom`](/slides/python-net/id/aspose.slides/itextframeformat/margin_bottom/) | Mengembalikan atau mengatur margin bawah (points) dalam TextFrame.<br/>            Baca/tulis **float**. |
| [`wrap_text`](/slides/python-net/id/aspose.slides/itextframeformat/wrap_text/) | **True** jika teks dibungkus pada margin TextFrame.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/id/aspose.slides/itextframeformat/anchoring_type/) | Mengembalikan atau mengatur penambatan vertikal teks dalam TextFrame.<br/>            Baca/tulis [`TextAnchorType`](/slides/python-net/id/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/id/aspose.slides/itextframeformat/center_text/) | Jika NullableBool.True maka teks harus dipusatkan secara horizontal dalam kotak.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/id/aspose.slides/itextframeformat/text_vertical_type/) | Menentukan orientasi teks.<br/>            Nilai visual rotasi teks yang dihasilkan dirangkum dari properti ini dan sudut khusus<br/>            pada properti RotationAngle.<br/>            Baca/tulis [`TextVerticalType`](/slides/python-net/id/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/id/aspose.slides/itextframeformat/autofit_type/) | Mengembalikan atau mengatur mode autofit teks.<br/>            Baca/tulis [`TextAutofitType`](/slides/python-net/id/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/id/aspose.slides/itextframeformat/column_count/) | Mengembalikan atau mengatur jumlah kolom dalam area teks.<br/>            Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol.<br/>            Nilai 0 berarti nilai tidak ditentukan.<br/>            Baca/tulis **int**. |
| [`column_spacing`](/slides/python-net/id/aspose.slides/itextframeformat/column_spacing/) | Mengembalikan atau mengatur jarak antar kolom teks dalam area teks (dalam points). Ini hanya berlaku<br/>            ketika ada lebih dari 1 kolom.<br/>            Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol.<br/>            Baca/tulis **float**. |
| [`three_d_format`](/slides/python-net/id/aspose.slides/itextframeformat/three_d_format/) | Mengembalikan objek ThreeDFormat yang mewakili properti efek 3d untuk teks.<br/>            Hanya-baca [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/id/aspose.slides/itextframeformat/keep_text_flat/) | Mengembalikan atau mengatur agar teks tidak berada dalam adegan 3D sama sekali.<br/>            Baca/tulis **bool**. |
| [`rotation_angle`](/slides/python-net/id/aspose.slides/itextframeformat/rotation_angle/) | Menentukan rotasi khusus yang diterapkan pada teks di dalam kotak pembatas. Jika tidak<br/>            ditentukan, rotasi shape yang menyertainya yang digunakan. Jika ditentukan, maka ini<br/>            diterapkan secara independen dari shape. Artinya shape dapat memiliki rotasi<br/>            selain teks itu sendiri yang juga memiliki rotasi.<br/>            Nilai visual rotasi teks yang dihasilkan dirangkum dari properti ini dan tipe vertikal<br/>            yang telah ditentukan pada properti TextVerticalType.<br/>            Baca/tulis **float**. |
| [`transform`](/slides/python-net/id/aspose.slides/itextframeformat/transform/) | Mendapatkan atau mengatur bentuk pembungkus teks.<br/>            Baca/tulis [`TextShapeType`](/slides/python-net/id/aspose.slides/textshapetype). |

## Metode

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/id/aspose.slides/itextframeformat/get_effective/#) | Mendapatkan data pemformatan frame teks yang efektif dengan pewarisan yang diterapkan. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)