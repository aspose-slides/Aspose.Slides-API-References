---
title: ParagraphFormat class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/paragraphformat/
---
## ParagraphFormat kelas

Kelas ini berisi properti pemformatan paragraf. Tidak seperti [`IParagraphFormatEffectiveData`](/slides/python-net/id/aspose.slides/iparagraphformateffectivedata), semua properti kelas ini dapat ditulis.

**Pewarisan:**[`ParagraphFormat`](/slides/python-net/id/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/id/aspose.slides/pviobject)

Tipe ParagraphFormat mengekspos anggota berikut:

## Konstruktor

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides/paragraphformat/__init__/#) | Menginisialisasi instance baru dari kelas [`ParagraphFormat`](/slides/python-net/id/aspose.slides/paragraphformat). |

## Properti

| Property | Description |
| :- | :- |
| [`alignment`](/slides/python-net/id/aspose.slides/paragraphformat/alignment/) | Mengembalikan atau menetapkan perataan teks dalam paragraf tanpa pewarisan.<br/>            Baca/tulis [`TextAlignment`](/slides/python-net/id/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/id/aspose.slides/paragraphformat/space_within/) | Mengembalikan atau menetapkan jumlah ruang antar garis dasar dalam paragraf. Nilai positif berarti persentase, nilai negatif – ukuran dalam poin. Tidak ada pewarisan yang diterapkan.<br/>            Baca/tulis **float**. |
| [`space_before`](/slides/python-net/id/aspose.slides/paragraphformat/space_before/) | Mengembalikan atau menetapkan jumlah ruang sebelum baris pertama dalam paragraf tanpa pewarisan.<br/>            Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih.<br/>            Nilai negatif menentukan ukuran ruang putih dalam poin.<br/>            Baca/tulis **float**. |
| [`space_after`](/slides/python-net/id/aspose.slides/paragraphformat/space_after/) | Mengembalikan atau menetapkan jumlah ruang setelah baris terakhir dalam paragraf tanpa pewarisan.<br/>            Nilai positif menentukan persentase ukuran font yang harus menjadi ruang putih.<br/>            Nilai negatif menentukan ukuran ruang putih dalam poin.<br/>            Baca/tulis **float**. |
| [`east_asian_line_break`](/slides/python-net/id/aspose.slides/paragraphformat/east_asian_line_break/) | Menentukan apakah pemutusan baris Asia Timur digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/id/aspose.slides/paragraphformat/right_to_left/) | Menentukan apakah penulisan Dari Kanan ke Kiri digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/id/aspose.slides/paragraphformat/latin_line_break/) | Menentukan apakah pemutusan baris Latin digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/id/aspose.slides/paragraphformat/hanging_punctuation/) | Menentukan apakah tanda baca menggantung digunakan dalam paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Baca/tulis [`NullableBool`](/slides/python-net/id/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/id/aspose.slides/paragraphformat/margin_left/) | Mengembalikan atau menetapkan margin kiri dalam paragraf tanpa pewarisan.<br/>            Baca/tulis **float**. |
| [`margin_right`](/slides/python-net/id/aspose.slides/paragraphformat/margin_right/) | Mengembalikan atau menetapkan margin kanan dalam paragraf tanpa pewarisan.<br/>            Baca/tulis **float**. |
| [`indent`](/slides/python-net/id/aspose.slides/paragraphformat/indent/) | Mengembalikan atau menetapkan Inden Baris Pertama/Inden Menggantung paragraf tanpa pewarisan. Inden Menggantung dapat didefinisikan dengan nilai negatif.<br/>            Baca/tulis **float**. |
| [`default_tab_size`](/slides/python-net/id/aspose.slides/paragraphformat/default_tab_size/) | Mengembalikan atau menetapkan ukuran tabulasi default tanpa pewarisan.<br/>            Baca/tulis **float**. |
| [`tabs`](/slides/python-net/id/aspose.slides/paragraphformat/tabs/) | Mengembalikan tabulasi paragraf. Tidak ada pewarisan yang diterapkan.<br/>            Baca-saja [`ITabCollection`](/slides/python-net/id/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/id/aspose.slides/paragraphformat/font_alignment/) | Mengembalikan atau menetapkan perataan font dalam paragraf tanpa pewarisan.<br/>            Baca/tulis [`FontAlignment`](/slides/python-net/id/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/id/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/id/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/id/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/id/aspose.slides/paragraphformat/default_portion_format/) |  |

## Metode

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/id/aspose.slides/paragraphformat/get_effective/#) | Mendapatkan data pemformatan paragraf yang efektif dengan pewarisan yang diterapkan. |


### Catatan

Kelas ini digunakan untuk mengembalikan dan memanipulasi properti pemformatan paragraf yang didefinisikan untuk paragraf tertentu. Ini berarti bahwa
            tidak ada pewarisan yang diterapkan saat mengambil nilai sehingga dalam kebanyakan kasus Anda akan mendapatkan nilai yang berarti "undefined".


Untuk mendapatkan nilai parameter pemformatan yang efektif termasuk yang diwarisi, Anda perlu menggunakan metode [`ParagraphFormat.get_effective`](/slides/python-net/id/aspose.slides/paragraphformat/get_effective) 
            yang mengembalikan sebuah instance [`IParagraphFormatEffectiveData`](/slides/python-net/id/aspose.slides/iparagraphformateffectivedata).


### Lihat Juga
* kelas [`IParagraphFormatEffectiveData`](/slides/python-net/id/aspose.slides/iparagraphformateffectivedata)
* kelas [`ParagraphFormat`](/slides/python-net/id/aspose.slides/paragraphformat)
* kelas [`PVIObject`](/slides/python-net/id/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)