---
title: IParagraphFormat class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iparagraphformat/
---
## IParagraphFormat kelas

Kelas ini berisi properti pemformatan paragraf. Tidak seperti [`IParagraphFormatEffectiveData`](/slides/python-net/id/aspose.slides/iparagraphformateffectivedata), semua properti kelas ini dapat ditulis.

Tipe IParagraphFormat menampilkan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`bullet`](/slides/python-net/id/aspose.slides/iparagraphformat/bullet/) | Mengembalikan format bullet paragraf.<br/>            Hanya baca [`IBulletFormat`](/slides/python-net/id/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/id/aspose.slides/iparagraphformat/depth/) | Mengembalikan atau mengatur kedalaman paragraf.<br/>            Nilai 0 berarti nilai tidak terdefinisi.<br/>            Baca/tulis **int**. |
| [`alignment`](/slides/python-net/id/aspose.slides/iparagraphformat/alignment/) | Mengembalikan atau mengatur perataan teks dalam paragraf tanpa pewarisan.<br/>            Baca/tulis [`TextAlignment`](/slides/python-net/id/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/id/aspose.slides/iparagraphformat/space_within/) | Mengembalikan atau mengatur jumlah spasi antara garis dasar dalam paragraf. Nilai positif berarti persentase, negatif - ukuran dalam poin. Tidak ada pewarisan yang diterapkan.<br/>            Baca/tulis **float**. |
| [`space_before`](/slides/python-net/id/aspose.slides/iparagraphformat/space_before/) | Mengembalikan atau mengatur jumlah spasi sebelum baris pertama dalam paragraf tanpa pewarisan.<br/>            Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih.<br/>            Nilai negatif menentukan ukuran ruang putih dalam poin.<br/>            Baca/tulis **float**. |
| [`space_after`](/slides/python-net/id/aspose.slides/iparagraphformat/space_after/) | Mengembalikan atau mengatur jumlah spasi setelah baris terakhir dalam paragraf tanpa pewarisan.<br/>            Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih.<br/>            Nilai negatif menentukan ukuran ruang putih dalam poin.<br/>            Baca/tulis **float**. |
| [`east_asian_line_break`](/slides/python-net/id/aspose.slides/iparagraphformat/east_asian_line_break/) | Menentukan apakah jeda baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/id/aspose.slides/iparagraphformat/right_to_left/) | Menentukan apakah penulisan Right to Left digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/id/aspose.slides/iparagraphformat/latin_line_break/) | Menentukan apakah jeda baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/id/aspose.slides/iparagraphformat/hanging_punctuation/) | Menentukan apakah tanda baca gantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/id/aspose.slides/iparagraphformat/margin_left/) | Mengembalikan atau mengatur margin kiri dalam paragraf tanpa pewarisan.<br/>            Baca/tulis **float**. |
| [`margin_right`](/slides/python-net/id/aspose.slides/iparagraphformat/margin_right/) | Mengembalikan atau mengatur margin kanan dalam paragraf tanpa pewarisan.<br/>            Baca/tulis **float**. |
| [`indent`](/slides/python-net/id/aspose.slides/iparagraphformat/indent/) | Mengembalikan atau mengatur Indent Baris Pertama/Indent Gantung paragraf tanpa pewarisan. Indent Gantung dapat didefinisikan dengan nilai negatif.<br/>            Baca/tulis **float**. |
| [`default_tab_size`](/slides/python-net/id/aspose.slides/iparagraphformat/default_tab_size/) | Mengembalikan atau mengatur ukuran tabulasi default tanpa pewarisan.<br/>            Baca/tulis **float**. |
| [`tabs`](/slides/python-net/id/aspose.slides/iparagraphformat/tabs/) | Mengembalikan tabulasi paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Hanya baca [`ITabCollection`](/slides/python-net/id/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/id/aspose.slides/iparagraphformat/font_alignment/) | Mengembalikan atau mengatur perataan font dalam paragraf tanpa pewarisan.<br/>            Baca/tulis [`FontAlignment`](/slides/python-net/id/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/id/aspose.slides/iparagraphformat/default_portion_format/) | Mengembalikan format bagian default paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Hanya baca [`IPortionFormat`](/slides/python-net/id/aspose.slides/iportionformat). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/id/aspose.slides/iparagraphformat/get_effective/#) | Mendapatkan data pemformatan paragraf efektif dengan pewarisan yang diterapkan. |

### Catatan

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan paragraf yang didefinisikan untuk paragraf tertentu. Ini berarti tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga untuk kebanyakan kasus Anda akan mendapatkan nilai yang berarti "tidak terdefinisi".

Untuk mendapatkan nilai parameter pemformatan yang efektif termasuk yang diwarisi, Anda perlu menggunakan metode [`IParagraphFormat.get_effective`](/slides/python-net/id/aspose.slides/iparagraphformat/get_effective) yang mengembalikan sebuah instance [`IParagraphFormatEffectiveData`](/slides/python-net/id/aspose.slides/iparagraphformateffectivedata).

### Lihat Juga
* kelas [`IParagraphFormatEffectiveData`](/slides/python-net/id/aspose.slides/iparagraphformateffectivedata)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)