---
title: BulletFormat class
second_title: Aspose.Slides untuk Python via .NET - Referensi API
description: 
type: docs
url: /id/aspose.slides/bulletformat/
---
## BulletFormat kelas

Mewakili properti pemformatan bullet paragraf.

**Pewarisan:**[`BulletFormat`](/slides/python-net/id/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/id/aspose.slides/pviobject)

Tipe BulletFormat menampilkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`type`](/slides/python-net/id/aspose.slides/bulletformat/type/) | Mengembalikan atau mengatur tipe bullet dari sebuah paragraf tanpa pewarisan.<br/>            Baca/tulis [`BulletType`](/slides/python-net/id/aspose.slides/bullettype). |
| [`char`](/slides/python-net/id/aspose.slides/bulletformat/char/) | Mengembalikan atau mengatur karakter bullet dari sebuah paragraf tanpa pewarisan.<br/>            Baca/tulis **System.Char**. |
| [`font`](/slides/python-net/id/aspose.slides/bulletformat/font/) | Mengembalikan atau mengatur font bullet dari sebuah paragraf tanpa pewarisan.<br/>            Baca/tulis [`IFontData`](/slides/python-net/id/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/id/aspose.slides/bulletformat/height/) | Mengembalikan atau mengatur tinggi bullet dari sebuah paragraf tanpa pewarisan.<br/>            Nilai float.NaN menentukan bahwa bullet mewarisi tinggi dari bagian pertama dalam paragraf.<br/>            Baca/tulis **float**. |
| [`color`](/slides/python-net/id/aspose.slides/bulletformat/color/) | Mengembalikan format warna bullet dari sebuah paragraf tanpa pewarisan.<br/>            Baca-saja [`IColorFormat`](/slides/python-net/id/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/id/aspose.slides/bulletformat/numbered_bullet_start_with/) | Mengembalikan atau mengatur nomor pertama yang digunakan untuk grup bullet bernomor tanpa pewarisan.<br/>            Baca/tulis **int**. |
| [`numbered_bullet_style`](/slides/python-net/id/aspose.slides/bulletformat/numbered_bullet_style/) | Mengembalikan atau mengatur gaya bullet bernomor tanpa pewarisan.<br/>            Baca/tulis [`NumberedBulletStyle`](/slides/python-net/id/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/id/aspose.slides/bulletformat/is_bullet_hard_color/) | Menentukan apakah bullet memiliki warna sendiri atau mewarisinya dari bagian pertama dalam paragraf.<br/>            **NullableBool.True**  jika bullet memiliki warna sendiri dan **NullableBool.False**  jika bullet<br/>            mewarisi warna dari bagian pertama dalam paragraf.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/id/aspose.slides/bulletformat/is_bullet_hard_font/) | Menentukan apakah bullet memiliki font sendiri atau mewarisinya dari bagian pertama dalam paragraf.<br/>            **NullableBool.True**  jika bullet memiliki font sendiri dan **NullableBool.False**  jika bullet<br/>            mewarisi font dari bagian pertama dalam paragraf.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/id/aspose.slides/bulletformat/picture/) | Mengembalikan gambar yang digunakan sebagai bullet dalam sebuah paragraf tanpa pewarisan.<br/>            Baca-saja [`ISlidesPicture`](/slides/python-net/id/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/id/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/bulletformat/presentation/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/id/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Mengatur pergeseran non-zero default untuk Indent dan MarginLeft paragraf yang efektif ketika bullet diaktifkan (seperti yang dilakukan PowerPoint jika mengaktifkan bullet/penomoran paragraf). Jika bullet dinonaktifkan, cukup mengatur ulang Indent dan MarginLeft paragraf (seperti yang dilakukan PowerPoint jika menonaktifkan bullet/penomoran paragraf). Pergeseran indent diterapkan berdasarkan konteks bullet saat ini - IBulletFormat.Type, .NumberedBulletStyle dan FontHeight dari bagian pertama. Pergeseran indent non-zero diterapkan pada Indent dan MarginLeft yang efektif dari paragraf saat ini (menjadikan nilai hasil sebagai nilai lokal). |
| [`get_effective(self)`](/slides/python-net/id/aspose.slides/bulletformat/get_effective/#) | Mendapatkan data format bullet yang efektif dengan pewarisan yang diterapkan. |

### Lihat Juga
* kelas [`BulletFormat`](/slides/python-net/id/aspose.slides/bulletformat)
* kelas [`PVIObject`](/slides/python-net/id/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)