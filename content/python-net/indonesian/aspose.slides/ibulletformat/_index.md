---
title: IBulletFormat class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ibulletformat/
---
## IBulletFormat kelas

Mewakili properti pemformatan bullet paragraf.

Tipe IBulletFormat menampilkan anggota-anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/id/aspose.slides/ibulletformat/type/) | Mengembalikan atau mengatur jenis bullet dari paragraf tanpa pewarisan.<br/>            Baca/tulis [`BulletType`](/slides/python-net/id/aspose.slides/bullettype). |
| [`char`](/slides/python-net/id/aspose.slides/ibulletformat/char/) | Mengembalikan atau mengatur karakter bullet dari paragraf tanpa pewarisan.<br/>            Baca/tulis **System.Char**. |
| [`font`](/slides/python-net/id/aspose.slides/ibulletformat/font/) | Mengembalikan atau mengatur font bullet dari paragraf tanpa pewarisan.<br/>            Baca/tulis [`IFontData`](/slides/python-net/id/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/id/aspose.slides/ibulletformat/height/) | Mengembalikan atau mengatur tinggi bullet dari paragraf tanpa pewarisan.<br/>            Nilai float.NaN menentukan bahwa bullet mewarisi tinggi dari bagian pertama dalam paragraf.<br/>            Baca/tulis **float**. |
| [`color`](/slides/python-net/id/aspose.slides/ibulletformat/color/) | Mengembalikan format warna bullet dari paragraf tanpa pewarisan.<br/>            Hanya baca [`IColorFormat`](/slides/python-net/id/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/id/aspose.slides/ibulletformat/picture/) | Mengembalikan gambar yang digunakan sebagai bullet dalam paragraf tanpa pewarisan.<br/>            Hanya baca [`ISlidesPicture`](/slides/python-net/id/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/id/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Mengembalikan atau mengatur nomor pertama yang digunakan untuk grup bullet bernomor tanpa pewarisan.<br/>            Baca/tulis **int**. |
| [`numbered_bullet_style`](/slides/python-net/id/aspose.slides/ibulletformat/numbered_bullet_style/) | Mengembalikan atau mengatur gaya bullet bernomor tanpa pewarisan.<br/>            Baca/tulis [`IBulletFormat.numbered_bullet_style`](/slides/python-net/id/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/id/aspose.slides/ibulletformat/is_bullet_hard_color/) | Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf.<br/>            **NullableBool.True**  jika bullet memiliki warna sendiri dan **NullableBool.False**  jika bullet<br/>            mewarisi warna dari bagian pertama dalam paragraf.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/id/aspose.slides/ibulletformat/is_bullet_hard_font/) | Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf.<br/>            **NullableBool.True**  jika bullet memiliki font sendiri dan **NullableBool.False**  jika bullet<br/>            mewarisi font dari bagian pertama dalam paragraf.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |

## Metode

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/id/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Menetapkan pergeseran non-nol default untuk Indent dan MarginLeft paragraf yang efektif ketika bullet diaktifkan (seperti yang dilakukan PowerPoint jika mengaktifkan bullet/penomoran paragraf). Jika bullet dinonaktifkan maka hanya mengatur ulang Indent dan MarginLeft paragraf (seperti yang dilakukan PowerPoint jika menonaktifkan bullet/penomoran paragraf). Pergeseran indent diterapkan dengan memperhatikan konteks bullet saat ini — IBulletFormat.Type, .NumberedBulletStyle, dan FontHeight bagian pertama. Pergeseran indent non-nol diterapkan pada Indent dan MarginLeft paragraf yang efektif (menjadikan nilai hasil sebagai nilai lokal). |
| [`get_effective(self)`](/slides/python-net/id/aspose.slides/ibulletformat/get_effective/#) | Mendapatkan data pemformatan bullet yang efektif dengan pewarisan diterapkan. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)