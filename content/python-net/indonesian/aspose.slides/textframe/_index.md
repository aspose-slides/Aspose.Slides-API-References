---
title: TextFrame class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/textframe/
---
## TextFrame kelas

Mewakili sebuah TextFrame.

Tipe TextFrame menampilkan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`paragraphs`](/slides/python-net/id/aspose.slides/textframe/paragraphs/) | Mengembalikan daftar semua paragraf dalam sebuah bingkai.<br/>            Hanya-baca [`IParagraphCollection`](/slides/python-net/id/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/id/aspose.slides/textframe/text/) | Mendapatkan atau mengatur teks biasa untuk sebuah TextFrame.<br/>            Baca/tulis **str**. |
| [`text_frame_format`](/slides/python-net/id/aspose.slides/textframe/text_frame_format/) | Mengembalikan objek pemformatan untuk objek TextFrame ini.<br/>            Hanya-baca [`ITextFrameFormat`](/slides/python-net/id/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/textframe/hyperlink_queries/) | Menyediakan akses mudah ke hyperlink yang terkandung.<br/>            Hanya-baca [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/id/aspose.slides/textframe/slide/) | Mengembalikan slide induk dari sebuah TextFrame.<br/>            Hanya-baca [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/textframe/presentation/) | Mengembalikan presentasi induk dari sebuah TextFrame.<br/>            Hanya-baca [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/id/aspose.slides/textframe/parent_shape/) | Mengembalikan shape induk atau None jika objek induk tidak mengimplementasikan antarmuka IShape<br/>            Hanya-baca [`IShape`](/slides/python-net/id/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/id/aspose.slides/textframe/parent_cell/) | Mengembalikan sel induk atau None jika objek induk tidak mengimplementasikan antarmuka ICell.<br/>            Hanya-baca [`ICell`](/slides/python-net/id/aspose.slides/icell). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/id/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | Menyoroti semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/id/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Menyoroti semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/id/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Menyoroti semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/id/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Menyoroti semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/id/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | Menyoroti semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/textframe/join_portions_with_same_formatting/#) | Menggabungkan run dengan pemformatan yang sama dalam semua paragraf. |
| [`split_text_by_columns(self)`](/slides/python-net/id/aspose.slides/textframe/split_text_by_columns/#) | Membagi konten teks dari [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe) menjadi sebuah array string, <br/>            di mana setiap elemen sesuai dengan kolom teks terpisah dalam bingkai. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/id/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/id/aspose.slides/textframe/replace_regex/#str-str) | Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)